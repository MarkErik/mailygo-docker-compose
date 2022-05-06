# mailygo-docker-compose
A Branch of Jan-Lukas Else and Emanuel Pina MailyGo Form Service for use behind Nginx Proxy

I added a Docker file (for building and running the service), and a Docker Compose file to run the service behind a Nginx Proxy.

If you want to use this, clone this repository, and edit the Compose yaml file and input your own SMTP mailer information, as well as URL.

The MailyGo server listens on 8080 (which can be changed), and the Nginx Proxy handles the HTTPS connection, so you don't need to use the port in the HTML form.

All credit to the original authors:
https://codeberg.org/emanuelpina/mailygo
https://git.jlel.se/jlelse/MailyGo

