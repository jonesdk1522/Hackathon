# Hackathon

Our challenge is legacy decommissioning, but team Paradigm decided to take a look at the bigger picture. We're about adding real, quantifiable business value. We're about enabling the IRS to become a better, faster, efficient, cost-effective machine. We believe the answer comes in the form of a microservice architecture, and the legacy decommissioning challenge provides an excellent vehicle to showcase the opportunities.

So what is microservices architecture? You've heard the buzz words, and when implemented wrong, that's all it is, buzz words attached to costly technical debt. It has to be designed right from the beginning, and we believe we have the right formula for success. Microservice architecture is the concept of creating an abstract layer between the consumer and the application. This layer is called the enterprise service bus. The consumer uses an interface that interacts with the service bus, and the service bus communicates with the underlying applications through predefined services. Solution engineers review applications to identify their capabilities and then map those capabilities to individual concise services. Microservices follow the UNIX concept of "doing one thing and doing it well."

Most applications provide more functionality than is required to support the business. They do this to engage a larger audience. We believe it's essential to keep the Pareto principle in mind when identifying application capabilities as possible microservice candidates. 80% of an application's use comes from 20% of its capabilities. The idea is to focus on and identify services that deliver real business value.

As a general statement, we are creatures of habit; we don't like change.
Change, be it an application or business process, introduces learning curves, and impacts productivity during the transition period. Change is best adopted when it provides the path of least resistance. The new way should be more comfortable, more efficient, and intuitive. Users will naturally embrace the change with less resistance if they can see the value in it.

Going back to the microservices, once all applicable services are published to the enterprise service bus, it's time to build a slimmed-down intuitive interface made to fit the user. The interface is kept simple and only contains the components necessary for the user to perform their duties. It should be designed with the user experience in mind, adhering to the principle of least astonishment (POLA). POLA proposes that "the design should match the user's experience, expectations, and mental models." Users should not struggle to understand and interact with an application; it should just make sense.

We built a prototype environment to show you this concept in a real-world scenario. We have the legacy application in the background, the application selected to replace the legacy application, a service bus, and the interface that communicates with the service bus.
