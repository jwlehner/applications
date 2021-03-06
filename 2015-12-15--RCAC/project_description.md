---
output: 
  pdf_document: 
    latex_engine: xelatex
---

<!--
Project Description (Maximum 1500 words)

The project description should include the project’s relevance to the given
field, the resources required in Turkey, and steps taken to get permissions to
access those resources, as appropriate to your study. The applicant should
indicate also how much s/he has already undertaken on the proposed project as
well as what specific products (e.g., dissertation, articles, books) are
expected as outcomes. This document should contain no bibliography nor
footnotes.  


--------------------------------------------------------------------------------
-->
Koç RCAC: Post-Doc Fellowship application

(words: 1458) 



# Visualize Diachronic Human-environment Interactions: A Model for the Milesian Peninsula {.unnumbered}

 
This project will characterize the human-environment interactions, their nature
and intensity on the Milesian Peninsula (southwestern Turkey, province of Aydın)
from the prehistoric to the ottoman period (ca. 5th millennium B.C./2nd
millennium A.D.). A new intensive survey on the peninsula provides the
opportunity to reassess hypothesis concerning hinterland occupation, settlement
patterns, interconnection and flows of commodities in this particular setting.
More generally for the field of archeology, this work will formulate innovative
generalizations about the visualization of uncertainty and inaccuracy in time
and space - intrinsic to the nature of data - to address human-environment
interactions. The three principal lines of research encompass : 

 1. Focus on traditional narrative reconstructions and their visualization by
    using data from the extensive and intensive survey of the *Panormos Project*
on top of previous research. To what extent  and how was this landscape used
during different eras? How did dramatic changes in the landscapes (silting of the
Büyük Menderes) associated with complex cultural variations shift the patterns
of human-environment interactions? 

 2. Develop tools (open-source software packages) to explore the analytical
    consequences of temporal and spacial uncertainty and how they enrich our
visualization and consequently our narrative reconstructions.  How can
quantification of uncertainties - a potsherd dating somewhere between 800 and 400
B.C. - be integrated  into archaeological analysis and be represented? 

 3. Leverage the (computational) transparency and reusability of my research to
    make it easily adaptable and modifiable by other (anatolian) survey
projects.  

To achieve this goal, a 9-month fellowship at RCAC will give me the opportunity
to, on one hand, interact with the very rich network of fellows and researchers
at RCAC and at the Koç Universitiy bringing expertise and guidance in digital
archeology as well as in the material culture from the prehistoric to the
ottoman period and, on the other hand, collaborate with other survey teams in
Anatolia by promoting an open access and open research commitment.


## Background to the project 

Multiple works have been dedicated on the geology of the Milesian Peninsula
(Helmut Brückner), and  its archaeological remains (Milet, Priene, Didyma,
Tavşan Adası) as well as  extensive surveys (Paul Wilski, Hans Lohmann) covering
over a century of research. These works provides plenty of valuable information
about the peninsula but need to be integrated and complemented to build
computational model and to test hypotheses concerning hinterland occupation,
integration or economic organization. My involvement in the intensive survey of
the *Panormos Project* made me aware of how small or short occupations, which
populated this landscape, remain undocumented. Thus, 'unknown', 'negative' or
'non significant' results tend to be dramatically overlooked. This lead to a
biased representation of what exist. In addition, uncertainty and inaccuracy in
time and space (intrinsic to the nature of data) as well as in the collection of
data ('human error') has been underestimated, if not wholly ignored, in
archaeological applications. By counter-balancing such selective reporting, this
project aims to expand the capacity of formulating human-environment
generalizations. Here I present a research proposal for an analysis of data from
the Milesian Peninsula collected as part of the survey of the *Panormos
Project*.






## Case Study: *The Project Panormos*  

Excavations were carried out from 2012 to 2014 at a necropolis near Panormos
(ancient harbor of Didyma). The necropolis (mid-7th and late-6th centuries BC)
has not been identified by extensive survey and was first identified by
geologists, who reported a concentration of ancient ceramics in a modern
drainage trench. These results raised a number of questions about the wider
context of the landscape surrounding the necropolis, the intensity and types of
usage of the area, before and after its main occupation. Why after different
extensive surveys was this necropolis still undiscovered and what does that mean
for the general assessment of the region? In 2014, the *Project Panormos* team
started an intensive pedestrian survey that will continue during the summer
2016.

The survey teams systematically walking the landscape, which was divided into
survey tracts (50 x 50 m), using a coverage of 20 % (five walkers, each
covering a swath of two meters, with a spacing between walkers of approximately
ten meters). All archaeological materials encountered were counted and
diagnostic finds were collected. A wide array of relevant data, such as
visibility conditions, topographical and geomorphological characteristics,
present land-use, and so forth were also recorded. 

Records from the  Chalcolithic to the Ottoman period  demonstrate that long-held
assumptions should be revised. On the one hand, we find scarce evidence for
prehistoric interactions in regard to known settlements; yet on the other, we
find abrupt and rapidly evolving change during the 1th millennium driven by
politics but also geographic changes (continuous sedimentation of the
Peninsula), when the occupation was generally assumed concentrated in
settlements. 



**Authorization to study the material**: Anja Slawisch and Toby C. Wilkinson,
responsible of the *Panormos Project*, wholly support this application, which I
elaborated in constant exchange with them. They may be contacted for further
information (contacts at the end of my CV).





## Methodology 

The application of GIS (Geographical Information Systems) forms the primary
methodology of this project. Computerized GIS and database technology is being
used as the backbone to develop new tools to visualize uncertainty in time and
space. 

1.  **Scripting and automation** (foundational implementation started in 2015): The
general approach is that of a scripted workflow. Among archaeologists who share
code with their publications, R is currently the most widely used programming
language and will be, therefore, implemented for this research. Using a
programming language such as R extend beyond enhanced reproducibility: it may be
freely distributed over different platforms, quickly reused, modified or
augmented. 

2. **Integrating Environmental and Extensive Survey Work** (Started by T.C.
   Wilkinson in 2015): Creating a detailed geographic database of published
archaeological sites, digitization of environmental data, natural resource, roads,
modern land-use, elevation model, etc.
 
3. **Visualizing uncertainty**: The landscape is not static and time is
   constrained in ranges. Collection of data at various moments result in
different archaeological data set (before or after a field being plowed for
example, or heavy rain). Attributed time to artifacts varies between ranges of
25 years to 300 years, which are susceptible to evolve according to new
discoveries or reevaluation of precedent assumption. To address spatial patterns
and processes  and, potentially, the underlying process behind them, I will
create visualization using point pattern analysis (for example, the repartition
of diagnostic sherds from a period) and surface modeling (for assessing general
trends like pottery densities). I focus on accounting for uncertainty in the
mapping by integrating formally the temporal dimension. In this part I will
implement research done in geographical research using aoristic analysis.
Spatial uncertainty will be processed with multi-scalar and Monte Carlo
approaches. Thus the results will not be to propose a single solution (a single
pattern or process) but rather an environment where comparisons between
alternative hypotheses are made easier.


## Resources required in Turkey

- Specific libraries for the collection of archaeological and environmental data
  from the Milesian Peninsula (RCAC, DAI, IFEA, Orient-Institut, İTÜ, İÜ, BOA) 

- Light Computational Environment (Server running *R* and *Gitlab*)




## Relevance for the field of archeology

This work will test long-held assumptions about the occupation from Prehistoric
to Ottoman periods from the Milesian Peninsula, and demonstrate how
uncertainties play a role in the construction of narratives. This research aims
to build a model by examining a mirco-region using extensive, intensive survey,
excavation data, but also integrating environmental data. Furthermore, an
important goal of this project is to strength the ongoing relations and
facilitate comparisons between surveys by providing reusable code and enabling
the creation of personalized maps to forge similar basis. This research project,
which implements cuting-edge research methods in the spirit of Open Access will
support to establish myself into the forefront of the emerging field of 'Digital
Archeology'. I believe that this project and future collaborations that develop
out of this project will help serve to accomplish this.

## Outcomes 

Tangible results of this work will include:

1. **Workshop**: A small "internal" workshop will be organized to discuss
   methods, mapping techniques, and data sharing with survey project from
Anatolia (March 2017)

2. **Article**:  "Visualize diachronic Human-environment Interactions: A Model
  for the Milesian Peninsula" (to be submitted in June 2017)

3. **Software Package**: All the code created for the article will be
  documented and available in a form of a package, freely accessible on-line
(Github/Zenodo). This aims to provide a transparent research but also allow
other project to modify my research for similar, but different and particular
aims (to be submitted in June 2017 in parallel to the article). 

4. **Contribution to the Panormos-Survey publication**: The maps created during
  the fellowship  will serves as a basis for innovative  narratives for
the survey publication (to be published by the DAI). The interdisciplinary team of
researchers agreed to hand over their manuscripts in December 2017.



<!-- Commented out
1. **Article** (with T.C. Wilkinson): "Methodological transparency in the Field:
  collaboration, version control and reproducibility on the Project Panormos
survey" (Provisional title, to be submitted to the *Journal of Field Archaeology*
in March 2016) 

5. **Interactive interface**: An interactive interface will be provided on-line (with a light restricted
access for the protection of cultural heritage). 
--> 
