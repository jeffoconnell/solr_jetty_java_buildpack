#Oracle Java 1.8, Jetty, and SOLR Buildpack

#Basics
This buildpack will install:
* Oracle JDK 1.8
* Jetty web server 8.1.12
* SOLR 4.4.0
* MongoDB 2.6.0

#SOLR Config
This installation will copy all files in the root of the service repository
on top of the solr to `solr-home`. Typically, you will have a solr.xml and you
`./cores` right off the root of your service repository.
