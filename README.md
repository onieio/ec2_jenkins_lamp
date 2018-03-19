# Ansible Ec2 spin up, Jenkins Github OAuth and LAMP Stack Playbooks
Ec2 spin up with new *.pem file and updateting the hosts file aswell.
Jenkins installation with Java8
This is a Ansible Playbook to deploy a LAMP Stack infrastructure on ubuntu hosts. 


### Ec2
* ec2
### Jenkins
* Github OAuth Jenkins
### Stack - 
* apache2
* mysql 
* php7.0-fpm 


### Pre-requisites
Boto (Aws Acccess/Secret key)
python 2
You must have Ansible 2.3 installed.
Create an organizaton on github and generate clientID and Client secret


### Setup
* Run command `sudo ansible-playbook -i hosts lamp.yml`
 
* Run command `sudo ansible-playbook -i hosts ec2.yml`

* Run command `sudo ansible-playbook -i "jenkins.domain.com," jenkins-github-Oauth.yml`



### Database Configuration
* USERNAME: root
* PASSWORD: rajendra@75


Note:
test -e /usr/bin/python || (sudo apt -y update && sudo apt install -y python-minimal)


