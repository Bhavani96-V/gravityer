FROM tomcat:latest
WORKDIR /apps
RUN apt update && apt upgrade
COPY . /apps
EXPOSE 8080
CMD ["catalina.sh" , "run"]
