# Using Predictive Modeling to Save Lives through analyzing Opiate Prescriptions in the U.S. 

## The Opioid Epidemic

Fatal drug overdoses account for a significant portion of accidental deaths in adolescents and young adults in the United States. The majority of fatal drug overdoses involve [opioids](https://www.drugabuse.gov/publications/research-reports/misuse-prescription-drugs/summary), a class of inhibitor molecules that disrupt transmission of pain signals through the nervous system. Medically, they are used as powerful pain relievers; however, they also produce feelings of euphoria. This makes them highly addictive and prone to abuse. The same mechanism that suppresses pain also suppresses respiration, which can lead to death in the case of an overdose.
Over the past 15 years, deaths from prescription opiates have [quadrupled](https://www.cdc.gov/drugoverdose/epidemic/#), but so has the amount of opiates prescribed. This massive increase in prescription rates has occurred while the levels of pain experienced by Americans has remain largely [unchanged](http://time.com/3663907/treating-pain-opioids-painkillers/). Intuitively it follows that unneccessary prescriptions potentially play a significant role in the increase in opioid overdoses. Patients who do not truly need the medication run the risk of becoming addicted themselves or tempted to sell their refills for significant profit, increasing the supply of narcotics in illegal drug markets. An effective strategy for identifying instances of overprescribing is therefore a potentially life saving endeavor.

## Goal

The goal of this experiment is to demonstrate the possibility that predictive analytics with machine learning can be used to predict the likelihood that a given doctor is a significant prescriber of opiates.

## Methodolgy 

First, I’ll do some cleaning of the data, and build a predictive model using a gradient boosted classification tree ensemble with `gbm` and `caret` that predicts with >80% accuracy that an arbitrary entry is a significant prescriber of opioids.
Then, I’ll do some analysis and visualization of the results combined with those pulled from other sources.

## steps

1. Data Cleaning
2. Model Building
3. Model Training
4. Prediction
5. bar plot
6. data summary

# Data Summary and graphs

![alt text](https://github.com/MohamedSeliem/Opioid/blob/master/U.S.%20Opiate%20Overdose%20Death%20Rate.png)

![alt text](https://github.com/MohamedSeliem/Opioid/blob/master/Feature%20Importance%20for%20Detecting%20Opioid%20Prescription.png)
