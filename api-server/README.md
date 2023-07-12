# mochat
mochat

docker run -it --rm -w /var/www/html -v$(pwd):/var/www/html --name php mochat/mochat:v1 /bin/bash

composer install
