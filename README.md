<div align="center">

# NEXUS
### Crisis Management Dashboard

**When a smart city's mind is attacked, its operators become its last line of defense.**

![Team](https://img.shields.io/badge/team-SMA--W1-FF751C?style=for-the-badge)
![Status](https://img.shields.io/badge/status-active--development-FF751C?style=for-the-badge)
![Type](https://img.shields.io/badge/type-competition--project-13C6D1?style=for-the-badge)
![Stack](https://img.shields.io/badge/stack-HTML%20·%20CSS%20·%20JavaScript-3BD17B?style=for-the-badge)

**Team SMA-W1**

</div>

---

## Table of Contents

- [Overview](#overview)
- [The Scenario](#the-scenario)
- [Original Challenge](#original-challenge)
- [Why NEXUS Stands Out](#why-nexus-stands-out)
- [Main Features](#main-features)
- [Pages](#pages)
- [Real-Time Data Engine](#real-time-data-engine)
- [Original Data Examples](#original-data-examples)
- [Design System](#design-system)
- [Technologies](#technologies)
- [Responsive Design](#responsive-design)
- [Team](#team)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Competition Purpose](#competition-purpose)
- [Closing Note](#closing-note)

---

## Overview

**NEXUS** is a front-end crisis management dashboard built for a simulated smart city in the Middle East — a city whose every artery, from traffic signals to power plants, is run by a single artificial intelligence, also named **NEXUS**.

This project imagines the moment that system is compromised, and answers a single design question: *what does an operator need in front of them, in the first sixty seconds of a citywide crisis, to regain control?*

The result is a full-scale operational interface — not a mockup, not a static prototype — built to look, feel, and behave like software a real emergency command center would trust its city to.

---

## The Scenario

The city's central AI — **NEXUS** — governs:

- Traffic lights and intersections
- Power plants and the electrical grid
- Water systems and reservoirs
- Air pollution monitors
- Security cameras
- Thousands of distributed city sensors

Then, a **massive cyberattack** tears through part of the system. In its wake:

- Traffic collapses into gridlock across multiple districts
- Air pollution spikes to critical, health-threatening levels
- Entire districts sit on the edge of blackout
- Sensor data starts arriving **delayed**
- Sensor data starts arriving **corrupted**
- And somewhere in a control room, operators are left with one tool to make sense of it all — this dashboard.

NEXUS isn't just a UI. It's the operator's only window into a city that's fighting to stay online.

---

## Original Challenge

This project is built on top of the official **NEXUS Web Challenge**, which required:

- A fully interactive web application
- JavaScript-based data management
- Simulated real-time data
- City-sector monitoring
- Map-based data visualization
- Traffic monitoring
- Air-quality monitoring
- Power-grid monitoring
- Crisis detection

Every one of those requirements is met in full. But rather than treating the brief as a checklist, our team treated it as a foundation — expanding it into a coherent, believable operational product with its own visual language, narrative logic, and depth of functionality.

**We didn't replace the original challenge. We built the system it was describing.**

---

## Why NEXUS Stands Out

- **A real command-center feel** — not a dashboard template with different labels, but a purpose-built interface shaped around how a crisis actually unfolds.
- **Depth over decoration** — eleven fully realized operational pages, each with its own working logic, not filler screens.
- **Honest data simulation** — sensor values drift and evolve believably over time instead of jumping to random numbers every refresh.
- **A design system with intent** — every color in the palette has a job; red is earned, not decorative.
- **Built for scrutiny** — structured, documented, and organized clearly enough that a judge — or a new developer — can understand the entire system in minutes.
- **Full ownership, not division of labor** — every page in NEXUS was built end-to-end by a single team member, which means every screen was designed, coded, and refined by someone who understood exactly what it needed to do.

---

## Main Features

| Category | Capabilities |
|---|---|
| **Monitoring** | Real-time city monitoring, interactive city map, traffic monitoring, power-grid monitoring, air-quality monitoring, water-system monitoring, security monitoring |
| **Response** | Alerts & incidents management, critical-zone monitoring, severity-based triage |
| **Intelligence** | City-wide analysis, sensor reliability & data-quality monitoring |
| **Experience** | Real-time sensor simulation, fully responsive interface, Google Maps integration, interactive charts, filtering and search across every module |

---

## Pages

### Login
Professional NEXUS operator login screen — the operator's entry point into the command system.

### Dashboard
The main city command center, giving an at-a-glance read on the entire city:
- Traffic Index
- City AQI
- Power Grid
- Active Alerts
- System Health
- City Map
- Critical Zones
- Live Alerts
- Sensor Feed

### City Map
An interactive map for monitoring city infrastructure at a glance, with independently toggleable layers:
- Traffic
- Air Quality
- Power Grid
- Water System
- Security Cameras
- Sensors
- Incidents

The map includes a movable **Map Layers** widget, so operators can arrange their view around what matters most in the moment.

### Traffic
Includes:
- Traffic map
- Congestion levels
- Accidents
- Closed roads
- Average speed
- Traffic flow
- Traffic cameras
- Historical traffic data

Original challenge data encoding:

| Value | Meaning |
|:---:|---|
| `0` | Normal street |
| `1` | Heavy traffic |
| `2` | Accident |
| `3` | Closed area |

### Power Grid
Includes:
- Power plants
- Power generation
- Capacity
- Station status
- Critical stations
- Blackout-risk districts
- Consumption charts
- Grid stability

Example reading during an active crisis:

| Station | Status | Power |
|---|:---:|:---:|
| North Plant | Active | 82% |
| South Plant | **CRITICAL** | 21% |

### Air Quality
Includes:
- City AQI
- Air-quality map
- Monitoring zones
- Critical zones
- Sensor status
- AQI trends
- Pollutant levels

Tracked pollutants: `PM2.5` · `PM10` · `NO2` · `SO2` · `CO` · `O3`

### Water System
Includes:
- Water pressure
- Reservoir levels
- Pump stations
- Water consumption
- Pipeline status
- Water leaks
- Critical zones
- Sensors
- Maintenance alerts

### Security
Includes:
- Security cameras
- Camera status
- Security incidents
- Restricted zones
- Sensors
- Camera feeds
- Response status

### Alerts & Incidents
The operational heartbeat of the crisis response. Includes:
- Total alerts
- Critical alerts
- Open incidents
- Resolved incidents
- Incident map
- Incident feed
- Severity filters
- District filters
- Incident details
- Incident timeline

Severity levels: **Critical** · **High** · **Medium** · **Low**

### Data Quality
Includes:
- Active sensors
- Delayed sensors
- Corrupted sensors
- Offline sensors
- Data quality percentage
- Sensor health
- Data-quality trends
- Corrupted-data table
- Delayed-sensor table

This page directly answers one of the hardest parts of the original brief: a crisis dashboard is only as trustworthy as the data behind it. This is where operators can see — and question — that trust.

### Analysis
The intelligence and analytical center of NEXUS. Includes:
- City Risk Trend
- Sector Performance
- Traffic Analysis
- Air Quality Analysis
- Power Analysis
- Incident Statistics
- Sensor Reliability
- Detected Anomalies

### Settings
Includes:
- Operator preferences
- Notifications
- Alert preferences
- Display settings
- Data refresh rate
- Map preferences
- System information

---

## Real-Time Data Engine

NEXUS uses JavaScript to simulate real-time sensor data across the entire city. The simulation continuously updates:

- Traffic
- AQI
- Power generation
- Sensor status
- Alerts
- Live feed
- Incident status
- Timestamps

Crucially, the data is engineered to **behave**, not just change. Values drift, trend, and respond the way real infrastructure data would — so the dashboard tells a believable, evolving story of the crisis rather than flashing random noise at the operator.

---

## Original Data Examples

**Traffic:**

```javascript
const trafficMap = [
 [0,0,1,0,0],
 [0,1,1,1,0],
 [0,0,2,0,0],
 [1,1,1,0,0],
 [0,0,0,0,3]
];
```

**Pollution:**

```javascript
const pollutionData = [
 { zone: "A1", aqi: 120 },
 { zone: "B4", aqi: 250 },
 { zone: "C2", aqi: 90 }
];
```

**Power Grid:**

```
North Plant
Status: Active
Power: 82%

South Plant
Status: Critical
Power: 21%
```

---

## Design System

NEXUS's visual identity is built around a single idea: **a command center at night, run by people who cannot afford to misread the screen.** The interface uses:

- Dark, futuristic aesthetic
- Smart-city command-center styling
- Middle Eastern visual identity
- Cybersecurity-inspired elements
- Professional emergency-management UI conventions
- Data-focused, noise-free layouts

**Color Palette**

| Purpose | Hex | Role |
|---|:---:|---|
| Background | `#03080D` | The near-black base the whole interface breathes in |
| Panels | `#08131C` | Elevated surfaces for data and modules |
| Borders | `#182C38` | Quiet structural separation |
| NEXUS Orange | `#FF751C` | The system's signature — action, identity, focus |
| Cyan | `#13C6D1` | Data, live feeds, and system intelligence |
| Normal | `#3BD17B` | Everything operating as expected |
| Warning | `#EAB42F` | Something needs attention |
| High | `#FF8C22` | Something needs attention *now* |
| Critical | `#E33E3A` | Reserved — deliberately — for the moments that matter most |

Red is never used decoratively in NEXUS. It is earned only by genuinely critical states, so that when an operator sees it, they know it's real.

---

## Technologies

- HTML5
- CSS3
- JavaScript
- Google Maps API
- Charting library (as applicable)
- Responsive CSS
- Simulated real-time data engine

---

## Responsive Design

NEXUS is built to be operated anywhere a crisis might demand it — from a full command-center wall display down to a single tablet in the field. It supports **Desktop**, **Tablet**, and **Mobile** through:

- Responsive grids
- Collapsible navigation
- Responsive charts
- Responsive maps
- Mobile-friendly controls
- Scrollable tables

---

## Team

### Team SMA-W1

NEXUS is built by **Team SMA-W1**, a four-person front-end team that split full ownership of the system across its members rather than dividing work by convenience. Each page below was owned end-to-end by the developer responsible for it — from layout and logic to the data it displays.

| Member | Responsibilities |
|---|---|
| **ELENA ALIMIRZADEHKARGAR** | Login, City Map, Data Quality, Analysis, Air Quality, Alerts & Incidents |
| **MANIYA GHARAYAGHZANDI** | Dashboard, Traffic, Power Grid, Settings, Water System |
| Mehrsam Hosseini | Team Member |
| MOHAMMAD SADEGH ZADEH | Team Member |

**ELENA ALIMIRZADEHKARGAR** and **MANIYA GHARAYAGHZANDI** jointly led:

- Linking the project pages into a single cohesive system
- Project integration
- README documentation

---

## Project Structure

```
NEXUS/
│
├── index.html # Login page
├── dashboard.html # Main command center
├── city-map.html # Interactive city map
├── traffic.html # Traffic monitoring
├── power-grid.html # Power grid monitoring
├── air-quality.html # Air quality monitoring
├── water-system.html # Water system monitoring
├── security.html # Security monitoring
├── alerts-incidents.html # Alerts & incidents
├── data-quality.html # Data quality monitoring
├── analysis.html # Analytics center
├── settings.html # Operator settings
│
├── css/
│ ├── main.css
│ ├── dashboard.css
│ └── ...
│
├── js/
│ ├── main.js
│ ├── data-simulation.js
│ ├── map.js
│ └── ...
│
├── assets/
│ ├── icons/
│ ├── images/
│ └── fonts/
│
└── README.md
```

---

## How to Run

1. Clone or download the project folder.
2. Open the project folder in a code editor (e.g., VS Code).
3. If a live server is available, run the project through it for the smoothest experience with real-time data simulation.
4. Alternatively, open `index.html` directly in a modern web browser.
5. If the Google Maps API is enabled, add a valid Google Maps API key to the designated configuration file/script before loading the City Map page.

---

## Competition Purpose

NEXUS was built to demonstrate command over the full breadth of front-end engineering and product thinking:

- Front-End development
- UI/UX design
- JavaScript programming
- Real-time data simulation
- Data visualization
- Interactive maps
- Crisis management systems
- Smart-city concepts
- Responsive web development

---

## Closing Note

A city under attack doesn't need another pretty screen — it needs a system its operators can trust with their next decision. That's the standard **NEXUS** was designed to meet, and it's the standard **Team SMA-W1** held itself to at every stage of the build: from the first data model to the last pixel of the design system.

<div align="center">

### NEXUS — Command. Monitor. Respond.

**Built by Team SMA-W1**

</div>
