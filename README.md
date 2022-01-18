# Applied Container Basics for Data Scientists 

# Prerequisites

Basic Linux.
Docker Installation.

# Why Containers?

Today's modern computing requires use to use more and more dependencies. If you have ever used the `pandas`, `NumPy` or `Keras` libraries, then you have used an application dependency. 

A Container like Docker is a process that can help reduce application deployment complexity by packaging all the specific ingredients for your app so you can ship and deploy your application to any production environment whether that is a private server or public cloud (aws, azure, google).

Learning to build your own containers is powerful skillset that will allow you to save money, increase development and build powerful applications that can scale. 

```
Ensure Docker is installed by the following command:
docker --version
```

```
docker run -it ubuntu /bin/bash
```

Congrats, we have just downloaded a linux image of type Ubuntu.
