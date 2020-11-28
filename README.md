# Elasticsearch, Logstash and Kibana (ELK Stack)
This is a simplified docker (compose) project to boot up the ELK Stack.

**So, what is the ELK Stack?** "ELK" is the acronym for three open source projects: Elasticsearch, Logstash, and Kibana. 
Elasticsearch is a search and analytics engine. Logstash is a server‑side data processing pipeline that ingests data from 
multiple sources simultaneously, transforms it, and then sends it to a "stash" like Elasticsearch. Kibana lets users 
visualize data with charts and graphs in Elasticsearch.  
For more information please read [ELK Stack](https://www.elastic.co/what-is/elk-stack).

`Note: You may not use this stack in production!`
## Setup
For custom configurations you may look at the config folders and read 
[Get started with Docker](https://www.elastic.co/guide/en/elastic-stack-get-started/current/get-started-docker.html).  

To start the Stack execute the lines below. 
```bash
$ git clone https://github.com/CSalih/elk-docker-stack.git
$ cd elk-docker-stack
$ docker-compose up -d
```

Now you can connect to http://localhost:5601/ to access the Kibana UI. 
You may login with `elastic` and `passwd`.  

`Note: Boot time of Kibana may took a bit`