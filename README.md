# Read me

The original idea is from  
https://medium.com/graalvm/oracle-graalvm-now-available-as-a-paketo-buildpack-7b6a7dbb939c

./mvnw clean spring-boot:build-image

./mvnw clean -Pnative spring-boot:build-image

docker run -d -p 8080:8080 my-graal-app:0.1.0

Go to
http://localhost:8080/actuator


