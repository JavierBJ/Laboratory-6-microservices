# Web Engineering 2015-2016 / Microservices

1. Two services registered
![Two services registered](http://imgur.com/xjjveBI "Two services registered")

2. Registration has both services
![Registration](http://imgur.com/hS4vB7V "Registration has both services")

3. Another accounts service added
![Another one](http://imgur.com/MfGwvdj "New accounts added with no problem")

4. What happens when killing microservice in 2222?
As we've registered a new Accounts service in port 4444, everything keeps working. The registration service detects that one service has been cancelled and, after that, it detects that another one exists, so the availability of the service is guaranteed.
