## Building Angular App

To build the project run:
node >= 18.19.1

```bash
  npm install
  npm run build
```

## Create Spring Boot image 

```bash
  mvn spring-boot:build-image                      
```

## Start container

```bash
  docker run -it -p9090:8080 spring-boot-image:0.0.1-SNAPSHOT                 
```
