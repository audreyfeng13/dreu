# Week 7

**Dates:** 08-03 to 08-09

## Goals
- Create plan for new project direction
- Extend QFabric BB84 implementation to include privacy amplification and error correction


## Approach and Implementation
I outlined a plan for a new project direction that focuses on silent data corruptions (SDCs) in classical post-processing and how these can be undetectable by just observing QBER and key rate. I will implement privacy amplification and error correction in QFabric and create a fault injection that creates bit flips in the Toeplitz matrix computations, hash outputs, and reconciliation state. I plan to evaluate results based on final key correctness, include testing for mitigation techniques, and incorporate simultaneous detector and quantum faults to observe interactions.

I read Mitra et al., which provides motivation for our work based on SDCs in silicon at Google. I also read Tomamichel et al. and Tupkary et al. for background on the theory of QKD and its pipeline, as well as to learn more about privacy amplification and error correction. I read Veiga and Hanggi for how to implement privacy amplification and documentation for Rijsman's Cascade implementation.

## Results
- Successfully implemented privacy amplification and error correction
- Created fault injector for SDC injection
- Found preliminary results using mock data


## Notes
I need to meet with Dr. Cao next week for feedback on new direction. I had to travel back to California this week

