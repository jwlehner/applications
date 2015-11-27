Project Description (Maximum 1500 words)

The project description should include the project’s relevance to the given
field, the resources required in Turkey, and steps taken to get permissions to
access those resources, as appropriate to your study. The applicant should
indicate also how much s/he has already undertaken on the proposed project as
well as what specific products (e.g., dissertation, articles, books) are
expected as outcomes. This document should contain no bibliography nor
footnotes.  

--------------------------------------------------------------------------------

Koç RCAC: Post-Doc Fellowship application



# Visualize Human-environment Interactions in Space and Time: A Model for the Milesian Peninsula


## Background to the project 
 
Anthropologists play unique and critical roles in understanding
human-environment interactions, environmental transformations, and the place of
weather and climate in everyday life as well as in contemporary global
discourse.  Records of landscapes (physical and cultural) are contingents upon
historical, cultural, and economic processes that vary across time, and suggest
narratives of spatial relationships explaining how people engage with their
environment. Excavations associated with surveys provide a full range of
materials to generate  narrative reconstructions and their visualizations,
traditionally communicated with maps. Static or interactive mapping, is a
powerful tool to combine, represent and disseminate information about spatial
relationships, which are too broad and too complex to be easily understood. At
the same time, maps are subjective visualizations that capture our understanding of
the cultural and physical records, shaping our mental image of places and
constructing our sense of spatial relations. Different techniques are widely
employed in the mapping of archaeological records. Point pattern analysis, for
example, refers to one such group of methods that examine the spatial
configuration of point observations across a study area  and, potentially, the
underlying process behind its formation. Common point pattern analysis includes
representation of sites from a period or the repartition of a type of artifact.
Surface modeling is another analytical tool extremely valuable for assessing
general trends. Elevation models or pottery densities are probably the most
common representation for surface modeling in archeology.

Here I present a research proposal for an analysis of data from the Milesian
Peninsula (southwestern Turkey) collected as part of the survey of the *Panormos 
Project*. My project calls attentions on the importance of uncertainty in
mapping data from survey to investigate human-environmental interactions over time.
Uncertainty and inaccuracy in time and space (intrinsic to the nature of data)
as well as in the collection of data ('human error') has been underestimated, if
not wholly ignored, in archaeological applications. In addition,
'unknown', 'negative' or 'non significant' results tend to be overlooked in
visualization. This lead to a biased representation of what existed. By
counter-balancing such selective reporting, this project contributes to the field of archeology by formulating
generalizations about human-environment interactions.  Records from the
Chalcolithic to Byzantine periods (ca. 5th millennium B.C./1th millennium A.D.)
demonstrate that long-held assumptions should be revised. On the one hand, we
find scarce evidence for prehistoric interactions in regard to known
settlements; yet on the other, we find abrupt and rapidly evolving change
during the 1th millennium driven by politics but also geographic changes
(continuous sedimentation of the Peninsula), when the occupation was generally
assumed concentrated in settlements. Effort to apply the tenets of
‘Reproducibility’ and ‘Open Data’ to the creation of the data at Panormos makes
this data-set outstanding for a case study.

For my project, first, I will focus on traditional narrative reconstructions and
their visualization by using data from the extensive and intensive survey of the
*Panormos Project*. To what extent was this landscape used during different
historical eras?  Second, I will adopt and develop tools (open-source software
packages) to explore the analytical consequences of temporal and spacial
uncertainty and how they enrich our visualization and consequently our narrative
reconstructions.  How quantification of uncertainties can be integrated  into
archaeological analysis and represented?  Finally, I will release the different
modules of open-source software, and focus on their reusability to make my
research easily adaptable and modifiable by other (anatolian survey) projects.  



## Case Study: *The Project Panormos*  

Museum excavations were carried out from 2012 to 2014 at a necropolis near
Panormos (ancient harbor of Didyma). The necropolis has not been identified by
extensive survey and was first identified by geologists, who reported a
concentration of ancient ceramics in a modern drainage trench. The excavation
established that the necropolis was mainly used from the mid-7th and late-6th
centuries BC. Locally-produced vessels were found alongside a wide range of
imports from Etruria, Corinth, Athens or Egypt, but prehistoric fragments also
turned up scarcely during the excavation. These results raised a number of
questions about the wider context of the landscape surrounding the necropolis,
the intensity and types of usage of the area, before and after its main
occupation. Why after different extensive surveys was this necropolis still
undiscovered and what does that mean for prehistoric periods? In 2015, the
*Project Panormos* team started an intensive pedestrian survey around the
necropolis with the aim of increasing ‘horizontal’ and ‘diachronic’ knowledge of
this part of the Milesian peninsula. This work will continue during the summer 2016.

The survey teams systematically walking the landscape, which was divided into
survey tracts (50 x 50 m), using a coverage of 20 % : five walkers, each
covering a swath of two meters, with a spacing between walkers of approximately
ten meters). All archaeological materials encountered were counted and
diagnostic finds were collected. A wide array of relevant data, such as
visibility conditions, topographical and geomorphological characteristics,
present land-use, and so forth were also recorded. The survey was designed 'born
digital' and 'Free'. The digital infrastructure produces standardized data,
and structures data in a form ready for long term archiving and quick
open access dissemination. This has not only provided a smooth field
documentation process, it has also opened a whole new area of possibilities for
fieldwork techniques, simultaneous cooperation in different locations as well as
expanding transparency in the methodology and the results by using scripts of
code for reproducible, reusable and modifiable analysis.


** Authorization to study the material ** (layout: in a frame box)

Anja Slawisch and Toby C. Wilkinson, responsible of the *Panormos Project*,
wholly support this application, which I elaborated in constant exchange with
them. They may be contacted for further information (contacts at the
end of my CV).



## Methodology 

The application of GIS (Geographical Information Systems) forms the primary
methodology of this project. Computerized GIS and database technology is being
used as the backbone to develop new tools to visualize uncertainty in time and
space. 

1.  Scripting and automation (Already implemented during the summer 2015): The
general approach is that of a scripted workflow. Among archaeologists who share
code with their publications, R is currently the most widely used programming
language and will be, therefore, implemented for this research. Using a
programming language such as R extend beyond enhanced reproducibility: it may be
freely distributed over different platforms, quickly reused, modified or
augmented. Scripting enables automation of process and produces new outputs as
soon as fresh data are collected, delivering steadily up-to-date maps.


2. Uncertainty: The landscape is not static and time is constrained in ranges. Collection of
data at various moments result in different archaeological data set (before or after a field being plowed for example,
or heavy rain). Attributed time to artifacts varies between ranges of 25 years to 300
years, which are susceptible to evolve according to new discoveries or
reevaluation of precedent assumption. I focus on accounting for uncertainty when
mapping distributions by integrating formally the temporal dimension. In this
part I will implement research done in geographical research using aoristic
analysis. The output will thus not be to propose a single solution (a single
pattern) but rather an environment where comparisons between alternative
hypotheses are made easier and new 


3. Interactivity: Re-assessment of established narratives is often an extremely
   slow process. It is seldom possible to quickly retrieve information from an
archaeological project to reuse it for his own research. I will move beyond our
singular focus on printed map to take advantage of digital interactivity by
creating an easy to use interactive interface (with the library *Leaflet*). I
want to  ease the  construction of alternative explanations by leveraging the
capacities to draw personalized maps (zoom ability, selection of information,
colors, style),.

## Cooperation in Istanbul

 - With IT-Facilities of Koç: R Server, Gitlab Server
 - 


## Relevance for the given field 

The proposed project will characterize the human-environment interactions, their
nature and intensity on the Milesian Peninsula from the prehistoric to the
Byzantine time. Nearly all previous work on this topic has relied on excavations
or extensive surveys, which are often inadequate to test hypotheses concerning
hinterland occupation, integration or economy. Small or short occupations,
which made the landscape, remained undocumented. By examining a mirco-region
materials using extensive but also intensive survey data and excavation, this work will test
long-held assumptions about the occupation from Prehistoric to Byzantine periods
and explain how uncertainty plays a role in the construction of this narratives.
Furthermore, an important goal of this project is to strength the ongoing
relations among survey by providing reusable code and enabling the creation of
personalized maps to compare surveys, which a similar basis. This research
project, which implements cuting-edge research methods in the spirit of Open
Access will support the establishment of RCAC and Koç into the forefront of the
emerging field of 'Digital Archeology'. I believe that this project and future
collaborations that develop out of this project will help serve to accomplish
this.

## Outcomes 

The tangible results of this work, I hope, will take three different forms.
Firstly, the maps drawn and the narrative I will add to the maps will serve as
contribution in the Panormos-Survey publication. The interdisciplinary team of
researchers agreed to hand over their manuscripts  between June and September 2017.
Secondly, all the code will be documented and available in a form of a package,
freely accessible. This aims to provide a transparent research but also allow
other project to modify it for similar, but different aims. Thirdly, an
interactive interface will be provided on-line (with a light restricted
access for the protection of cultural heritage). I would benefit
immensely meeting key Turkish and other researchers working on similar topics in
Turkey, by providing key support for reusing my data-set and advocating for a
decentralized cooperation.

