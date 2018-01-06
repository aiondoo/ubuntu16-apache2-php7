# ubuntu16-apache2-php7
Docker Image ubuntu16.04, apache2, php7

Run:
  - docker pull aiondoo/ubuntu16-apache2-php7:latest
  
  - docker run -itd -p 127.0.0.1:8083:80 \
    -v /tmp:/var/www/html  \
    --name=dev_php7 \
    aiondoo/ubuntu16-apache2-php7:latest

  - docker exec -i -t dev_php7 /bin/bash
  - cd /var/www/html
