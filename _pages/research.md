---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
My research focuses on designing computational algorithms that solve challenging problems in healthcare and communication networks. My work currently spans two research areas: **Machine Learning for Healthcare** and **Satellite-Based Quantum Key Distribution (QKD)**. Although these areas address different scientific problems, both involve developing intelligent algorithms that analyze complex data, optimize system performance, and support reliable decision making.

---

# Research Area I

# Machine Learning for Depression Treatment Outcome Prediction

<p align="center">
  <img src="/images/Revised_Structure.png"
       alt="Machine learning framework for depression treatment outcome prediction"
       width="750">
</p>

<p align="center">
  <em>Machine learning framework for predicting depression treatment outcomes from behavioral and clinical data.</em>
</p>

## Motivation

Depression is one of the most common mental health disorders worldwide, yet predicting whether a patient will respond to treatment remains a major challenge. Traditional clinical assessments usually depend on periodic questionnaires completed during hospital visits. However, a patient's behavior changes continuously throughout treatment, and these daily changes often contain valuable information about recovery.

Machine learning provides an opportunity to continuously analyze these behavioral changes and assist clinicians by identifying patients who may require additional attention much earlier than traditional assessment methods.

---

## Research Overview

My research develops machine learning methods for predicting depression treatment outcomes using behavioral data. Instead of relying on a single clinical assessment, my models learn from sequential information collected over time.

The behavioral data include daily mood ratings, daily anxiety ratings, physical activity (step counts), smartphone-derived behavioral features, location and mobility patterns, and clinical questionnaire scores.

My current research investigates how different observation windows, including 7-day, 14-day, and 21-day behavioral sequences, influence depression treatment outcome prediction. By comparing these temporal windows, I study the trade-off between making earlier predictions and improving predictive performance with additional behavioral information.

To improve model transparency, I employ Explainable Artificial Intelligence techniques, particularly SHAP, to identify which behavioral features and temporal patterns contribute most to model predictions. These analyses provide interpretable insights that can support clinicians in understanding the factors influencing treatment outcomes.

---

## Research Topics

- Depression Treatment Outcome Prediction
- Longitudinal Time-Series Machine Learning
- Explainable Artificial Intelligence
- Behavioral Health Analytics
- Clinical Decision Support

---

## Selected Publications

Please see the **Publications** page for papers related to this research area.

---

# Research Area II

# Satellite-Based Quantum Key Distribution Networks

<p align="center">
  <img src="/images/Single_Sat_Model.png"
       alt="Satellite-based Quantum Key Distribution network"
       width="350">
</p>

<p align="center">
  <em>Satellite-based Quantum Key Distribution network connecting geographically separated ground stations.</em>
</p>

## Motivation

## Motivation

As quantum computers continue to advance, many widely used cryptographic techniques may become vulnerable to future attacks. Quantum Key Distribution (QKD) provides a fundamentally secure method for distributing cryptographic keys based on the principles of quantum mechanics.

Satellite-based QKD extends secure communication across global distances where fiber-based QKD becomes impractical. However, efficiently distributing quantum keys over large satellite constellations introduces many computational challenges, including routing, scheduling, and resource allocation.

---

## My Research

My research investigates algorithmic challenges in **Satellite-Based Quantum Key Distribution (QKD) networks**.

My earlier work focused on **single-satellite QKD systems**, where quantum keys are generated between ground stations through individual satellites. This research examined efficient key generation and resource utilization under realistic satellite communication constraints.

Building on this foundation, my current research studies **large-scale satellite constellations** for global quantum communication. I develop routing, scheduling, and optimization algorithms that determine how quantum keys should be distributed efficiently across dynamic satellite networks.

More recently, my work has expanded to include **Inter-Satellite Links (ISLs)**, which allow quantum keys to be forwarded between satellites before reaching their destination ground stations. This significantly increases network flexibility and global coverage while introducing new optimization challenges in routing, scheduling, and resource allocation.

Overall, my goal is to design scalable algorithms that improve the efficiency, fairness, and performance of future satellite-based quantum communication networks.

---

## Current Research Topics

- Satellite-Based Quantum Key Distribution
- Quantum Communication Networks
- Satellite Constellation Optimization
- Routing Algorithms
- Scheduling Algorithms
- Resource Allocation
- Inter-Satellite Links (ISLs)

---

## Selected Publications

Please see the **Publications** page for papers related to this research area.

---

# Future Research Vision

My long-term research vision is to develop trustworthy and secure intelligent systems by combining advances in Artificial Intelligence and quantum communication technologies.

As healthcare increasingly depends on AI-driven decision support, protecting sensitive patient information throughout data collection, transmission, and analysis will become increasingly important. I am interested in exploring how quantum-secure communication can strengthen privacy and security for future AI-enabled healthcare systems while continuing to advance research in both machine learning and quantum communication.

---

# Research Collaboration

I welcome collaborations with researchers, students, and industry partners interested in Machine Learning, Artificial Intelligence for Healthcare, Quantum Communication, Network Optimization, and Satellite-Based Quantum Key Distribution.
