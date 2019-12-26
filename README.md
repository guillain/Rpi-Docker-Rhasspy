# Rpi-Docker-Rhasspy
Just a quick fashOn to have a personnal voice assistant up & ready in 1 minute! 


It's based on server (1 container) and for the demo on one client (another container :)

## Pre-requisite
- Raspberry min 3
- At least a micro-phone
- Network access (two web nterfaces provided) 
- Docker up & ready (under *pi* user)

## HowTo...

### Start & Configure 
1/ Execute the script `./run`. This will create two containers (rhasspy-server and rhasspy-client)`

2/ Finalise the **server** configuration
  - Go on the web interface of the server (http://<IP>:12101) and valid the package to install
  - train your models

3/ Finalise the **client** configuration
  - Go on the web interface of the client (http://<IP>:12102) and valid the package to install
  - Play with!!!

### Stop
Execute the script `./stop`

### Clean
Execute the script `./clean`

## Support
- Rhasspy doc: https://rhasspy.readthedocs.io/en/latest/tutorials/#clientserver-setup
- Rhasppy git: https://github.com/synesthesiam/rhasspy
- Raspberry: https://www.raspberrypi.org
- Docker: https://www.docker.com
 
