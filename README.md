# Applied Container Basics for Data Scientists 

# Prerequisites

Basic Linux.
Docker Installation.

# Why Containers?

Today's modern computing requires use to use more and more dependencies. 
If you have ever used the `pandas`, `NumPy` or `Keras` libraries, then you have used an application dependency. 

A Container like Docker is a process that can help reduce application deployment complexity by packaging all the specific ingredients for your app so you can ship and deploy your application to any production environment whether that is a private server or public cloud such as Amazon Web Services, Google Cloud or Microsoft's Azure Cloud.

Learning to build your own containers is powerful skillset that can help you and your team save money, deploy faster and more frequently, and leverage powerful infrastruture to power your applications to scale to many end users.

To illustrate: we will download and run an linux server with one command:

```
Ensure Docker is installed by the following command:
docker --version
```

```
docker run -it ubuntu /bin/bash
```

Once you see your terminal to change to root@..., type: 

```
ls
```

![image](https://user-images.githubusercontent.com/4943759/149857696-32a773c5-19ba-4df0-a4b3-773e6710ea87.png)


You should the file contents of a full Ubuntu linux server! Congrats!

Did you notice how fast it took to run a container process of a entire server? 

Did you notice the simplicity?

In this course, we will continue to walk through all the benefits of containers and build custom containers of increasing complexity step by step.

We will build production-level python, fastapi, react, redis, worker queue containers to deploy your machine-learning or application code to modern cloud services such as Google Cloud Run.


