``` shell
# parent
mvn clean install
# auth-server
cd ./auth-server
mvn spring-boot:run
# client-a
cd ./client-a
mvn spring-boot:run
# client-b
cd ./client-b
mvn spring-boot:run
``` 


