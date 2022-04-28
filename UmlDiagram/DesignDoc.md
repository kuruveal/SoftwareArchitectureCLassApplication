DesignDoc:

The libcore will contain all of the core Observer services. Observer's application-specific parts will be stored in relevant libraries. Has a Session object at the highest level. As a result, on CoreSession, application-specific observers are not registered. Adding a second use case for observers to demonstrate how core functionality may be segregated while still being adaptable.

The UML sequence diagram depicting how this capability operates is shown below:
![image](https://user-images.githubusercontent.com/97775815/165695199-65187ee8-6ad9-483d-967e-034f3687b163.png)

The UML class diagram depicting how this capability works is shown below:
![image](https://user-images.githubusercontent.com/97775815/165695245-257ba778-d5ca-413a-8aab-5a6773005527.png)
