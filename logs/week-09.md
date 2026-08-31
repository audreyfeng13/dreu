# Week 9

**Dates:** 08-17 to 08-23

## Goals
- Data collection on real FABRIC links
- Add finite key analysis
- Try mitigation techniques
- Began drafting paper for NSDI conference


## Approach and Implementation
I added a method for sweeping fault firing probabilities on real FABRIC links and ran the protocol, although it is rather time consuming. During the process, I realized that my hash output fault was not what I intended it to be, so I added a verification digest fault and changed the original hash output fault to a final key fault. This required me to rerun the data several times. The new type of fault also led me to add a post-privacy amplification verification step.

I also began studying finite key analysis by reading Tomamichel et al. (2014) and Tomamichel and Leverrier (2017). Using their guidelines, I added a finite key calculation to my implementation, although it still has to be validated. Furthermore, I tested some preliminary mitigation techniques like key verification, redundant privacy amplification, and TMR.

I updated all this in my write up/paper draft, which I will try to submit to NSDI '27. 

## Results
- Preliminary implementation for finite key analysis and mitigation techniques
- Began data collection on FABRIC


## Notes
I need to validate and double check my finite key calculation

