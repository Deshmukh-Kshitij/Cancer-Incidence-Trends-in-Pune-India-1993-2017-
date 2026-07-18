# Cancer Incidence Trends in Pune, India (1993–2017)

## Research Question
**How has the burden of cancer incidences in the city of Pune changed over a 25-year period from 1993–2017, and how do these patterns differ by sex, age, and cancer type?**

## About Pune

Pune is the second-largest city in the state of Maharashtra and one of India's most populous urban centers. It is widely known as an educational hub — sometimes called the "Oxford of the East" — home to numerous universities and research institutes, alongside a thriving information technology and manufacturing industry sector.

Pune's population has grown rapidly over the past few decades, driven largely by migration of students and professionals. Pune has a relatively young demographic profile with a median age in the late 20s. This combination of rapid urbanization, a large population base, and long-standing institutional infrastructure makes Pune's population-based cancer registry one of the longest-running in India which provides a particularly valuable source for tracking long-term cancer trends.

## About IACR Cancer Registries and the CI5 Series

The International Association of Cancer Registries (IACR), in collaboration with the International Agency for Research on Cancer (IARC), maintains the *Cancer Incidence in Five Continents* (CI5) series — a set of volumes published roughly every five years that compiles cancer data from population-based registries around the world.

A population-based cancer registry systematically records cancer incidences within a defined geographic area providing a broader picture of how common each cancer type is in a community.

The Pune (Poona) registry has contributed data to the CI5 series since Volume VIII (1993), making it possible to trace over two decades of cancer trends in this specific urban population.

This kind of data is valuable because it informs public health planning by helping researchers and health officials answer practical questions such as which cancers are becoming more or less common, which age groups or sexes are most affected, and where prevention or screening resources should be directed.

## Objective
This notebook extracts, cleans, and analyzes population-based cancer registry data for Pune from five successive volumes of the IARC's *Cancer Incidence in Five Continents* (CI5) series (Volumes VIII through XII).

The goal is to:

- Build a single, consistent dataset from five differently formatted source files, standardizing cancer codes, age groups, and registration periods across volumes.
- Calculate crude cancer incidence rates (cases per 100,000 people) overall, by sex, and by age group, to track how cancer burden evolved across the five registration periods (1993-1997 through 2013-2017).
- Identify the 10 most frequently diagnosed cancer types in Pune over this period and examine how each one trended over time and across age groups.

## Data Source
All data originates from the International Agency for Research on Cancer's (IARC) *Cancer Incidence in Five Continents* database, covering the Pune (Poona) population-based cancer registry. Source files: https://ci5.iarc.fr

## Key Conclusions

- Both the male and female population at risk between 0-79 years of age in Pune grew by 2.15 and 2.13 times for males and females respectively between 1993 and 2017.
- All-sites crude cancer incidence rates per 100k among females remained consistently higher than male rates across registration periods from 1993 to 2017.
- All-sites crude cancer incidence rates per 100k increased with age in males and females within each registration period from 1993-2017.
- Collective analysis of top 10 crude cancer incidence rates per 100k after filtering for consistent cancer names across registration periods, shows that colon, mouth, oesophagus, rectum, stomach, and tongue were tissues commonly diagnosed with cancer between males and females, whereas, bladder, larynx, liver, and prostate in males and breast, cervix uteri, corpus uteri, ovary in females were diagnosed at a higher rate.
- Age-specific trends of crude cancer incidence rates per 100k for top 10 tissues between males and females show an overall increase in cancer incidence rates with age.
  
## TO RUN THE PROJECT, PLEASE PLACE THE PYTHON SCRIPT AND THE iarc_registeries_data ZIP FILES IN THE SAME FOLDER.
