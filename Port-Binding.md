### port Binding  ###

# 1. docker run -p8080:3306 IMAGE_NAME
-->

--> when we create a container which get binded to a port

## example ##
docker run -d -e MYSQL_ROOT_PASSWORD= secret --name mysql-latest -p8080:3306 mysql

