# Selfmade integrations for NSACyber's WALKOFF project 
Here to show off some integrations ive made related to https://github.com/nsacyber/WALKOFF
Other apps that are NOT UP TO DATE can be found at https://github.com/nsacyber/WALKOFF-apps

* RE TheHive issue: https://github.com/TheHive-Project/TheHive/issues/956
* TheHive webhook that can interact easily: https://github.com/frikky/walkoff-webhook

## Apps 
* thehive 		- Contains two specific endpoints to interact with TheHive
* cortex 		- (CHANGE api.yaml for prod) Can find and run analyzers 
* helper 		- Has some helper functions useful for JSON & string manipulation
* splunk		- Can run searches in splunk 
* Carbon Black 	- Can isolate and run process / binary searches in cb

## Goal
* Help analysts leveraging TheHive & MISP be able to automate processes without the need for writing code (This is hard :()) 
* Automate wrapper creation for python libraries & swagger docs (this might take a while)

## Done-ish
* generator - autogenerating a new app based on an input library (done with thehive4py). This might make walkoff apps easier to create :) 
* docker - An attempt at making it easier to deploy in an enterprise setting without docker-compose and a lot of proxy issues

## Todo
* Add TheHive webhook directly as an app - Not sure how to approach this
* MISP testing
