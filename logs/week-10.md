# Week 10

**Dates:** 08-24 to 08-30

## Goals
- Create probabilistic model to predict probability of a mismatch given a fault fires
- Continue data collection


## Approach and Implementation
I met with Ashish Kashinath on Tuesday to discuss his collaboration and the project direction. We discussed the papers that I've been referencing and the data that I collected so far. He suggested a few more details to add in the implementation. 

I spent the majority of the week collecting data, which I had to redo several times because of some errors in the pipeline. I also realized that my mock/simulation sessions had errors injected on both sender and receiver, while my actual implementation only had it with the receiver. 

While my data ran, I began the derivation for a probabilistic model to predict the probability of a mismatch given a fault fires. Using Tomamichel and Leverrier (2017) and Tomamichel et al. (2014), I was able to derive a formula for Toeplitz faults. I began derivation for reconciliation faults, although it is much more complex because of the backtracking involved in the Cascade algorithm. I found Ng et al. (2014), which provided an aid for a similar protocol, BINARY, without the backtracking. In the future, I hope to have a larger probabilistic model that takes in multiple types of faults as parameters. 

## Results
- Further debugging of the protocol and data collection
- Derived Toeplitz probablistic model


## Notes
I plan to continue this project past this summer, so my work is still in progress. I hope to collect more data/concrete results before submitting my final write up, although I have a poster and draft with work from my previous direction.

