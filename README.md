``` shell
# parent
mvn clean install
# auth-server http://localhost:8300
cd ./auth-server
mvn spring-boot:run
# client-a http://localhost:8301
cd ./client-a
mvn spring-boot:run
# client-b http://localhost:8302
cd ./client-b
mvn spring-boot:run
``` 


