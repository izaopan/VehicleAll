# VehicleAll

Contains all components

To build the executable jars

## To start the containerized apps
1. go to vehicle-monitor-system
mvn clean install spring-boot:repackage

2. go to frontend
mvn clean install
mvn run build

3. go back to the root folder:
docker-compose up


## Other commands
docker-compose build 
  or 
docker-compose up --build
