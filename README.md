## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
   - is a sofware development approach that allows services to be reused and communicate across platforms and languages to create new applications.

2. List and discuss the characteristics of SOA.
   A service-oriented architecture consists of four main components: 
   - Service, which contains the basic service-oriented architecture(SOA) building blocks. It can be open source and accessible to the public or private, available only to authorized users. Each service has three main features, a Service Implementation, Service Contract, and Service Interface. Where in Service Implementation, is the code that creates the logic for filling the specific service function. While in the Service Contract, defines the parameters of a service as well as its cost and quality. Lastly is the Service Interface, which describes how to interface handles communication with other services and systems.
   - Service provider, it creates, handles, and provides one or more services that others can use.
   - Service consumer, is an individual, system, application, or other service that seeks services from the service provider. Also specifies the terms and conditions under which a service provider and a service requester get involved.
   - Service registry, additionally known as a service repository, is a listing of available services. It is in charge of keeping service descriptions as well as additional relevant data on how to use a service provider's services.

3. Define Microservices.
   - is a different approach to software development that focuses on creating single-function modules with well-defined interfaces and operations.

4. List and discuss the benefits of using Microservices.
   - Improved productivity, it improves creation and maintenance of software applications by breaking them down into smaller autonomous fragments.
   - Scalability improvements, since each cloud microservice runs independently, it is simpler to add, remove, update, or scale them. Where the developers can complete these tasks without affecting with any other microservices in the system.
   - Improved Data Security, when the components of a computer system's design are broken down into smaller pieces, sensitive data is protected from outside invaders.

5. List and discuss the similarities and differences of SOA and Microservices.
   The similarities of SOA and Microservices are:
   - both require designing and operating apps in a cloud or hybrid cloud environment. 
   - it is designed to organize multiple services required for the creation and use of apps. 
   - each efficiently divides huge, complex applications into smaller components that are easier to design and deploy. Because both microservices and SOA operate in cloud environments, they can grow to meet modern needs for big data capacity and speed.

   While their differences are:
   - Microservices architecture is based on smaller, tiny services that are focused on a particular purpose and can operate independently of one another while supporting the same application.  While the SOA contains larger, more modular services that are not self-contained, it is designed to share resources as much as feasible.
   - An individual microservices are frequently utilize their own data storage. While in SOA, almost all services share the same data storage units.
   - Microservices is based on Bounded Context, while SOA is centered on the concept of sharing components.

