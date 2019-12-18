---
layout: col-sidebar
title: OWASP Docker Top 10
tags: Docker
level: 2
type: documentation
pitch: none yet
---


## About Docker Top 10

The OWASP Docker Top 10 project is giving you ten bullet points to plan and implement a secure docker container environment. Those 10 points are ordered by relevance. They don't represent risks as each single point in the OWASP Top 10, they represent security controls. The controls range from baseline security to more advanced controls, depending on your security requirements.

You should use it as a
* guidance in the design phase as a system specification or
* for auditing a docker environment,
* also for procurement it could provide a basis for specifying requirements in contracts.


## Where is it? / Getting Involved

Development and discussions take place @ [Github](https://github.com/OWASP/Docker-Security Github). After release you will find the released version also here.

## Description

This guide is for developers, auditors, architects, system and networking engineers. As indicated above you can also use this guide for externals to add formal technical requirements in your contract. The information security officer should have some interest too to meet security requirements.

The 10 bullet points here are about system and network security and also architecture. As a developer you don't have to be an expert in those -- that's what this guide is for. But as indicated above best is to start thinking about those points early. Please do not just start building it.

Security in Docker environments seemed often to be misunderstood. It was/is a highly disputed matter what the threats are supposed to be. So before diving into the Docker Top 10 bullet points, the threads are modeled. It not only helps understanding the security impacts but also gives you the ability to prioritize your task.


## Why not "Container Security"

Albeit the name of this project carries the word "Docker", it also can be used with little abstraction for other containment solutions. Docker is as of now the most popular one, so the in-depth details are focusing for now on Docker. This could change later.

## A single container?

If you run more than 3 containers you probably have an orchestration solution to manage them. '''Specific''' security pitfalls of those are currently beyond the scope of this document. That doesn't mean that this guide just looking at one or a few containers managed manually -- on the contrary. It means only that we're looking at the containers including their networking and their host systems in such an orchestrated environment and not on special pitfalls of e.g. ''Kubernetes'', ''Swarm'', ''Mesos'' or'' OpenShift''.

## Licensing

[![license](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-nc-sa.svg)](https://github.com/OWASP/Docker-Security/blob/master/License.md)

The Docker OWASP Top 10 document is licensed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/), the Creative Commons Attribution-ShareAlike 4.0 license. Some rights reserved.


## Roadmap

The highest priorities for the next months are:

* Publish and work on a first draft of the documentation
* Complete this first draft
* Get other people involved to review the documentation and provide feedback
* Incorporate feedback into the documentation
* First Release

Subsequent Releases will add

* Go from Draft to Release
* Being promoted from an Incubator Project to a Lab Project

## Project Leader

Dirk Wetter


