# Web Engineering 2015-2016 / Microservices

1. Two services registered
![registered](screenshots/registered.png "Two services registered")

2. Registration has both services
![registration](screenshots/registration.png "Registration has both services")

3. Another accounts service added
![another](screenshots/another.png "New accounts added with no problem")

4. What happens when killing microservice in 2222?
As we've registered a new Accounts service in port 4444, everything keeps working. The registration service detects that one service has been cancelled and, after that, it detects that another one exists, so the availability of the service is guaranteed.
