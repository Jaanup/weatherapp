This version of the weatherapp has been made to work in google cloud in the address http://weather.inconclusive.info:8000/ where it is running as I'm typing this readme

There are 2 docker files and a docker compose file, if one were to clone this repository it could be deployed with just the command 'sudo docker-compose build && sudo docker-compose up
' provided that the system used is a ubuntu system or any other that uses sudo with the caveat that all the configuration files point to the domain inconclusive.info, so those would have to be changed before one were to deploy this.

There are certain things in the code that aren't recomended, like using "disable hosts check" which leaves the host vunerable to dns rebinding attacks, this will be fixed once I figure out how.


