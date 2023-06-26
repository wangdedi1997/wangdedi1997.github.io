---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My **work so far** can be classified in two areas:

***I. Physics-informed representation learning and modeling for dynamical systems.***

To study the complex molecular systems, I capitalized on physics-inspired insights to learn useful but also meaningful low dimensional representations of the deluge of data generated from experiments and simulations. 

<ins>*1. Learn **useful** representations:*</ins> Molecules such as proteins are dynamic entities capable of adopting a wide range of metastable states or conformations beyond their crystal structure. I have demonstrated that physics-informed representations effectively focus on these state-to-state transitions, facilitating automated partitioning of the configuration space and generating concise yet comprehensible descriptions of kinetic pathways using Markov models. These representations have proven to be valuable in providing mechanistic insights across various domains of chemical and biological physics. 

<ins>*2. Learn **unique** and **meaningful** representations:*</ins> The lack of uniqueness in AI-learned representations poses a challenge for interpretation. I have addressed this issue by imposing constraints on latent representations, requiring them to adhere to a generic class of dynamics inspired by fundamental physics principles. These constraints are justified as different molecular systems follow similar fundamental dynamics, such as Newton's or Schrödinger's equations of motion. This physics-informed representation learning method consistently outperforms the competing method, yielding unique and highly interpretable representations across diverse datasets, including real-world fluorescent single-molecule movies.

***II. AI augmented molecular dynamics (MD) that reach experimental timescales.***

I have developed AI augmented molecular dynamics (MD) methods that allow for studying complex molecular systems across an extensive range of timescales, from femtoseconds to seconds, while preserving all-atom resolution. By leveraging the learned physics-informed representation as a blueprint, these methods significantly accelerate simulations of molecular systems which would otherwise be prohibitively slow. These techniques have been shown to speed up the MD simulations for a variety of systems, including permeation and dissociation of medically relevant ligands, conformational changes in proteins and nucleation of crystal polymorphs. 
