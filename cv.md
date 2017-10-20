# CV - Kim Johansson

Kim is a senior developer and system operator with more than 8 years of
experience in web based systems. The past years Kim has focused on
infrastructure automation, continuous integration and deployment
pipelines, with Amazon Web Services as the main target.

Kim is new in the consultancy-world, but has solid experience in
upscaling applications, migrating from physical hardware to the cloud and
creating agile development workflows.

## Recent Projects

### Devrex/Memstate 2017

Assisting in the development of an in-memory database built upon the idea
of Command-Query Responsibility Segregation and Command-sourcing.

*Tech used:* .NET Core, CQRS, PostgreSQL

### Devrex/TJAFS 2017

Created a web application to manage bookings and book pickups of trash.

*Tech used:* .NET Core, ASP.NET Core, C#, PostgreSQL, AWS CloudFormation, AWS EC2, Ansible

### Medaptation 2017

Added features on an existing Android application written in Java.

*Tech used:* Android, Android Studio, Java

### Detectify 2017

Created a monitoring solution based on Collectd, Graphite and Grafana. Alerted on
disk usage, CPU usage, RAM usage, etc.

*Tech used:* Ansible, Collectd, Graphite, Grafana, Nginx, CloudFormation

### Detectify 2017

Scrapped the old logging solution based on Graylog and introduced a new one based
on Elasticsearch, Logstash, Kibana and various beats. This was done to allow greater
flexibility and more control over the logged data.

*Tech used:* Elasticsearch, Kibana, Logstash, Filebeat, Journalbeat, Ansible, CloudFormation

### Detectify 2017

Set up automatic deployment of PHP websites via TeamCity, using Ansible to do the configuration
of the target instances.

*Tech used:* nginx, PHP, php-fpm, Ansible, CloudFormation

### Detectify 2016

Created a logging solution based on Graylog. Each application sent their logs via
the syslog receiver in Graylog.

*Tech used:* Graylog, Ansible, CloudFormation

### Detectify 2016

Set up a 3 node Elasticsearch cluster. A node to do analytics and provide a web based
dashboard where also set up.

*Tech used:* Elasticsearch, Ansible, CloudFormation

### Detectify 2016

Created an internal dashboard in ASP.NET MVC Core to collect information about systems
in all environments and to do common tasks, like restarting services, resolve websites
and hostnames within the different environments.

*Tech used:* ASP.NET MVC Core, Ansible, CloudFormation, Fleet, SSH, cURL

### Detectify 2015

Set up TeamCity to build and publish all microservices and custom AMIs. Documented and
taught how to use TeamCity to collegues.

*Tech used:* Jetbrains TeamCity, Docker, Go, PHP, .NET, Windows, Bash, Ansible

### Detectify 2015

Set up a CoreOS cluster to host all microservices. Configured automatic repairing of the cluster
in case a node failed.

*Tech used:* CoreOS, Etcd, Fleet, Docker, Ansible, AWS EC2 AutoScaling

### Detectify 2015

Migrated old environment into a new environment managed by AWS CloudFormation, configured with
Ansible. Used the built in snapshot capabilities in AWS RDS to move the data from the EC2 Classic
environment into the VPC environment.

*Tech used:* CloudFormation, Ansible, AWS RDS

### Detectify 2015

Set up two VPN instances with OpenVPN to allow all employees to connect to the different environments.
The instances provided redundancy and different levels of security.

*Tech used:* OpenVPN, CloudFormation, Ansible

### Detectify 2015

Set up a RabbitMQ instance to allow services to use publish/subscribe and request/response communication
with each other.

*Tech used:* RabbitMQ, Ansible, CloudFormation

### Detectify 2015 - 2017

Maintained the entire stack of applications. Websites, microservices, servers, database services, queue
servers, etc.

*Tech used:* N/A

### Bosbec 2015

Built a complete invoice and payment solution optimized for high transaction throughput.

The systems was deployed as two applications, one server which ran as a Windows Service and one
ASP.NET MVC website which ran in IIS.

*Tech used:* C#, .NET, PostgreSQL, Rebus, RabbitMQ, Dapper, ASP.NET MVC