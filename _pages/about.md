---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Najmeh Nazari is a Ph.D. student in the ECE department at the University of California, Davis. She received her B.Sc. and M.Sc. degrees both in computer engineering from the Shiraz University and the Isfahan University of Technology in 2010 and 2013, respectively. 
From 2013 to 2015, she served as a lecturer at the Shahid Chamran University of Ahwaz. Her research interests include deep learning, embedded systems, and hardware security.

Research Projects
======
1. Adversarial Attacks against Machine Learning-based Resource Provisioning Systems
In cloud computing, microarchitectural attacks can expose sensitive information by exploiting shared hardware resources between virtual machines (VMs). However, such attacks are traditionally limited by the need for attacker and victim VMs to co-locate on the same hardware. My research in adversarial attacks against machine learning-based resource provisioning systems (RPSs) tackles this limitation, demonstrating that RPSs themselves can be manipulated to achieve co-location. By deploying adversarial evasion attacks on RPSs, we can successfully position attacker VMs alongside targeted victim VMs, bypassing conventional constraints on microarchitectural attacks. This work also examines the adaptability of defense techniques from image classification to RPSs, revealing both the possibilities and limitations of cross-domain defenses.

2. SpecScope: Automating the Discovery of Spectre Gadgets
Spectre and related transient execution attacks underscore a fundamental security flaw in modern processors, revealing that performance-boosting features like speculative execution can leak sensitive data. SpecScope, my second major project, introduces a framework for automatically identifying Spectre gadgets in code using a black-box approach to microarchitectural analysis. By leveraging contention between transient and non-transient instructions, SpecScope reduces false positives by 8.9\% and increases true positives by 10.4\% over previous methods, enabling efficient mitigation strategies without sacrificing performance. This work provides a scalable tool for identifying Spectre vulnerabilities, striking a balance between security and system efficiency—a critical objective in mitigating the widespread impacts of speculative execution attacks.

3. Architectural Whispers: Side-Channel Fingerprinting of Machine Learning Models
With the proliferation of machine learning models, protecting the intellectual property and security of model architectures has gained importance. My research into frequency throttling-based side-channel fingerprinting unveils a novel technique to identify machine learning model architectures through timing variations. By leveraging adversarial kernels and a time-series classifier, this approach achieves up to 96\% accuracy in identifying model architectures across platforms with minimal privileges. This study highlights the feasibility of extracting confidential architectural details via side-channel attacks, demonstrating that securing ML models requires comprehensive protections beyond conventional software-based measures.

4. Forget and Rewire: Resilience of Transformers against Bit-Flip Attacks
Bit-flip attacks (BFAs) are a potent threat to AI models, allowing adversaries to disrupt model functionality by flipping key bits in model parameters. While the effects of BFAs on traditional neural networks are well-documented, their impact on Transformer-based models remains underexplored. My research introduces the Forget and Rewire (FaR) method, a unique approach inspired by neural "rewiring" to protect transformers from BFAs. FaR obfuscates neuron connections in Transformers' linear layers, redistributing tasks from essential to non-essential neurons to enhance resilience against targeted bit-flips. This method reduces BFA success rates by up to 4.2 times with minimal accuracy loss, paving the way for robust defenses in complex AI models and informing future research into resilient model architectures.
