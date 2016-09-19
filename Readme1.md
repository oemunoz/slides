---
layout: slide
title: Slides&#58;Software Engineering  
description: A presentation for OSS to SEMAT
theme: black
transition: slide
---

<section data-background="/images/background.png" data-markdown data-separator="^----" data-separator-vertical="^====" >

![Men Working](/images/menworking.png "Document under maintenance!")

Warnings:
There are some attempts at humor here.

----

# Software engineering

Software engineering is the application of engineering to the design, development, implementation, testing and maintenance of software in a systematic method.

https://en.wikipedia.org/wiki/Waterfall_model

![Google search](/images/WhyRAD/GoogleSearchWaterfall.png "Google searh: waterfall methodology")

_
====

# Software Development Methodologies

[![UFF what a miss](/images/WhyRAD/methodologies.png "List methodologies")](http://www.itinfo.am/eng/software-development-methodologies/)


----

# Software Development Methodologies

- [Waterfall ](http://www.cs.umd.edu/class/spring2003/cmsc838p/Process/waterfall.pdf)
- [OSSD ](http://oss-watch.ac.uk/resources/softwaredevelopment)
- [Agile ](http://agilemanifesto.org/principles.html)
- [RAD ](http://www.revolvy.com/main/index.php?s=Rapid%20application%20development)

_
====

# Waterfall methodology

Winston Royce 1970.

[![Waterfall Royce](/images/WhyRAD/1970-WaterfallWinsonRoyce2.gif "Royce 1970")](http://www.cs.umd.edu/class/spring2003/cmsc838p/Process/waterfall.pdf)

 A Waterfall Systems Development Methodology … Seriously? From wikipedia

_
====

## publish or perish

Some sceptics suggest that the waterfall model is a false argument used purely to market alternative development methodologies.

[![publish or perish](/images/WhyRAD/death-motto-team-university-uni-publisher-cgan2808_low.jpg "List methodologies")](https://www.cartoonstock.com/directory/c/chancellors.asp)

----

### open-source methodology ([OSSD ](http://oss-watch.ac.uk/resources/softwaredevelopment) Open Source Software Development)?

[![UFF Another methodologie](/images/WhyRAD/OSSD_process_data_diagram.png "List methodologies")](http://www.itinfo.am/eng/software-development-methodologies/)

----

### Agile

[![UFF Another methodologie](/images/WhyRAD/maxresdefault.jpg "List methodologies")](https://www.google.com.co/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=0ahUKEwihzZ27kJvPAhXK1x4KHWwuDnoQjxwIAw&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DCb-EQDDwqq8&bvm=bv.133178914,d.eWE&psig=AFQjCNEVjA4eMiDivwWzaxr5pW4dzpDSdg&ust=1474364111752418)

_
====

[Method or methodology, ](http://whanauoraresearch.co.nz/news/method-or-methodology-whats-the-difference/) what’s the difference?

- Methods,               
**Research methods are the tools**, techniques or processes that we use in our research. These might be, for example, surveys, interviews, Photovoice, or participant observation. Methods and how they are used are shaped by methodology.

- Methodology,
Is the study of how research is done, how we find out about things, and how knowledge is gained. In other words, [methodology is about the principles ]((http://agilemanifesto.org/principles.html) that guide our research practices. Methodology therefore explains why we’re using certain methods or tools in our research.

----

### Why RAD describe the open-source

Put less emphasis on planning and **more emphasis on process**.

- RAD as approximation to open-source methodology.
- Because some projects need easy, fast methodology.
- Simplicity in the work is a key factor on RAD.
- Strong customer communication.
- Projects that generate many deliverables, are not easily administrable.

_
====

You be able to get a compressive RAD introduction on [Rapid application development ](http://www.revolvy.com/main/index.php?s=Rapid%20application%20development).

![Alt text](http://g.gravizo.com/g?
  digraph G {
  subgraph cluster_rad {
    style ="filled";
    color ="lightgrey";
    label ="Children";
    userdesing [label="User Desing"];
    construction [label="Construction"];
    userdesing -> construction -> userdesing;
  }
  requerplan [label="Requirements Planning"];
  requerplan -> userdesing;
  construction -> cutover;
  node [shape=box,style=filled,color=".7 .3 1.0"];
  title [label="RAD"];
  }
)

_
====

## [RAD ](http://www.revolvy.com/main/index.php?s=Rapid%20application%20development) approaches emphasized **developing prototypes**:

- Risk Reduction
- Users are better at using it
- Prototypes can be re-usable
- Deliver new Apps in days rather than mounts
- Innovate via funcional prototypes rather than UI scketchs

_
====

The actuals technologies modify the methodology, the current technologies make the code often rapid.

[![publish or perish](/images/WhyRAD/DevO.png "List methodologies")]()

_
====

### How open-source centralize efforts?

RAD is a methodology oriented to the available tools:
  - How most of open-source projects works?
  - Which tools are using?

----

## RAD dimensions

According to Steve McConnell (McConnell 1996), there are four dimensions of development speed:

  - people
  - process
  - product
  - technology

[![RAD projects componets](/images/WhyRAD/mcquaid_fig1.gif "Project Management Issues to Consider")](http://asq.org/pub/sqp/past/vol3_issue3/mcquaid.html) [![RAD projects componets](/images/WhyRAD/bur_e1_radelements.gif "Essential ingredients of RAD")](https://www.dlsweb.rmit.edu.au/toolbox/ecommerce/bur_respak/bur_e1/html/bur_e1_intro.htm)

_
====

# **People**:

- Revision Control System
- Communication

_
====

## Revision Control System

The best people must be well-trained in both the methodology and the tools. Small teams that work consistently well together should be grouped together on assignments.

  - Remote work.
  - Same Version Control software (GIT for be specific).

[![RAD projects componets](/images/WhyRAD/centr-decentr2x.png "A successful Git branching model")](http://nvie.com/posts/a-successful-git-branching-model/)


_
====

[![GIT](/images/WhyRAD/github_data.png "Git branching model")](https://github.com/hakimel/reveal.js/graphs/commit-activity)

_
====

[![GIT](/images/WhyRAD/github_data1.png "Git branching model")](https://github.com/hakimel/reveal.js/graphs/commit-activity)


_
====

[![GIT](/images/WhyRAD/github_data2.png "Git branching model")](https://github.com/hakimel/reveal.js/graphs/commit-activity)

_
====

## Communication

[![Slack](/images/WhyRAD/slack.png "A successful Git branching model")](http://www.a2apple.com/slack-attack/)

_
====

## Communication

According to a survey of its users, Slack adoption has resulted in a 49% reduction in email volume. Nearly 80% of users indicate that it improves transparency and office culture, while reducing the number of superfluous meetings by 24%. On average, users report productivity increases of more than 32%.

[![Slack](/images/WhyRAD/slackEfi.png "A successful Git branching model")](http://www.a2apple.com/slack-attack/)

----

# **Tools**:
Software programs that help Systems Analysts and Designers to analyze, document and construct information systems.

_
====

### Docker the world (Actual Example of set of tools for many type of software).

![alt tag](/images/WhyRAD/AppDep.png)

Docker is an open-source program that enables a Linux application and its dependencies to be packaged as a container.

_
====

Containers technology keeps some time around, this fact of Docker make a very strong, but this essentially is not only a technology advance is a methodology advance.

  - The other containers options are persistent.
  - Docker can instance multiple instances from the same image.
  - GitHub

![alt tag](/images/WhyRAD/DevO.png)

_
====

# Continuous Integration

[![alt tag](/images/WhyRAD/JeqCI.jpg)](http://www.oracle.com/technetwork/articles/java/deployment-tools-2227133.html)



----

# **Management**:
Set of process or techniques such as facilitated the Management of Issues, Requirements etc.

_
====

  - Task and requirements can be split to smaller parts. Smaller means better objectives and control.
[![RAD projects componets](/images/WhyRAD/GitHubReq.png "Requirements management in GitHub")](http://www.sis.uta.fi/~tp54752/pub/github-requirements/github-requirements.pdf)
  - The term "business process" is sometimes used by IT practitioners as synonymous with the management of middleware processes or with integrating application software tasks.

[![Alt text](http://g.gravizo.com/g?
      digraph G {
         subgraph clusterA { labeljust=l; label="sectionA@company.com";
          AS [label="", shape=circle, width="0.3"];
          AE [label="", shape=circle, width="0.3", style=bold];
          A1 [label="A1:step1"];
          A2 [label="A2:step2"];
          A3 [label="A3:step3"];
          A4 [label="A4:step4"];
          Ae [label="Ae:error\ncase"];
          A5 [label="A5:step5\nLong Name"];
          AS -> A1;
          A5 -> AE [weight=10];
          A1 -> A2 -> A3 -> A4 -> A5 [style=invis,weight=10];
          A4 -> Ae;
          Ae -> AE;
          {rank=same Ae A5};
         }
         subgraph clusterB { labeljust=l; label="sectionB@company.com";
          B1 [label="B1:step1"];
          B2 [label="B2:step2"];
          B3 [label="B3:step3"];
          B4 [label="B4:step4", style="rounded,filled" fillcolor=red];
          B5 [label="B5:step5", style="rounded,filled" fillcolor=green];
          B1 -> B2 -> B3 -> B4 -> B5 [style=invis];
         }
         subgraph clusterBL { labeljust=l; label="sectionB-leader@company.com";
          BL1 [label="BL1:step1"];
          BL2 [label="BL2:Message", shape=ellipse, style=dotted];
          BL3 [label="BL3:TEXT", shape=none];
          BL1 -> BL2 [style=invis];
          BL2 -> BL3 [minlen=2];
         }
        A1 -> B1 [arrowtail=odiamond, label="X>100"];
        B1 -> BL1 [arrowtail=rcrowlvee];
        B2 -> A4 [tailport=ne,headport=w];
        B2 -> BL2 [arrowhead=onormal, style=dotted]
      }
    "Q-BPM:Process Diagram Images")](http://en.q-bpm.org/mediawiki/index.php/Q-BPM:Process_Diagram_Images)
  - UML was meant to be a unifying language enabling IT professionals to model computer applications.
[![Alt text](http://g.gravizo.com/g?
  @startuml;
  actor User;
  User -> A: DoWork;
  activate A;
  A -> B: Create Request;
  activate B;
  B -> C: DoWork;
  activate C;
  C --> B: WorkDone;
  destroy C;
  B --> A: Request Created;
  deactivate B;
  A --> User: Done;
  deactivate A;
  @enduml
  )](http://www.ffnn.nl/pages/articles/media/uml-diagrams-using-graphviz-dot.php)

[![Alt text](http://g.gravizo.com/g?
@startuml;
Object <|-- ArrayList;
Object : equals%28%29;
ArrayList : Object[] elementData;
ArrayList : size%28%29;
@enduml
 "UML diagrams for Jekyll and Markdown")](http://www.dilek.me/uml/plantuml/markdown/2016/01/15/Uml-diagrams-in-Markdown-pages/)

### SEMAT is not new, had some impact on software development?

### Opportunity
The set of circumstances that makes it appropriate to develop or change a software systems.

![Alt text](http://g.gravizo.com/g?
  digraph G {
  subgraph cluster_rad {
    style ="filled";
    color ="lightgrey";
    node [style=filled,color=white];
    label ="RAD";
    userdesing [label="User Desing"];
    construction [label="Construction"];
    userdesing -> construction -> userdesing;
  }
  requerplan [label="Requirements Planning"];
  requerplan -> userdesing;
  construction -> cutover;
  node [shape=box,style=filled,color=".7 .3 1.0"];
  title [label="RAD/Opportunity"];
  subgraph cluster_oppor {
    style ="filled";
    color ="darkseagreen3";
    node [style=filled,color=white];
    label ="Opportunity";
    identified [label="Identified"];
    solutioneed [label="Solution Nedded"];
    value [label="Value Established"];
    viable [label="Viable"];
    addressed [label="Addressed"];
    benefit [label="Benefit Accrued"];
    }
    node [shape=box,style=filled,color="darkseagreen3"];
    identified -> requerplan;
    solutioneed -> requerplan;
    value -> requerplan;
    viable -> requerplan;
    addressed -> userdesing;
    benefit -> cutover;
  }
)

### Stakeholders
The people, groups or organizations that affect or are affected by a software systems.

![Alt text](http://g.gravizo.com/g?
  digraph G {
  subgraph cluster_rad {
    style ="filled";
    color ="lightgrey";
    node [style=filled,color=white];
    label ="RAD";
    userdesing [label="User Desing"];
    construction [label="Construction"];
    userdesing -> construction -> userdesing;
  }
  requerplan [label="Requirements Planning"];
  requerplan -> userdesing;
  construction -> cutover;
  node [shape=box,style=filled,color=".7 .3 1.0"];
  title [label="RAD/Stakeholders"];
  subgraph cluster_stakeholders {
    style ="filled";
    color ="darkseagreen3";
    node [style=filled,color=white];
    label ="Stakeholders";
    recongnized [label="Recognized"];
    represented [label="Represented"];
    involved [label="Involved"];
    inagreement [label="In Agreement"];
    satisfed [label="Satisfed for Deplyment"];
    inuse [label="Satisfed in Use"];
    }
    node [shape=box,style=filled,color="darkseagreen3"];
    recongnized -> requerplan;
    represented -> requerplan;
    involved -> requerplan;
    inagreement -> userdesing;
    satisfed -> userdesing;
    inuse -> cutover;
  }
)

### Requirements
What the software system must do to address the opportunity and satisfy the stakeholders.

![Alt text](http://g.gravizo.com/g?
  digraph G {
  subgraph cluster_rad {
    style ="filled";
    color ="lightgrey";
    node [style=filled,color=white];
    label ="RAD";
    userdesing [label="User Desing"];
    construction [label="Construction"];
    userdesing -> construction -> userdesing;
  }
  requerplan [label="Requirements Planning"];
  requerplan -> userdesing;
  construction -> cutover;
  node [shape=box,style=filled,color=".7 .3 1.0"];
  title [label="RAD/Requirements"];
  subgraph cluster_stakeholders {
    style ="filled";
    color ="lightgoldenrod";
    node [style=filled,color=white];
    label ="Requirements";
    conceived [label="Conceived"];
    bounded [label="Bounded"];
    coherent [label="Coherent"];
    acceptable [label="Acceptable"];
    addressed [label="Addressed"];
    fulfilled [label="Fulfilled"];
    }
    node [shape=box,style=filled,color="darkseagreen3"];
    conceived-> requerplan;
    bounded -> requerplan;
    coherent -> userdesing;
    acceptable -> userdesing;
    addressed -> construction;
    fulfilled -> cutover;
  }
)

### Software System
A system made up of software, hardware, and data that provides its primary value by the execution of the software.

![Alt text](http://g.gravizo.com/g?
  digraph G {
  subgraph cluster_rad {
    style ="filled";
    color ="lightgrey";
    node [style=filled,color=white];
    label ="RAD";
    userdesing [label="User Desing"];
    construction [label="Construction"];
    userdesing -> construction -> userdesing;
  }
  requerplan [label="Requirements Planning"];
  requerplan -> userdesing;
  construction -> cutover;
  node [shape=box,style=filled,color=".7 .3 1.0"];
  title [label="RAD/Software System"];
  subgraph cluster_stakeholders {
    style ="filled";
    color ="lightgoldenrod";
    node [style=filled,color=white];
    label ="Software System";
    achiselected [label="Achitecture Selected"];
    demostrable [label="Demostrable"];
    usable [label="Usable"];
    ready [label="Ready"];
    operational [label="Operational"];
    retired [label="Retired"];
    }
    node [shape=box,style=filled,color="darkseagreen3"];
    achiselected-> requerplan;
    demostrable -> requerplan;
    usable -> construction;
    ready -> cutover;
    operational -> cutover;
    retired -> cutover;
  }
)

### Team
The group of people actively engaged in the development, maintenance, delivery, and support of a specific software system.

![Alt text](http://g.gravizo.com/g?
  digraph G {
  subgraph cluster_rad {
    style ="filled";
    color ="lightgrey";
    node [style=filled,color=white];
    label ="RAD";
    userdesing [label="User Desing"];
    construction [label="Construction"];
    userdesing -> construction -> userdesing;
  }
  requerplan [label="Requirements Planning"];
  requerplan -> userdesing;
  construction -> cutover;
  node [shape=box,style=filled,color=".7 .3 1.0"];
  title [label="RAD/Team"];
  subgraph cluster_stakeholders {
    style ="filled";
    color ="lightskyblue";
    node [style=filled,color=white];
    label ="Team";
    seeded [label="Seeded"];
    formed [label="Formed"];
    collaborating [label="Collaborating"];
    performing [label="Performing"];
    adjourned [label="Adjourned"];
    }
    node [shape=box,style=filled,color="darkseagreen3"];
    seeded-> requerplan;
    formed -> requerplan;
    collaborating -> userdesing;
    performing -> userdesing;
    adjourned -> construction;
  }
)

### Work
Activity involving mental of physical effort done in order to achieve a result.

![Alt text](http://g.gravizo.com/g?
  digraph G {
  subgraph cluster_rad {
    style ="filled";
    color ="lightgrey";
    node [style=filled,color=white];
    label ="RAD";
    userdesing [label="User Desing"];
    construction [label="Construction"];
    userdesing -> construction -> userdesing;
  }
  requerplan [label="Requirements Planning"];
  requerplan -> userdesing;
  construction -> cutover;
  node [shape=box,style=filled,color=".7 .3 1.0"];
  title [label="RAD/Team"];
  subgraph cluster_stakeholders {
    style ="filled";
    color ="lightskyblue";
    node [style=filled,color=white];
    label ="Work";
    initiated [label="Initiated"];
    prepared [label="Prepared"];
    started [label="Started"];
    undercontrol [label="Under Control"];
    concluded [label="Concluded"];
    cloused [label="Cloused"];
    }
    node [shape=box,style=filled,color="darkseagreen3"];
    initiated -> userdesing;
    prepared -> userdesing;
    started -> userdesing;
    undercontrol -> construction;
    concluded -> cutover;
    cloused -> cutover;
  }
)

## Way of Working
The tailored set of practices and tools used by a team to guide and support their work.

![Alt text](http://g.gravizo.com/g?
  digraph G {
  subgraph cluster_rad {
    style ="filled";
    color ="lightgrey";
    node [style=filled,color=white];
    label ="RAD";
    userdesing [label="User Desing"];
    construction [label="Construction"];
    userdesing -> construction -> userdesing;
  }
  requerplan [label="Requirements Planning"];
  requerplan -> userdesing;
  construction -> cutover;
  node [shape=box,style=filled,color=".7 .3 1.0"];
  title [label="RAD/Team"];
  subgraph cluster_stakeholders {
    style ="filled";
    color ="lightskyblue";
    node [style=filled,color=white];
    label ="Team";
    prinest [label="Principles Established"];
    foundation [label="Foundation Established"];
    inuse [label="In Use"];
    inplace [label="In Place"];
    workingwell [label="Working Well"];
    retired [label="Retired"];
    }
    node [shape=box,style=filled,color="darkseagreen3"];
    prinest -> userdesing;
    foundation -> userdesing;
    inuse -> userdesing;
    inplace -> construction;
    workingwell -> cutover;
    retired -> cutover;
  }
)



![Alt text](http://g.gravizo.com/g?
  digraph G {
  subgraph cluster_rad {
    style ="filled";
    color ="lightgrey";
    node [style=filled,color=white];
    label ="RAD";
    userdesing [label="User Desing"];
    construction [label="Construction"];
    userdesing -> construction -> userdesing;
  }
  requerplan [label="Requirements Planning"];
  requerplan -> userdesing;
  construction -> cutover;
  node [shape=box,style=filled,color=".7 .3 1.0"];
  title [label="RAD/Team"];
  subgraph cluster_stakeholders {
    style ="filled";
    color ="lightskyblue";
    node [style=filled,color=white];
    label ="Team";
    prinest [label="Principles Established"];
    foundation [label="Foundation Established"];
    inuse [label="In Use"];
    inplace [label="In Place"];
    workingwell [label="Working Well"];
    retired [label="Retired"];
    }
    node [shape=box,style=filled,color="darkseagreen3"];
    p1 [shape=hexagon, style=bold, label=<first line<br/><font point-size="8">second line</font>>, image="images/menworking.png", labelloc=b];
    prinest -> userdesing;
    foundation -> userdesing;
    inuse -> userdesing;
    inplace -> construction;
    workingwell -> cutover;
    retired -> cutover;
  }
)

### State of Art

Some academy authors make to think that a methodology is requested by software develop, the methodology are overrated and the most part of time the academy is not a vanishing point. But this article is about RAD and the actual emphasis on prototyping, the [article](https://opensource.com/business/15/12/docker-improves-software-development-ez) make an approximation to the point.

![alt tag](/images/containership.png)

### Git make the difference on development.
![alt tag](/images/WhyRAD/GitAll.png)

Open source isn't about a set of free tools, are communities of developers working together. Then where are the methodology there? why some of the most important projects of software born on this environment?

"Git is a brilliant piece of software that has redefined how we do open source development, and software development in general. Certainly there were other distributed version control tools before it, but nothing in my time in the industry has so dramatically changed how we version and share our work." - [10. How Git redefined open source software development](https://opensource.com/life/14/4/git-redefine-open-source-software-dev)

![alt tag](/images/WhyRAD/linux-kernel.0021.jpg)

Things we always have, always do, always produce when developing software:

![alt tag](/images/WhyRAD/git_workflow_github_flow.jpg)

![alt tag](/images/WhyRAD/Linux-25-graphic-Linux-Development.png)

### Useful links

- [Motherfucker methodology](http://programming-motherfucker.com/)
- [1. Hybrid App Development Using RAD Tools A Buzzword For Enterprises](http://www.slideshare.net/algoworks/hybrid-app-development-using-rad-tools?qid=079921ae-066f-4ee7-a69f-0ef26c1ad9db&v=&b=&from_search=1)
- [2. Definitive checklist to buy a RAD Platform](http://www.slideshare.net/KarthickViswanathan2/definitive-checklist-to-buy-a-rad-platform?qid=51545b25-ee69-4884-aac8-7224674ca7ff&v=&b=&from_search=10)
- [3. Open Source Development](http://www.lcc.uma.es/~amg/ISE/OOP-Java-UML/Chapter9.html)
- [4. DevOps and Continuous Delivery Reference Architectures](http://www.slideshare.net/SonatypeCorp/nexus-and-continuous-delivery)
- [5. Rapid Application Development in the Cloud](http://www.slideshare.net/niklasheidloff/rapid-application-development-in-the-cloud-and-onpremises-with-docker?ref=http://heidloff.net/article/05.10.2015094641NHEB5Q.htm)
- [6. Motherfucker methodology](http://programming-motherfucker.com/)
- [7. Methodological challenges and reference data for Open Source](http://pear.accc.uic.edu/ojs/index.php/fm/article/view/1151/1071)
- [8. IBM strikes Docker deal and rolls out its own Containers beta](http://www.zdnet.com/article/ibm-strikes-docker-deal-and-rolls-out-its-own-containers-beta/)
- [9. Rapid application development](http://www.revolvy.com/main/index.php?s=Rapid%20application%20development)
- [10. How Git redefined open source software development](https://opensource.com/life/14/4/git-redefine-open-source-software-dev)
- [11. LINUX FOUNDATION RELEASES REPORT ON LINUX DEVELOPMENT](http://www.enterpriselinuxinsights.com/linuxcon-news-linux-foundation-releases-report-on-linux-development/)
- [12. Project Management Issues to Consider RAD](http://asq.org/pub/sqp/past/vol3_issue3/mcquaid.html)
- [sematacc](http://sematacc.herokuapp.com/demo)

### Future:
- [Combining agile and SEMAT yields more advantages than either one alone](http://queue.acm.org/detail.cfm?id=2541674)
- [ReadySET](http://readyset.tigris.org/nonav/templates/frameset.html)
- [sematcc](https://github.com/s4fs/sematacc)
- [Agile and SEMAT](https://www.ivarjacobson.com/sites/default/files/field_iji_file/article/agile_and_semat_v0.91.pdf)
- [software development methodology](http://agilerules.blogspot.com.co/2014/07/software-development-methodologies.html)
- [The Advantages of Virtualization in Software Development](https://www.techopedia.com/2/30932/trends/virtualization/the-advantages-of-virtualization-in-software-development)
- [Virtualization technologies for agile software development](http://www.ibm.com/developerworks/aix/library/au-virtualizationagile/)
- [
Software Development Methodologies](http://www.itinfo.am/eng/software-development-methodologies/)
-[Getting RAD with CakePHP](http://bennyfreshness.com/2009/08/rapid-application-development-with-cakephp/)
- [OpenUP –The Best of Two Worlds](http://www.methodsandtools.com/archive/archive.php?id=69)
- [Requirements management in GitHub with a
lean approach](http://www.sis.uta.fi/~tp54752/pub/github-requirements/github-requirements.pdf)
- [GitLab Flow](https://about.gitlab.com/2014/09/29/gitlab-flow/)
- [Git Branching and Merging Strategies](https://www.youtube.com/watch?v=to6tIdy5rNc&t=1208s)

- [Rapid Prototyping is an Enduring Methodology.](http://chipdesignmag.com/sld/blog/2015/09/24/rapid-prototyping-is-an-enduring-methodology/)
- [EPF Wiki.](http://epf.eclipse.org/)
- [Redhat SEMAT EXISTS](http://redhat.slides.com/mherbert/methodologies-10-11?token=3OlK22cp#/)


Nuevas competencia:

Como es el modelo de CI en semat.
Como es el fork and rebase (o merge) de codigo.
Si Agile esta muerto tambien Semat?

Si no puedo ver como fluye el desarrollo menos puedo enmarcar el CI o el Branching para el Prototyping

Tesis:
- Tal y como trabaja el software libre actualmente es un modelo RAD.
- No veo como encajan las tecnicas de actuales de desarrollo en Semat.


No space for the comunities on SEMAT

most of projects needs a simple strategy not a methology
Works on issues on github, the tags are important for projects, must be based on SEMAT.

Que actores estan involucrados?
- Quien prueba la aplicacion?

Con software boolebar cuantos buscaron una alternativa open source.
SEMAT knows GIT
OPEN SORUCE IS SHARE IN ESSEENCE

Todas las personas tienen su propia opinion sobre la ingenieria del software, y metodologias, por eso usamos herramientas en donde es es posible.


</section>
