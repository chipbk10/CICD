# Containerization

@Todo

## Docker

- image: is a template that defines how to build a container, including the application code, dependencies, and configuration
- container: is a running instance of image. Containers are isolated from each other and from the host system, and provide a consistent runtime environment for the application
- snapshot: 
- volume:
  - to share data between containers, and between containers and the host system.
  - data in volume is not lost if containers are stopped or deleted.
  - can be used to store sensitive data, such as credentials or configuration files, outside of the container's file system, improving security and reducing the risk of data breaches.

## Docker Registry

- Docker Registry is a service that allows users to store and distribute Docker images. It provides a central location for storing and sharing Docker images, making it easier to manage and distribute Docker images across different environments and teams.
  
  - Private image storage: Docker Registry can be used to store and manage private Docker images within an organization, providing a secure and centralized location for storing images.
  - Image sharing: Docker Registry allows users to share Docker images with others, enabling collaboration and making it easier to share images across teams and environments.
  - Continuous integration and deployment: Docker Registry can be integrated with continuous integration and deployment (CI/CD) pipelines, making it easier to automate the build, test, and deployment of Docker images.
  - Versioning and tagging: Docker Registry supports versioning and tagging of images, making it easier to manage and track different versions of images over time.
 
## Kubernet

- Using Docker alone is suitable for local development or running isolated applications. However, when you need to manage a complex application with multiple containers, handle scaling, load balancing, and automatic failover, that's where Kubernetes comes in.

- Kubernetes provides additional capabilities for container orchestration, service discovery, automatic scaling, and high availability. It allows you to manage multiple containers and their interactions across a cluster of machines. So, while Docker focuses on building and running individual containers, Kubernetes provides a higher level of abstraction and management for containerized applications in a production environment.

## Sources

- [Docker & Kubernet Tutorial](https://www.youtube.com/watch?v=bhBSlnQcq2k&ab_channel=Amigoscode)
