# Steps To Get Started On Digital Ocean In Linux

[Reference Link](https://www.digitalocean.com/docs/droplets/how-to/create/)

- ### Create A Droplet In Digital Ocean
    <img src="https://github.com/khuzema786/Digital-Ocean/blob/master/Images/Screenshot%20(92).png"/>
    <img src="https://github.com/khuzema786/Digital-Ocean/blob/master/Images/Screenshot%20(93).png"/>
    <img src="https://github.com/khuzema786/Digital-Ocean/blob/master/Images/Screenshot%20(94).png"/>
    <img src="https://github.com/khuzema786/Digital-Ocean/blob/master/Images/Screenshot%20(95).png"/>
    <img src="https://github.com/khuzema786/Digital-Ocean/blob/master/Images/Screenshot%20(96).png"/>
    <img src="https://github.com/khuzema786/Digital-Ocean/blob/master/Images/Screenshot%20(97).png"/>
    
  - #### Commands (For generating ssh key)
    - ssh-keygen
    - cat ~/.ssh/id_rsa.pub

[Reference Link](https://www.digitalocean.com/docs/droplets/how-to/connect-with-ssh/openssh/)

- ### Connect To Droplet
  - #### Commands
    - ssh root@your_server_ip

[Reference Link](https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-18-04)

- ### Installing Apache Web Server

  - #### Commands
    - sudo apt update
    - sudo apt install apache2
    - sudo ufw app list
    - sudo ufw allow 'Apache'
    - sudo ufw status
      - If status: <b>inactive</b>
        - sudo ufw enable
    - sudo systemctl status apache2

- #### Now enter http://your_server_ip in your web browser, an apache page should be displayed

[Linux Command Line Reference](https://www.howtogeek.com/412055/37-important-linux-commands-you-should-know/)

- ### Adding files in Linux
  - Go to, https://transfer.sh/
  - Upload your all web file and copy the link
  - #### Commands
    - ls
    - cd /var/www/html
    - ls
    -
