## Assignment in Advanced Systems Integration & Architecture

1. Define Service Oriented Architecture(SOA).

- Service Oriented Architecture (SOA) is a software architecture architectural style in which application components give services to other components over a network communication protocol. The fundamental idea behind SOA is to enable users to combine huge pieces of functionality to make applications, which are developed using services as building blocks. SOA stresses loose coupling between services, which means that services maintain a connection that reduces dependencies and needs just that they understand one other.

2. List and discuss the characteristics of SOA.

- Loose Coupling: Services are meant to be as self-contained as possible.
- Interoperability: SOA services may communicate with one another across platforms and languages.
- Reusability: Services are meant to be utilized in a variety of scenarios and applications.
- Abstraction: Services keep their implementation details secret from their customers.
- Composability: Services can be used in conjunction to give more complicated functionality.
- Standardized Protocol: Standard protocols like as HTTP, SOAP, and others are used to communicate between services.
- Discoverability: Services in a network can be found, making it easier to locate and integrate them into new applications.

3. Define Microservices.

- Microservices is an architectural approach in which an application is structured as a series of loosely connected services that provide business capabilities. Each service is a discrete, self-contained process that can be deployed, created, run, and scaled independently. Microservices design facilitates the delivery of big, sophisticated applications in a timely, frequent, and dependable manner. It also enables an organization's technological stack to adapt.

4. List and discuss the benefits of using Microservices.

- Scalability: Each component may be scaled separately.
- Flexibility in Technology: Different technologies and languages can be used by different services.
- Faster Deployment: Smaller codebases and services result in faster deployment.
- Fault Isolation: Problems with one service do not affect the entire program.
- Ease of Understanding: Smaller code bases are simpler to comprehend and maintain.
- Agility and Speed: Teams may operate autonomously, which reduces the time required for development cycles.

5. List and discuss the similarities and differences of SOA and Microservices.

- Similarities:

  - Both designs seek to deconstruct apps into smaller components/services.
  - They encourage service reuse, while the breadth and granularity vary.
  - To define the bounds of services, both require rigorous planning and design.

- Differences:
  - Granularity: Microservices are often smaller and more focused on performing one thing effectively, whereas SOA services are bigger and may include broader business functions.
  - Inter-Service Communication: SOA frequently employs enterprise service buses (ESBs), whereas microservices employ lightweight protocols such as HTTP/REST or message queues.
  - Data Storage: Microservices frequently handle their own databases, whereas SOA relies on a more centralized data management technique.
  - Coupling and Cohesion: Microservices emphasize very loose coupling and good cohesiveness, whereas SOA may emphasis tighter coupling and looser coupling.
  - Technology Heterogeneity: Microservices frequently encourage the use of the best technology for the individual needs of the service, whereas SOA services are more homogeneous.
