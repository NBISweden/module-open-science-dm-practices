---
title: "Reasons for Open Science"
teaching: 0
exercises: 0
questions:
- "Key question Open Science <TODO>"
objectives:
- "To get acquainted with, and reflect upon, the principles of Open Science and FAIR, and how the course content support those. <TODO>"
keypoints:
- "Open Science is good. <TODO>"
---
# Reasons for Open Science

By Open Science we mean the movement to make scientific research and its dissemination accessible to all levels of society. Principles of open science are:

* Open methodology
* **Open source**
* **Open data**
* Open access
* Open peer review
* Open educational resources

Of these, Open data and Open source are some of the main drivers for good Data Management practices.

Discussion

What do you think are reasons for Open Data? Discuss with your neighbours.

Credibility

Research fraud has been exposed

The scientific process is not understood

…

Reproducibility

Methods unclear

Software not available

Data not available

Researchers don’t get academic credit for being transparent

You can build a CV faster when being sloppy(?)

…

When surveyed, the research community to a large extent seem to agree to that there is a reproducibility crisis. Many studies have been done on Reproducibility of published research, and regardless of scientific domain, it seems that more or less half of the publications looked at are not possible to reproduce. A large part of those are because the underlying data is not available or not understandable. Often it is also not possible to understand how the analyses were done.

To illustrate some issues around research data, let us look at this short movie:

Data Sharing and Management Snafu in 3 Short Acts



FAIR (20 min)
To try to guide the scientific community on how to ensure that the research data is useful for others in the digital age, the FAIR principles were published in 2016.

“To be useful for others data should be FAIR - Findable, Accessible, Interoperable, and Reusable
… for both Machines and Humans”

So what this mean? A brief condensed summary:

Findable
Data have a globally unique persistent identifier

e.g. a DOI, database accession number, etc

Data are described by metadata

Information that explains the data

Data and metadata are findable in a search resource

There must be ways of searching for the data

Accessible
Data is retrievable through a standardised communication protocol (open, free, allowing authentication & authorisation where necessary)

e.g. http, sftp, etc

Metadata are accessible, even if data is no longer available

Information about the data can be found even if data is no longer available

Interoperable
Metadata use a formal, accessible, shared language for knowledge representation

…

Metadata use vocabularies that follow the FAIR principles

Standardised ways of capturing information about the data

Metadata include qualified references to other metadata

…

Reusable
Data have a clear data usage license

It is obvious under what conditions the data can be reused

Metadata are associated with detailed provenance

The metadata is detailed enough to understand for what research questions it is relevant to reuse

Metadata meet domain-relevant community standards

Metadata is described according to existing standards in the research field

This is quite a mouthful, and a different angle on what is considered to be part of the scientific process for most researchers. So what is a poor researcher to do?

Which is easier, use practices that supports the FAIR principles from the start of a project (“FAIR at source“), or after it is done, when someone asks for it, retroactively?

The first thing is to start thinking about, and planning for, what practices I can apply in my research to make this easier. And that is what the rest of this course is about.

Data Management Plans, to do your thinking ahead of time

Using standard metadata descriptions, to clearly define your data

Organising your analysis, so you and others can understand what you have done

Use versioning control to keep track of changes you do

Clean up metadata and data to be consistent with the standards you have chosen

Submit your data to international public repositories, so others can find and reuse your data

Use scripted analysis of your data, that can be understood by others

The political landscape (5 min)
Globally, there is an increasing demand at the political level for Open Science and FAIR.

Already in 2012, the European Commission recommended the member states to establish national guidelines for Open Access (publications and data). The Swedish Research Council (Vetenskapsrådet, VR) submitted a proposal to the government in 2015. The government in the Research Bill of 2017 stated an ambition that “research data underlying scientific publications should be openly accessible at the time of publication”. In 2018, VR was assigned by the government to coordinate national efforts to implement open access to research data.

EU and the G20 have endorsed the FAIR principles. EU has established the European Open Science Cloud (EOSC), that aims at being a trusted environment for sharing and analysing data from all publicly funded research. Making the FAIR principles work is central to the realisation of this vision.

There is also EU “Open data directive” (2019/1024) from June 2019, that is to be implemented into national member state laws by 17 July 2021. The directive has writings about research data, and states that  EU countries must adopt policies and take action to make publicly funded research data openly available, following the principle of ‘open by default’ and support the dissemination of research data that are findable, accessible, interoperable and reusable (the ‘FAIR’ principles). A proposal about at Swedish Open Data law to implement this directive has been presented to the government in September 2020.

Funders are to a larger extent demanding that the data generated by research project that they fund is made available. All future EU funding will demand data management planning where FAIR aspects are considered. In Sweden, the VR, Formas, and Riksbankens jubileumsfond are demanding Data Management Plans for grants.

Universities are starting to establish research data policies (see e.g. Stockholm university) that calls for public access to publicly funded data, and the adherence to the FAIR principles.

The political push for EOSC and FAIR can considered to be more of a stick than a carrot for researchers, but it will not become a reality if researchers don’t see the carrot, and if infrastructure and training are not available. The aim of this course is to encourage you to use good Data Management practices to make your research easier in the long run, so that you can meet the emerging demands in this area from the society.



References

https://en.wikipedia.org/wiki/Open_science

Rochelle Tractenberg “Unexpected Ethical Challenges in Bioinformatics and Genomics.”

Turning FAIR into reality, European Commission Expert Group on FAIR Data

EU “Open Data Directive” (2019/1024)


{% include links.md %}
