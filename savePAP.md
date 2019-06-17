# Study title: SAVE - Solent Achieving Energy Through Efficiency

# Citation

If you want to refer to this PAP please use:

 * Anderson, B., Rushby, T., Bahaj, A., James, P. (2019) Solent Achieving Energy Through Efficiency (SAVE) Project Research Protocol, Southampton: University of Southampton.

# Geographical area
County of Hampshire and the Cities of Southampton and Portsmouth

# Date of data colletion
January 2017 - June 2019

# Unit of study
Households

# Research questions/purpose (brief)
To test a series of energy efficiency and demand response interventions using a representative population sample of households from the above area(s)

# Research methodology
Randomised control trials

## Sample recruitment
Stratified random address-based sampling to provide an address list using English IMD deciles for OAs as a strata. Random selection of Census OAs within each IMD strata, random selection of ~30 addresses within OAs. Addresses sent an initial letter and follow-up house call to recruit household to sample and install electricity monitor.

## Research methods
 * 15 min whole-household kWh consumption data
 * repeated household surveys and time-use diaries to co-incide with trial interventions

## Sample size and justification
4,000 (1,000 for a control group and 1,000 each for 3 subsequent intervention groups). Sample size based on statistical power analysis using the Irish CER Demand Response Trial dataset to test the samples required to detect >= 6% evening peak period (16:00 - 20:00) consumption reduction. ~10% over-recruitment in each sample to allow for attrition.

## Allocation to study groups (if any)
Pre-recruitment random allocation of selected addresses to control or intervention groups.

# Proposed data cleaning

We will scan the data for extreme outliers that show implausible kWh values and these will be removed from analysis. 

0 or exceedingly small daily sum values will be used to test for correct monitoring installation. If not corrected by follow-up the household's data will be excluded from analysis.

# Proposed analytic methods

Assuming randomisation process produces no systematic biase between groups:

 * ANOVA analysis of differences in mean peak period energy consumption between the control and trial groups;
 * Multivariate regression models to test interaction of intervention effects and customer types.
 
If systematic biases between the groups emerges over time then we will conduct:

 * Difference in Difference (DiD) analysis to control for differing consumption trajectories;
 * Multivariate DiD analysis as above.
 
We expect that all such models will require the use of log(consumption) values to correct for strong positive skew.
 
# Code release
All analytic R code is currently held in a Univeristy of Southampton resitricted access git repository. This will be made public when the data is depositied (see Data).

# Data release
All survey and electricity consumption data will be depositied with the UK Data Service.

 * Study number: XX _link_ XX

# Research partners
SSEN, University of Southampton, DNV-GL with BMG Research (recruitment and installation) and Navetas (elelctricity monitor supplier).

See www.energy.soton.ac.uk/tag/save/

# Funding source
UK ofgem [Low Carbon Networks Fund](https://www.ofgem.gov.uk/publications-and-updates/low-carbon-networks-fund-submission-southern-electric-power-distribution-%E2%80%93-solent-achieving-value-efficiency)