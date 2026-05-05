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

## 03. Key Design Features:
* **Preliminary Sorting:** A motor-driven roller with specialized bristles to gently agitate the grapes and surface the insects.
* **Pneumatic Extraction:** High-velocity compressed air jets (5–10m/s) targeted to expel adult SLF based on their specific mass (0.2–0.3g).
* **Vacuum Collection:** A synchronized suction system to capture expelled SLF for contained disposal, preventing re-entry into the harvest stream.

> **Why it’s better:** Unlike standard MOG (Material Other than Grapes) systems, this is specifically tuned for the weight and grip strength of the Spotted Lanternfly.


## 04. Engineering Considerations & Risk Mitigation
To move from concept to reality, our design addresses several critical engineering constraints:
* **Volumetric Flow:** Adjusting air pressure dynamically to ensure insects aren't buried under high-density grape layers.
* **Yield Preservation:** Ensuring the pneumatic force is sufficient to move an insect but insufficient to bruise a grape.
* **Sanitation:** Designing the roller and vacuum components to meet food-grade cleaning requirements for harvest equipment.


## 05. Technical Documentation & Industry Context
For a deep dive into our technical analysis, risk mitigation strategies, and the questions we developed for our industry clients (CALS Extension / E&J Gallo Winery), you can view our full client outline below.

## 06. Full Report

[**Download Full Client Outline (PDF)**]({{ "/assets/pdf/Client Outline and Pitch.pdf" | relative_url }})

## 07. Industry Research
Our design was informed by current state-of-the-art optical and mechanical sorting technologies used in large-scale agriculture:
* [Harvest Optimization Technology (MOG)](https://www.youtube.com/watch?v=JEM50O9d-M8)
* [Optical Sorting in Motion](https://www.youtube.com/watch?v=iSd4RgrFOtg)

</div>

</details>

---

<details>
<summary><strong>2. Functional Prototype</strong></summary>

<div markdown="1">

## Quick Navigation
- [1. Purpose](#system-overview)
- [2. Prototype Design](#prototype-design)
- [3. Prototype Sketch](#prototype-sketch)
- [4. Assembled Prototype](#assembled-prototype)
- [5. What Was Tested](#what-was-tested)
- [6. Results & Outcomes](#results-and-outcomes)
- [7. Key Takeaways](#key-takeaways)
- [8. Full Report](#full-prototype-report)

## 01. Purpose <a name="purpose"></a>
The purpose of this functional prototype was to evaluate whether a brush-based mechanical system could effectively dislodge Spotted Lanternflies (SLF) from grape clusters without damaging the fruit or disrupting flow conditions. The prototype focuses on validating the feasibility of mechanical agitation as a primary separation method.

---

## 02. Prototype Design <a name="prototype-design"></a>

The prototype consists of a simplified inline system including:

- A **shaft-mounted rotary brush** driven by a handheld drill  
- A **manual conveyor simulation** using a sliding cardboard base  
- A **partition and collection region** to separate dislodged SLF  

This setup replicates the key interactions between brush, grapes, and contaminants in a controlled environment.

---

## 03. Prototype Sketch <a name="prototype-sketch"></a>

<div style="text-align: center;">
  <img src="{{ '/assets/images/agkgdfa .png' | relative_url }}" 
       style="width: 60%; max-width: 500px; height: auto;">
</div>


*Figure: Conceptual sketch of the prototype system showing brush placement, conveyor direction, and collection regions.*

---

## 04. Assembled Prototype <a name="assembled-prototype"></a>

<div style="text-align: center;">
  <img src="{{ '/assets/images/IMG_1492.jpg' | relative_url }}" 
       style="width: 60%; max-width: 500px; height: auto;">
</div>

*Figure: Physical prototype used for testing, including rotary brush, shaft, and conveyor simulation.*

---

## 05. What Was Tested <a name="what-was-tested"></a>

- Brush rotation speed and its effect on SLF removal  
- Bristle coverage across the conveyor width  
- Stability and consistency of the conveyor simulation  
- Overall SLF removal efficiency per pass  

---

## 06. Results & Outcomes <a name="results-and-outcomes"></a>

- Optimal brush speed identified at approximately **500 RPM**  
- SLF removal efficiency reached **~70–75% per pass**  
- Minimal grape damage observed, though some displacement occurred  
- Inconsistent removal across width due to uneven bristle distribution  
- Conveyor instability led to occasional loss of grape clusters  

---

## 07. Key Takeaways <a name="key-takeaways"></a>

- Mechanical brushing is an effective **preliminary separation method**  
- System performance depends heavily on **uniform material flow**  
- Brush design and coverage are critical to improving efficiency  

---

## 08. Full Report <a name="full-prototype-report"></a>

[**View Full Prototype Report (PDF)**]({{ "/assets/pdf/ODP 5.pdf" | relative_url }})
</div>

</details>

---
<details>
<summary><strong>3. Client Report</strong></summary>

<div markdown="1">


## Quick Navigation
- [1. System Overview](#system-overview)
- [2. Final System Architecture](#system-architecture)
- [3. Prototype Construction](#prototype-construction)
- [4. Testing & Performance](#testing--performance)
- [5. Demonstrations](#demonstrations)
- [6. Conclusions & Next Steps](#conclusion)

---

## 1. System Overview <a name="system-overview"></a>

The final system addresses a high-throughput agricultural challenge: **Spotted Lanternfly (SLF) contamination in mechanically harvested grapes**. At industrial harvesting rates (2–3 tons/hour), even small contamination levels can lead to rejected loads.

Rather than relying on post-harvest sorting or manual labor, the proposed solution integrates a **continuous inline mechanical separation system** directly into the harvesting flow. The system is designed to be **retrofit-compatible**, meaning it can be added to existing conveyor-based harvesters without redesigning the entire machine.

The separation strategy is based on three physical principles:

- **Mechanical agitation** to dislodge insects from grape clusters  
- **Controlled airflow separation** to exploit mass and aerodynamic differences  
- **Continuous conveyor transport** to maintain throughput without interruption  

---

## 2. Final System Architecture <a name="system-architecture"></a>

The final design combines mechanical and pneumatic subsystems into a continuous flow pipeline:

- **Conveyor Belt System:** Maintains steady transport of grape clusters  
- **Rotary Brush Module:** Applies controlled agitation to expose hidden SLF  
- **Airflow Separation Unit:** Uses directed high-speed air to remove insects  
- **Dual Collection System:** Separates grapes and SLF into independent bins  
- **Secondary Capture Zone:** Prevents re-entrainment of dislodged insects  

This multi-stage design ensures that separation is **progressive rather than single-pass**, improving reliability while preserving grape integrity.

---

## 3. Prototype Construction <a name="prototype-construction"></a>

### 3.1 Concept Sketch

<div style="text-align:center;">
  <img src="{{ '/assets/sketch.png' | relative_url }}" style="width:65%; border-radius:8px;">
</div>

*Initial system layout showing conveyor flow, brush placement, airflow zone, and collection regions.*

---

### 3.2 CAD Development


<div style="display:flex; gap:10px; justify-content:center; flex-wrap:wrap;">
  <img src="{{ '/assets/cad.png' | relative_url }}" style="width:48%; border-radius:8px;"> 
</div>

*CAD models used to validate alignment of brush shaft, airflow direction, and conveyor clearance.*

---

### 3.3 Physical Prototype Build

The final prototype was constructed using a combination of **wood, cardboard, and 3D-printed components** to replicate industrial-scale behavior at bench scale.

<div style="display:flex; gap:10px; justify-content:center; flex-wrap:wrap;">
  <img src="{{ '/assets/exhibit.png' | relative_url }}" style="width:48%; border-radius:8px;"> 
</div>


#### Structural Frame
- Two wooden side walls mounted on a long wooden baseboard  
- Ensures alignment and stability of conveyor subsystem  

#### Conveyor System
- Two cardboard rollers (paper towel cores) act as drums  
- Paper belt wrapped tightly and reinforced with wax paper  
- Wooden dowels run through roller centers to enable rotation  
- Dowels pass through drilled holes in side walls  
- 3D-printed knobs attached for manual actuation  

#### Rotary Brush System
- Drill-driven **machined steel shaft** used as the main agitator  
- Shaft connected via drill chuck for controlled RPM variation  
- Three 3D-printed shaft rings positioned along shaft length  
- Each ring holds bristles in evenly spaced slots for uniform contact  
- System supported by a reinforced 3D-printed mount on opposite wall  

#### Airflow System
- Hair dryer used to simulate compressed air jets  
- Positioned adjacent to brush zone for immediate separation response  

#### Collection System
- 3D-printed angled bin for grapes at conveyor exit  
- Secondary side-mounted bin captures airborne SLF  
- Both bins aligned with conveyor edges for clean separation flow  

#### Flow Control Features
- Thin wooden ridges added across conveyor surface to simulate grip variation  
- System height adjusted iteratively to prevent jamming and improve flow  

---

### 3.4 Final Assembled Prototype

<div style="text-align:center;">
  <img src="{{ '/assets/IMG_7151.jpeg' | relative_url }}" style="width:70%; border-radius:8px;">
</div>

*Final assembled prototype integrating conveyor, brush system, airflow unit, and dual collection bins.*

---

## 4. Testing & Performance <a name="testing--performance"></a>

Testing was conducted using **fresh grapes and paper SLF models** to evaluate:

- Separation efficiency  
- Fruit integrity  
- Flow stability across conveyor system  
- Sensitivity to brush speed and airflow strength  

### Key Experimental Findings

- **Optimal brush speed:** ~500 RPM  
- **Best performance configuration:**  
  - Medium conveyor speed  
  - High airflow setting (Dyson Airwrap high mode)  
  - Continuous brush contact across full width  

- **Average SLF removal efficiency:** ~70–75% per pass  
- **Grape damage:** Negligible under optimal settings  
- **Primary limitation:** Non-uniform brush coverage across conveyor width  

### Observed Failure Modes
- Uneven bristle density caused spatial variation in removal efficiency  
- Conveyor alignment inconsistencies occasionally disrupted flow continuity  
- Lightweight SLF models responded more consistently than heavier grape clusters  

---

### Testing in Action

#### Live Prototype Operation
<div style="text-align:center;">
  <video width="70%" controls>
    <source src="{{ '/assets/IMG_1574.MOV' | relative_url }}" type="video/mp4">
  </video>
</div>

*Full system operation showing conveyor movement, brush interaction, and airflow separation.*

---

#### SLF Removal Testing
<div style="text-align:center;">
  <video width="70%" controls>
    <source src="{{ '/assets/IMG_5824.mov' | relative_url }}" type="video/mp4">
  </video>
</div>

*Targeted testing of SLF removal efficiency under varying RPM and airflow conditions.*

---

## 5. Demonstrations <a name="demonstrations"></a>

This system demonstrates a complete **continuous inline separation workflow**:

1. Grapes enter conveyor system  
2. Rotary brush agitates clusters and exposes insects  
3. Airflow subsystem removes dislodged SLF  
4. Dual collection system separates outputs  
5. Grapes exit with reduced contamination load  

The system maintains throughput while introducing **no interruption to flow**, which is critical for industrial scalability.

---

## 6. Conclusions & Next Steps <a name="conclusion"></a>

### Conclusion
The prototype successfully demonstrates that **mechanical agitation + pneumatic separation** can significantly reduce SLF contamination while preserving grape integrity and maintaining continuous flow conditions.

### Recommended Improvements
- Improve brush uniformity across full conveyor width  
- Replace hair dryer with engineered compressed air manifold (5–10 m/s target)  
- Add vacuum-assisted capture to prevent SLF re-entrainment  
- Transition to higher-throughput testing conditions representative of vineyard-scale operations  
- Replace cardboard conveyor with rigid industrial-grade belt system for durability testing  

### Overall Assessment
The system is **functionally validated at prototype scale** and shows strong potential for further development toward field-ready deployment.

---

</div>
</details>



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

