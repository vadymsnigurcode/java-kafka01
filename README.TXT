https://coderlessons.com/tutorials/bolshie-dannye-i-analitika/vyuchit-apache-kafka/apache-kafka-prostoi-primer-dlia-prodiusera

start kafka windows
1. zookeeper-server-start.bat ..\..\config\zookeeper.properties
2. kafka-server-start.bat ..\..\config\server.properties


default kafka test applications
kafka-console-producer --topic topicName --bootstrap-server broker:9092 --property parse.key=true --property key.separator=":"
kafka-console-consumer --topic topicName --bootstrap-server localhost:9092 --from-beginning --property print.key=true --property key.separator="-"