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
    * For a qualitative reseearcher, sentiment analysis algorithms can be coded in Python to increase efficiency and capacity of analysed text. The results can then be visualised using graphical packages from Python or R. {% endcapture %}{% include card.html header="Intermediate" text=text %}

{% capture text %}
Could you code up your work so its completely automated? 
{% endcapture %}{% include card.html header="Advanced" text=text %}
