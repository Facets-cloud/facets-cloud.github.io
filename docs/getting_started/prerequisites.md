# Prerequisites - Onboarding Applications to facets.

In order to migrate your applications to Facets we would need them to be dockerized and ready for kubernetes deployments.

Following are few guidelines to follow while containerising your applications or readying your existing containers.

> Checkout the best practices for creating a docker image [here](https://cloud.google.com/solutions/best-practices-for-building-containers) and [here](https://docs.docker.com/develop/dev-best-practices/)

**Logging:**
 - Log your applications to stdout and stderr. 
 >Read [here](https://howtodoinjava.com/log4j/log4j-console-appender-example/) for java application

**Environment Variables:**
 - Use environment variables for reading all database usernames and passwords in your applications. This will later help us auto-wire these details and manage credential management for you once you are on Facets.
 - Use environment variables to refer to any cloud resource like S3, SQS or SNS. Facets can then dynamically fulfil these variables.

**AWS SDK (If Used):**
 - Use AWS keys and secrets in your applications via environment variables, rather use the default credential provider.  This will enable auto provision the IAM for your application and have seamless access to resources it has requested
 >Details [here](https://docs.aws.amazon.com/sdk-for-java/v1/developer-guide/credentials.html).

**Image Registry:**
 - Use either dockerhub private registry or Amazon Elastic Container Registry (Amazon ECR) for storing your docker images. Facets has support for onboarding these registries and can pull images from here.

**Service Discovery:**
 - Use either DNS or IP based service discovery via environment variables for communication between services and/ or databases easier. This will enable easy porting into kubernetes on Facets.
 
**Readiness and Liveliness checks:**
 - Readiness and Liveliness checks are important and should be configured appropriately to keep your application well managed. 
 >Read [here](https://cloud.google.com/blog/products/containers-kubernetes/kubernetes-best-practices-setting-up-health-checks-with-readiness-and-liveness-probes) for more details
----