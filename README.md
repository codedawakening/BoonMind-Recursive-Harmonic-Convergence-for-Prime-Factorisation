# BoonMind RHC – Prime Factorization (Public Release v1.0)

This repository contains the **public technical overview** of BoonMind’s  
**Recursive Harmonic Convergence (RHC)** framework applied to integer factorization.

BoonMind RHC models factorization as a *harmonic state-evolution problem*, using  
continuous–discrete recursion and resonance-driven optimisation to guide  
candidate factors toward stable attractor states.

This v1.0 public edition presents:

- ✅ 100% correctness on all tested numbers up to **9 digits**  
- ✅ Successful detection of large primes (e.g., 100000007)  
- ✅ Correct factorization of semiprimes such as 1000000127 = 31627 × 31661  
- ✅ Fast convergence (~0.045s per instance)  
- ❗ **Testing deliberately limited to pre-cryptographic scale**

No claims are made about RSA-grade moduli in this release.

---

## 🔍 Document Contents

See:

**`docs/BoonMind_RHC_Prime_Factorization_v1.0.md`**

This report includes:

- High-level description of the RHC dynamical system  
- Explanation of the state vector Ψₙ, gradient behaviour, resonance term, and tension threshold  
- Safe pseudocode illustrating the structure (all proprietary operators removed)  
- Experimental results across multiple integer classes  
- Debugging insights and emergent behaviours  
- Discussion of potential implications for number theory and optimisation  

This document provides **insight and transparency**, while intentionally  
withholding proprietary equations and implementation details.

---

## 🚫 What Is Intentionally Withheld

To protect IP and prevent premature replication, this repository **does not** include:

- full solver implementation  
- harmonic operators  
- resonance/damping formulae  
- internal constants (α, β, φ, ε dynamics)  
- discretisation/collapse rules  
- code for large-integer factorization  
- any experiments beyond the 9-digit range

Researchers may request access under NDA.

---

## 📈 Scope & Limitations (v1.0)

This release is intentionally limited to:

- small composites  
- medium semiprimes  
- pre-cryptographic-scale 8–9 digit integers  

Key clarifications:

- This release does **not** include RSA-100 or RSA-2048 experiments  
- This release does **not** claim breakthroughs in cryptographic-grade factoring  
- The results are presented **solely as an exploration of the harmonic optimisation method**

---

## 🤝 Collaboration

BoonMind is open to collaboration with:

- computational number theorists  
- physicists working on dynamical systems  
- cryptographers exploring novel optimisation approaches  

To discuss research access or NDA-based review:

- **X / Twitter**: @BoonEcho90810  
- **GitHub**: @codedawakening  

Please use the subject: **“RHC Collaboration Request”**
