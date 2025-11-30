# Paper Review: When FRODO Flips

This repository contains slides and supporting material for a paper review of “When FRODO Flips: End-to-end key recovery on FrodoKEM via Rowhammer” (Fahr et al., 2022).

## Talk video

Watch the presentation here:  
- Talk video: https://drive.google.com/file/d/1GX5wd5IzAvl-3PL8tpaA7xcYrMU7o8SD/view

## Contents

- FRODO-When-FRODO-Flips-Review.pptx – slide deck for the paper review.
- references.txt – bibliographic entry for the original paper and related work.

## Paper being reviewed

The talk reviews the attack from “When FRODO Flips: End-to-end key recovery on FrodoKEM via Rowhammer,” which demonstrates how a Rowhammer-based fault attack can be used to recover keys from FrodoKEM, a lattice-based post-quantum key encapsulation mechanism. 

Key high-level points covered in the slides include:

- Background on DRAM, memory hierarchy, and the Rowhammer bug.
- Overview of FrodoPKE and FrodoKEM, including KEM construction from PKE and the LWE assumption. 
- How Rowhammer can be used to poison the error matrix during FrodoKEM key generation (“key poisoning”).
- Use of increased decryption failure rates and decryption-failure attacks for secret-key and session-key recovery.
- Practical considerations such as memory profiling, memory massaging (“frame feng shui”), and constraints of DRAM bit flips. 
- Discussion of possible countermeasures against Rowhammer-based attacks on PQC KEMs. 

## How to use this repo

- Clone the repository:

```git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git```


- Open `FRODO-When-FRODO-Flips-Review.pptx` in PowerPoint, Keynote, LibreOffice, or Google Slides to view or present the deck.
- Use the README and slide deck as a reference when preparing your own talk or notes about Rowhammer attacks on post-quantum KEMs. Please respect the original authors’ intellectual property and properly cite their paper. 

## References

- Fahr et al., “When FRODO Flips: End-to-end key recovery on FrodoKEM via Rowhammer,” 2022. (See `references.txt` for a full bibliographic entry if included.)
- FrodoKEM specification and NIST PQC documentation for FrodoKEM parameters and failure-rate analysis.




