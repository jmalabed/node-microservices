# Node-microservices
[Course from Daniel Kahn on Linkedin Learning, covering Microservices on Node.js](https://www.linkedin.com/learning-login/share?forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fnode-js-microservices%3Ftrk%3Dshare_ent_url%26shareId%3DcD8H8qlOSV2Qp8t%252BvxQk%252Bg%253D%253D)
## Learning Takeaways
### Service based Software Paradigm
Services allow one application to be split up into several different applications that communicate with each other. 

Advantages of this approach are as follows:
- Non-functional services won't bring your whole application down
- Operational service application errors can be smoothed over by the parent application, by using cacheing
- Broken service application can be given time to come back online by parent application instead of crashing entire app
- Services can scale on multiple different concurrent service applications to allow faster processing when demand increases (scaling out), as well as load balance by a distribution management system
- Service management systems can be used to easily scale an application as demand increases (Docker, Kubernates)
- Code is easier to break apart and learn in certain areas, less tangled than a monolith

Cons of this approach include:
- Service architecture can be messy and hard to convert a monolith into
- Services require more planning to get started with
- On larger applications, service orchestration is (almost) a must in order to roll out new versions
- This approach may be harder for new engineers on the project to jump on and be productive with

### Other
- AMQP message queueing mechanics, viewing how these work. Troubleshooting rabbitmq instal/ config
- Cacheing on front end application is a great way to increase reliability on an application, can increase speed depending on how API calls are set up
- More sophisticated folder structuring, class files are stored as first letter capitalized in '/lib', used within service routing to add sophisticated functionality

## Resources
* [Explained](https://acropolium.com/blog/microservices-architecture-implementation-benefits-practices/)
* [Opinion](https://lightstep.com/blog/the-end-of-microservices/)
