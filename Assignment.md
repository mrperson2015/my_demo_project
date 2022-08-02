# Assignment
This project contains sample data and an Apache Zeppelin note in a self contained docker container and instructions to use a community edition databricks cluster. The note has 6 exercises to test your PySpark abilities. With the note open, you can download the note as a .zpln file (docker) or export as ipynb (databricks). This allows you to share your code for others to import and run in the same environment.

# To Run
1. Clone (this) repo ```git clone https://github.com/mrperson2015/my_demo_project.git```
1. Change directory to cloned repo ```cd my_demo_project/```

## To Run Using Docker Compose
1. Run docker images ```docker-compose up```
1. Browse to Apache Zeppelin at ```localhost:9001```
1. Open note ```Assignment/6 Exercises```
1. Enjoy ;)

### Validated On Systems
* Windows 10
* Ubuntu 19.04
* macOS Majave 10.14.2

### Apache Zeppelin
Web-based notebook that enables data-driven,  interactive data analytics
https://zeppelin.apache.org/
* ```Address```:  localhost:9001

### PostgreSQL
* ```Address```:  localhost:5432
* ```Database```: message_store
* ```Username```: message_store
* ```Password```: 
* ```Username```: postgres
* ```Password```: 

### Portainer
  (Not part of docker-compose)\
  Build and manage your Docker environments
https://www.portainer.io/
* ```Address```:  localhost:9000
* ```Username```: admin
* ```Password```: password1


## To Run Using databricks:
1. Signup for community account at databricks.com
    1. Choose a cloud provider: "Get started with Community Edition"
    </br>![image](https://user-images.githubusercontent.com/13457838/182223227-774ba96b-34cc-464c-8777-588346143542.png)
    3. Validate email addres
1. Create cluster
    1. Databricks runtime version: Runtime: 10.4 LTS (Scala 2.12, Spark 3.2.1)
1. Create notebook
    1. Default Language: Python
    2. Cluster: 6-questions
![image](https://user-images.githubusercontent.com/13457838/182253070-8a813721-bc95-42a3-9785-4f033f190c07.png)
1. In the notebook `databricks_6-questions.ipynb` you will find instructions to upload the data required for this notebook
