# Kamstrup-Radius to MQTT deamon
Based on Python example provided by Radius and work by https://github.com/Asbjoern/
Idea is a stable well behaved deamon for getting power usage data and more from the Kamstrup meter (model 486)

## Project contains:
my-reader.py - daemon code

## Plan: 
 - Figure out the specifications for a well behaved UNIZ daemon and make the code behave in this way.
 - Signals from the meter comes in burst every 10 seconds, figure out how to read data at the correct interval, every time.
 - Do some logging
 - Make different output modules (MQTT, file, DB?)
 - Maybe make it into a docker container

## Tasks:

Development in Develop branch. Working releases in master branch.
