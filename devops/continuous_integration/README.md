# Continuous Integration

Continuous integration (CI) is the practice of continuously integrating (and testing) new code with your existing source code, merging all developer working copies to a shared mainline several times a day.

It aims to avoid integration problems and deliver the software often, but with the security it will work, so it's based in "maximum automation".


![alt text](https://github.com/beeva/beeva-best-practices/blob/master/static/horizontal-beeva-logo.png "BEEVA")

# Index


* [Objectives](#objectives)
* [Technologies and tools](#)
	* [Jenkins](#jenkins)
		* [Funcionamiento general](#funcionamiento)
		* [Consejos de uso](#consejos)
		* [Herramientas y plugins](#herramientasyplugins)
			* [Maven (compilación)](#maven)
			* [SVN (control de versiones)](#svn)
			* [Git/Github (control de versiones)](#git)
			* [Sonar (calidad de código)](#sonar)
			* [Selenium (pruebas de navegabilidad de front)](#selenium)
			* [Dimensions (herramienta de control de versiones y despliegue entre entornos usada en BBVA)](#dimensions)
		* [Bamboo](#bamboo)


## Objectives

This document aims at make a complete description of the continuous integration system used in BEEVA projects.

Using CI we will be able to keep a making sure the software checked in on the mainline is always in a state that can be deployed. 
Test, support, development and operations work together as one delivery team to automate and streamline the build, test and release process.

Continuous Delivery is the natural extension of Continuous Integration: an approach in which teams ensure that every change to the system is releasable, and that we can release any version at the push of a button.

To help in this work, there are a variety of tools available like Jenkins, Apache Continuum or Bamboo.



## Architecture, technologies and tools


### Jenkins

Jenkins is an continuous integration and continuous delivery application that increases your productivity allowing to build and test your software projects continuously making it easier for developers to integrate changes to the project, and making it easier for users to obtain a fresh build.

#### How Jenkins work

Jenkins needs an installed Tomcat versión 5.0 or later.
Jenkins requires Java7 or above to function. Java8 is recommended. Jenkins requires a fair amount of memory to operate well. Smaller installations should start around 256MB-1GB.

[Jenkins install official documentation](https://wiki.jenkins-ci.org/display/JENKINS/Tomcat)


In the next picture you can see the list of jobs ready to be executed in a jenkins instance.

![Jenkins Projects](static/jenkins_projects.png)


Primary options to configure, execute and a history of the executed jobs
![Jenkins job options](static/jenkins_job_options.png)


The result of a deploy in a Jenkins job:

![Jenkins job deploy 1](static/jenkins_job1.png)
![Jenkins job deploy 2](static/jenkins_job2.png)

#### Configuration





### Maven



### Sonar


### Bamboo

Bamboo is a continuous integration and delivery tool that ties automated builds, tests and releases together in a single workflow.


[BEEVA](http://www.beeva.com) | 2015

