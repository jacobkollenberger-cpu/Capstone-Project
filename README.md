## Executive Summary

This repository contains the senior capstone research paper completed for the B.S. in Cybersecurity degree at Gardner-Webb University (May 2026). 

The research addresses the structural implementation gap between theoretical post-quantum cryptographic algorithms and production-ready enterprise infrastructure. Specifically, it analyzes the transition from classical asymmetric encryption (RSA, ECC) to NIST's 2024 standardized post-quantum algorithms, evaluating migration hurdles, protocol constraints, and performance overhead.

---

## Key Research Focus Areas

* **NIST 2024 Standards Analysis:** Evaluation of Module-Lattice-Based Key-Encapsulation Mechanism (**ML-KEM / FIPS 203**), Module-Lattice-Based Digital Signature Algorithm (**ML-DSA / FIPS 204**), and Stateless Hash-Based Digital Signature Algorithm (**SLH-DSA / FIPS 205**).
* **Threat Modeling:** Risk assessments focusing on **"Harvest Now, Decrypt Later" (HNDL)** adversary strategies targeting long-term sensitive enterprise data.
* **Infrastructure Trade-Offs:** Benchmarking packet fragmentation, processing latency, memory footprint, and bandwidth expansion resulting from larger key and signature sizes in lattice-based cryptography.
* **Migration Frameworks:** Step-by-step strategies for hybrid classical/PQC implementation, crypto-agility, and institutional compliance.

---

## Abstract Brief

> As quantum computing advances toward breaking classical public-key cryptography (RSA and ECC via Shor's algorithm), organizations face an unprecedented migration challenge. While NIST has finalized initial post-quantum standards, dropping these primitives into modern network stacks reveals significant friction: increased public key and ciphertext sizes lead to network fragmentation, protocol handshakes exceed maximum transmission units (MTUs), and computational overhead strains constrained embedded devices. This paper synthesizes empirical benchmarking and protocol integration tests to outline a pragmatic roadmap for achieving quantum resilience in enterprise environments.

---

## Author & Citation

**Jacob Keith Ollenberger**  
*B.S. in Cybersecurity, Gardner-Webb University*  
* **LinkedIn:** [linkedin.com/in/jacob-ollenberger](https://linkedin.com/in/jacob-ollenberger)
* **GitHub:** [github.com/jacobkollenberger-cpu](https://github.com/jacobkollenberger-cpu)