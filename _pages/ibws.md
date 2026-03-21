---
permalink: /ibws/
title: "iBWS: Intelligent Building Water Systems"
excerpt: "Autonomous digital twins for building water infrastructure"
author_profile: true
---

## Autonomous Digital Twins for Building Water Infrastructure

**iBWS** (Intelligent Building Water Systems) is a 10-year research program founded by Dr. Juneseok Lee developing autonomous digital twin technology for building-scale water infrastructure. Building water systems — the premise plumbing networks within hospitals, hotels, universities, and residential buildings — cause **8,000–18,000 Legionella-related hospitalizations annually** in the U.S. and remain the least-monitored segment of drinking water infrastructure.

iBWS transforms building water management from reactive to autonomous through a four-layer architecture: data integration, physics-based simulation engines, AI-driven intelligence, and autonomous orchestration.

---

### Six Validated Components

**1 · P03 · BIM2WNTR — Automated Model Generation**  
Converts Building Information Models (BIM) to WNTR-ready hydraulic simulation networks automatically. Achieves R²>0.99 accuracy in under 10 seconds.

**2 · P00 · Pump Scheduling Optimization**  
Multi-objective pump scheduling using NSGA-II and 54,000 HPC simulations. Achieves **45.6% energy savings** relative to conventional always-on scheduling.

**3 · P06 · Thermal Risk Modeling — Legionella Prevention**  
Physics-based thermal simulation identifying zones in the 25–45°C growth range, triggering automated flushing protocols before outbreak conditions develop.

**4 · P04 · Hydraulic Transient Analysis**  
Pressure surge quantification across 96 building scenarios using TSNet. Identifies transient-induced pipe failure risks and informs protective control strategies.

**5 · P01 · One Water Simulation**  
Coupled potable-drainage simulation enabling simultaneous modeling of water supply, greywater recycling, and drainage systems.

**6 · P18/P19 · iBWSS — Water Sustainability Optimization**  
Multi-objective optimization of rainwater harvesting, greywater recycling, and solar-assisted water heating. Achieves up to **62% water self-sufficiency** across 12 U.S. cities.

---

### Three Levels of Autonomous Control

<style>
.ibws-card{background:#fff;border:1px solid #dddbd2;border-radius:12px;overflow:hidden;margin-bottom:1.25rem;box-shadow:0 1px 4px rgba(0,0,0,0.06);}
.ibws-header{display:flex;align-items:center;gap:12px;padding:0.9rem 1.25rem;border-bottom:1px solid #dddbd2;flex-wrap:wrap;}
.ibws-badge{font-size:11px;font-weight:700;letter-spacing:0.4px;text-transform:uppercase;padding:3px 10px;border-radius:20px;white-space:nowrap;}
.badge-l1{background:#E1F5EE;color:#0F6E56;}
.badge-l2{background:#FAEEDA;color:#854F0B;}
.badge-l3{background:#E6F1FB;color:#185FA5;}
.ibws-title{font-size:15px;font-weight:700;color:#1a1a18;}
.ibws-sub{font-size:12px;color:#5f5e5a;}
.ibws-time{margin-left:auto;font-size:12px;color:#888780;font-style:italic;}
.ibws-diagram{padding:1.25rem 1.25rem 0.75rem;overflow-x:auto;}
.ibws-diagram svg{display:block;width:100%;min-width:520px;}
.ibws-who{display:flex;align-items:flex-start;gap:8px;margin:0 1.25rem;padding:0.6rem 0.9rem;border-radius:6px;font-size:12px;line-height:1.5;}
.ibws-who strong{white-space:nowrap;font-weight:700;}
.who-1{background:#FAECE7;color:#712B13;}
.who-2{background:#FAEEDA;color:#633806;}
.who-3{background:#E6F1FB;color:#0C447C;}
.ibws-caption{padding:0.75rem 1.25rem 1rem;font-size:12px;color:#5f5e5a;line-height:1.65;border-top:1px solid #f0ede4;margin-top:0.75rem;}
.ibws-legend{display:flex;flex-wrap:wrap;gap:1rem;margin-top:0.5rem;padding:1rem 1.25rem;background:#fff;border:1px solid #dddbd2;border-radius:10px;font-size:11.5px;color:#5f5e5a;}
.ibws-legend-item{display:flex;align-items:center;gap:6px;}
.ibws-swatch{width:14px;height:14px;border-radius:3px;flex-shrink:0;}
</style>

<div class="ibws-card">
<div class="ibws-header">
  <span class="ibws-badge badge-l1">Level 1</span>
  <span class="ibws-title">Decision Support</span>
  <span class="ibws-sub">Agent diagnoses · Human executes</span>
  <span class="ibws-time">Current · 2025–2026</span>
</div>
<div class="ibws-diagram">
<svg viewBox="0 0 800 162" xmlns="http://www.w3.org/2000/svg">
<defs>
  <marker id="ag1" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto"><path d="M2 1L8 5L2 9" fill="none" stroke="#888780" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></marker>
  <marker id="ac1" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto"><path d="M2 1L8 5L2 9" fill="none" stroke="#993C1D" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></marker>
</defs>
<rect x="10" y="30" width="148" height="60" rx="8" fill="#F1EFE8" stroke="#5F5E5A" stroke-width="0.5"/>
<text x="84" y="52" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="13" font-weight="600" fill="#2C2C2A">Building sensors</text>
<text x="84" y="72" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#5F5E5A">temp · flow · pressure</text>
<line x1="158" y1="60" x2="182" y2="60" stroke="#888780" stroke-width="1.5" marker-end="url(#ag1)"/>
<rect x="184" y="30" width="172" height="60" rx="8" fill="#E6F1FB" stroke="#185FA5" stroke-width="0.5"/>
<text x="270" y="52" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="13" font-weight="600" fill="#0C447C">iBWS agent</text>
<text x="270" y="72" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#185FA5">GPT-4o + physics models</text>
<line x1="356" y1="60" x2="380" y2="60" stroke="#888780" stroke-width="1.5" marker-end="url(#ag1)"/>
<rect x="382" y="30" width="162" height="60" rx="8" fill="#E1F5EE" stroke="#0F6E56" stroke-width="0.5"/>
<text x="463" y="52" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="13" font-weight="600" fill="#085041">Decision report</text>
<text x="463" y="72" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#0F6E56">risk zones · work orders</text>
<line x1="544" y1="60" x2="568" y2="60" stroke="#888780" stroke-width="1.5" marker-end="url(#ag1)"/>
<rect x="570" y="30" width="220" height="60" rx="8" fill="#FAECE7" stroke="#993C1D" stroke-width="0.5"/>
<text x="680" y="52" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="13" font-weight="600" fill="#712B13">Facility manager</text>
<text x="680" y="72" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#993C1D">reads report · decides · acts</text>
<line x1="680" y1="90" x2="680" y2="116" stroke="#993C1D" stroke-width="1.5" stroke-dasharray="4 3" marker-end="url(#ac1)"/>
<text x="680" y="134" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#712B13" font-style="italic">manual on-site action</text>
<text x="680" y="150" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="10" fill="#993C1D">(flush valve, adjust pump, log incident)</text>
<text x="10" y="134" font-family="system-ui,sans-serif" font-size="10" fill="#993C1D" font-weight="700">HUMAN</text>
<text x="10" y="150" font-family="system-ui,sans-serif" font-size="10" fill="#993C1D">IN LOOP</text>
</svg>
</div>
<div class="ibws-who who-1"><strong>WHO ACTS:</strong> Facility manager — iBWS provides the diagnosis and ranked work order; a human performs every physical action manually on-site. Most existing buildings fall into this category today.</div>
<div class="ibws-caption">iBWS agent monitors sensor data and executes physics-based simulations (P06 thermal risk, P03 hydraulic model, P00 pump optimization). When a threshold is exceeded — e.g., Zone 3 at 35°C — the agent generates a prioritized action report. The facility manager reads the report and manually acts. No building automation hardware required. Deployable today.</div>
</div>

<div class="ibws-card">
<div class="ibws-header">
  <span class="ibws-badge badge-l2">Level 2</span>
  <span class="ibws-title">Semi-Autonomous</span>
  <span class="ibws-sub">Agent commands · System executes · Human oversees</span>
  <span class="ibws-time">3–5 years · BAS/BMS integration required</span>
</div>
<div class="ibws-diagram">
<svg viewBox="0 0 800 182" xmlns="http://www.w3.org/2000/svg">
<defs>
  <marker id="ag2" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto"><path d="M2 1L8 5L2 9" fill="none" stroke="#888780" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></marker>
  <marker id="ao2" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto"><path d="M2 1L8 5L2 9" fill="none" stroke="#854F0B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></marker>
</defs>
<rect x="10" y="22" width="134" height="60" rx="8" fill="#F1EFE8" stroke="#5F5E5A" stroke-width="0.5"/>
<text x="77" y="44" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="13" font-weight="600" fill="#2C2C2A">Sensors / IoT</text>
<text x="77" y="64" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#5F5E5A">24/7 monitoring</text>
<line x1="144" y1="52" x2="168" y2="52" stroke="#888780" stroke-width="1.5" marker-end="url(#ag2)"/>
<rect x="170" y="22" width="165" height="60" rx="8" fill="#E6F1FB" stroke="#185FA5" stroke-width="0.5"/>
<text x="252" y="44" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="13" font-weight="600" fill="#0C447C">iBWS agent</text>
<text x="252" y="64" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#185FA5">GPT-4o + physics models</text>
<line x1="335" y1="52" x2="359" y2="52" stroke="#888780" stroke-width="1.5" marker-end="url(#ag2)"/>
<rect x="361" y="22" width="168" height="60" rx="8" fill="#EAF3DE" stroke="#3B6D11" stroke-width="0.5"/>
<text x="445" y="44" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="13" font-weight="600" fill="#27500A">BAS / BMS system</text>
<text x="445" y="64" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#3B6D11">receives iBWS commands</text>
<line x1="529" y1="52" x2="553" y2="52" stroke="#888780" stroke-width="1.5" marker-end="url(#ag2)"/>
<rect x="555" y="22" width="235" height="60" rx="8" fill="#E1F5EE" stroke="#0F6E56" stroke-width="0.5"/>
<text x="672" y="44" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="13" font-weight="600" fill="#085041">Smart valves · pumps</text>
<text x="672" y="64" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#0F6E56">auto-execute commands</text>
<rect x="170" y="100" width="359" height="50" rx="8" fill="#FFF8EE" stroke="#854F0B" stroke-width="1" stroke-dasharray="5 3"/>
<text x="349" y="118" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="12" font-weight="600" fill="#633806">Human override / approval</text>
<text x="349" y="136" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#854F0B">available at any step — operator can pause, override, or abort</text>
<line x1="252" y1="100" x2="252" y2="84" stroke="#854F0B" stroke-width="1" stroke-dasharray="3 3" marker-end="url(#ao2)"/>
<line x1="445" y1="100" x2="445" y2="84" stroke="#854F0B" stroke-width="1" stroke-dasharray="3 3" marker-end="url(#ao2)"/>
<text x="10" y="120" font-family="system-ui,sans-serif" font-size="10" fill="#854F0B" font-weight="700">HUMAN</text>
<text x="10" y="134" font-family="system-ui,sans-serif" font-size="10" fill="#854F0B">OVERSIGHT</text>
</svg>
</div>
<div class="ibws-who who-2"><strong>WHO ACTS:</strong> Automation executes iBWS commands through the building's BAS/BMS — human operator retains full override authority at any time. Requires smart valve and VFD pump infrastructure.</div>
<div class="ibws-caption">The iBWS agent issues commands directly to the Building Automation System (BAS) or Building Management System (BMS) via standard protocols (BACnet, Modbus). The BAS executes thermal flushing, pump scheduling adjustments, and setpoint changes automatically. Suitable for hospitals, hotels, and universities with existing smart building infrastructure. Reduces response time from hours to seconds.</div>
</div>

<div class="ibws-card">
<div class="ibws-header">
  <span class="ibws-badge badge-l3">Level 3</span>
  <span class="ibws-title">Fully Autonomous</span>
  <span class="ibws-sub">Agent monitors · decides · executes · reports — no human in control loop</span>
  <span class="ibws-time">10-year vision · 2035+</span>
</div>
<div class="ibws-diagram">
<svg viewBox="0 0 800 178" xmlns="http://www.w3.org/2000/svg">
<defs>
  <marker id="ag3" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto"><path d="M2 1L8 5L2 9" fill="none" stroke="#888780" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></marker>
  <marker id="at3" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto"><path d="M2 1L8 5L2 9" fill="none" stroke="#185FA5" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></marker>
  <marker id="ar3" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto"><path d="M2 1L8 5L2 9" fill="none" stroke="#5F5E5A" stroke-width="1.2" stroke-linecap="round" stroke-linejoin="round"/></marker>
</defs>
<rect x="10" y="22" width="168" height="60" rx="8" fill="#F1EFE8" stroke="#5F5E5A" stroke-width="0.5"/>
<text x="94" y="44" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="13" font-weight="600" fill="#2C2C2A">Smart sensors</text>
<text x="94" y="64" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#5F5E5A">continuous data stream</text>
<line x1="178" y1="52" x2="202" y2="52" stroke="#888780" stroke-width="1.5" marker-end="url(#ag3)"/>
<rect x="204" y="22" width="196" height="60" rx="8" fill="#E6F1FB" stroke="#185FA5" stroke-width="1"/>
<text x="302" y="44" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="13" font-weight="700" fill="#0C447C">iBWS autonomous agent</text>
<text x="302" y="64" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#185FA5">GPT-4o + all validated models</text>
<line x1="400" y1="52" x2="424" y2="52" stroke="#888780" stroke-width="1.5" marker-end="url(#ag3)"/>
<rect x="426" y="22" width="196" height="60" rx="8" fill="#EAF3DE" stroke="#3B6D11" stroke-width="0.5"/>
<text x="524" y="44" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="13" font-weight="600" fill="#27500A">Smart infrastructure</text>
<text x="524" y="64" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#3B6D11">valves · pumps · thermal systems</text>
<rect x="640" y="22" width="150" height="60" rx="8" fill="#E1F5EE" stroke="#0F6E56" stroke-width="0.5" stroke-dasharray="5 3"/>
<text x="715" y="44" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="12" font-weight="600" fill="#085041">Audit log</text>
<text x="715" y="64" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#0F6E56">reports to stakeholders</text>
<line x1="622" y1="52" x2="638" y2="52" stroke="#5F5E5A" stroke-width="1" stroke-dasharray="4 3" marker-end="url(#ar3)"/>
<path d="M 524,82 L 524,116 L 94,116 L 94,82" fill="none" stroke="#185FA5" stroke-width="1.5" marker-end="url(#at3)"/>
<text x="309" y="133" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="12" font-weight="600" fill="#185FA5">continuous 24/7 autonomous control loop</text>
<text x="309" y="150" text-anchor="middle" dominant-baseline="central" font-family="system-ui,sans-serif" font-size="11" fill="#5F5E5A" font-style="italic">no human decision-making in the control loop</text>
<text x="680" y="110" text-anchor="middle" font-family="system-ui,sans-serif" font-size="10" fill="#888780" font-weight="700">STAKEHOLDERS</text>
<text x="680" y="124" text-anchor="middle" font-family="system-ui,sans-serif" font-size="10" fill="#888780">audit log only</text>
</svg>
</div>
<div class="ibws-who who-3"><strong>WHO ACTS:</strong> The iBWS autonomous agent — monitors, decides, and executes all water system management actions without human involvement. Stakeholders receive audit reports only.</div>
<div class="ibws-caption">The fully autonomous iBWS operates as a closed-loop system: real-time sensor data feeds continuously into the agent, which runs validated physics simulations, makes decisions using multi-objective optimization, and issues direct commands to smart infrastructure. Analogous to how HVAC building automation systems operate today — but for water. This is the iBWS 10-year research and commercialization target.</div>
</div>

<div class="ibws-legend">
  <div class="ibws-legend-item"><div class="ibws-swatch" style="background:#F1EFE8;border:1px solid #5F5E5A"></div> Sensors / data input</div>
  <div class="ibws-legend-item"><div class="ibws-swatch" style="background:#E6F1FB;border:1px solid #185FA5"></div> iBWS agent</div>
  <div class="ibws-legend-item"><div class="ibws-swatch" style="background:#E1F5EE;border:1px solid #0F6E56"></div> Outputs / audit log</div>
  <div class="ibws-legend-item"><div class="ibws-swatch" style="background:#EAF3DE;border:1px solid #3B6D11"></div> Automated execution</div>
  <div class="ibws-legend-item"><div class="ibws-swatch" style="background:#FAECE7;border:1px solid #993C1D"></div> Human operator</div>
  <div class="ibws-legend-item"><div class="ibws-swatch" style="background:#FFF8EE;border:1px dashed #854F0B"></div> Human override (optional)</div>
</div>

---

### Technology Stack

* **Simulation engines**: WNTR, PySWMM, TSNet, custom thermal models
* **Optimization**: NSGA-II, multi-objective Pareto optimization
* **AI orchestration**: OpenAI Agents SDK, GPT-4o, physics-informed neural surrogates
* **Data integration**: BIM2WNTR automated pipeline
* **Computing**: HPC-enabled simulation (NAIRR/ACCESS aligned)

---

### Research Roadmap

| Phase | Timeline | Milestone |
|---|---|---|
| Component validation | 2002–2025 | Six validated physics models |
| Agent architecture | 2025–2026 | Autonomous orchestration proof-of-concept |
| Field validation | 2026–2028 | Pilot deployment in real buildings |
| Generalized platform | 2028–2030 | Multi-building scalable product |
| Full autonomy | 2030–2035 | Level 3 autonomous control |

---

### Publications

Selected iBWS-related publications are listed on the [Publications](/publications/) page. Key venues include ASCE Journal of Water Resources Planning and Management, AWWA Water Science, Journal of Hydraulic Engineering, and ASCE/ASEE conference proceedings.

---

### Collaboration & Contact

Dr. Lee welcomes collaboration with researchers, building owners, utilities, and industry partners interested in intelligent building water systems.

**Email**: juneseok.lee@manhattan.edu  
**Google Scholar**: [View iBWS-related publications](https://scholar.google.com/citations?user=VPOh9yoAAAAJ&hl=en)

---

*iBWS is the 10-year research and commercialization vision of Dr. Juneseok Lee, building on 24 years of validated building water systems research (2002–present).*
