---
layout: project
title: MAE 2250 ODP 3
image: /assets/images/odp3-diagram.jpg
---

# Inline Separation of Spotted Lanternflies (SLF)
**Team:** Di-Vine Intervention | **Client:** Cornell CALS Extension / E&J Gallo Winery 

## The Challenge: Contamination in Grape Harvesting 
Mechanical grape harvesters often collect Spotted Lanternflies (SLF) along with the fruit. Even a small amount of contamination—more than 1–2 SLF per 1000g—can lead to entire loads being rejected by processors. Current manual sorting is only 50% effective and slows down commercial throughput.

## Our Solution: Pneumatic & Physical Sorting
I worked on a team to design an **Inline Sorter** that integrates directly with existing conveyor systems to remove pests without bruising the fruit. 

### Key Design Features:
* **Mechanical Pre-Sorting:** A motor-driven roller with bristles for initial agitation.
* **Pneumatic Extraction:** A compressed air system utilizing jet velocities of 5-10m/s to dislodge adult SLF based on their 0.2-0.3g mass.
* **Vacuum Collection:** A suction system positioned opposite the air jets to safely collect and remove the pests from the harvest stream.



## Addressing Implementation Risks
In response to design feedback, our team focused on the "reproducibility" of the system. While pneumatic sorting is effective for whole insects, we identified and addressed several critical challenges:
* **Grape Loss vs. Purity:** We calibrated air pressure to minimize "false identifications" (accidentally blowing away grapes) while maintaining high SLF removal rates.
* **Sanitation & Maintenance:** The system is designed for easy retrofitting to avoid requiring a total harvester redesign, ensuring it meets food-grade sanitation requirements.
* **High Volumetric Flow:** We accounted for the challenge of sorting bugs buried under large volumes of crushed fruit and juice.

## Skills Demonstrated
* **Mechanical Design:** Prototyping a multi-stage sorting assembly.
* **Pneumatic Analysis:** Calculating air jet force requirements based on insect mass.
* **Client Collaboration:** Developing engineering solutions for real-world agricultural stakeholders.

---

### Project Documentation
For a deep dive into the technical specifications, risk analysis, and client questions, view the full proposal below:

[**Download Full Project Proposal (PDF)**]({{ "/assets/pdf/project-proposal.pdf" | relative_url }})

---
[← Back to Projects]({{ "/projects/" | relative_url }})
<style>
  h2:contains("Technologies Used"), 
  h3:contains("Technologies Used"),
  .project-technology-header { 
    display: none !important; 
  }
</style>
