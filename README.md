# Auto-deploy Ubuntu Server 20.04.5 on ESXi host

## Prepare

 ```pip3 install --upgrade -r pip_requirements.txt```
 ```ansible-galaxy collection install --upgrade -r requirements.yml```

## Usage

 ```ansible-playbook UbuntuOnESXi.yml --ask-become-pass```
--ask-become-pass needed for running apt (installing packages for autoinstall script)

## Password in Ubuntu

copy output of command below to /ISO/user-data in password: section
 ```openssl passwd -salt xx password```

# Wordpress on ESXi VM

## Prepare

 ```pip3 install --upgrade -r pip_requirements.txt```
 ```ansible-galaxy collection install --upgrade -r requirements.yml```

## Usage

 ```ansible-playbook WordPressOnVM.yml ```

