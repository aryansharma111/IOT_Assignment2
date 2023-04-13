# IOT_Assignment2
IOT Assignment 2

Here, the objective is to develop a kind of weather station that uses a variety of sensor readings based on its choice. It is a component of the course application project for Syracuse University's MS in Cybersecurity program.
We simulate data sensors in Python and feed them to Thingsboard in JSON format. The script can be found on Github. We must first download the library using the following command before running the script: Installing MQTT with --save
Start a connection between the client and our broker using the host, port, and topic values demo.thingsboard.io, v1/devices/.
Real-time modifications require the Websocket API and its authorization, which may be deduced from: Using this bash script and an X-Authorization token, http POST http://demo.thingsboard.io/api/auth/login 'Content-Type:application/json' 'Accept:application/json'
We use the command line tool httpie to make HTTP requests with JSON payloads.
Download the required libraries to speed up the connection to the cloud service.
