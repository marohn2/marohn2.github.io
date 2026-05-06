---
layout: post
title: NarxCare- A Harmful Cloud Application in Biomedicine
subtitle: When clinical prediction models go unchecked
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

The United States has the highest overdose and drug related death rate in the world by a significant margin. The US overdose epidemic is a complex issue for which many mistakes have been made due to oversimplification. Complex issues can have seemingly viable solutions for which tech companies are often happy to quickly provide / roll out solutions for in the form of cloud-based applications. One noteworthy example of a seemingly viable solution is Bamboo Health’s Narxcare – a prescription drug monitoring program-based analytics platform marketed as a clinic al support tool. 

Narxcare belongs to a class of monitoring and surveillance programs called prescription drug monitoring programs or PDMPs
[which have been the subject of much public scrutiny by numerous clinicians](https://journals.lww.com/journaladdictionmedicine/abstract/2022/05000/_nobody_knows_how_you_re_supposed_to_interpret.26.aspx). Narxcore claims to  impact over one billion patient encounters annually across the US and has been used across 52 states and territories in the US while its platform still lacks sufficient evidence for its wide clinical implementation and still has yet to be approved or cleared by the FDA. 

Here's a Map from Narxcare on PDMP Coverage of the US from their 2025 Impact Report: 

![Map of Narxcare US Coverage](/images/Narxcoremap.png?raw=true)

## The Application
Narxcare is a cloud application marketed as a clincal decision support tool. 

## The Impact

The negative impact of Narxcare's scoring system has been felt by a variety of patients. Chronic pain patients or even patients who have sick pets (link) can be flagged and loose access to prescriptions and medical care. According to one study, 20 percent of the patients who are most likely to be flagged as doctor-shoppers actually have cancer, which often requires seeing multiple specialists.

## The Road Ahead
Narxcare has still not been approved by nor investigated by the FDA yet it is still being utilitzed today across the United States. It claims that it is not to be intended to be the sole tool that should be used to halt medicine / care to patients, yet it is often used as such. While many of the papers in this post date back to the early 2020s, the cloud application is still not regulated by the FDA and there are [still petitions being filed in 2026,](https://insights.citeline.com/medtech-insight/digital-technologies/fda-weighs-second-citizen-petition-on-bamboo-healths-narxcare-AHZVKQCQSBCFNM7DVKJQC4R32A/) pushing for it regulation.

## The References
  - Buonora, Michele J., et al. “Paths forward for clinicians amidst the rise of unregulated clinical decision support software: Our perspective on NarxCare.” Journal of General Internal Medicine, vol. 39, no. 5, 14 Nov. 2023, pp. 858–862, https://doi.org/10.1007/s11606-023-08528-2. 
  -McCarty, Mark. “FDA Weighs Second Citizen Petition on Bamboo Health’s NarxCare.” Insights, Insights, 11 Mar. 2026, insights.citeline.com/medtech-insight/digital-technologies/fda-weighs-second-citizen-petition-on-bamboo-healths-narxcare-AHZVKQCQSBCFNM7DVKJQC4R32A/. 
  -Szalavitz, Maia. “The Pain Was Unbearable. so Why Did Doctors Turn Her Away?” Wired, Conde Nast, 11 Aug. 2021, www.wired.com/story/opioid-drug-addiction-algorithm-chronic-pain/. 

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
