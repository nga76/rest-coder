Introduction
============

REST Coder is a collection of tools for auto-generating documentation and client stubs for RESTful web APIs. This release of REST Coder comes with four primary tools.

 * Client stub generators

   * Python client stub generator
   * JavaScript/AJAX client stub generator

 * API doc generators

   * Sphinx API doc generator
   * HTML API doc generator

Each of the above tools take an API description (specification) in JSON format as input. Client stubs generated by REST Coder tools can be embedded in a wide range of desktop, mobile and web applications to consume the target web APIs with or without human intervention. The documentation generated by these tools can be published on the web as reference material for the developers and users. The REST Coder stub generators are primarily designed for application and mashup developers who regularly need to write code that consumes one or more web APIs. The REST Coder documentation generators allow generating high-quality API docs from a given API specification, which allows API providers to publish comprehensive API docs for their APIs, and speed up the release cycles by avoid spending time on manually writing and editing API docs.

Prerequisites
-------------

The Python client stub generator and Sphinx API doc generator require following software to be setup.

* `Python 2.7 <http://www.python.org/download/releases/2.7>`_
* `Sphinx documentation engine <http://sphinx-doc.org>`_

The AJAX client stub generator and the HTML API doc generator require following software to be setup.

* JDK 1.6 or higher
* NodeJS and Express (Installation Instructions included on the documentation)

Installation
------------

Use a Git client to check out the necessary source and binary artifacts of RESTCoder. ::

  git clone https://github.com/hiranya911/rest-coder.git

No additional installation/setup procedures are necessary.

If you also wish to setup the sample ``Starbucks`` service to run some tests using RESTCoder, you need to first download and install `Apache Tomcat 6.0 or higher <http://tomcat.apache.org>`_. Copy the ``starbucks-1.0-SNAPSHOT.war`` file in the ``java-lib`` directory of RESTCoder into the ``webapps`` directory of Tomcat, and start the Tomcat server. The mock service will be available on the URL http://localhost:8080/starbucks-1.0-SNAPSHOT

Next Steps
----------

Refer the documentation of individual REST Coder tools to learn more about how to use them. 

 
