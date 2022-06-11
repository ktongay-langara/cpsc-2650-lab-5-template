# cpsc-2650-lab-5-template

### Setup

Install RabbitMQ on your system using the following: 
```
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.10-management
```
Check if RabbitMQ server is running at localhost:15672 (default username: guest, password: guest)

To run the send.js and receive.js files, you need amqplib installed:

```
npm install amqplib
```

Then just run each file as a script, e.g., in bash

```
./send.js
./receive.js
```

or

```
node send.js
node receive.js
```
