# rpi-ts3server
Teamspek 3 server on Raspberry 3 with Docker


Pull:

docker pull adralim/rpi-ts3server


To launch container :

docker run -it -d -p 9987:9987/udp -p 30033:30033 <image_id>

Recover token and admin password in container log file.
