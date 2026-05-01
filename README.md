# covid_vaccine_io
Code and line-level data for MSK analysis of SARS-CoV-2 mRNA vaccines and immunotherapy outcomes

## Dependencies
python                    3.10.13
pandas                    2.2.1
numpy                     1.26.4
lifelines                 0.29.0 
tableone                  0.8.0
matplotlib                3.8.4

## column meta-data for data files
CANCER_TYPE:Highest-level oncotree code
CANCER_TYPE_DETAILED:Most granular oncotree code
stop:days from treatment start to death or last follow-up 
start:days from treatment start to cohort entry (tumor sequencing) if after treatment start (otherwise 0)
start_wvax:days from treatment start to vaccination if after treatment start and peri-ICI vaccinated
VAX:vaccinated within 100 days of treatment start
OLDVAX:vaccinated prior to 100 days of treatment start
STAGE_DX_INT:AJCC stage at diagnosis
ecog_parsed:ECOG performance status
dt_med-dx:days from diagnosis to treatment start
YEAR:year of treatment start 
LANDMARK_INCLUDE:treated from Mar 20, 2021 onward (see paper for details)
