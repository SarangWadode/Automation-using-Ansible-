# Automate Docker Using Ansible !

## Ansible
Ansible is an Open-Source IT Automation Engine that is used to automate application deployment, infrastructure automation, cloud provisioning, and many IT services. Ansible improves the scalability, consistency & reliability of the IT environment.

Ansible is easy-to deploy as it is agentless and doesn't require any security infrastructure. Ansible uses the concept of a playbook and uses a language. YAML (Yet Another Markup Language) for its configuration management. Its advantage is that playbooks are so simple that even the support guys can debug it.

## Docker
Docker is an OpenSource containerization platform for Building, Shipping, and Running applications using Container Virtualization technology. Docker packages all the dependencies in form of Docker containers to ensure that our application works seamlessly in any of the environments.

If you are not familiar with Docker and have not installed Docker on your device, you can go through my last article mentioning the installation  [here](https://hashnode.com/post/get-started-with-docker-ckhud2v3p01pyses11ply63rn).

For Automation, we need to write a PlayBook for the following operation given below.

* Configure Docker
* Start and enable Docker services
* Pull the httpd server image from the Docker Hub
* Run the httpd container and expose it to the public
* Copy the html code in /var/www/html directory and start the webserver


