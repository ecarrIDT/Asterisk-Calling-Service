# Asterisk-Calling-Service
Calling Service that allows a software application to do basic telephony call flows by interfacing with the Asterisk telephony software


## Description
The Asterisk Calling Service (ACS) is the middleware between applications that wish to dial out to customer to play a prompt and/or 
collect digits and to the Asterisk software that provides the calling capabilities and the media capabilities.  ACS will be written 
in GoLang and will be a micro-service to the applications such that requests will be sent via HTTP PUT and HTTP GET requests.  

ACS uses webhooks (initially) to report back to the application certain events from Asterisk related to the call session.  ACS will 
interface to Asterisk using a combination of web sockets (that are used to see the status changes for all the call sessions) and HTTP requests which are used to send Asterisk requests.

ACS goal is to provide Communications-as-a-Service (CaaS) and will look to replace the PCS OCM Server/Dialer component to play messages to Boss Revolution Customers.

## Features

## Requires
### CyCoreSystems -- For the Golang version of the Asterisk RESTful Interface (ARI)

## Configurations

## Jenkins Build

## How to run locally

## How to run from Docker container

## Monitoring

## Logs

## Alerts
