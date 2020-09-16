# websphere thin client

[![Build Status](https://travis-ci.org/sjeandeaux/websphere-thin-client.svg?branch=develop)](https://travis-ci.org/sjeandeaux/websphere-thin-client)

TIPS:

* [console](http://localhost:9060/ibm/console)

## installation

## All you need is love and these following jars

* com.ibm.ws.admin.client_9.0.jar (/opt/IBM/WebSphere/AppServer/runtimes/com.ibm.ws.admin.client_9.0.jar)
* com.ibm.ws.orb_9.0.jar (/opt/IBM/WebSphere/AppServer/runtimes/com.ibm.ws.orb_9.0.jar)
* com.ibm.ws.security.crypto.jar (/opt/IBM/WebSphere/AppServer/plugins/com.ibm.ws.security.crypto.jar)
* ibmkeycert.jar (/opt/IBM/WebSphere/AppServer/java/8.0/jre/lib/ext/ibmkeycert.jar)
* ibmpkcs.jar (/opt/IBM/WebSphere/AppServer/java/8.0/jre/lib/ibmpkcs.jar)

```bash
mvn clean verify
```
(Besides Maven repos: `docker cp` or https://github.com/ducquoc/legacy_m2_repo/tree/master/release )

## Play


https://ducquoc.wordpress.com/2011/02/20/websphere-thin-client/#WebSpherethinclient-Launching


```bash
./wsadmin.sh \
             -host <your host> \
             -user wsadmin \
             -password was \
             -f wonderful-script.py \
```


## Jenkins 

```
https://plugins.jenkins.io/websphere-deployer/
```

### Plugin Custom Tools

  https://github.com/orctom/was-util

  https://github.com/orctom/was-gradle-plugin#parameters

  https://github.com/orctom/was-maven-plugin#parameters

TODO

### How do we use it

```
  https://github.com/orctom/was-gradle-plugin#continues-deployment-with-jenkins
  https://github.com/orctom/was-maven-plugin#continues-deployment-with-jenkins
```

TODO
