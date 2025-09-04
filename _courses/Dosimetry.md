---
title: "Dosimetry"
collection: courses
date: 2025-01-01
permalink: /courses/Dosimetry/
completed: true
---

## Program and Course Objectives Achieved
### Graduate-Level Skill Development

- **Quantitative Problem Solving:**

	- Completed multiple homework assignments addressing complex dosimetric calculations, including photon and electron beam calibrations, neutron dosimetry, and shielding analysis
	- Applied cavity theory to practical scenarios including clinical calibration protocols using TG-51
	- Solved problems involving attenuation, stopping power, detector response, and in vivo dosimetry principles

- **Applied Physics and Mathematical Modeling:**

	- Modeled physical interactions of radiation with matter, applying principles from charged particle equilibrium and Bragg-Gray cavity theory
	- Performed dose estimation using exponential attenuation and fluence-to-dose conversion models
	- Applied statistical techniques to analyze measurement uncertainties and calibration reliability

- **Clinical Integration and Laboratory Experience:**

	- Participated in TG-51 calibration practice for both photon and electron beams
	- Attended an onsite clinical tour at UNMC, observing real-world applications of dosimetry protocols and QA tools
	- Explored clinical implementation of QA protocols (TG-51, TG-142) for radiotherapy units

- **Computer and Technical Proficiency:**

	- Utilized software and spreadsheets for calculation, analysis, and simulation of dosimetric parameters
	- Interpreted TG-51 worksheets and calibration data, correlating with treatment planning and quality assurance needs

- **Radiation Safety and Ethical Awareness:**

	- Investigated national and international radiation protection guidelines (NCRP, ICRP, NRC regulations)
	- Evaluated the biological effects of ionizing radiation in occupational and clinical settings
	- Assessed environmental and public health considerations related to radiation use and waste disposal

## Comprehensive Learning Outcomes

- **Dosimetry Foundations**

	- Developed a robust understanding of radiation dose quantities (e.g., absorbed dose, equivalent dose, effective dose) and associated units
	- Analyzed physical mechanisms behind detector response (ionization chambers, TLDs, OSLs, scintillators)

- **Detector Technologies and Applications**

	- Studied operational principles, sensitivity, and calibration processes for pulse-mode and integrating dosimeters
	- Compared technologies across diagnostic, therapeutic, and environmental monitoring contexts

- **Radiation Protection and Safety Programs**
	- Designed shielding scenarios for clinical settings using NCRP 49, 147, and 151 guidelines
	- Reviewed regulations governing occupational exposure limits and personnel monitoring practices

### Key Competency Highlights

- Analytical Reasoning: Proficiency in interpreting and deriving radiation transport equations
- Regulatory Literacy: Familiarity with U.S. and international radiation protection laws
- Clinical Relevance: Ability to connect theoretical models with practical clinical implementations

## Academic Resources
### Primary Texts

- Fundamentals of Ionizing Radiation Dosimetry – Andreo et al., 2017
- Atoms, Radiation, and Radiation Protection – Bogard et al., 2023

## Professional Significance
This course developed advanced competencies in radiation physics, aligning with CAMPEP standards and preparing me for both clinical application and Part I of the ABR Medical Physics certification.

## Reflective Insights
This course provided a robust and interdisciplinary bridge between theoretical dosimetry and clinical practice. Highlights included:

- Integration of TG protocols in hands-on activities
- Exposure to real-time clinical setups and QA procedures
- A nuanced perspective on ethical, environmental, and human aspects of radiation protection

# Artifacts

{% assign items = site.portfolio | where_exp: "post", "post.categories contains 'Dosimetry'" %}
{% for post in items %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
