# Human fertility models

R code to reproduce models testing for cross-national human fertility patterns relative to underlying drivers

code updated September 2021

R code accompanies the following paper:

Perry, C, CJA Bradshaw, CM Saraswati, M Judge, J Heyworth, PN Le Souëf. In review. Lower infant mortality and access to contraception reduce fertility in low- and middle-income nations. Lancet Global Health

BY: Corey J.A. Bradshaw (Flinders University, Australia)

CONTACT: corey.bradshaw@flinders.edu.au
globalecologyflinders.com

Data:
- basedata.csv = main input data
- matmort.csv = maternal mortality data
- pop.yr.csv = national population data
- continent.country2.csv = naming file necessary for data merging

Requires the following libraries:
- lme4
- Hmisc
- ggplot2
- plotly
- nlme
- car
- dismo
- gbm
- rgeos
- rworldmap
- rworldxtra
- rcompanion
- SpatialEpi
- ggridges
- dplyr
- ggpubr
- plyr
- fields
- ncf
- AICcmodavg
- modEvA

and following source-code files:
- new_lmer_AIC_tables3.R
- r.squared.R
