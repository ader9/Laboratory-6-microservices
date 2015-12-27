1.Microservices running and registered

Account

![Alt text](https://github.com/ader9/Laboratory-6-microservices/blob/master/accounts.JPG)

Web

![Alt text](https://github.com/ader9/Laboratory-6-microservices/blob/master/web.JPG)

2.Service with the two microservices registered

![Alt text](https://github.com/ader9/Laboratory-6-microservices/blob/master/register.JPG)

3.Second account in port 4444

![Alt text](https://github.com/ader9/Laboratory-6-microservices/blob/master/account 4444.JPG)

4.What happens when you kill the microservice in port 2222

When you disconnect the microservice in the port 2222, the web microservice try to connect again during three tries but when the service finds another microservice with the same name (the service in the port 4444), it connects and start to work again.


