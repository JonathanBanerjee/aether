# aether
Proof of concept for an ELK stack.

### Description
This is an ELK stack that uses docker-compose to create 3 containers: ElasticSearch, Kibana and Logstash. The ELK stack enables the user to store, manipulate and visualise data. This is very useful when a company has a large amount of logs that need to be visualized. 

A case study of Elasticache vs AWS can be found in the casestudy.md file. 

### Prerequisite
* git 
* bash
* docker 

### How to run
clone the repository 
```
$ git clone https://github.com/JonathanBanerjee/aether
$ cd aether
$ docker-compose up
```
### Visualisation
1. visit `localhost:5601`
