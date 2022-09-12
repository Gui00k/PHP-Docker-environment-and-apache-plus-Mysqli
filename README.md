# PHP-Docker-environment-and-apache-plus-Mysqli

For create the container just go to the paste locate the composer file and run docker-compose up -d

Remember that 
volumes:
      - ./:/var/www/html/ 
will be created along with the container, everything you put in this folder is linked to the container and will automatically be updated
