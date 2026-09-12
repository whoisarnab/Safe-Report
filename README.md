# SAFEREPORT AI 🚨
### AI-Powered Public Safety Detection, Prioritization & Emergency Response Platform

**Hackathon Project**

🌐 **Live Demo:** https://quick-aid-alert.lovable.app/

---

## 🧠 Problem Statement

Public safety incidents can develop rapidly while authorities must simultaneously understand **what happened, how urgent it is, where it occurred, and which resources should respond**.

**SAFEGRID AI** is an AI-powered public safety intelligence and response platform designed to transform incoming incident reports into actionable operational information.

### Core workflow

**Detect → Classify → Locate → Prioritize → Coordinate → Resolve**

---

## 🚀 Key Features

- 🤖 **AI Incident Classification** — identifies the likely type of public-safety incident.
- 🧠 **AI Severity & Urgency Scoring** — assigns a 0–100 priority score and Critical/High/Medium/Low level.
- 📍 **Location Intelligence** — associates incidents with reported/GPS locations.
- 🗺️ **Live Incident Map** — geographic view of active incidents.
- 🚨 **AI Priority Queue** — ranks incidents according to urgency and potential impact.
- 🚑 **Resource Coordination** — coordinates simulated ambulance, police, fire and rescue units.
- 🔄 **Incident Lifecycle** — Reported → AI Analyzing → Verified → Dispatched → On Scene → Resolved.
- 🧩 **Duplicate & Multi-Report Correlation** — combines reports that may describe the same event.
- 🎤 **Multimodal Intake** — interfaces for text, voice, image and video reports.
- 🏥 **Hospital Capacity** — emergency beds, ICU and ventilator availability.
- 💬 **AI Operations Copilot** — command-center decision support.
- 📊 **Safety Analytics** — incident trends, response metrics and resolution statistics.
- 🔥 **Risk & Hotspot Intelligence** — highlights areas with elevated activity.
- 🔴 **SOS Workflow** — one-tap emergency demonstration flow.
- 🎭 **Simulation Mode** — complete demo without connecting to real emergency infrastructure.

---

## 🎯 Innovation

Traditional emergency reporting mainly answers:

> **“How can someone report an incident?”**

SAFEGRID AI goes further:

> **“What is happening, how urgent is it, where is it, what resources are needed, and what should the response team consider next?”**

The platform is designed as an **AI-assisted decision-support layer**, not a replacement for trained emergency personnel.

---

## 🏗️ System Architecture

```text
Citizen / Voice / Image / Video / Sensors
                  │
                  ▼
          AI Incident Intake
                  │
                  ▼
       Incident Classification
                  │
                  ▼
       Severity & Urgency Engine
                  │
                  ▼
          Location Intelligence
                  │
                  ▼
       Duplicate / Correlation AI
                  │
                  ▼
          AI Priority Queue
                  │
                  ▼
        Response Recommendation
                  │
                  ▼
       Resource / Dispatch Layer
             │     │     │
             ▼     ▼     ▼
          Police  Fire  Medical
                  │
                  ▼
          Incident Resolution
                  │
                  ▼
       Analytics & Safety Insights
```

---

## 🚨 Incident Priority Model

| Score | Priority | Suggested Meaning |
|---:|---|---|
| 76–100 | 🔴 Critical | Immediate / multi-agency attention |
| 51–75 | 🟠 High | Urgent response |
| 26–50 | 🟡 Medium | Local response / follow-up |
| 0–25 | 🟢 Low | Monitor / routine response |

The score is intended as decision support and should be reviewed by authorized personnel before real-world action.

---

## 📍 Supported Incident Types

- 🔥 Fire
- 🚑 Medical Emergency
- 🚗 Road Accident
- 👮 Crime / Public Disturbance
- 🌊 Flood / Waterlogging
- 🏚️ Structural Collapse
- ⚠️ Other Public Safety Incidents

---

## 🖥️ Command Center

The command dashboard provides:

- Critical and high-priority incident counts
- Live incident map
- AI-ranked priority queue
- Responder readiness
- AI situation brief
- Incident status
- Resource availability
- Emergency operations Copilot

---

## 🧩 AI Incident Correlation

Multiple citizens may report the same event.

```text
Report A → “Fire near Central Market”
Report B → “Heavy smoke at Central Market”
Report C → “People evacuating Central Market”
                    │
                    ▼
            AI Correlation Layer
                    │
                    ▼
             ONE INCIDENT
```

This reduces duplicate operational records and gives responders a consolidated situation picture.

---

## 🚑 Resource Coordination

SAFEGRID AI represents emergency resources such as:

```text
🚑 Ambulances
👮 Police Units
🚒 Fire Units
🛟 Rescue Units
🏥 Hospitals
```

The system can display availability, distance, ETA and recommended response combinations.

---

## 💬 AI Operations Copilot

Command operators can ask:

- “What is our highest-priority incident?”
- “How many ambulances are available?”
- “Which incident should we respond to first?”
- “What resources are recommended?”

The Copilot provides decision support while keeping final operational decisions with authorized human personnel.

---

## 🎭 Hackathon Demo Flow

### 1. Citizen Report

> “Heavy smoke and fire near Central Market. People are evacuating.”

### 2. AI Analysis

```text
Type: Fire
Priority: Critical
AI Confidence: High
Potential Impact: High
```

### 3. Location

The incident appears on the command-center map.

### 4. Correlation

Additional reports from the same area are associated with the existing incident.

### 5. Prioritization

The incident moves to the top of the AI priority queue.

### 6. Response Recommendation

```text
🚒 Fire Response
🚑 Ambulance Support
👮 Police / Traffic Control
```

### 7. Responder Coordination

Units progress through:

```text
AVAILABLE → EN ROUTE → ON SCENE → RESOLVED
```

### 8. Analytics

Response time and incident information become available for operational analysis.

---

## 🏆 Alignment With the Hackathon Problem

| Hackathon Requirement | SAFEGRID AI |
|---|---|
| Detect incidents | AI incident intake |
| Classify incidents | AI classification |
| Determine urgency | AI severity score |
| Determine location | Location intelligence + map |
| Prioritize response | AI priority queue |
| Coordinate response | Resource and responder coordination |
| Help authorities | Command center + AI Copilot |
| Improve awareness | Correlation + live map |
| Measure response | Analytics |

---

## 🛠️ Technology Stack

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS
- Lucide Icons
- Recharts

### Backend / Data
- Supabase
- PostgreSQL
- Supabase Realtime
- Authentication
- Row Level Security

### AI Layer
Designed for integration with AI models for:
- Text classification
- Image/video understanding
- Severity assessment
- Report summarization
- Incident correlation
- Response recommendations

### Mapping
Designed for GIS/map integration for:
- Incident locations
- Responder locations
- Hospitals
- Distance/ETA
- Safety hotspots

---

## 🔐 Responsible AI & Safety

SAFEGRID AI is a **hackathon decision-support prototype**.

- AI recommendations should be reviewed by authorized personnel.
- AI confidence should be visible to operators.
- The prototype does not directly control real emergency infrastructure.
- Demonstration data is not live emergency-service data.
- Production deployment would require appropriate security, privacy, reliability testing, audit logging and authorization.

**For real emergencies, contact the appropriate official emergency service.**

---

## 🌐 Live Demo

**Hosted application:**  
https://quick-aid-alert.lovable.app/

---

## 💻 Local Development

### Requirements
- Node.js 18+
- npm

### Installation

```bash
git clone <your-github-repository-url>
cd quick-aid-alert
npm install
npm run dev
```

Open the local URL provided by Vite, usually:

```text
http://localhost:5173
```

---

## 🔧 Environment Variables

For Supabase integration, create `.env.local`:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_PUBLISHABLE_KEY=your_supabase_publishable_key
```

Never expose a Supabase service-role/secret key in frontend code.

---

## 🔮 Future Scope

- Real-time CCTV event detection
- Computer vision for fire, accidents and crowd incidents
- Speech-to-text emergency reporting
- Real-time responder GPS
- Traffic-aware ETA prediction
- Predictive safety-risk mapping
- Weather and environmental risk integration
- Hospital API integration
- Offline-first emergency reporting
- Multi-agency communication
- Multilingual citizen reporting
- Advanced GIS analytics
- Production-grade authentication and audit trails

---

## 📌 Project Status

**Hackathon Prototype / Demonstration**

The current application demonstrates the command-center workflow, incident management experience and AI-assisted public safety concepts. Real emergency-service integrations and production AI inference require additional engineering, validation and authorization.

---

## ⭐ Vision

> **See the incident. Understand the incident. Prioritize the incident. Coordinate the response.**

SAFEGRID AI aims to move public safety technology from **reactive reporting** toward **intelligent situational awareness and coordinated response**.

---

**Built for a hackathon focused on AI-powered public safety, emergency prioritization and coordinated response.**
