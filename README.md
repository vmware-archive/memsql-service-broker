
# Overview

This sample project uses the Spring Cloud - Cloud Foundry Service Broker to implement a MemSQL service broker and assumes that you have MemSQL running somewhere and have access to it.

Steps to run MemSQL Broker:

1. Checkout the memsql service broker from github
2. Option 1: Upload the .pivotal artifact in memsql-service-broker/tile/product/releases to your Ops Manager (tested on and works on Version 1.6.9+) and set up your MemSQL configuration
3. Option 2: Navigate to memsql-service-broker/tile
4. $ > mvn clean
5. $ > mvn package
6. $ > tile init
7. $ > tile build
8. Upload the newly created .pivotal artifact from memsql-service-broker/tile/product/releases to your Ops Manager (tested on and works on Version 1.6.9+) and set up your MemSQL configuration as usual



