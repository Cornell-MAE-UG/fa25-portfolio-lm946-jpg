---
layout: project
title: "Spotted Lanternfly Inline Separation System"
subtitle: "Inline Mechanical Sorting for Agricultural Contamination Control"
image: /assets/images/odp3-diagram.jpg
---
## Project Milestones

The development of this system is documented through the following milestones. Click each section to explore detailed design evolution, testing, and outcomes.

---

<details>
<summary><strong>1. Client Pitch</strong></summary>

<div markdown="1">

## 01. The Problem
During mechanical grape harvesting, Spotted Lanternflies (SLF) are unintentionally collected with the fruit. At a commercial scale (2–3 tons/hour), more than 1–2 insects per 1000g can trigger contamination concerns and lead to rejected loads.

Current sorting methods manual labor or post-harvest washing can remove up to 50% of usable yield, making them economically unviable at the speed required for commercial viticulture. 

## 02. The Solution: SLF Inline Sorter
Our team proposed a mechanical system designed to be retrofitted onto existing conveyor systems. The goal is to remove SLF without bruising grapes, slowing the harvest, or requiring a total harvester redesign.

### Key Design Features:
* **Preliminary Sorting:** A motor-driven roller with specialized bristles to gently agitate the grapes and surface the insects.
* **Pneumatic Extraction:** High-velocity compressed air jets (5–10m/s) targeted to expel adult SLF based on their specific mass (0.2–0.3g).
* **Vacuum Collection:** A synchronized suction system to capture expelled SLF for contained disposal, preventing re-entry into the harvest stream.

> **Why it’s better:** Unlike standard MOG (Material Other than Grapes) systems, this is specifically tuned for the weight and grip strength of the Spotted Lanternfly.


## 03. Engineering Considerations & Risk Mitigation
To move from concept to reality, our design addresses several critical engineering constraints:
* **Volumetric Flow:** Adjusting air pressure dynamically to ensure insects aren't buried under high-density grape layers.
* **Yield Preservation:** Ensuring the pneumatic force is sufficient to move an insect but insufficient to bruise a grape.
* **Sanitation:** Designing the roller and vacuum components to meet food-grade cleaning requirements for harvest equipment.


## 04. Technical Documentation & Industry Context
For a deep dive into our technical analysis, risk mitigation strategies, and the questions we developed for our industry clients (CALS Extension / E&J Gallo Winery), you can view our full client outline below.

[**Download Full Client Outline (PDF)**]({{ "/assets/pdf/Client Outline and Pitch.pdf" | relative_url }})

### Industry Research
Our design was informed by current state-of-the-art optical and mechanical sorting technologies used in large-scale agriculture:
* [Harvest Optimization Technology (MOG)](https://www.youtube.com/watch?v=JEM50O9d-M8)
* [Optical Sorting in Motion](https://www.youtube.com/watch?v=iSd4RgrFOtg)

</div>

</details>

---

<details>
<summary><strong>2. Functional Prototype</strong></summary>

<div markdown="1">

## Functional Prototype

### Purpose
The purpose of this functional prototype was to evaluate whether a brush-based mechanical system could effectively dislodge Spotted Lanternflies (SLF) from grape clusters without damaging the fruit or disrupting flow conditions. The prototype focuses on validating the feasibility of mechanical agitation as a primary separation method.

---

### Prototype Design

The prototype consists of a simplified inline system including:

- A **shaft-mounted rotary brush** driven by a handheld drill  
- A **manual conveyor simulation** using a sliding cardboard base  
- A **partition and collection region** to separate dislodged SLF  

This setup replicates the key interactions between brush, grapes, and contaminants in a controlled environment.

---

### Prototype Sketch

<div style="text-align: center;">
  <img src="{{ '/assets/images/agkgdfa .png' | relative_url }}" 
       style="width: 60%; max-width: 500px; height: auto;">
</div>


*Figure: Conceptual sketch of the prototype system showing brush placement, conveyor direction, and collection regions.*

---

### Assembled Prototype

<div style="text-align: center;">
  <img src="{{ '/assets/images/IMG_1492.jpg' | relative_url }}" 
       style="width: 60%; max-width: 500px; height: auto;">
</div>

*Figure: Physical prototype used for testing, including rotary brush, shaft, and conveyor simulation.*

---

### What Was Tested

- Brush rotation speed and its effect on SLF removal  
- Bristle coverage across the conveyor width  
- Stability and consistency of the conveyor simulation  
- Overall SLF removal efficiency per pass  

---

### Results & Outcomes

- Optimal brush speed identified at approximately **500 RPM**  
- SLF removal efficiency reached **~70–75% per pass**  
- Minimal grape damage observed, though some displacement occurred  
- Inconsistent removal across width due to uneven bristle distribution  
- Conveyor instability led to occasional loss of grape clusters  

---

### Key Takeaways

- Mechanical brushing is an effective **preliminary separation method**  
- System performance depends heavily on **uniform material flow**  
- Brush design and coverage are critical to improving efficiency  

---

### Full Report

[**View Full Prototype Report (PDF)**]({{ "/assets/pdf/ODP 5.pdf" | relative_url }})
</div>

</details>

---

## Project Overview

Mechanical grape harvesting operates at high throughput rates (2–3 tons/hour), where even minor contamination by Spotted Lanternflies (SLF) can result in rejected harvest loads and significant economic loss. Existing mitigation strategies such as manual sorting or post-harvest washing are not scalable and often result in reduced yield and increased labor costs.

This project proposes an **inline mechanical separation system** designed to integrate directly into existing harvesting workflows. The objective is to selectively remove SLF during conveyance without interrupting throughput or compromising grape integrity.

---

## System Concept

The proposed system combines **mechanical agitation and pneumatic separation** to target the physical characteristics of SLF while preserving delicate grape clusters.

Key components of the system include:

- **Partitioned Conveyor Belt:** Regulates material distribution and creates controlled flow zones for consistent separation conditions  
- **Rotary Brush Mechanism:** A motor-driven brush introduces controlled agitation to dislodge SLF from grape clusters and expose them for removal  
- **Primary Collection Trough:** Positioned beneath the conveyor to capture debris and dislodged material during initial agitation  
- **Pneumatic Separation System:** High-velocity compressed air jets selectively remove SLF based on mass and aerodynamic response  
- **Dual Side Collection Troughs:** Capture SLF displaced by air jets, preventing re-entry into the product stream  
- **Secondary Brush Cleaning Interface:** A downstream collection trough removes SLF retained in brush bristles, ensuring continuous operation without accumulation  

This multi-stage approach enables **continuous, non-destructive separation** while maintaining compatibility with existing harvesting equipment.

---

## Conceptual Design

<div style="text-align: center;">
  <img src="{{ '/assets/images/odp3-diagram.jpg' | relative_url }}" alt="SLF Inline Separation System Diagram" style="max-width: 100%; height: auto; border-radius: 6px;">
</div>

*Figure: Conceptual diagram of the inline Spotted Lanternfly separation system, showing conveyor partitioning, rotary brush agitation, pneumatic extraction via compressed air jets, and multi-stage collection troughs for insect removal.*

---

