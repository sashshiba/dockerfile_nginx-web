# dockerfile_nginx-web
FROM nginx:latest
RUN apt-update
RUN apt-get install -y git
RUN git pull https://github.com/oscarplatoon/static-webpage.git
