# RapidAid — Emergency Dispatch System
### Graph-E-Thon 3.0 | Track: Intelligent Health & Learning | SDG 3

> Because the nearest ambulance isn't always the fastest.

## What is RapidAid
RapidAid is a web-based emergency dispatch platform that fixes 
India's broken ambulance response chain. It calculates real-time 
ETA for every available ambulance using live traffic data and 
dispatches the fastest one — not the nearest.

## Prototype Files

| File | What it shows |
|---|---|
| rapidaid_dispatch.html | 3 ambulances, same distance, fastest selected using live TomTom traffic |
| rapidaid_ems.html | Route planner — enter any coordinates, get 2 live routes with traffic overlay |
| rapidaid_dashboard.html | Hospital dashboard — ETA countdown, patient info, ER alerts, fleet status |

## How to Run
1. Download any .html file
2. Open in Chrome — no server needed
3. Add your free TomTom API key where marked in the code
4. Get free key at: https://developer.tomtom.com

## Tech Stack
- **Frontend:** React.js, Leaflet.js, OpenStreetMap
- **Backend:** Python FastAPI
- **Routing & Traffic:** TomTom Routing API (live traffic)
- **Real-time sync:** Firebase Realtime Database
- **Maps:** Leaflet.js + OpenStreetMap

## The Core Problem We Solve
India loses 1.6 lakh lives yearly to road accidents.
50% preventable within the Golden Hour.
Current 108 dispatch sends the nearest ambulance — not the fastest.
A 2km ambulance stuck in traffic arrives after a 3km ambulance 
on a clear road. RapidAid fixes this.

## Research Backing
- TU Munich 2025 (arXiv:2503.11848) — ETA dispatch reduces 
  response time up to 30%
- ISRO/AIIMS Jodhpur 2024 — Golden Hour timeline data
- AIIMS/NITI Aayog 2020 — Only 3% hospitals get pre-arrival notification

## 5 Modules
1. National Ambulance Registry
2. ETA-based Dispatch Engine (TomTom live traffic)
3. Emergency Navigation
4. Hospital Coordination Dashboard
5. Civilian Traffic Alert System

## Team
Ashish Bisht — Backend & API Integration
[Name 2] — Frontend & Firebase  
[Name 3] — Research & UI
[Name 4] — Systems & Routing

## Contact
ashishbisht170249@gmail.com
