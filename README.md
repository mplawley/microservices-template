# microservices-template

This is a template to quickly get started with microservices. This template sets up a basic project skeleton and uses...

- Spring Boot for the 'api' (just a skeleton for a microservice here)
- Angular for the front-end, which is deployed with the proxy
- JHipster UAA (Oauth2, JWT)
- JHipster Registry for services
- MongoDB
- Hazelcast
- Sonar
- Bootstrap
- Elasticstack
- Docker (in the docker-compose folder)
- Cucumber
- Protractor
- Maven for a build tool
- International support (English, Spanish, Japanese, Korean)


# intention

To quickly be able to deploy microservices with one command.

# installation

`git clone` this repo.

# deploy

`cd docker-compose` and deploy with `docker-compose up -d`

# deployment expected output

```
Starting docker-compose_gateway-mongodb_1        ... done
Starting docker-compose_uaa-mongodb_1            ... done
Starting docker-compose_jhipster-registry_1      ... done
Starting uaa-mongodb-config                      ... done
Starting docker-compose_uaa-mongodb-node_1       ... done
Starting docker-compose_uaa-app_1                ... done
Starting docker-compose_api-mongodb_1            ... done
Starting docker-compose_gateway-app_1            ... done
Starting docker-compose_jhipster-elasticsearch_1 ... done
Starting docker-compose_api-app_1                ... done
Starting docker-compose_api-elasticsearch_1      ... done
Starting docker-compose_jhipster-logstash_1          ... done
Starting docker-compose_jhipster-import-dashboards_1 ... done
Starting docker-compose_jhipster-zipkin_1            ... done
Starting docker-compose_jhipster-console_1           ... done
```
