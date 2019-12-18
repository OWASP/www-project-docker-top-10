---

layout: col-sidebar
title: OWASP Docker Top 10
tags: Docker
level: 2
type: documentation

---


== About Docker Top 10
The OWASP Docker Top 10 project is giving you ten bullet points to plan and implement a secure docker container environment. Those 10 points are ordered by relevance. They don't represent risks as each single point in the OWASP Top 10, they represent security controls. The controls range from baseline security to more advanced controls, depending on your security requirements.

You should use it as a
* guidance in the design phase as a system specification or
* for auditing a docker environment,
* also for procurement it could provide a basis for specifying requirements in contracts.


== Where is it? / Getting Involved

Development and discussions take place @  [https://github.com/OWASP/Docker-Security Github]. After release you will find the released version also here.

== Description

This guide is for developers, auditors, architects, system and networking engineers. As indicated above you can also use this guide for externals to add formal technical requirements in your contract. The information security officer should have some interest too to meet security requirements.

The 10 bullet points here are about system and network security and also architecture. As a developer you don't have to be an expert in those -- that's what this guide is for. But as indicated above best is to start thinking about those points early. Please do not just start building it.

Security in Docker environments seemed often to be misunderstood. It was/is a highly disputed matter what the threats are supposed to be. So before diving into the Docker Top 10 bullet points, the threads are modeled. It not only helps understanding the security impacts but also gives you the ability to prioritize your task.


== Why not "Container Security"

Albeit the name of this project carries the word "Docker", it also can be used with little abstraction for other containment solutions. Docker is as of now the most popular one, so the in-depth details are focusing for now on Docker. This could change later.

== A single container? ==

If you run more than 3 containers you probably have an orchestration solution to manage them. '''Specific''' security pitfalls of those are currently beyond the scope of this document. That doesn't mean that this guide just looking at one or a few containers managed manually -- on the contrary. It means only that we're looking at the containers including their networking and their host systems in such an orchestrated environment and not on special pitfalls of e.g. ''Kubernetes'', ''Swarm'', ''Mesos'' or'' OpenShift''.

== Licensing

The Docker OWASP Top 10 document is licensed under the [https://creativecommons.org/licenses/by-nc-sa/4.0/ Creative Commons Attribution-ShareAlike 4.0 license] (CC BY-NC-SA 4.0). Some rights reserved.

[[File:CC-BY-SA-NC.4.0.size88x31.png|link=https://creativecommons.org/licenses/by-nc-sa/4.0/]]

== Roadmap

The highest priorities for the next months are:

* Publish and work on a first draft of the documentation
* Complete this first draft
* Get other people involved to review the documentation and provide feedback
* Incorporate feedback into the documentation
* First Release

Subsequent Releases will add

* Go from Draft to Release
* Being promoted from an Incubator Project to a Lab Project

== Project Resources

'''Github'''<br />
*  See [https://github.com/OWASP/Docker-Security Github]
<br />
'''Slides'''<br />
* Dirk Wetter: ([https://www.owasp.org/images/f/fd/Dirk_Wetter_-_Docker_Top10-OWASP_KA.pdf long version, talk in Karlsruhe]), ([https://www.owasp.org/images/7/7e/Dirk_Wetter_-_Docker_Security_GOD2018.pdf short version @ German OWASP Day 2018]),
* Dirk Wetter, older talks from [https://www.owasp.org/images/1/17/Dirk_Wetter_-_Docker_Security_Brussels.pdf Belgium Chapter Meeting], [https://2018.appsec.eu/presos/DevOps_Docker_201_Security_Dirk-Wetter_AppSecEU2018.pdf OWASP AppSec Europe 2018]


* Jack Mannino and Abdullah Munawar: [https://2018.appsec.eu/presos/DevOps_Securing-Containers_Jack-Mannino_Abdullah-Munawar_AppSecEU2018.pptx Slides of Presentation]  at OWASP AppSec Europe 2018

== Project Leader
Dirk Wetter



<!-- Standard Chapter Page Template
This is an example of a Project or Chapter page.
Please change these items to indicate the actual information you wish to present. In addition to this information, the 'front-matter' above the text should be modified to reflect your actual information.  An explanation of each of the front-matter items is below:

{front matter for this file}

```
- layout: This is the layout used by project and chapter pages.  You should leave this value as col-sidebar
- title: This is the title of your project or chapter page, usually the name.  For example, OWASP Zed Attack Proxy or OWASP Baltimore
- tags: This is a space-delimited list of tags you associate with your project or chapter.  If you are using tabs, at least one of these tags should be unique in order to be used in the tabs files (an example tab is included in this repo) 
- region: This is the region you are in according to our data
```

{copy for this file (index.md)}
Replace the text above the commented area with your information in the format below:
```
## Welcome
Include some information here about your chapter

## Participation
The Open Web Application Security Project (OWASP) is a nonprofit foundation that works to improve the security of software. All of our projects ,tools, documents, forums, and chapters are free and open to anyone interested in improving application security. 

Chapters are led by local leaders in accordance with the [Chapter Leader Handbook](/www-policy/rules-of-procedure/chapter-handbook). Financial contributions should only be made online using the authorized online donation button. To be a SPEAKER at ANY OWASP Chapter in the world simply review the [speaker agreement](/www-policy/speaker-agreement) and then contact the local chapter leader with details of what OWASP Project, independent research, or related software security topic you would like to present.

Everyone is welcome and encouraged to participate in our [Projects](/projects), [Local Chapters](/chapters), [Events](/events), [Online Groups](https://groups.google.com/a/owasp.com/){:target='_blank'}, and [Community Slack Channel](https://owasp.slack.com/){:target='_blank'}. We especially encourage diversity in all our initiatives. OWASP is a fantastic place to learn about application security, to network, and even to build your reputation as an expert. We also encourage you to be [become a member](/membership) or consider a [donation](/donate) to support our ongoing work.

## Local News
- Meeting Location
- Everyone is welcome to join us at our chapter meetings.

```
{info.md}

This separate file is where you should place links to your Google Group and Meetup page. It will be automatically rendered in the column sidebar.

{leaders.md}

Another separate file that should simply include each leaders name with mailto link as a list. It will also be automatically rendered in the column sidebar.

-->
