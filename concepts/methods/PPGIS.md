# Public Participation GIS

#spring-school #methods #gis #ppgis

*Workshop by Anna Kajosaari, Aalto University*

- [[#Introduction to digital participatory mapping methods|Introduction to digital participatory mapping methods]]
	- [[#Introduction to digital participatory mapping methods#PPGIS methods|PPGIS methods]]
	- [[#Introduction to digital participatory mapping methods#Applications|Applications]]
	- [[#Introduction to digital participatory mapping methods#Summary of PPGIS as a research tool|Summary of PPGIS as a research tool]]
	- [[#Introduction to digital participatory mapping methods#Qs|Qs]]
- [[#PPGIS Survey Design|PPGIS Survey Design]]
- [[#PPGSI Data Analysis|PPGSI Data Analysis]]
- [[#MaptionNAIRE analysis tool|MaptionNAIRE analysis tool]]


#### Introduction to digital participatory mapping methods

Geographic Information Systems (GIS) for viewing, processing, editing, analysing spatial data; from data to maps.

Type of data: nodes (pixel), vectors (points, lines, areas)

What knowledge GIS data represent: **how urban space is used** (how do residents use the street), **how is the space experienced and perceived** (is it safe, [[PPUE]]), **how do citizens envision the future of the space** (soft GIS knowledge), physical elements (eg. street, street direction, street lights), land uses (eg. parking areas), social data (eg. crime rate mapped to a neighbourhood)

Participatory: soft knowledge coming from local experiences -> getting knowledge you can only get from people

Participatory + GIS:
- **Participatory GIS** (PGIS): emphasis on community empowerement, building social capital; non-digital mapping methods; geographic focus on rural communities
- **Volunteered Geographic Information** (VGI): expand spatial information using citizens are sensors; location-based data from apps and social media (Twitter, Instagram, Strava, TripAdvisor); focus on varied geographic contexts;
- **Public Participation GIS** (PPGIS): emphasis on public involvment to informa land use planning and management; digital mapping technologies; geographic focus on Europe, USA, Australia

##### PPGIS methods

- **Mapping people's spatial knowledge**: mapping behaviours, perceptions, values, development ideas 
- **Spatial and non-spatial data**: PPGIS tools are digital survey tools combining traditional survery elements (eg. questions) and mapping activities
- **Different uses and users**: used in diverse fields, at different scales, and among different population groups
- **Research and practice**: used both as a reserach method and as a participatory planning tool

##### Applications

PPGIS focuses on **human spatial behaviour and experiences**, is about locating diverse human-environment interactions.

Part of **environmental psychology**: place attachement research, affordance theory, perceived envrionmental quality

**Ecosystem services and landscape values**: identifying ecosystem services, cultural services (eg. recreation, aesthetic enjoyment, physical and mental health benefits, spiritual experiences); mapping landscape values (eg. cultural, historic, therapeutic, aesthetic, spiritual value) #thesis-method

**Use and accessibility of public open space**: focus on green and blue environments; travel behaviours, envrionemntal health reserach

Can be used in the **planning process**: during initiation, evaluation, decision making, comparing alternatives, maintenance

##### Summary of PPGIS as a research tool

Benefits:
- Integrating place-based, experiential knowledge into GIS
- Digital method allows for large sample sizes
- Customisable for research use

Limitations:
- Reliance on access to mapping hardware and internet
- Accessibility barriers
- Spatial precision and temporal granularity lower than in GPS-based methods

##### Qs
- How small can a sample be in order to be valuable? -> depends on suface area, eg. 20 people for a courtyard, 200 for a public park...
- Feasibility of using ppgis to analyse envrionmental justice as masters thesis?
- Can PPGIS be used to understand who isn't using a space, and why? or can this only be inferred based on who uses the space; assuming you don't have access to everyone in the city, and are asking for survey responses in the research space (eg. park)



#### PPGIS Survey Design

[maptionnaire](https://new.maptionnaire.com/)

Considerations:
- What is the added benefit of the mapping activity? Do you need spatial data to study the phenomenon?
- How to represent human experiences in GIS as points, lines, and polygons (areas)?
- What is the geographic context and scale of your survey
- Who will be answering your survey? What can you expect them to know, and what not? How motivated will they be?
- How do the mapping software, hardware, supporting materials and instructions influence the mapping experience?

Walkibility
- circularity: walking is the mode of transport that is least impactful on environment, free, mode of transport, thus should be accessible and attractive for all; minimal infrastructure/resources required compared to public transport (no fuel, little road/street infra...); 1using what is already built and not using more land;
- experience of walking on daily/weekly basis: is it good or bad?
- why is it this way? categorise why good/bad: infrastructure, safety, accessibility, attractiveness, other
- 

#### PPGSI Data Analysis

- Individual data points/heat maps
- Outliers: be careful when removing them from the data set (eg. a point in the sea might be valid, depending on the associated question)
- **Spatial analysis**: find spatial patterns and relationships (using GIS software), combine spatial and non-spatial (eg. softGIS) PPGIS data with secondary sources of GIS data
	- Hot/cold spot analysis: where eg. green spaces are more or less used or nice #thesis-method 
	- Geographically weighted regression: eg. probability of good/bad green space
- **Statistical analysis**: descriptive and inferential analysis of quantitative research data; variables derived from spatial and non-spatial survey responses;
	- eg. reporting frequencies, tendency, distribution, parametric and non-parametric statistical tests, regression analysis
- **Qualitative analysis**: thematic or content analysis for open-ended survey questions; usually combined with spatial analysis for place-based knowledge


#### Maptionnaire analysis tool
