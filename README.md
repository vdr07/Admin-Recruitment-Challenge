# Admin Recruitment Challenge

To unzip the file, run the following command:

```
unzip -n Admin_Recruitment_Challenge.zip
```

To generate the Docker image, run the following command:

```
docker build -t tomcat-ssl .
```

To deploy the application, run the command below:

```
docker run -d -p 4041:4041 tomcat-ssl
```