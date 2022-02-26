# java-spring-boot-amazon-bucket-s3

* https://dev.to/aws-builders/integrating-your-spring-boot-project-with-amazon-s3-3e3
* https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
* https://medium.com/analytics-vidhya/aws-s3-with-java-using-spring-boot-7f6fcf734aec


```
mvn archetype:generate -DgroupId=com.hawksys.s3 -DartifactId=s3-demo -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
```


## To test
* Download a file
```
curl -X GET "http://127.0.0.1:8080/api/v1/files" -H  "accept: */*" -H  "Content-Type: application/json" -d "{  \"fileName\": \"beach.jpg\"}" --output beach.jpg
```

* List all files
``` 
curl -X GET "http://127.0.0.1:8080/api/v1/files/list" -H  "accept: */*"


 
