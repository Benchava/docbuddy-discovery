# docbuddy-discovery
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/b12f11b394294ff78e3284006d1d127a)](https://www.codacy.com/app/Benchava/docbuddy-discovery?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=nbantar/docbuddy-discovery&amp;utm_campaign=Badge_Grade)
[![Build Status](https://travis-ci.org/nbantar/docbuddy-discovery.svg?branch=master)](https://travis-ci.org/nbantar/docbuddy-discovery)

Note: This is a continuous WORK IN PROGRESS.

## SUMMARY

Discovery is a service that the Netflix's Eureka service as a registration point for all the other services that compose
the architecture of the Docbuddy app.
DocBuddy is a REST API developed as part of a test for implementing a small micro-services architecture.
The complete set of micro-services are meant to work as a small system to manage Doctor-Client relationships and also to
serve as a way of having a centralized clinical history for them.

## TECHNOLOGIES

JDK is built using Java 8, Gradle, Spring-Boot, Lombok and Eureka (Netflix) among other technologies.

## HOW TO RUN IT

JDK uses Spring-Boot so, once the project is cloned and built (using Gradle), all you have to do is run the 
"bootRun" gradle task and the service will come up.
The API can be hit using Postman or any other tool that you see fit.