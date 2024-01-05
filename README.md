# **V-Profile-using-Docker**
Hosted a web application using multiple services over multiple VMs by the help of Bash scripting and Docker.
Created a whole pipeline of Deployment of an application containing data in different VMs having multiple services (NGINX, Tockat Apache, MySQL, Memcached & Rabbit MQ) by both Manual and Automated Provisioning using the Docker.

Solution for this is been done locally and publically in both ways.
a. Locally we will create multiple VMs manually using Vagrant and provision them using the commands.
The feaures of using and doing the setup locally is - The whole procedure will be automated, it is repeatable, Infrastructure as a Code (TAAC) is utilised, Research and Development (R&D) can be done in our own machine.
b. Publically using the Docker service to create and upload the provisioned Docker images and post them on Docker hub so that others can also use and utilise the code.

All the services being used in the VMs are -
NGINX - Used as a front end server/web server also can be used as a Load Balancer.
Tocat Apache - Application server used to host Java Web Applications
MySQL - Used as a SQl Database server.
Rabbit MQ - Used as a message broker.
Memcached - Used as in memory key value storage for arbitrary data (strings, objects) from results of database calls.
