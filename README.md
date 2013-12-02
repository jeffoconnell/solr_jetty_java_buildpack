#Oracle Java 1.7, Jetty, and SOLR Buildpack
Work in progress, proceed at your own peril

#Basics
This buildpack will install:
    * Oracle JDK 1.7
    * Jetty web server 9.1.0.20131115
    * SOLR 4.5.1


#SOLR Config
The installation will look for a /solr directory at $1, and copy those files and directories into /opt/solr as part of the installation.