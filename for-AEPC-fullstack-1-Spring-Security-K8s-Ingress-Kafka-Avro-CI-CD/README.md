# aepc configuration files
this is the readme for aepc project configuration files
## utility microservices files:
	- ***ms-registration-service.yml***
	- ***gateway-proxy-service.yml***
## security microservoce file:
	- ***ms-spring-security-service***
## business microservices files:
	- ***clean-archi-bs-ms-address.yml***
	- ***clean-archi-bs-ms-employee.yml***
	- ***clean-archi-bs-ms-project.yml***
	- ***clean-archi-bs-ms-company.yml***
## common configurations to all microservices
	- ***application.yml***
the configurations inside each file are made for docker images related
## startup scenario:
On application start up:
- each service gets the configurations from config server
- the config server checks the git repo of all services configurations
- the config server pulls and expose configuration for the services
