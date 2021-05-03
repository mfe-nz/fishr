# fishr
This repo contains code to implement methods proposed by Joy and Death (2004) for calculating a Index of Biotic Integrity with application to New Zealand fish communities. 
It also updates these methods by utilising quantile regression to define the Maximum Species Richness Lines (used for scoring metrics), as first used by Joy (2007) for the Waikato region. 

## Pre-processing

- Contains functions to get NZFFD data in the appropriate format for later functions
to work.

## Calculate metrics

- Process site-level summaries of the information needed to calculate metric scores

## Scoring

- Code to fit quantile regression and assign scores

## Construct index

- Takes individual scores from each of the 6 metrics and combines to give overall IBI score
- Cut continuous IBI score into categories
