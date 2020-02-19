# Ansible provisioning

## Ansible

Ansible is a provisioning, configuration management and application-deployment tool.

## How ansible has been used

In this project I have used ansible as a provisioning tool using playbooks. I created two playbooks, one for the application and one for the database.  
## Running the app

in the command line run the following code to enter into the app file:
```
cd /home/ubuntu/app
```
in the command line run the following code to install the npm (node packaging manager):
```
npm install
```
in the command line run the following code to populate the /posts page:
```
node seeds/seed.js
```
in the command line run the following code to start running the app:
```
node app.js
```

To see the app running type in development.local:3000

For more information on using this app https://github.com/dilanmorar/node-sample-app

## Installing ansible

enter machine
```
vagrant ssh
```
installing
```
sudo apt install software-properties-common
```
fghj
```
sudo apt-add-repository ppa:ansible/ansible
```
updating
```
sudo apt update
```
installing ansible
```
sudo apt install ansible
```
