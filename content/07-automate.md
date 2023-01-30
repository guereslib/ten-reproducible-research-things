---
nav_order: 8
title: 7 - Automation
---

{% include figure.html img="2022_AutoImage.JPG" alt="Image representing automation" caption="Automating repetitive data tasks can reduce errors." width="75%" %}

## Can you automate any repetitive tasks?

Often, computer tasks that need to be done over and over again by a human can be opportunities for error to sneak in. Setting up an automated way of running repetitive (and boring) tasks can eliminate this issue. Anything from a MS Excel formula or macro to coding in a data science frameword can help.

{% capture text %}
Let's think about the repetitive tasks that you could automate - do you always rename files the same way? Do you manually copy files across?

Ways you can automate things:
* Spreadsheet Macros and formulas - [Using macros in microsoft excel to facilitate cleaning of research data](https://doi.org/10.1080/20009666.2021.1954282) has instructions on how.
* MacOS - Automator [find out how to automate 10 useful things](https://www.idownloadblog.com/2018/11/21/cool-things-mac-automator-tutorial/)
* Win 10 - Task scheduler [learn how with this blog post](https://www.windowscentral.com/how-create-automated-task-using-task-scheduler-windows-10)
* [Microsoft Power Automate](https://powerautomate.microsoft.com/en-gb/) or [Google Apps Script](https://www.google.com/script/start/){% endcapture %}{% include card.html header="First steps" text=text %}

{% capture text %}
From survey tools to programming languages, there are several ways to automate beyond macros, and spreadsheet formulas. If you are reliant on a survey tool to conduct qualitative research, try and select a survey tool with a lot of functionality. For example, some survey tools allow the survey creator/administrator to request demographic responses, which then informs how a survey particpants is guided through the survey with specific questionnaires for each predefined demographic.

Alternatively, could you code up your work so its completely automated?
* Learn to code in [Python](https://www.python.org/) or [R](https://www.r-project.org/) - Talk to your local hacky hour or Software Carpentry people.

Developing code requires an initial outlay of effort, but you will reap rewards in future time saved.

* **Data Cleaning**
    * Code can be used to automatically process data, impute corrections, or format data into long/wide structures. 

* **Data Analysis and Visualisation**
    * For a qualitative reseearcher, sentiment analysis algorithms can be coded in Python to increase efficiency and capacity of analysed text. The results can then be visualised using graphical packages from Python or R. 

## Create and Capture

Collecting qualitative data is commonplace across many research projects. As such, having a robust automated survey solution can improve research workflows and the quality of data being collected.

Griffith University maintains two official survey tools:

* REDCap (Research Electronic Data Capture)
* LimeSurvey

Each solution has different strengths and its own use cases. To learn more about these tools, visit this Griffith site: https://www.griffith.edu.au/library/research-publishing/working-with-data/create-and-capture

There are also two repositories for self-paced learning: 

* REDCap - https://griffithunilibrary.github.io/redcap-intro/
* LimeSurvey - https://griffithunilibrary.github.io/limesurvey/

{% endcapture %}{% include card.html header="Intermediate" text=text %}

{% capture text %}
In 2022, the National Academies of Sciences, Engineering, and Medicine published a report titled *Automated Research Workflows for Accelerated Discovery: Closing the Knowledge Discovery Loop.*

The National Academies Press defines Automated Research Workflows as: (NAS, 2022, p. 22)
* *ARWs integrate computation, laboratory automation, and tools from artifical intelligence in the performance of tasks that make up the research process such as designing experiements, observations, and simulations; collecting and anlaysing data; amd learning from the results to inform further experiments, observations, and simulations.*

Artificial intelligence and machine learning (AI/ML) are beginning to be used more and more as fundamental drivers of ARW capabilities. The various sub-disciplines of AI/ML can support various stages of ARW design. Such as, text analysis for literature reviews; quantitative data science for analysis, computation, and visualisation; and learning algorithms for future experimental design. 

Workflows projects and programs support distributed computing, scalable data processing, or querying large and distributed datasets. Interactive notebooks such as Jupyter/RStudio have a place to support human-computer interaction as steps within steps (chunks) can be analysed for performance, tweaked, and improved.

**An example using climate science:**

Distributed computing and its scalability has allowed for simulation of high resolution climate models. ML is used to analyse micro-scale weather interactions both in a simulated environment and the real world. Data from space, ground, and ocean sensors can be integrated through various pipelines to one location to be used as a sole source for computaiton, simulation and analysis. 

Please see the image below for a graphic representation of this ARW concept in practice.

{% include figure.html img="Ch7_Climate_Automation_Graphic.JPG" alt="Climate science ARWn" caption="The 'learning and observing' feedback loops associated with this Automated Research Workflow." width="75%" %}

**If you identify the need for an Automated Research Workflow in your project, contact eResearch Services at Griffith University to start the conversation at: https://www.griffith.edu.au/eresearch-services**

{% endcapture %}{% include card.html header="Advanced" text=text %}
