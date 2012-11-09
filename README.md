java-quickstart
===============

My preferred quick-start config for a new "java" project

Need to keep a template + example of my best practices for setting up a project

Maven
======

Multi-module
Dependency management
Profile for build
Site generate
Unit + IT tests running (including deploy+Selenium)
Metrics (Checkstyle, PMD, FindBugs ...)
push to repository

Spring-ROO
==========

My current preferred bootstrap solutions
Required steps to go-live

Testing
=======

Unit test + mocking
IT test (with/out Embedded env management)
BDD (jBehave + Selenium)
CI (hudson/jenkins,sonar...)

IDE
====

Eclise vanilla / STS settings for getting started
Formatter / setting config files
Maybe a yoxos config

Documentation
=============

mylyn usage to JIRA
umlet + "wiki" interaction/integration

Example(s) App
============

Still need the app scope (another TODOMVC?)
CRUD + some flows + ACEGI + "Locking"

Few architectures:
* POWA: Plain Old Web App in pure Spring MVC (PURE JAVA)
* RESTful: RESTful API (with 2 backend SpringMVC or Jersey) + JMVC clients (canJS.us)
* JEE: multi-modules: core, engine, web(s), ws(s), ear(s) for scattered deployment with EJB,JMS...(AppServer(s)-JobServer(s)-WebServer(s))
