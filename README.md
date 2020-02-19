# Ansible provisioning

## Ansible

Ansible is a provisioning, configuration management and application-deployment tool.

## How ansible has been used

In this project I have used ansible as a provisioning tool using playbooks. I created two playbooks, one for the application and one for the database. In both the playbooks, they have been written to use shell commands. In the app playbook I installed nginx and nodejs and also removed and created a defaut file in the sites-enabled directory to allow a reverse proxy. In the database playbook I installed mongodb and also removed and created a mongod.conf file to allow port 27017 and changed the bindIP to 0.0.0.0.

## Running the app
to enter the machine containing the app
```
vagrant ssh app
```
in the command line run the following code to enter into the app file:
```
cd /home/ubuntu/app
```
in the command line run the following code to start running the app:
```
node app.js
```

To see the app running type in 'development.local:3000' in the web browser

For more information on using this app https://github.com/dilanmorar/node-sample-app

## Installing ansible

to enter the machine containing the app
```
vagrant ssh app
```
installing the software properties
```
sudo apt install software-properties-common
```
adding the ansible repository
```
sudo apt-add-repository ppa:ansible/ansible
```
updating the sources list
```
sudo apt update
```
installing ansible
```
sudo apt install ansible
```
