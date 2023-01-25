---
nav_order: 9
title: 8 - Version Control
---
{% include figure.html img="2022_VersionsImage.JPG" alt="Image representing versioning with numbers" caption="Version allows you to keep track of changes to your data." width="75%" %}

A version control system allows users to keep track of changes in your data or processes.

Are you keeping track of any versions or logs made by the software in use?

Make sure you have a copy of every step you have completed and if possible, version numbers for the program you are using and any libraries. Programs change over time and this can alter your results if someone asks to replicate your work post publication.


### Never make alterations to your raw data files

Instead, make a copy of the raw data files and keep them in a dedicated folder, somewhere safe like [Research Drive, or for long-term storage Research Vault](https://research-storage.griffith.edu.au/). That way, if you need to redo your work or you find an error earlier in your workflow, you have an original baseline to start from.

### Write down versions of analysis software

Write down the versions of analysis software (like SPSS or NVIVO etc) AND hardware (MRI machines etc). Your documentation is a great place for this, but even in your lab notebook will work.

### Random Number Generator

If you are using random numbers in your research, save your random seed generator number as part of your working data. This way, you can later reproduce your results.

{% capture text %}

It kind of sounds like a lot of effort, so why would you want to use version control? What are the benefits? 

**To avoid this!**
{% include figure.html img="VC_Bad.jpg" alt="Image representing what happens with bad version control" caption="Uncontrollable versions can derail your workflow." width="75%" %}

There are three key advantages of implementing version control practices or procedures that you should keep in mind:
1. **Infinite undos:** If you control your versions, between **active or live** and **archived**, there will always be scope to reverse or recover a previous copy of a document before changes were made.
2. **Branching and experimentation:** Being able to effectively make a copy of documentation or code, and identify it as such, you are therefore able to test changes and hypotheses. An example would be taking a copy of commonly used code, labelling it with a descriptive prefix in the file name to identify it is a test version before testing methods to speed up how quickly the code runs.
3. **Collaboration:** Allowing multiple people to contribute to a document or code can be an immensely powerful advantage that speeds up the progress of research. From using track changes in word processors, or GitHub for code, these platforms often manage the responsibility of highlighting changes, and merging them when required. 

{% endcapture %}{% include card.html header="Why use version control?" text=text %}

{% capture text %}
Copy your raw data to to a dedicated {% include icon.html icon='folder2-open' %} *RawData* folder in a cloud storage solution, such as [Research Drive](https://research-storage.griffith.edu.au/) for safe keeping.{% endcapture %}{% include card.html header="First steps" text=text %}

{% capture text %}
If you are using a workflow program like [Galaxy](https://usegalaxy.org.au/), [KNIME](https://www.knime.com/), or a virtual lab like [EcoCloud](https://ecocloud.org.au/) or [the Australian Text Analytics Platform - ATAP](https://www.atap.edu.au/), you can copy your workflow and save it as part of your documentation. Write the date that you ran the workflow if versions of the software are not available.{% endcapture %}{% include card.html header="Intermediate" text=text %}

{% capture text %}
If you are writing scripts (R/Python/Matlab etc), use [Git](https://git-scm.com/).

Note:
Griffith has a gitlab version you can use for private repositories. Also record the version of R/Python/Matlab, the operating system you are using and the version numbers of any library you are using.(??link to how to apply for gitlab??)

If you are using the HPC, also record the version of any modules you used there.{% endcapture %}{% include card.html header="Advanced" text=text %}

{% capture text %}
If you’ve heard of [Docker](https://www.docker.com/) or [Singularity](https://docs.sylabs.io/guides/latest/user-guide/#) and you are interested in using the functions, talk to [Griffith hacky hour/eResearch Services](https://www.griffith.edu.au/eresearch-services).{% endcapture %}{% include card.html header="SUPER Advanced" text=text %}

{% include alert.html text="Note: if you are going to *publish* a Git repository, contact [Griffith's Information Policy Officer](https://www.griffith.edu.au/copyright-matters) for a copyright licence advice." align="center" color="success" %}

### Internal Resources

* Workshops on how to use Git are available through [Software Carpentry workshops at Griffith](https://www.griffith.edu.au/eresearch-services/hacky-hour).

### External Resources

* [Reproducible research in Git ](https://nbis-reproducible-research.readthedocs.io/en/latest/git/)
* [What is git](https://opensource.com/resources/what-is-git)
* [Reproducibility in SPSS](https://andrewpwheeler.wordpress.com/2012/03/20/making-a-reproducible-example-in-spss/)
* [Learn Software Carpentry in Git](http://swcarpentry.github.io/git-novice)
