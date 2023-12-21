# aepc configuration files
this is the readme for aepc project configuration files
## utility microservices files:
	- ***ms-registration-service.yml***
	- ***back-front-gateway-service.yml***
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
- each service contacts the configuration server to get its configuration
- the config server checks the git repository where all services config are located
- the config server pulls and expose configuration for the service that need it
