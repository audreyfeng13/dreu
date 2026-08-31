# Week 8

**Dates:** 08-10 to 08-16

## Goals
- Start data collection for SDC fault injection
- Message Subho Banerjee to learn more about SDCs


## Approach and Implementation
Before starting data collection, I validated the implementation by confirming key agreement between synthetic key pairs and random seeds. First using Mock sessions instead of the real FABRIC links, I started data collection for one key with Toeplitz matrix faults, hash output faults, and reconciliation faults. I had issues with reconciliation faults causing non-convergence and timing-out, as the faults were injected in the middle of the protocol and caused an infinite loop. 

I also emailed Subho Banerjee, who previously worked with my mentor, to learn more about his work on SDCs, which is partially what motivated this project.

## Results
- Collected Mock data with SDC injection
- Confirmed that QBER is unaffected while key mismatch rate increases
- Emailed Dr. Banerjee to set up meeting

## Notes

