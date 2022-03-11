# SpringBoot_RabbitMQ_Example


# This SpringBoot RabbitMQ example is done with the docker installation of RabbitMQ

# To launch Docker image of RabbitMQ on your local machine. Run the following command on your terminal.


# docker run -d --hostname my-rabbit --name some-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management

# To view the RabbitMQ dashboard on your local machine. Launch the url

# http://localhost:15672
# Enter default user id : guest
# Enter default password : guest


# Launch the Spring Boot Rabbit MQ Producer Application and Spring Boot Rabbit MQ Consumer Application.


# Using Postman send the message on Rabbit MQ using the url
# http://localhost:9000/publish

# {
#    "message" : "My RabbitMQ Message"
# }


# Verify the message printed in the Rabbit MQ Consumer Application console.

