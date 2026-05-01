# covid_vaccine_io
Code and line-level data for MSK analysis of SARS-CoV-2 mRNA vaccines and immunotherapy outcomes

## Dependencies
python                    3.10.13,
pandas                    2.2.1,
numpy                     1.26.4,
lifelines                 0.29.0,
tableone                  0.8.0,
matplotlib                3.8.4

## column meta-data for data files
CANCER_TYPE:Highest-level oncotree code<br>
CANCER_TYPE_DETAILED:Most granular oncotree code<br>
stop:days from treatment start to death or last follow-up<br>
start:days from treatment start to cohort entry (tumor sequencing) if after treatment start (otherwise 0)<br>
start_wvax:days from treatment start to vaccination if after treatment start and peri-ICI vaccinated<br>
VAX:vaccinated within 100 days of treatment start<br>
OLDVAX:vaccinated prior to 100 days of treatment start<br>
STAGE_DX_INT:AJCC stage at diagnosis<br>
ecog_parsed:ECOG performance status<br>
dt_med-dx:days from diagnosis to treatment start<br>
YEAR:year of treatment start <br>
LANDMARK_INCLUDE:treated from Mar 20, 2021 onward (see paper for details)
