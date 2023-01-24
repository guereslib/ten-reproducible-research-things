---
nav_order: 5
title: 4 - Documentation
---
{% capture text %}
Scenario: A key person from your research team has left suddenly, could you continue your work? {% include icon.html icon='person-x' color="success" %}{% endcapture %}{% include alert.html text=text color=success %}

Throughout your research, you make many choices, from topic to methodology, from techniques to measurements, from data source to storage format. The choices you make at one stage will affect the choices you make at the next.  

For your research to be reproducible in the future, even by you, all those choices need to be documented and available. 

There may be more than one valid way to collect and to analyse data but if the same choices are not made later, the result may be different. Methods can vary, equipment may measure and record differently, approaches may have inherent biases for which adjustments need to be made. Each data point needs to be interpreted in the context in which it was collected. 

The choices made at the time may seem obvious, but it may not be so in future. Choices are often limited by methodology or technology but both may undergo changes or digital disruption after the project is over, or even during the project.  

Within a research group, another possible disruption is the loss of one of the members of the team. If that happens with someone whose role or skills are crucial to the project. Comprehensive documentation can be crucial to the future of the project when someone new takes over that role. 

{% include alert.html text="*'Documentation is a love letter to your future self'* - Dr Damian Conway, Computer Scientist" align="center" color="success" %}

## Documentation to safeguard the project

Documentation also reduces the risk to a research team from a low **Bus Factor**. 

The *Bus Factor* is the number of people who, if they were suddenly lost to the team (e.g., if they were hit by a bus), would cause a major disruption to the project and would compromise the entire research process. It is also called the *Lottery Number*, which has a more positive connotation but the threat to the team remains the same. 

{% include figure.html img="Busfactor.jpg" alt="Bus Factor" caption="Bus factor" width="50%" %}

Individual circumstances can change suddenly and if it should occur to one member of the team whose loss would cause major disruption, that is considered to be a *Bus Factor* of 1. The smaller the number, the greater the danger to the project. The number of people that would have to be lost for the research project to fail must be as high as possible. 

As an example, Terry is responsible for the coding for processing and analysing the data for a team project. To the rest of the team, his ability in coding is impressive, and they don't believe they have the skills and aptitude to do this work so they rely upon him to lead in this process. Terry enjoys his work and his status within the group. 

One day, Terry announces that his wife has been offered a lucrative position overseas and Terry is resigning. Suddenly, most of the knowledge of Terry’s role will be lost to the team.  Without careful management, a major change to a research team could be more than just disruptive; it has the potential to corrupt the entire project. 

Comprehensive documentation is the major strategy for minimising the disruption. 

## How?
{% capture text %}
Read [How to start Documenting and more](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/2.-Organise-Document/Documentation-and-metadata) by the *Consortium of European Social Science Data Archives* and the *European Research Infrastructure Consortium*. Take note of sections on how you can start documenting a project at study level and data level, and the methods for qualitative and quantitative data. 
 
* Start by documenting in a text (.txt) file or Micrososft Word document - any start is a good start. 
* include information on where your results and working data are saved. 
* include a copy your lab notebook if you have one onto a digital format.  
* save the documentation file somewhere that's accessible to your supervisor or team such as Microsoft Teams, Sharepoint or Research Drive.  

Find out more about shared storage spaces in [Step 7 - Cloud backups](https://gulibrarysandbox.github.io/ten-repo/content/07-cloud.html).{% endcapture %}
{% include card.html header="First steps" text=text %}

{% capture text %}
Document in detail on how your workflow goes from your raw data to the finished results. This can be anything from a downloaded function list from SPSS/NVIVO to the code used to create it. 

Consider developing a Standard Operating Procedure for your project team or lab.   

Read the PLoS article [Ten simple rules on how to write a standard operating procedure](https://doi.org/10.1371/journal.pcbi.1008095) and use the [template](https://zenodo.org/record/3678317#.Y2suUORByUk) the researchers have shared.

##### Application of cloud solutions to documentation in research

When teams, projects, institutes, or organisations refer to cloud, it can often take on various definitions that are not always clear. In this section, the focus will be made on using cloud technology to **sync** and **store** documentation relevant to your research project. For information on **backups**, please refer to https://guereslib.github.io/ten-reproducible-research-things/content/02-cloud.html.

Further to the concepts of **sync** and **store**, cloud providers can offer their solutions across three key product types:
1. **IaaS** - Infrastructure as a Service
2. **PaaS** - Platform as a Service
3. **SaaS** - Software as a Service

{% include figure.html img="SaaS_IaaS_PaaS_Model.jpg" alt="Cloud Services Model" caption="Source: Plesky, E. (2019) IaaS vs paas vs SAAS – cloud service models compared, Plesk. Plesk. Available at: https://www.plesk.com/blog/various/iaas-vs-paas-vs-saas-various-cloud-service-models-compared/ (Accessed: January 24, 2023)." width="75%" %}

As we can see above, the level of complexity to digitally store and sync documentation increases from SaaS products at the most convenient and accessible end, to IaaS products which have a significant amount of overhead associated with their use.

That is not to say that IaaS solutions are always preferred and assumed to be the *best* solution. Depending on the size of your project, budget, and available time, SaaS solutions may be a better option. 

We can see below that alongside complexity, the amount of control is inversely proportionate to ease of set up. 

{% include figure.html img="SaaS_IaaS_PaaS_Control.jpg" alt="Cloud Services Control Graph" caption="Source: Tsai, P. (2016) IAAS? Paas? saas? differences between cloud service models, The Spiceworks Community. Spiceworks. Available at: https://community.spiceworks.com/cloud/articles/2504-iaas-paas-saas-differences-between-cloud-service-models (Accessed: January 24, 2023)." width="75%" %}

Although each service options (SaaS, PaaS, IaaS) will all achieve sync and storage functions for your documentation. The difference lies in the level of granularity you can manipulate the type of storage, amount of storage, level of access for collaborators, method of sync (live, on save etc.), change tracking, or whether documents remain in the cloud instead of being downlaoded locally each time. 

{% endcapture %}{% include card.html header="Intermediate" text=text %}

{% capture text %}
Now that you've got a good head start, it's time to learn about Git Repositories and wikis for documenting. 
Learn how to create a code repository in Github with their [Hello world tutorial](https://docs.github.com/en/get-started/quickstart/hello-world).

Or you could explore how research projects with published data have created documentation.
Check out examples of documentation or readme files in these Australian researcher involved projects:
* Dinusha, B., Howell, L., Silbert, M., Daraganova, G. (2021). Ten to Men: The Australian Longitudinal Study on Male Health, Release 3 (Waves 1-3),, ADA Dataverse, V4. (Dataset). [doi:10.26193/JDE1TD](doi:10.26193/JDE1TD)
* Komarek, A., M. (2021). Replication Data for the study on income, consumer preferences, and the future of livestock-derived food demand. Dataverse. (Data Collection). [https://doi.org/10.7910/DVN/ZPWQBB](https://doi.org/10.7910/DVN/ZPWQBB){% endcapture %}{% include card.html header="Advanced" text=text %}


### Internal Resources
* ??Wiki options at Griffith??
* [Sharepoint at Griffith](https://griffitheduau.sharepoint.com/sites/Productivity-Content/SitePages/SharePoint-Online.aspx)
* [Research Space](https://research-storage.griffith.edu.au/)
* Griffith's Gitlab wiki options - talk to [eResearch Support](https://www.griffith.edu.au/eresearch-services) or [Hacky Hour](https://www.griffith.edu.au/eresearch-services/hacky-hour)

### External Resources
* [British Ecology Reproducibility Book](https://www.britishecologicalsociety.org/wp-content/uploads/2017/12/guide-to-reproducible-code.pdf)
* [How to start Documenting and more by CESSDA ERIC](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/2.-Organise-Document/Documentation-and-metadata)
* [Software Carpentry Git Workshop](https://swcarpentry.github.io/git-novice/)
