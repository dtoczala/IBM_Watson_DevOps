# IBM_Watson_DevOps
A collection of Python code and examples showing how to implement a DevOps pipeline.

**Author :** [D. Toczala](https://github.com/dtoczala)

**Contributors:** None yet

## Description

IBM Watson gives people the ability to deploy amazing applications and services based on a variety of different artificial intelligence capabilities and technologies.  One thing that is needed by many IBM customers, is the ability to move these applications and their associated components into new environments.

The vision for this is illustrated in the slide deck called "Cognitive_DevOps_Arch.pptx".  This shows all of the various Watson services, and highlights the issues and challenges in creating DevOps mechanisms for these services.  The first part of this deck focuses on HA architectures because they are also important for many Watson customers.  The challenges of DevOps and HA architectures both typically boil down to the ability to "save" or "snapshot" a cognitive capability, and then the ability to create a second instance of that capability that **_IS IDENTICAL IN FUNCTIONALITY TO THE ORIGINAL_**.  The HA use case then has additional requirements in the routing of traffic, data, and coordination of state between the different instances.

## Contents

This project consists of a large Python notebook.  This notebook can be copied and run (once you have modified it for yourself.  It is probably best if you brek it into pieces, as one of the cells should be pulled into it's own _IBM_CogDevOps.py_ file and then can be imported into any project.  The remainder of the code is more of an "example" of Python code that we use to test out these Python DevOps operations.

### The Example project

The example project is called _Cognitive\_DevOps\_Main.ipynb_.  It uses the IBM_Watson_DevOps module.

### The Common DevOps Module

The common DevOps module for the IBM Watson services is called _IBM_Watson_DevOps.py_.  It is what most people will be interested in.
