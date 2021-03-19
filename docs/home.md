# Facets 

Facets.cloud simplifies the creation, deployment and day-to-day operations of a cloud foot-print of a product over multiple deployments across multiple clouds. 
Any cloud deployment managed by Facets ships with best-practice observability, security, disaster recovery  and compliance suits powered by opensource and commercial tools.
A deployment is a complete manifestation of the following underlying components
* Applications (Micro-services)
* Infrastructure (Databases, queues, ingress etc.)
* Databases (Schema, password management)

The wiki is organized in the following sections
## Getting Started

* [A sample deployment](getting_started/demo.md)
* [Prerequisites - Onboarding Applications to facets](getting_started/prerequisites.md)


## Onboarding your product on Facets 
Onboarding your product to facets is three simple steps. 
### [1\. Declare - Define a product in Facets Stack Definition Language](fsdl/README.MD)

Facets stack definition language enables you to define your complete product as a stack.
A stack is a easy to write JSON that is committed as a git repository. Typical contents of a stack is
* Application
    * Image to use or a CI integration
    * Liveliness and Readiness checks
    * Credential Requests
    * Ingress rules
* Infrastructure
    * Type
    * Service name
* Database
    * Schema of the tables
    * Seed data
    
Now you can create a few clusters out of this stack.   

### [2\. Deploy - Create a few clusters out of the stack](deploy/README.md)

To create a cluster out of the stack definitions, follow the steps
* Register the stack in your control plane with read-only git credentials
* Create an IAM use in your target cloud provider account
* Provide the credentials, target region
* Choose a release stream, a continuous deployment pipeline stage, release sign-off criteria, and a cron to schedule release
* Launch the cluster

### [3\. Operate - Release, mutate your stack, monitor](operate/README.md)

Once your cluster is created, the following operations are possible on the control plane
* Application releases will automatically be pushed at the scheduled time as per the qualified build
* Change the stack to add newer resources
* Upgrade, change parameters of applications on the fly using Overrides
* Recover databases in case of a disaster from the UI
* Give access to your NOC team to access the built-in dashboard and alerts
* Access your security postures from the dashboard
* Give access to your infosec team to download compliance reports
* Temporary credentials for developers to login and do manual maintenance 

## [Roadmap](roadmap/README.md)
The roadmap is classified in the following aspects. 
* New Cloud support
* New Observability features such as anomaly detection
* New opensource and paid Security tools integration
* New Deployment strategies
* Cost Facets - Helps you analyze cloud cost    
## Resources
* [Demo Videos](getting_started/demo.md)
