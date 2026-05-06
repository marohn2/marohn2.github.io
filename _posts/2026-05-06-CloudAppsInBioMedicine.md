---
layout: post
title: NarxCare- A Harmful Cloud Application in Biomedicine
subtitle: When clinical decision support goes unchecked
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
mathjax: true
author: Bill Smith
---

{: .box-success}
Note: This blog post does not speak highly of a particular cloud application in Biomedicine. 

**If we don't critique harmful applications in biomedicine, how can we say we are promoting health?**

## A BIG problem doesn't have an easy solution

The United States has the highest overdose and drug related death rate in the world by a significant margin. The US overdose and opioid epidemic is a complex issue for which many mistakes have been made due to oversimplification. Complex issues can have seemingly viable solutions for which tech companies are often happy to quickly provide in the form of cloud-based applications. One noteworthy example of a seemingly viable solution to the complex problem of the overdose and opioid problem is Bamboo Health’s Narxcare – a prescription drug monitoring program-based analytics platform marketed as a clinic al support tool. 

Narxcare belongs to a class of monitoring and surveillance programs called prescription drug monitoring programs or PDMPs
[which have been the subject of much public scrutiny by numerous clinicians](https://journals.lww.com/journaladdictionmedicine/abstract/2022/05000/_nobody_knows_how_you_re_supposed_to_interpret.26.aspx). Narxcore claims to  impact over one billion patient encounters annually across the US and has been used across 52 states and territories in the US while its platform still lacks sufficient evidence for its wide clinical implementation and still has yet to be approved or cleared by the FDA. 

![Snapshot of Narxcare Tool](/images/NarxcareApp.png?raw=true)
Figure 1: A snapshot of the Narxcare Application

## The Application
Bamboo Health's Narxcare is a cloud application that utilizes PDMP-based analytics and is marketed as a clincal decision support (CDS) tool for physicians, pharmacists and policymakers. Its patented algorithm utilizes cloud-based computing and is embedded into clinic workflows which often rely on cloud applications and cloud based computing as well. The platform generates multiple "Narx Scores" to represent a patient's overall risk of overdose death and risk of non-meidcal use of prescription "narcotics," sedatives and stimulants. In comparison to WHO ASSIST, the World Health Organization's test to assist with early detection of substance use related health risk and substance risk disorder, Narxcare had a 17% false positive rate and 13% false negative rate with a Cohen's kappa of 0.35 (poor to fair agreement). False positive rates of this size are reason for concern, especially in a tool that impacts over one billion patient encounters annually. 

![Map of Narxcare US Coverage](/images/Narxcoremap.png?raw=true)
Figure 2: A Snapshot of PDMP Coverage from Narxcare's 2025 Impact Report

## The Impact

The negative impact of Narxcare's scoring system has been felt by a variety of patients. Chronic pain patients or [even patients who have sick pets] (https://www.wired.com/story/opioid-drug-addiction-algorithm-chronic-pain/) can be flagged and loose access to prescriptions and medical care. According to one study, 20 percent of the patients who are most likely to be flagged as doctor-shoppers actually have cancer, which often requires seeing multiple specialists. Evidence suggests the algorithm differentially identifies individuals on the basis of disability, work status, insurance coverage and other characteristics. Other studies found that patients with higher pain severity, widowed patients or patients on leave, retired or disabled were most likely to have elevated Narx Scores. 
The impact of high Narx scores and the potential events that follow neing denied medicine or care due to a high score can have a spiraling affect on a patients health and life. An elevated score could lead to reduction / termination of medicine / care which would then in turn could affect pain severity, health and employment. On top of that, seeing multiple physicians elevates the risk score, so a patient with a score too high for one physician might seek others which would then continue to elevate the score until little to no options are available. 


## The Road Ahead
Narxcare has still not been approved by nor investigated by the FDA yet it is still being utilitzed today across the United States. It claims that it is not to be intended to be the sole justification to halt medicine / care to patients, yet it is often used as such. While many of the papers in this post date back to the early 2020s, the cloud application is still not regulated by the FDA and there are [still petitions being filed in 2026,](https://insights.citeline.com/medtech-insight/digital-technologies/fda-weighs-second-citizen-petition-on-bamboo-healths-narxcare-AHZVKQCQSBCFNM7DVKJQC4R32A/) pushing for its regulation.

## The References
  - Buonora, Michele J., et al. “Paths forward for clinicians amidst the rise of unregulated clinical decision support software: Our perspective on NarxCare.” Journal of General Internal Medicine, vol. 39, no. 5, 14 Nov. 2023, pp. 858–862, https://doi.org/10.1007/s11606-023-08528-2. 
  - McCarty, Mark. “FDA Weighs Second Citizen Petition on Bamboo Health’s NarxCare.” Insights, Insights, 11 Mar. 2026, insights.citeline.com/medtech-insight/digital-technologies/fda-weighs-second-citizen-petition-on-bamboo-healths-narxcare-AHZVKQCQSBCFNM7DVKJQC4R32A/. 
  - Szalavitz, Maia. “The Pain Was Unbearable. so Why Did Doctors Turn Her Away?” Wired, Conde Nast, 11 Aug. 2021, www.wired.com/story/opioid-drug-addiction-algorithm-chronic-pain/. 

