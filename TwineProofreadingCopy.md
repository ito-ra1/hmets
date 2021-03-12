----------------------------------------
# Passage Name: StoryCaption

This site is an interactive guide through the process of planning and implementing harvestable metadata services at a research data repository. You'll find links and references to other online resources at every step.

How to use this site: <<button "Instructions">><</button>>

For more information, please go to the <<button "Site Documentation">><</button>>.
__Last Update:__ March 8, 2021
Powered by [Twine](https://twinery.org/)

----------------------------------------
# Passage Name: Instructions

__**Navigating the implementation plan**__
- To move forward to the next step of the implementation plan, select one of the buttons, mostly at the bottom of each passage.
- To return to the previous passage, select the left arrow **&#8592;** that is located on top of the sidebar. 

__**Adjusting the sidebar**__
- To hide the sidebar, click '<' on the top right corner of the sidebar.
- To unhide the sidebar, click '>' on the top right corner of the sidebar.

__**Saving and Restoring your Progress**__
Use the buttons at the bottom of the left sidebar.
- You can save a local copy of your progress (a `.save` file) to return to later. Selecting the **SAVE & LOAD* button will display a pop-up menu where you can select a local directory as destination for your progress. Select **SAVE & LOAD** to finish saving the file.
- To return to your saved walk-through, load the saved implementation progress by selecting **SAVE & LOAD*. Locate the `.save` file and select **SAVE & LOAD** in the pop-up menu.
- To remove any saved implementation progress files, select the **SAVE & LOAD** button. Locate the saved implementation progress and click **DELETE**.
- To restart the walk-through, select the **RESTART** button. Then click **OK** in the pop-up menu. 

----------------------------------------
# Passage Name: Hello

## Hello!
You are a data manager at your research institution's data repository.
Your organization has committed to providing open research data to the community, and to adopt the [FAIR](https://www.go-fair.org/fair-principles/) and [TRUST](https://doi.org/10.1038/s41597-020-0486-7) principles for data sharing. 

You would like to spearhead a project to serve your repository's metadata catalogue through an aggregation service, e.g. a harvestable metadata service, that increases the findability and interoperability of your repository assets.

### You've come to the right place...
This interactive guide will walk you through some of the main issues that must be addressed to create metadata aggregation services.

As you continue to gain insight into the aggregation landscape, and as you progress through the story and make decisions about your planned services, you will have the opportunity to record your answers. 

At the end of the walk-through, you'll have the option to print out a semi-customized implementation plan draft for your repository. The full template document (not customized) can be downloaded [here](https://drive.google.com/file/d/1__nsZNXswpmYwJHsNKgDc57rBmKjba-B/view?usp=sharing).

<<button [[Get started!|Repository basics]]>><</button>>

----------------------------------------
# Passage Name: Repository basics

## Repository and institution
What is the name of your repository? <<textbox "$repository" "">><small>*[optional]*</small>
What is/are the name(s) of your repository's host organization(s)?<<textbox "$orgname" "">><small>*[optional]*</small>
How would you describe your repository's stakeholders and user base? You can define your stakeholders as the users of your repository's data, or more broadly as anyone who will benefit from this project, e.g. institutions wanting to strengthen their international/interdisciplinary profile, or promote their research outputs/data assets.
<<textarea "$stakeholders" "">><small>*[optional]*</small>

### Next steps
Do you have the authority to spearhead a project of this nature, or have you already been given clearance to do so by someone who has that authority?

1. Yes, you have that authority. <<button [[Start planning|Expected outcomes]]>><</button>>

2. You need to ask for authorization before moving forward with this project.  <<button [[Get permission!|Making the case]]>><</button>>

----------------------------------------
# Passage Name: Making the case

## Making the case!
Sharing metadata through aggregators makes your repository assets more findable. This benefits your organization directly, as it can increase the reuse and impact of your datasets. 

In research organizations without a strong culture of <abbr title="Research Data Management">RDM</abbr>, it may take time to build support for expanding data services with initiatives such as a new metadata service. Through uses cases like the [Göttingen eResearch Alliance](https://doi.org/10.3390/ijgi5080133), we know that institutional support is built by engaging with the organization's key decision makers and stakeholders. Your stakeholders have to be able to envision the positive and tangible ways in which the project will impact their work, and how it will benefit the institution as a whole. Other challenges for less hierarchical organizations, such as research networks or federations, might be related to coordinating the development of a common standard or application profile, or the adoption of an existing technology (see, for example, [Yarmey & Baker’s 2013 proposal for a participatory framework for standards development](http://www.ijdc.net/article/view/8.1.157). 

### Why create a harvestable metadata service?

Harvestable metadata is an established and widely-used tool to support effective data discovery and data sharing. It opens up new ways to integrate with the wider data management community.

The [FAIR](https://doi.org/10.15497/RDA00050) framework lists harvestable metadata as an indicator of dataset findability. Harvestable metadata services are considered one measure of repository [TRUSTworthiness](https://doi.org/10.1038/s41597-020-0486-7). In fact, one of the certification requirements for the [CoreTrustSeal Trustworthy Repository](https://www.coretrustseal.org/) designation is effective data discovery. 

Findability relates to a catalogue's interoperability, whether a repository maintains a searchable metadata catalogue to appropriate standards, including persistent identifier systems. It also covers the ways in which metadata is made available, either by means of search interfaces on the repository site, via APIs, or through harvesting services. Additional criteria include repository presence in more than one resource registry (generic and disciplinary), and whether data citation recommendations are provided on the site.

Before approaching the instance that will make a decision about your request to create a new metadata service, have a look at some resources to help you make your argument:
- Chiarelli, A. & Johnson, R. (2017) [Making the case for research data management - Case studies.](https://doi.org/10.5281/zenodo.817936)
- Dierkes, J. & Wuttke, U. (2016) [The Göttingen eResearch Alliance: A case study of developing and establishing institutional support for research data management.](https://doi.org/10.3390/ijgi5080133) *ISPRS International Journal of Geo-Information*, *5*(8), 1-11.
- Garnett A., Leahey, A., Savard, D., Towell, B., & Wilson, L. (2017) [Open metadata for research data discovery in Canada.](https://doi.org/10.1080/19386389.2018.1443698) *Journal of Library Metadata*, *17*(3–4), 201-217.
- International Science Council (2019) [Advancing science as a global public good: Action plan 2019-2021.](https://council.science/wp-content/uploads/2019/12/Advancing-Science-as-a-Global-Public-Good_ISC-Action-Plan-landscape.pdf)
- Whyte, A. & Tedds, J. (2011) [Making the case for research data management.](https://www.dcc.ac.uk/guidance/briefing-papers/making-case-rdm)

### You asked the authority, and:
<<button [[permission was obtained|Expected outcomes]]>><</button>>
<<button [[permission was refused|Pre-final]]>><</button>>  

----------------------------------------
# Passage Name: Expected outcomes

# Project objectives
This section is to help you formulate your general goals and the expected outcomes. The outcomes should be as concrete as possible, and be associated with metrics and methods to benchmark and compare the repository's performance relative to those outcomes.
*(Metrics and methods will come up again in a later passage of this narrative.)*

**Goals**
Which goals are you striving for with the implementation of harvestable metadata services? 
<<textarea "$goals" "">><small>*[optional]*</small>

**Expected Outcomes**
What outcomes would you expect to see? If possible, indicate a time frame in which you'd expect these changes to occur.
<<textarea "$outcomes" "">><small>*[optional]*</small>
<<button [[Submit & continue|Catalogue]]>><</button>>

Or if you'd rather not provide that information yet:  <<button[[Skip to the next step|Catalogue]]>><</button>>

----------------------------------------
# Passage Name: Catalogue

## Your repository catalogue
**Current state of your repository**
The global RDM community has produced a few resources to assess the maturity of a data repository. They are practical, up-to-date frameworks to help you review your repository’s current state:
- CoreTrustSeal Standards and Certification Board (2019). [CoreTrustSeal trustworthy data repositories requirements 2020–2022](http://doi.org/10.5281/zenodo.3638211).
- RDA FAIR Data Maturity Model Working Group (2020). [FAIR data maturity model: specification and guidelines](https://doi.org/10.15497/RDA00050)
- Lin, D., Crabtree, J., Dillo, I. et al. (2020). [The TRUST Principles for digital repositories](https://doi.org/10.1038/s41597-020-0486-7). *Scientific Data*, 7, 144(2020).
- Rans, J., & Whyte, A. (2017). [Using RISE: The research infrastructure self-evaluation framework](https://www.dcc.ac.uk/sites/default/files/documents/publications/UsingRISE_v1_1.pdf). Digital Curation Centre.

The first thing you will need is a catalogue of well-formed metadata. 

### Does your repository already have a catalogue with standardized metadata?

1. Yes, you already have a catalogue. <<button [[Continue|Metadata standards]]>><</button>>

2. You have a metadata catalogue, but the metadata is not standardized.  <<button [[Improve your metadata catalogue|Almost metadata]]>><</button>>

3. You do not have a metadata catalogue for your repository yet.  <<button [[Create your metadata catalogue|Almost metadata]]>><</button>>

----------------------------------------
# Passage Name: Almost metadata

## Creating (or improving) a metadata catalogue

Different aggregators can support different metadata standards and transfer protocols. Some common metadata standards include [DataCite](https://schema.datacite.org/), the [Dublin Core Metadata Initiative (DCMI)](https://www.dublincore.org/schemas/), the [Data Documentation Initiative (DDI)](https://ddialliance.org/), and [ISO 19115-1:2014](https://www.iso.org/standard/53798.html), which is part of the [ISO 1900 series](https://schemas.isotc211.org/) of geographic information standards.

Here are some resources to get you started:
- Riley, J. (2017). [Understanding metadata: What is metadata, and what is it for?](https://groups.niso.org/apps/group_public/download.php/17446/Understanding%20Met%E2%80%A6) National	Information	Standards	Organization. 
- ANDS (2016). <a href="https://www.ands.org.au/guides/metadata-working">Guide to Metadata (Working Level)</a>. 
- Digital Curation Centre (n.d.). <a href="https://www.dcc.ac.uk/guidance/standards/metadata">Disciplinary metadata.</a>
- Research Data Alliance Metadata Standards Directory Working Group (n.d.). [Metadata](http://rd-alliance.github.io/metadata-directory/).
- Riley, J. (2018). [Seeing standards: A visualization of the metadata universe](https://doi.org/10.5683/SP2/UOHPVH).

Depending on the size of your repository and the state of metadata in your repository catalogue, it could take a lot of effort and resources to get your metadata in the repository catalogue up to current standards for aggregation.

### Your options
Upon reviewing the metadata resources, were you able to create a catalogue for your repository, or improve your repository's metadata to an interoperable standard?

<<button [[Yes, you now have a catalogue of well-formed metadata.|Metadata standards]]>><</button>>       
<<button [[No. You found that you currently lack the resources to create a catalogue or improve your existing metadata.|Pre-final]]>><</button>>

----------------------------------------
# Passage Name: Metadata standards

## Metadata in your repository
Metadata that uses established, interoperable standards can be more easily transformed and exchanged in a research data ecosystem. If metadata is syndicated through a federated service, it can be shared and retrieved via search interfaces across different subject domains, making datasets more findable.

(For more information and resources on metadata standards, take a quick detour through the [[Metadata|Almost metadata]] section)

### Your options:
1. Name the metadata schema, standards and/or formats used in your repository <<textarea "$mdstandards" "">><small>*[optional]*</small>  <<button [[Submit & continue|Services & Protocols]]>><</button>>
2. If you'd rather not provide that information yet, <<button[[skip to the next step|Services & Protocols]]>><</button>>

----------------------------------------
# Passage Name: Services & Protocols

## Existing service protocols
The metadata in your repository is now ready to be aggregated. Is your catalogue already being shared? For example, is it already searchable on your repository's site, or is it already served using a metadata transfer protocol?

Some common protocols include the [Open Archives Initiative Protocol for Metadata Harvesting (OAI-PMH)](https://www.openarchives.org/pmh/), the [Open Geospatial Consortium-Catalogue Service for the Web (OGC-CSW)](https://www.ogc.org/standards/cat), [ERDDAP](https://coastwatch.pfeg.noaa.gov/erddap/download/setup.html), or the [ResourceSync](https://www.niso.org/standards-committees/resourcesync) protocol. 

Some repository platforms have a specific API that can connect to data services, like the [CKAN-API](https://ckan.org/portfolio/api/), or the [Dataverse API](https://guides.dataverse.org/en/latest/api/index.html). Aggregators may support one or many protocols, or APIs (see for example the extensive list of protocols supported by the [GEOSS Discovery and Access Broker.](https://www.geodab.net/))

### Your options:
1. Metadata in your repository is being shared via the following services and/or protocols: <<textarea "$protocol" "">><small>*[optional]*</small>  <<button [[Submit & continue|New services]]>><</button>>
2. If you'd rather not fill out this part yet, <<button [[skip to the next step|New services]]>><</button>>

----------------------------------------
# Passage Name: New services

## New services
To help you understand more about metadata aggregation, we recommend reading the new International Technology Office (WDS-ITO) Guide, [14 Metadata Syndication things](https://doi.org/10.5281/zenodo.4589084).

If you are interested in creating a new metadata service, there are essentially two main types of metadata aggregation available to choose from:

**1. 'Traditional' metadata aggregation**
This approach relies on structured metadata that is schema-based and serialized into a standardized file type (e.g. XML, JSON), which is used to index the metadata records into a federated catalogue. The Canadian [Federated Research Data Repository (FRDR)](https://www.frdr-dfdr.ca/repo/?locale=en)--which harvests metadata catalogues using the [OAI-PMH](http://www.openarchives.org/OAI/2.0/guidelines-repository.htm#MinimalImplementation) protocol, and aggregates metadata using the [DataCite](https://schema.datacite.org/) schema--is a successful and well-documented example of the 'traditional' approach to metadata syndication.

**2. Semantic aggregation**
Within the RDM community, semantic aggregation occurs most frequently  with SDO metadata markup (specifically, [Schema.org](https://schema.org/), pronounced *Schema Dot Org*, or SDO) in a repository or data catalogue. SDO is a controlled vocabulary used to mark up content in a webpage in a way that search engines can understand. The core SDO vocabulary is constantly under development, and it grows in response to use cases across many communities. SDO can be used to describe many different things (“object types”) referred to in a webpage, including recipes, job posts, book reviews and in our case, datasets and data catalogues. Dataset landing pages, which contain datasert metadata records, are marked up with SDO terms and web crawlers such as [Google Dataset Search (GDSS)](https://datasetsearch.research.google.com/) index these tags and use them to populate their search results. For more on semantic aggregation, we recommend reading ‘Thing 3: Semantics and Schema.org’ in the [14 Metadata Syndication things](https://doi.org/10.5281/zenodo.4589084) guide.

### I am interested in:
<<button [[traditional aggregation only|Aggregators]]>><</button>>
<<button [[semantic aggregation only|Semantic metadata]]>><</button>>
<<button [[both traditional and semantic aggregation|Both-Semantic]]>><</button>>
<<button [[none of them|Pre-final]]>><</button>>

----------------------------------------
# Passage Name: Aggregators

## Find a metadata aggregator

The [Searchable Index of Metadata Aggregators](https://doi.org/10.5281/zenodo.4589050), a new product by the International Technology Office (WDS-ITO), contains up-to-date information about 70 platforms that are currently providing metadata aggregation services. To search this database, [download it from Zenodo](https://doi.org/10.5281/zenodo.4589050). The package contains an MS Access database with its associated documentation, as well as a PDF copy of the entire index.

### The basics
Some platforms only aggregate metadata related to a specific region, for example the [Federated Research Data Repository(FRDR)](https://www.frdr-dfdr.ca/repo/?locale=en), or [Research Data Australia](https://researchdata.edu.au/). Other platforms only aggregate metadata related to a specific subject domain, like [Clarin's Virtual Language Observatory](https://www.clarin.eu/content/virtual-language-observatory-vlo).

Some examples of international, multidisciplinary metadata aggregators include the European open science project [OpenAIRE](https://explore.openaire.eu/), the Canadian [Federated Research Data Repository (FRDR)](https://www.frdr-dfdr.ca/repo/?locale=en), and [LA Referencia](https://www.lareferencia.info/en/) in Latin America. Commercial aggregators such as [Clarivate's Data Citation Index(DCI)](https://clarivate.com/webofsciencegroup/solutions/webofscience-data-citation-index/), and [Elsevier's Mendeley Data](https://data.mendeley.com/) also aggregate data from all regions and subject domains.

### Making choices
When choosing metadata aggregator(s), there are a few things to consider:

### Your community
<div style="margin-left: 1em;">What data practices are established, or emerging in your community?</div>
<div style="margin-left: 1em;">What harvesters or repositories are being used in your subject area?</div>

### Findability goals
<div style="margin-left: 1em;">Who needs to be able to find your data?</div>
<div style="margin-left: 2em;"><span style='font-size:23px;'>&#8667;</span>*Aggregators target different subject domains. Some serve a general class of users and others have added functions that may appeal to some user groups only.*</div>
<div style="margin-left: 1em;">Where are your target users searching?</div>
<div style="margin-left: 2em;"><span style='font-size:23px;'>&#8667;</span>*Your data community has established practices around data sharing and searching. If you're targeting users outside your community, find out about their practices to adapt your efforts accordingly.*</div>
<div style="margin-left: 1em;">What information is relevant to them?</div>
<div style="margin-left: 2em;"><span style='font-size:23px;'>&#8667;</span>*Choose metadata standards that reflect the needs of target users. Rich metadata serves specialist communities, while high-level metadata makes your data visible to the general public, media, government and funding agencies, etc.*</div>

### Interoperability
<div style="margin-left: 1em;">How far will your current infrastructure take you?</div>
<div style="margin-left: 2em;"><span style='font-size:23px;'>&#8667;</span>*Find services that already support your existing metadata and endpoints/protocols.*
<span style='font-size:23px;'>&#8667;</span>*Software modules can bridge the gap between your (custom) repository and the harvester, e.g. [Viringo](https://github.com/datacite/viringo), used by DataCite and FRDR, or [pycsw](https://pycsw.org/), an open-source implementation of the [OGC CSW](https://docs.opengeospatial.org/is/12-168r6/12-168r6.html) standard for catalogue services.*</div>
<div style="margin-left: 1em;">Is your repository platform not supported by default?</div>
<div style="margin-left: 2em;"><span style='font-size:23px;'>&#8667;</span>*Ask aggregators about custom support options!*</div>

### Your options:
1. I would like to target these aggregators (Try to include at least the name, the URL of the main page, and the contact method of the aggregator(s)): <br/><<textarea "$aggrlist" "">><small>*[optional]*</small>  <<button [[Submit & continue|Metadata interoperability]]>><</button>>
2. I'd rather not fill out this part yet. <<button [[Skip to the next step|Metadata interoperability]]>><</button>>

----------------------------------------
# Passage Name: Metadata interoperability
<<if $aggrlist is "">>

## Metadata standards supported<<else>>

## Metadata standards supported
Upon reviewing the documentation for **your selected aggregators: **
<<print $aggrlist>>
<</if>>
Were you able to identify any aggregators that support the current metadata standards used by your repository? 
**Your current metadata standards:** <<if $mdstandards is "">>*You prefer not to disclose this information at this stage.*<<else>><<print $mdstandards>><</if>>

## If yes, please elaborate:<<textbox "$interopmd" "">><small>*[optional]*</small>

## If no, what changes (schemas, vocabularies, application profiles) will your repository have to make in order to be aggregated?
<<textarea "$newstandards" "">><small>*[optional]*</small>

Looking at the gaps between the current state of your catalogue and the required standards, you decide to:
<<button [[continue with the original plan to create a harvestable metadata service|Protocol interoperability]]>><</button>>
<<button [[postpone this project.|Pre-final]]>><</button>>

----------------------------------------
# Passage Name: Semantic metadata

## Semantic metadata and Schema.org
Semantic markup (i.e. Schema.org) is built into a metadata standard. As previously mentioned, <abbr title="Schema Dot Org">SDO</abbr> is implemented in the metadata landing page. That landing page contains a pointer to the data resource in the hosting repository, or instructions on how to access the data. Bots then parse the web pages, index them and include them in [Google Dataset Search (GDSS)](https://datasetsearch.research.google.com/). 

Importantly for those who manage sensitive or restricted data that are subject to privacy concerns, once a dataset is discovered in GDSS, the user is directed back to the repository to obtain the data. The access restrictions and protocols for data sharing remain as agreed upon during the submission process, and they are determined and maintained at the repository.

Here are some resources for you to understand more about SDO and how to implement SDO into your repository:
- Benjelloun, O, Chen, S., & Noy, N. (2020). [Google Dataset Search by the numbers](https://arxiv.org/abs/2006.06894).
- FAIRsFAIR (2020). [FAIR Semantics](https://github.com/FAIRsFAIR/FAIRSemantics)
- Fenner, M., Crosas, M., Durand, G., Wimalaratne, S.;  Gräf, F., Hallett, R., Bernal Llinares, M., & Clark, T. (2018). [Listing of data repositories that embed schema.org metadata in dataset landing pages](https://doi.org/10.5281/zenodo.1202174).
- Ogbuji, U. (2017). [Introduction to the Schema.org information model: Make your data more useful in automated applications](https://developer.ibm.com/articles/wa-schemaorg1/).
- Schema.org (2018). [Community examples](https://github.com/schemaorg/schemaorg/wiki/Community-Examples).
- Schema.org (2018). [External resources](https://github.com/schemaorg/schemaorg/wiki/External-Resources).
- W3C Community and Business Groups (n.d.). [Schema.org Community Group](https://www.w3.org/community/schemaorg/). 
- World Data System-International Technology Office (2021). [Crosswalks from schemas to schema.org](https://docs.google.com/spreadsheets/d/1P6WH8h4OnIVR9UJj3FcOebNUpLnKNBCuvEp3NsLRho4/edit?usp=sharing). 

Once you've found out more about schema.org, you'll be in a position to start its implementation.

<<button [[End this walk-through|Pre-final]]>><</button>>
----------------------------------------
# Passage Name: Both-Aggregator

## Find a metadata aggregator

The [Searchable Index of Metadata Aggregators](https://doi.org/10.5281/zenodo.4589050), a new product by the International Technology Office (WDS-ITO), contains up-to-date information about 70 platforms that are currently providing metadata aggregation services. To search this database, [download it from Zenodo](https://doi.org/10.5281/zenodo.4589050). The package contains an MS Access database with its associated documentation, as well as a PDF copy of the entire index.

### The basics
Some platforms only aggregate metadata related to a specific region, for example the [Federated Research Data Repository(FRDR)](https://www.frdr-dfdr.ca/repo/?locale=en), or [Research Data Australia](https://researchdata.edu.au/). Other platforms only aggregate metadata related to a specific subject domain, like [Clarin's Virtual Language Observatory](https://www.clarin.eu/content/virtual-language-observatory-vlo).

Some examples of international, multidisciplinary metadata aggregators include the European open science project [OpenAIRE](https://explore.openaire.eu/), the Canadian [Federated Research Data Repository (FRDR)](https://www.frdr-dfdr.ca/repo/?locale=en), and [LA Referencia](https://www.lareferencia.info/en/) in Latin America. Commercial aggregators such as [Clarivate's Data Citation Index(DCI)](https://clarivate.com/webofsciencegroup/solutions/webofscience-data-citation-index/), and [Elsevier's Mendeley Data](https://data.mendeley.com/) also aggregate data from all regions and subject domains.

### Making choices
When choosing metadata aggregator(s), there are a few things to consider:

### Your community
<div style="margin-left: 1em;">What data practices are established, or emerging in your community?</div>
<div style="margin-left: 1em;">What harvesters or repositories are being used in your subject area?</div>

### Findability goals
<div style="margin-left: 1em;">Who needs to be able to find your data?</div>
<div style="margin-left: 2em;"><span style='font-size:23px;'>&#8667;</span>*Aggregators target different subject domains. Some serve a general class of users and others have added functions that may appeal to some user groups only.*</div>
<div style="margin-left: 1em;">Where are your target users searching?</div>
<div style="margin-left: 2em;"><span style='font-size:23px;'>&#8667;</span>*Your data community has established practices around data sharing and searching. If you're targeting users outside your community, find out about their practices to adapt your efforts accordingly.*</div>
<div style="margin-left: 1em;">What information is relevant to them?</div>
<div style="margin-left: 2em;"><span style='font-size:23px;'>&#8667;</span>*Choose metadata standards that reflect the needs of target users. Rich metadata serves specialist communities, while high-level metadata makes your data visible to the general public, media, government and funding agencies, etc.*</div>

### Interoperability
<div style="margin-left: 1em;">How far will your current infrastructure take you?</div>
<div style="margin-left: 2em;"><span style='font-size:23px;'>&#8667;</span>*Find services that already support your existing metadata and endpoints/protocols.*
<span style='font-size:23px;'>&#8667;</span>*Software modules can bridge the gap between your (custom) repository and the harvester, e.g. [Viringo](https://github.com/datacite/viringo), used by DataCite and FRDR, or [pycsw](https://pycsw.org/), an open-source implementation of the [OGC CSW](https://docs.opengeospatial.org/is/12-168r6/12-168r6.html) standard for catalogue services.*</div>
<div style="margin-left: 1em;">Is your repository platform not supported by default?</div>
<div style="margin-left: 2em;"><span style='font-size:23px;'>&#8667;</span>*Ask aggregators about custom support options!*</div>

### Your options:
1. I would like to target these aggregators (Try to include at least the name, the URL of the main page, and the contact method of the aggregator(s)): <br/><<textarea "$aggrlist" "">><small>*[optional]*</small>  <<button [[Submit & continue|Metadata interoperability]]>><</button>>
2. I'd rather not fill out this part yet. <<button [[Skip to the next step|Metadata interoperability]]>><</button>>

----------------------------------------
# Passage Name: Both-Semantic

## Semantic metadata and Schema.org
Semantic markup (i.e. Schema.org) is built into a metadata standard. As previously mentioned, <abbr title="Schema Dot Org">SDO</abbr> is implemented in the metadata landing page. That landing page contains a pointer to the data resource in the hosting repository, or instructions on how to access the data. Bots then parse the web pages, index them and include them in [Google Dataset Search (GDSS)](https://datasetsearch.research.google.com/). 

Importantly for those who manage sensitive or restricted data that are subject to privacy concerns, once a dataset is discovered in GDSS, the user is directed back to the repository to obtain the data. The access restrictions and protocols for data sharing remain as agreed upon during the submission process, and they are determined and maintained at the repository.

Here are some resources for you to understand more about SDO and how to implement SDO into your repository:
- Benjelloun, O, Chen, S., & Noy, N. (2020). [Google Dataset Search by the numbers](https://arxiv.org/abs/2006.06894).
- FAIRsFAIR (2020). [FAIR Semantics](https://github.com/FAIRsFAIR/FAIRSemantics)
- Fenner, M., Crosas, M., Durand, G., Wimalaratne, S.;  Gräf, F., Hallett, R., Bernal Llinares, M., & Clark, T. (2018). [Listing of data repositories that embed schema.org metadata in dataset landing pages](https://doi.org/10.5281/zenodo.1202174).
- Ogbuji, U. (2017). [Introduction to the Schema.org information model: Make your data more useful in automated applications](https://developer.ibm.com/articles/wa-schemaorg1/).
- Schema.org (2018). [Community examples](https://github.com/schemaorg/schemaorg/wiki/Community-Examples).
- Schema.org (2018). [External resources](https://github.com/schemaorg/schemaorg/wiki/External-Resources).
- W3C Community and Business Groups (n.d.). [Schema.org Community Group](https://www.w3.org/community/schemaorg/). 
- World Data System-International Technology Office (2021). [Crosswalks from schemas to schema.org](https://docs.google.com/spreadsheets/d/1P6WH8h4OnIVR9UJj3FcOebNUpLnKNBCuvEp3NsLRho4/edit?usp=sharing). 

Once you've found out more about schema.org, you'll be in a position to start its implementation.

----------------------------------------
# Passage Name: Protocol interoperability
<<if $aggrlist is "">>

## Exposure protocols supported<<else>>

## Exposure protocols supported
Upon reviewing the documentation for **your selected aggregators:**
<<print $aggrlist>>
<</if>>
Are your repository’s software elements, APIs, and/or protocols supported by your preferred aggregators?

**Your repository’s exposure protocols:** <<if $protocol is "">>*[None selected]*<<else>><<print $protocol>><</if>>.

## If yes, <<button [[contact the selected aggregators and get harvested.|Measuring success]]>><</button>>

## If no, what changes will your repository have to make in order to be aggregated?
<<textarea "$newprotocols" "">><small>*[optional]*</small>
<<button [[contact aggregator(s) directly to ask about custom support options.|Custom support]]>><</button>>

----------------------------------------
# Passage Name: Custom support

## Requesting Custom Support for your Repository Platform
Some services are able to provide custom support to potential providers of repository metadata. Is this the case for your preferred aggregator(s)?

1. Yes, the aggregator has a way of providing custom support to your repository's existing infrastructure.  <<button [[Excellent! Let's continue|Measuring success]]>><</button>> 
2. No, the aggregator has no support desk, or the service does not offer custom support for your specific infrastructure.  <<button [[Explore your options|Software upgrades]]>><</button>>

----------------------------------------
# Passage Name: Software upgrades

## Repository upgrades and other options
If your preferred aggregator(s) cannot support your existing infrastructure, you still have a few options:
<<checkbox "$viringo">>Install [Viringo](https://github.com/datacite/viringo) on your custom repository, 'an OAI-PMH compatible provider for exposing PID related metadata', that is currently being used by DataCite and FRDR.
<<checkbox "$pycsw">>Install [pycsw](https://pycsw.org/), an open-source implementation of [OGC-CSW](http://www.opengis.net/doc/IS/cat/3.0) in Python. 
<<checkbox "$customAPI">>Work with your repository's IT department to create the functionality you need to interact with the APIs and protocols required by the aggregators of your choice.
<<checkbox "$migrate">>Migrate some, or all, of your datasets to a subject repository that does have the ability to provide metadata to aggregators. But this might involve having to adopt a different metadata application profile, or a new schema altogether.
<<button [[Save option(s) & continue|Measuring success]]>><</button>>

If none of this seems to be a possibility for now, <<button [[please let us walk you to the exit|Pre-final]]>><</button>>

----------------------------------------
# Passage Name: Measuring success

## Measuring success
<<if $servicetype is "semantic">>You have decided to enhance your existing metadata records in the repository with semantic metadata, using schema.org.
<<elseif $servicetype is "both">>You have decided to enhance your existing metadata records in the repository with semantic metadata, using schema.org.
You have also decided to create a traditional metadata aggregation service, to be exposed to metadata harvesters and shared via registries, and you are working on creating an implementation plan.

So far, you have:
- Described our repository’s current infrastructure
- Narrowed down your aggregation options to a set of preferred metadata aggregators
- Identified the gaps between your infrastructure and the minimum requirements to be aggregated by the aggregators you’ve selected
<<elseif $servicetype is "traditional">>
You have decided to create a traditional metadata aggregation service, to be exposed to metadata harvesters and shared via registries, and you are working on creating an implementation plan.

So far, you have:
- Described our repository’s current infrastructure
- Narrowed down your aggregation options to a set of preferred metadata aggregators
- Identified the gaps between your infrastructure and the minimum requirements to be aggregated by the aggregators you’ve selected
<<else>>
<</if>>

This section addresses two essential components of your implementation plan: A consumption benchmark and a method to establish whether your repository has reached that benchmark.

To begin, you need to know how to measure your repository’s “success”. The [COUNTER Code of Practice](https://www.projectcounter.org/wp-content/uploads/2017/07/Friendly_Guide_Providers_20170706-1.pdf) gives a framework to measure repositories’ impact in the research data community. It has become the standard framework for repository metrics.

How does your repository currently track your datasets’ impact and reach? (select all that apply)
<<checkbox "$views">>Landing page views. 
<<checkbox "$downloads">>Dataset downloads.
<<checkbox "$citations">>Reuse in research: scholarly citations (e.g. with DOI and other PIDs).
<<checkbox "$mentions">>References in other online scholarly communication platforms: Links and mentions on social media, blogs, websites, etc.
<<checkbox "$aggreuse">>Reuse by aggregation into other data products or services.
<<checkbox "$educational">>Educational use: Appearance in course syllabi, workshops, etc.
<<checkbox "$ot">>Others, please elaborate:
<<textarea "$othermetrics" "">><small>*[optional]*</small>

**Benchmarks and methods**
Could you give a brief description of the framework you plan to use to assess and evaluate a harvestable metadata service implementation at your repository?
<<textarea "$evalframework" "">><small>*[optional]*</small>
<<button [[Submit & continue|This and that]]>><</button>>


----------------------------------------
# Passage Name: This and that

## Your Implementation Plan is almost completed. 

You have the following options:
1. You can end this walkthrough now by clicking on this button:  <<button[[Skip to the next step|Pre-final]]>><</button>>, or 
2. Or you can use the section below to add more content to your implementation plan before printing it out. 

### 1. Project Summary
**1. Please write a summary of your project (50-150 words)**
<<textarea "$summary" "">><small>*[optional]*</small>
**2. Additional repository developments/activities**
Are there any other repository developments or activities that you want to consider in your workflow? Some examples might be:
- Converting metadata to an alternate format
- Temporary embargos before publishing
- Back-up procedures
- Generating PIDs or DOIs for metadata
- Conducting quality assurance
- Adding provenance metadata

<<textarea "$workflows" "">><small>*[optional]*</small>
**3. Resources needed (e.g. human effort, infrastructure upgrades, etc.)**
*Don’t underestimate the human effort required for a harvestable metadata project!*
<<textarea "$resources" "">><small>*[optional]*</small>
**4. Other support**
To what extent does your repository's host organization provide material and other support?
<<textarea "$support" "">><small>*[optional]*</small>
**5. Partners**
Are other organizations involved in this project? Do you have inter-institutional support from partners, groups, government or federations? Are there other projects related to this one? If so, please describe the nature of your collaborations/external support:
<<textarea "$partners" "">><small>*[optional]*</small>
**6. Difficulties/Challenges**
Can you think of any other difficulties or challenges in data sharing? For example, 
- Are you sharing open data or will a data sharing agreement or privacy controls be required?
- Do you have an existing research data  management plan or contract that you need to satisfy or a governance structure that needs to approve of your repository development plan?

Please describe the causes of these difficulties, and any possible measures to overcome them.
<<textarea "$challenges" "">><small>*[optional]*</small>
<<button [[Submit & continue|Pre-final]]>><</button>>

----------------------------------------
# Passage Name: Pre-final

## Congratulations!
You have reached the end of the implementation plan walk-through and you are ready to have your metadata aggregated.

### Please choose an option:
<<button [[View and save a copy of your responses (print your customized implementation plan template)|Implementation Plan]]>><</button>>
<<button [[End the walk-through without saving.|Game over]]>><</button>> 

<<elseif $congrats is "t" and $servicetype is "both">>

## Congratulations! 
You have reached the end of the implementation plan walk-through and you are ready to have your metadata aggregated. You are ready to start tackling semantic metadata aggregation for your repository as well! 

### Please choose an option:
<<button [[View and save a copy of your responses (print your customized implementation plan template)|Implementation Plan]]>><</button>>
<<button [[End the walk-through without saving.|Game over]]>><</button>> 

<<elseif $servicetype is "semantic">>

## Congratulations! 
You have reached the end of the implementation plan walk-through and you are ready to start tackling semantic metadata aggregation for your repository. 

### Please choose an option:
<<button [[View and save a copy of your responses (print your customized implementation plan template)|Implementation Plan]]>><</button>>
<<button [[End the walk-through without saving.|Game over]]>><</button>> 

<<elseif $authority is "ask">>

## Don't give up!
You may need to shelve this project until it's institutionally possible.

### Until then, please choose an option:
<<button [[Try again (restart the walk-through)|Hello]]>><</button>>
<<button [[View and save a copy of your responses (print your customized implementation plan template)|Implementation Plan]]>><</button>>
<<button [[End the walk-through without saving|Game over]]>><</button>> 

<<elseif $metadatafail is "true">>

## Don't give up!
You may need to shelve this project until your catalogue and metadata are up to the standard you need.

### Until then, please choose an option:
<<button [[View and save a copy of your responses (print your customized implementation plan template)|Implementation Plan]]>><</button>>
<<button [[End the walk-through without saving.|Game over]]>><</button>> 

<<elseif $servicetype is "none" or $aggrservice is "postpone" or $aggrprotocol is "notmatch">>

## Don't give up!
You can come back later to make a plan that maximizes your datasets’ impact and reach by making the best of your current metadata services.

### Until then, please choose an option:
<<button [[View and save a copy of your responses (print your customized implementation plan template)|Implementation Plan]]>><</button>>
<<button [[End the walk-through without saving.|Game over]]>><</button>> 

<<else>>
<</if>>

----------------------------------------
# Passage Name: Implementation Plan

## Harvestable Metadata Services: Implementation Plan

<<button "Print your plan">><</button>>  <<button [[End the walk-through|Game over]]>><</button>>

### 1. Repository Information
**a) Name of repository:** <<print $repository>>
**b) Hosted by <small>(name of organization)</small>:** <<print $orgname>> 

### 2. Project Summary
<<print $summary>>

### 3. Current state of <<if $repository is "">>your repository<<else>><<print $repository>><</if>>

### a) Current metadata formats and standards:
<<print $mdstandards>>

### b) Current metadata transfer protocols used: 
<<print $protocol>>

### 4. Project Overview

### a) Objectives
<<if $servicetype is "semantic">>The repository's main interest is to improve the discoverability of data assets by enhancing the existing metadata. This will facilitate indexing by web crawling services such as Google. For that purpose, we will start a different project, distinct from HMetS, where semantic markup, in the form of schema.org tags, will be added to metadata records' landing pages.
<<elseif $servicetype is "none" or $aggrservice is "postpone">>The aim of this project is to provide harvestable metadata to align with FAIR principles and TRUST principles. Providing the harvestable metadata services to traditional metadata aggregators and/or web crawlers is out of the scope of this project.
<<elseif $servicetype is "traditional">>The aim of this project is to improve the discoverability of data assets in the repository with a traditional metadata aggregation strategy. A harvestable metadata service will be created, which can then be exposed to metadata harvesters and registries.
<<elseif $servicetype is "both">>The general aim is to improve the discoverability of data assets in the repository, using a dual approach: A traditional metadata aggregation strategy, and a semantic one. 
The project will create a harvestable metadata services, through which metadata will be exposed to metadata harvesters and registries. Then, in a separate project, metadata landing pages will be enhanced with schema.org tags, to facilitate indexing by webcrawling services such as Google.
<<else>><</if>>

### b) Anticipated Goals
*Which goals are you striving for with this implementation of harvestable metadata services?*
<<print $goals>>

### c) Expected outcomes
*What outcomes would you expect to see? If possible, indicate a time frame in which you'd expect these changes to occur?*
<<print $outcomes>>

### d) Project Beneficiaries
*The project will serve these stakeholders:*
<<print $stakeholders>>

### 5. Project Details

### a) Aggregators/Harvesting Services targeted
<<if $servicetype is "none">>None
<<elseif $servicetype is "semantic">>Semantic aggregation (e.g.) Google Dataset Search
<<elseif $servicetype is "undefined">>
<<elseif $servicetype is "both">>Semantic aggregation (e.g. Google Dataset Search) in a separate implementation plan, and these metadata aggregator(s): <<print $aggrlist>>
<<else>>These metadata aggregator(s): <<print $aggrlist>><</if>>

### b) Metadata Formats/Standards
<<if $metadatafail is "true">>The repository's metadata catalogue is not yet up to current standards for metadata sharing. 
<<else>>The existing metadata catalogue is currently using these standard(s): <<print $mdstandards>>
	<<if $newstandards isnot "">>It will be converted to these new standard(s): <<print $newstandards>><<else>><</if>> 
<</if>>

### c) Metadata Transfer Protocols (e.g. APIs/ harvesting protocols)
<<if $aggrprotocol is "match" and $aggrsupport is "notrequired">>The existing metadata catalogue is currently using these metadata transfer protocol(s): <<print $protocol>>
The targeted metadata aggregator(s) support: <<print $newprotocols>>:
The existing metadata transfer protocol is supported by the targeted aggregator(s). <<if $interopmd isnot "">>Explanation: <<print $interopmd>><<else>><</if>>
<<elseif $aggrprotocol is "notmatch" and $aggrsupport is "supported">>The existing metadata catalogue is currently using these metadata transfer protocol(s): <<print $protocol>>
The targeted metadata aggregator(s) support: <<print $newprotocols>> 
The targeted metadata aggregator(s) can provide custom support for the new metadata transfer protocols.
<<elseif $aggrprotocol is "notmatch" and $aggrsupport is "notsupported">>The existing metadata catalogue is currently using these metadata transfer protocol(s): <<print $protocol>>
The targeted metadata aggregator(s) support these protocols: <<print $newprotocols>>
The targeted metadata aggregator(s) cannot provide custom support for the new metadata transfer protocols. Providing HMetS to the metadata aggregators project is postponed.
<<else>>The existing metadata catalogue is currently using these metadata transfer protocol(s): <<print $protocol>>
The targeted metadata aggregator(s) support these protocols: <<print $newprotocols>>:<</if>>


### d) New repository components to be developed/built/upgraded
<<if $viringo is true>>*Install Viringo on your custom repository, 'an OAI-PMH compatible provider for exposing PID related metadata', that is currently being used by DataCite and FRDR.<<else>><</if>>
<<if $pycsw is true>>*Create a catalogue service on your custom repository using pycsw, a Python implementation of the OGC CSW standard.<<else>><</if>>
<<if $customAPI is true>>*Work with your repository's IT department to create the functionality you need to interact with the APIs and protocols required by the aggregators of your choice.<<else>><</if>>
<<if $migrate is true>>*Migrate some, or all, of your datasets to a subject repository that does have the ability to provide metadata to aggregators. But this might involve having to adopt a different metadata application profile, or a new schema altogether.<<elseif $aggrsupport is "supported">>Since the targeted metadata aggregators can provide custom support under the existing infrastructure, new repository components are not required to develop/build/upgrade.<</if>>

### e) Additional repository developments/activities considered
*Do you have any other repository developments or activities that you want to consider in your workflow? 
Some examples could be:
- Converting metadata to an alternate format
- Temporary embargos before publishing
- Back-up procedures
- Generating PIDs or DOIs for metadata
- Conducting quality assurance
- Adding provenance metadata*
<<print $workflows>>

### 6. Project Resources and Challenges

### a) Resources needed:
*For example, human effort, infrastructure upgrades, etc. (Don’t underestimate the human effort required for a harvestable metadata project!)*
<<print $resources>>

### b) Support from host organization
To what extent does your repository's host organization provide material and other support?
<<print $support>>

### c) Partners
*Are other organizations involved in this project? Do you have inter-institutional from partners,  groups, government or federations? Are there other projects related to this one? If so, please describe the nature of your collaborations/external support:*
<<print $partners>>

### d) Difficulties/Challenges
*Can you think of any other expected difficulties or challenges in data sharing? Some examples could be:

## Are you sharing open data or will a data sharing agreement or privacy controls be required?

## Do you have an existing research data  management plan or contract that you need to satisfy or a governance structure that needs to approve of your repository development plan?

## What are the causes of these difficulties, and/or possible measures to overcome them.*
<<print $challenges>>

### 7. Evaluation framework

### a) Metrics

## Landing page views: <<if $views is true>>Yes<<elseif $view is false>>No<<else>>Yes / No<</if>>

## Dataset downloads: <<if $downloads is true>>Yes<<elseif $downloads is false>>No<<else>>Yes / No<</if>>

## Reuse in research: scholarly citations (e.g. with DOI and other PIDs). <<if $citations is true>>Yes<<elseif $citations is false>>No<<else>>Yes / No<</if>>

## References in other online scholarly communication platforms: Links and mentions on social media, blogs, websites, etc.: <<if $mentions is true>>Yes<<elseif $mentions is false>>No<<else>>Yes / No<</if>>

## Reuse by aggregation into other data products or services: <<if $aggreuse is true>>Yes<<elseif $aggreuse is false>>No<<else>>Yes / No<</if>>

## Educational use: Appearance in course syllabi, workshops, etc.: <<if $educational is true>>Yes<<elseif $educational is false>>No<<else>>Yes / No<</if>>

## Others: <<if $ot is true>><<print $othermetrics>><<elseif $ot is false>>No<<else>>*Please specify:*<</if>>

### b) Benchmarks and methods
*Could you give a brief description of the framework you plan to use to assess and evaluate an HMetS implementation at your repository?*
<<print $evalframework>>

### 8. Other Implementation Plan Templates
Some examples of (broad-scope) data services development plans using CESSDA SaW (EU) and JISC (UK) guidance documents, tools, and templates have been collected in this document. A general outline of a detailed project plan for HMetS implementation is proposed below.
a.	General Planning 
i. Work packages
ii.  Complete Timeline
iii.  Partnership Coordination
iv.  Staffing and Project Management
v.  Project Budget
vi.  Evaluation Plan
vii.  Sustainability Plans
b.	Establishment plan (timeline before day 1)
c.	Operational plan (timeline after day 1)
  i.	Prototyping the service
  ii.	Testing plan
d.	Conclusion 
  i	Concluding remarks
  ii.	Next steps

<<button [[End|Game over]]>><</button>>

----------------------------------------
# Passage Name: Game over
End of story

Thank you for playing!

<<button [[RESTART|Hello]]>><</button>> to play again.

The International Technology Library (InTeLibrary) collects and shares RDM information resources, most of which are freely available on the web. It is curated and maintained by the International Technology Office (ITO). 
Visit [InTeLibrary’s Harvestable Metadata Services collection](https://www.zotero.org/groups/2597955/intelibrary_-_harvestable_metadata_services) for more than 300 resources about harvestable metadata services planning, development, and implementation. Areas covered include metadata standards, exchange protocols, metadata aggregation services, certification, assessment frameworks and metrics, as well as data sharing principles, best practices and recommendations.

<<button "Print the resources list">><</button>>

## Resources

### Making the case for RDM and writing an implementation plan
- Chiarelli, A. & Johnson, R. (2017) [Making the case for research data management - Case studies](https://doi.org/10.5281/zenodo.817936).
- CoreTrustSeal (2019). [CoreTrustSeal trustworthy data repositories requirements 2020-2022](https://doi.org/10.5281/ZENODO.3638211)
- Dierkes, J. & Wuttke, U. (2016) [The Göttingen eResearch Alliance: A case study of developing and establishing institutional support for research data management](https://doi.org/10.3390/ijgi5080133). *ISPRS International Journal of Geo-Information*, *5*(8), 1-11.
- Garnett A., Leahey, A., Savard, D., Towell, B., & Wilson, L. (2017) [Open metadata for research data discovery in Canada](https://doi.org/10.1080/19386389.2018.1443698). *Journal of Library Metadata*, *17*(3–4), 201-217
- International Science Council (2019) [Advancing science as a global public good: Action plan 2019-2021](https://council.science/wp-content/uploads/2019/12/Advancing-Science-as-a-Global-Public-Good_ISC-Action-Plan-landscape.pdf).
- RDA FAIR Data Maturity Model Working Group (2020). [FAIR data maturity model: Specification and guidelines](https://doi.org/10.15497/RDA00050). Research Data Alliance
- Whyte, A. & Tedds, J. (2011) [Making the case for research data management](https://www.dcc.ac.uk/guidance/briefing-papers/making-case-rdm).
- Yarmey, L., & Baker, K. S. (2013). [Towards standardization: A participatory framework for scientific standard-making](https://doi.org/10.2218/ijdc.v8i1.252). *International Journal of Digital Curation*, *8*(1), 157–172.

### Interoperability
- Crosas, Mercè. (2019). [Data federation: Standards, best practices, and thoughts](https://scholar.harvard.edu/mercecrosas/presentations/data-federation-standards-best-practices-and-thoughts). Presented at the Sixth Open Research Cloud Alliance Workshop, May 22, 2019. 
- Research Data Repository Interoperability Working Grouop (2017). [Research data repository interoperability primer](http://doi.org/10.15497/RDA00020).
- Wilkinson, M. D., Dumontier, M., Aalbersberg, I. J., Appleton, G., Axton, M., Baak, A., Blomberg, N., ... Mons, B. (2016). [The FAIR guiding principles for scientific data management and stewardship](https://doi.org/10.1038/sdata.2016.18). *Scientific Data*, *3*(1), 1–9.
- Verhey, C., Urquidi Díaz, A., & Payne, K. (2021). [14 metadata syndication things: Training guide](https://doi.org/10.5281/zenodo.4589084). WDS International Technology Office.
- Zhao, Z., & Hellström, M. (2020). *[Towards interoperable research infrastructures for Environmental and Earth Sciences : A reference model guided approach for common challenges](https://doi.org/10.1007/978-3-030-52829-4)*. Springer Nature.

### Metadata Standards
- Digital Curation Centre (n.d.). <a href="https://www.dcc.ac.uk/guidance/standards/metadata">Disciplinary metadata.</a>
- Research Data Alliance Metadata Standards Directory Working Group (n.d.). [Metadata](http://rd-alliance.github.io/metadata-directory/).
- Tilmes, C. (2013). [Data formats: Choosing and adopting community accepted standards](https://commons.esipfed.org/node/1424).
- WDS-ITO SDO Interoperability Primer 

### Machine interoperable interfaces

### ERDDAP
- National Oceanic and Atomspheric Administration (n.d.). [Set up your own ERDDAP](https://coastwatch.pfeg.noaa.gov/erddap/download/setup.html).

### ResourceSync
- Knoth, P., Cancellieri, M., & Klein, M. (2019). [Comparing the Performance of OAI-PMH with ResourceSync](https://www.slideshare.net/martinklein0815/comparing-the-performance-of-oaipmh-with-resourcesync).
- Sompel, H. V. (2014). [Overview of ResourceSync](https://www.niso.org/standards-committees/resourcesync).

### Open Archives Initiative-Protocol for Metadata Harvesting(OAI-PMH)
- Breeding, M. (2002). [Understanding the Protocol for Metadata Harvesting of the Open Archives Initiative](	https://librarytechnology.org/document/9944). *Computers in LIbraries*, *22*(8), 24-29.
- Carpenter, L. (2003). [Implementing OAI-PMH](https://web.archive.org/web/20180418113309/http://www.oaforum.org/tutorial/english/page4.htm).
- Haslhofer, B., & Schandl, B. (2010). [Interweaving OAI-PMH data sources with the linked data cloud](https://doi.org/10.1504/IJMSO.2010.032648). *International Journal of Metadata, Semantics and Ontologies (IJMSO)*, *5*(1), 17-31.
- Kata team repository (n.d.). [Open Archives Initiative-Protocol for Metadata Harvesting(OAI PMH) extension to CKAN](https://extensions.ckan.org/extension/oaipmh/)
- Knoth, P., Cancellieri, M., & Klein, M. (2019). [Comparing the Performance of OAI-PMH with ResourceSync](https://www.slideshare.net/martinklein0815/comparing-the-performance-of-oaipmh-with-resourcesync).
- Lagoze, C., Sompel, H.V., Nelson, M., & Warner, S. (2005). [Implementation guidelines for the Open Archives Initiative Protocol for Metadata Harvesting: Guidelines for repository implementers](http://www.openarchives.org/OAI/2.0/guidelines-repository.htm)

### Open Geospatial Consortium-Catalogue Services for the Web (OGC-CSW) 
- Open Geospatial Consortium (n.d.). [Catalogue Services standard 2.0 extension package for ebRIM application profile: Earth Observation Products](https://www.ogc.org/standards/cat2eoext4ebrim).
- Open Geospatial Consortium (n.d.). [OGC API - Records - Overview](https://ogcapi.ogc.org/records/overview.html).

### International Organization for Standardization (ISO)
International Organization for Standardization (2005). [ISO 19128:2005: Geographic information — Web map server interface](https://www.iso.org/standard/32546.html).

### Sitemaps
Sitemap.org (2016). [Sitemaps XML format](https://www.sitemaps.org/protocol.html).

### Metadata Aggregators
- Hudson-Vitale, C. (2017). [The current state of meta-repositories for data](https://openscholarship.wustl.edu/lib_papers/19/). In *University Libraries Publications* (pp. 251-261). Washington University in St. Louis.
- Schirrwagen, J. (2019). [Cross-disciplinary discovery in a global repository network: The case of BASE – Bielefeld Academic Search Engine](https://www.opensciencefair.eu/images/workshops/OSFair2019_74-BASE.pdf). Presented at the Open Science Fair Workshop on Data Discovery Across Disciplines, Porto, Portugal.
- World Data System-International Technology Office (2021). [Guide to metadata aggregators for repository managers](https://doi.org/10.5281/zenodo.4589055), and the [Searchable index of metadata aggregators](https://doi.org/10.5281/zenodo.4589050) 

### Measuring success
- Crosas, M. (2017). [Measuring the impact of digital repositories](https://scholar.harvard.edu/mercecrosas/presentations/measuring-impact-digital-repositories). Presentation at the meeting on Measuring the Impact of Digital repositories, NSF, Arlington, VA.
- Downs, R. R., Chen, R. S., & Schumacher, J. A. (2017). [Measuring the interdisciplinary impact of using geospatial data with remote sensing data](https://doi.org/10.7916/d8-57q4-h516). Paper PA11C-09 Presented at American Geophysical Union, Fall Meeting 2017. New Orleans, LA.
- Liu, C. (2018). [Data Impact Score (DIS) —A quantitative method of data performance to the data-driven sciences](https://doi.org/10.3974/geodp.2018.02.02). *Journal of Global Change Data & Discovery*, *2*(2), 135-143.
- Suleman, H. (2005). Analysis and evaluation of service oriented architectures for digital libraries. In C. Türker & H.-J. Schek (Eds.), *Peer-to-peer, grid, and service-orientation in digital library architectures* (pp. 130-146). Springer.

### Data sharing principles, recommendations and best practices
- Global Indigenous Data Alliance (n.d.). [CARE principles for Indigenous data governance](https://www.gida-global.org/care).
- Yarmey, L., & Baker, K. S. (2013). [Towards standardization: A participatory framework for scientific standard-making](https://doi.org/10.2218/ijdc.v8i1.252). *International Journal of Digital Curation*, *8*(1), 157–172.
