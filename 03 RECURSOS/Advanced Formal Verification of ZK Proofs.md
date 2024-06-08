---
tags:
  - resource
Area:
  - "[[Blockchain Area]]"
---
[[Advanced Formal Verification of ZK Proofs]]
[[Certik]]

Dive into the technical world of Zero Knowledge Proofs (ZKP) and discover how formal verification ensures the security and correctness of zkVM systems by identifying and resolving critical bugs.

---
Intro to ZKP and zkVM Formal Verification

Zero Knowledge Proof (ZKP) allows verification of a computation's correctness without revealing its details, and formal verification ensures zkVM systems meet their security and correctness requirements.

---
Understanding FV-Directed Auditing

FV-directed auditing involves combining traditional code review with formal verification to identify specific properties and vulnerabilities in ZK systems.

---
Identifying ZK Bugs

A ZK bug is a vulnerability that allows fraudulent proofs to be accepted, potentially compromising the security of the entire system.

---
The Code Bug: Load8 Data Injection

An example is the Load8 bug. The Load8 data injection bug in zkWasm is caused by an error in constraints, allowing unexpected data bytes to be loaded and potentially causing data corruption.

![[2024-06-08_11h50_09.jpg]]

---
The Design Bug: Faked Return

Another example is the faked return bug. The faked return bug involves improper tracking of call and return instructions, allowing hackers to inject fake returns and manipulate the execution sequence.

![[2024-06-08_11h51_10.jpg]]

---
Comparison of Code and Design Bugs

Code bugs are typically easier to identify and fix as they stem from coding errors, while design bugs are harder to spot and require thorough analysis of system design.

---
Best Practices for Securing ZK Systems

[
![Link Preview Image](https://images.ctfassets.net/v0qht4wq59vi/5GoZLQHlqrp1ZWYVlVuWCS/a7a8cda3d84438943c1816be86b9894e/Advanced_Formal_Verification_of_ZKP-_A_Tale_of_Two_Bugs.jpg)

CertiK - Advanced Formal Verification of ZKP: A Tale of Two Bugs
](https://www.certik.com/resources/blog/advanced-formal-verification-of-zkp-a-tale-of-two-zk-bugs)

Securing ZK systems requires both auditing and formal verification to ensure that all potential vulnerabilities are identified and addressed. Learn more in our blog post.

---
![[2024-06-08_11h54_54.jpg]]

![[2024-06-08_11h56_40.jpg]]