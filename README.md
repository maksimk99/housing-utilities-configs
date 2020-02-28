# Housing utilities
1)Start Kafka server:
```
bin/zookeeper-server-start.sh config/zookeeper.propeies  
bin/kafka-server-start.sh config/server.properties
```
2)Start config server ``mvn spring-boot:run``  
3)Start eureka server `` mvn spring-boot:run``  
4)Start zuul server `` mvn spring-boot:run``  
5)Start auth server `` mvn spring-boot:run``  
6)Start all other microservices  
7)Start client app