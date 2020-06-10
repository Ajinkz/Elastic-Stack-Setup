# Elastic Stack Setup
[site](https://ajinkz.github.io/Elastic-Stack-Setup/)

## 1. Install latest JDK 
* [Download Java](https://www.oracle.com/java/technologies/javase-jdk14-downloads.html)
* Install Java 
* Set environment variable  
```
   JAVA_HOME = "C:\Program Files\Java\jdk-14" 
   add to PATH :  "C:\Program Files\Java\jdk-14\bin" 
```
* Verify installation 
```
C:\>java -version
java version "14" 2020-03-17
Java(TM) SE Runtime Environment (build 14+36-1461)
Java HotSpot(TM) 64-Bit Server VM (build 14+36-1461, mixed mode, sharing)
``` 

## 2. Install Elasticsearch for windows 
* [Download Elasticsearch](https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-7.6.2-windows-x86_64.zip)
* Unzip it and place this folder here `C:\Program Files`
* Go to Environment variable > system variable >  add new to Path : `C:\Program Files\elasticsearch-7.6.2\bin`
* Open cmd in administreative mode and type `elasticsearch`
* Launch browser `localhost:9200`
* If setup is successfully completed it should show this message else checks logs for error. 

 

 

  

 

 

## 3. Download Kibana for windows 
* [Download Kibana](https://artifacts.elastic.co/downloads/kibana/kibana-7.6.2-windows-x86_64.zip)
* Unzip it and place this folder here `C:\Program Files` 
* Go to Environment variable > system variable >  add new to Path : `C:\Program Files\kibana-7.6.2-windows-x86_64\bin`
* Open cmd in administrative mode and type `kibana` (launch elastic search in separate terminal before launching kibana) 
* Launch browser `localhost:5601`

 

 
