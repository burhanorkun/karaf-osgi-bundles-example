#Karaf OSGI bundle example

A short OSGI example with two bundles.

###Setting up the karaf environment
Download and unzip karaf 4.3.0 Start the server and the console using

```
bin\karaf
```

after mvn clean install we can install bundles. 

```
install mvn:org.ogra/Bundle1/0.0.1-SNAPSHOT
```

```
install mvn:org.ogra/Bundle2/0.0.1-SNAPSHOT
```
