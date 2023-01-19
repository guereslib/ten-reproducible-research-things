---
nav_order: 11
title: 10 - Publish Data with Persistent Identifiers 
---

{% include figure.html img="2022-11-29_14-50-46.jpg" alt="Image representing identification" caption="Use persistant identifiers to make your research discoverable" width="75%" %}

<div class="p-3 mb-2 bg-secondary text-white">Scenario: Someone has published contradicting results to your published paper. Can your provide your data and methods?{% include icon.html icon='journal-medical' %}</div> 


At the end of your project, make your research data [Findable, Accessible, Interoperable and Re-useable (F.A.I.R)](https://ardc.edu.au/resource/fair-data/) and ultimately reproducible, by publishing it with a Persistant Identifier (PiD) such as a Digital Object Identifier (DOI).


{% capture text %}
#### Identifiers

An identifier is any label used to name an item (whether digital or physical).  URLs and serial numbers are an examples of digital identifiers. 

Personal names are also identifiers, but are not necessarily unique as you may share the same name with other researchers around the world.
{% include figure.html img="Barcodes.png" alt="Serial numbers & URLS" caption="Serial numbers & URLS" width="25%" %}
Management of these digital identifiers is NOT guaranteed:

* links disappear
* websites shut down
* product support ends

#### Persistent Identifiers

A persistent identifier is long-lasting unique digital reference to a webpage, digital object, even a person.

Examples include the [Open Researcher and Contributor ID (ORCID)](https://orcid.org/) and [Digital Object Identifiers (DOI)](https://www.doi.org/).

Management of persistent identifiers IS guaranteed:

* links are kept up to date over a defined time period
* links will find the object, even when websites change.{% endcapture %}{% include card.html header="Identifiers vs Persistent Identifiers" text=text %}

{% capture text %}
#### A Digital Object Identifier (DOI) is a unique alphanumeric string that:

* is assigned by either a publisher, organisation or agency 
* identifies content
* provides a **persistent** link to its location or record on the internet and links to other related research output
* facilitates citation and citation metrics 

{% capture text %}
A DOI example: [http://dx.doi.org/10.4225/01/4F8E15A1B4D89](http://dx.doi.org/10.4225/01/4F8E15A1B4D89)

One persistent identifier example: [https://research-repository.griffith.edu.au/handle/10072/394379](https://research-repository.griffith.edu.au/handle/10072/394379), from [Griffiths' Research Data Repository](https://research-repository.griffith.edu.au/).{% endcapture %}{% include alert.html text=text color=warning %}

#### DOIs uniquely identify research data and support citation and citation metrics.

Watch this short video from Research Data Netherlands explaining Persistant identifiers and data citation (4:52) 

<iframe width="560" height="315" src="https://www.youtube.com/embed/PgqtiY7oZ6k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


#### Key messages:
* DOIs are the globally accepted identification standard for digital scholarly publications, detailing the necessary metadata to support credit and attribution.
* DOIs can be created for datasets and associated outputs (e.g. grey literature, workflows, algorithms, software etc.) - DOIs for data are equivalent to DOIs for other scholarly publications
* DOIs enable accurate data citation and bibliometrics (both metrics and altmetrics)
* Resolvable DOIs provide easy online access to research data for discovery, attribution and reuse
* Dataset DOIs can be linked using standard metadata schemas to other research output, increasing opportunities to reproduce research.

The examples below show how DOIs connect scholarly publications with supporting datasets.

{% include figure.html img="2022_BrownDOI.PNG" alt="DOIs linking Chris Brown's research" caption="DOIs linking Chris Brown's research" width="100%" %}
Chris's dataset is a large collecttion which has been analysed for multiple projects and articles. The dataset is available for validation of his work and also reuse by other researchers, with a citation and DOI created by GRO. Chris also shares the supporting code via [Github](https://github.com/cbrown5/fishscape/blob/master/data-raw/fish-hab-db_v1.csv).
* Data Citation: Brown, C.J. & Broadley, A.. (2017). Fishscape. [https://doi.org/10.25904/1912/4017](https://doi.org/10.25904/1912/4017)
* Article Citation: Brown, C. J., Broadley, A., Adame, M. F., Branch, T. A., Turschwell, M. P., & Connolly, R. M. (2019). The assessment of fishery status depends on fish habitats. Fish and Fisheries, 20(1), 1-14. [https://doi.org/10.1111/faf.12318](https://doi.org/10.1111/faf.12318)

{% include figure.html img="2022_PaynterDOI.PNG" alt="DOIs linking Jessica Paynter's research" caption="DOIs linking Jessica Paynter's research" width="100%" %}
Jessica's research was published in a journal which could also publish and mint a DOI for her supporting dataset.
* Data and Article Citation: Paynter, J., Luskin-Saxby, S., Keen, D., Fordyce, K., Frost, G., Imms, C., Miller, S., Trembath, D., Tucker, M., & Ecker, U.. (2019). Evaluation of a template for countering misinformation—Real-world Autism treatment myth debunking (Version 1). PLOS ONE. [https://doi.org/10.1371/journal.pone.0210746](https://doi.org/10.1371/journal.pone.0210746){% endcapture %}{% include card.html header="DOIs" text=text %}


{% capture text %}
Ensure data you publish or associate with a publication has a DOI. 

How?
* Deposit final state data to support your publications in an institutional or discipline data repository which can mint a DOI and create a citation for your work. 
* Examples include:
  * [Griffith Research Online (GRO) Data Repository](https://research-repository.griffith.edu.au/handle/10072/392600) 
  * [re3data.org](https://www.re3data.org/) registry of discipline and other data repositories
  * [PLoS journals recommended repositories](https://journals.plos.org/plosone/s/recommended-repositories)
* Cite your dataset in the references of the articles it supports.  This is the best way for others to find and access your dataset, for reproducibility purposes or to use with attribution in their own research. Professor Mark Finnane illustrates this in the citation to his dataset [*The Prosecution Project Database*](https://prosecutionproject.griffith.edu.au/dataverse/) in reference 27 of his [article](https://research-repository.griffith.edu.au/handle/10072/340488) published in the *UNSW Law Journal*.
* Contact your Library staff for guidance.{% endcapture %}{% include card.html header="First steps" text=text %}

{% capture text %}
* Learn more about how DOIs [and their use in data citations enables tracking and quantitative measuring of publication impact and data impact.](https://www.frontiersin.org/articles/10.3389/fninf.2016.00034/full) from Honor et. al.
* Read the [ARDC Data & Software Citation Guide](https://ardc.edu.au/resource/data-and-software-citation/).{% endcapture %}{% include card.html header="Intermediate" text=text %}

{% capture text %}
* Learn more about the [ARDC's policy supporting PiDs](https://ardc.edu.au/resource/ardc-persistent-identifiers-policy/) to improve tracking of research impact, contribute to research integrity and enable research innovation.
* Read the article [Ten simple rules for getting and giving credit for data](https://doi.org/10.1371/journal.pcbi.1010476) or [Ten simple rules for improving research data discovery](https://doi.org/10.1371/journal.pcbi.1009768) for researcher perspectives on linking data to publications. {% endcapture %}{% include card.html header="Advanced" text=text %}

##### Internal Resources
* Contact the Library Repository Team via the [online form](https://intranet.secure.griffith.edu.au/library/forms/help) for advice on how to obtain a DOI for your data upon project completion.

##### External Resources
* [ARDC Data & Software Citation Guide](https://ardc.edu.au/resource/data-and-software-citation/)
* Honor, L. B., Haselgrove, C., Frazier, J. A., & Kennedy, D. N. (2016). Data citation in neuroimaging: Proposed best practices for data identification and attribution. Frontiers in neuroinformatics, 10, 34. [https://doi.org/10.3389/fninf.2016.00034](https://doi.org/10.3389/fninf.2016.00034)
