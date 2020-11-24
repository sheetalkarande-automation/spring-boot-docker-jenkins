## Overview

An example project to demonstrate:

* Continous intigration pipeline for Spring boot app containarization with Jenkins (Pipeline as code)


## Pre-requisites

* JDK 11+
* Docker

## Spin up container
* docker run -p <8087>:8080 -d --name <ko_ko> <msrinivascharan>/spring-boot-api-example:0.1.0-SNAPSHOT
## Using API

* get all rides - GET [/ride](http://localhost:8080/ride) to get a list of all the rides
* get specific ride - GET [/ride/${id}](http://localhost:8080/ride/1) to get a specific ride
* create ride - POST JSON to [/ride](http://localhost:8080/ride) to create a new ride 
(see [article](https://tomgregory.com/building-a-spring-boot-application-in-jenkins/#2_Trying_out_our_Spring_Boot_application) for full details)
