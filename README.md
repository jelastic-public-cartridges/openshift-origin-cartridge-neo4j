# Jelastic Neo4j Cartridge
This cartridge provides [Neo4j](http://www.neo4j.org/) on Jelastic Platform.

**Neo4j** is an open-source graph database supported by Neo Technology. It stores data in nodes connected by directed, typed relationships with properties on both, also known as a Property Graph. This database uses the most generic data structure, capable of elegantly representing any kind of data in a highly accessible way.

Neo4j is characterized as:
* *intuitive*, using a graph model for data representation
* *reliable*, with full ACID transactions
* *durable and fast*, using a custom disk-based, native storage engine
* *massively scalable*, up to several billion nodes/relationships/properties
* *highly-available*, when distributed across multiple machines
* *fast*, with a powerful traversal framework for high-speed graph queries
* *embeddable*, with a few small jars
* *simple*, accessible by a convenient REST interface or an object-oriented Java API

Follow the [link](http://ops-docs.jelastic.com/private-add-cartridge) in order to find out how to enable the current cartridge at Jelastic dashboard.

### What Jelastic cartridge is?

Jelastic [Platform-as-Infrastructure](http://docs.jelastic.com/what-is-platform-as-infrastructure) supports **OpenShift’s cartridge model** to make it easier for independent software vendors (ISVs) offering core services in multiple platforms and for a wider array of cloud ecosystems and marketplaces. This open standard for technology packaging and deployment enables ISVs and end-users to integrate their own middleware, databases, and services into the platform and make them available to PaaS developers building applications.

A **cartridge** is an advanced packaging format. In our case, it is represented with existing OpenShift cartridge specifications, extended with Jelastic configurations, to provide more complex functionality and the ability to make adjustments in Jelastic. This additional tuning is required based on the difference between the architectures of the two platforms (Jelastic and OpenShift).

Such configuration is quite easy - you just need to fork a basic cartridge and add custom settings. Detailed instruction on how to create your own cartridge can be seen [here](http://ops-docs.jelastic.com/create-cartridge).


### How to add a cartridge to Jelastic Cloud?

Ready cartridge (your own or one of those we’ve already prepared for you) can be added to the Jelastic PaI via JCA. After that it should be tested and published in order to become available through the dashboard. Find out the details in [this](http://ops-docs.jelastic.com/private-add-cartridge) instruction.
