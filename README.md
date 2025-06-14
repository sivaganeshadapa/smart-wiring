# ⚡ SmartWiring Pro

> An AI-powered intelligent system for designing, optimizing, and integrating electrical and solar systems in residential and commercial buildings.

---

## 🚀 Project Overview

**SmartWiring Pro** is a comprehensive web-based software platform designed to automate the planning and optimization of electrical wiring systems and solar integration for buildings. Tailored especially for small and medium-sized structures in India, the tool enables users to:

- Parse building blueprints
- Calculate power load per room
- Recommend wire gauges & circuit protection
- Suggest energy-efficient appliances & smart devices
- Integrate solar power systems with ROI estimations

---

## 🧠 Problem Statement

Many buildings in India are constructed without structured electrical blueprints. This leads to:

- ❌ Poor maintenance & troubleshooting
- ⚠️ Safety risks due to wrong wire sizing
- 🔌 Difficulty in adding smart home devices
- ☀️ Lack of guidance in solar energy adoption
- 💰 High upfront costs & complex planning

---

## ✅ Solution Summary

SmartWiring Pro solves these challenges with an AI-powered tool that offers:

- 🏠 Custom wiring layouts based on uploaded blueprints
- ⚙️ Wire gauge optimization & circuit protection suggestions
- 💡 Energy-efficient appliance recommendations
- 🌞 Solar system design with ROI & cost estimation
- 📊 Room-wise and floor-wise report generation

---

## 🔧 Key Features

### 📐 House Blueprint Input
- Uploads support: `DXF`, `SVG`, `PDF`, AutoCAD, Revit
- AI parses floor plans, identifies rooms, extracts dimensions

### 🔌 Power Load Calculation
- Input: Device list per room (e.g., lights, fans, ACs)
- Output: Wattage per room & cumulative power load

### 🔩 Wire Gauge Optimization
- Calculates proper wire size (e.g., 2.5mm², 4mm²)
- Recommends fuses & circuit breakers for safety

### 💡 Energy-Efficient Suggestions
- Suggests LED lighting and energy-star appliances
- Recommends IoT smart devices (e.g., motion lights, plugs)

### ☀️ Solar Power Integration
- Accepts roof dimensions & tilt
- Estimates optimal solar panel size (kW)
- Calculates cost, ROI, and payback period using regional irradiance data

### 🧾 Report Generator
- Exports:
  - Wiring layouts (PDF/DXF)
  - Appliance load reports
  - Solar energy reports

### 🖥️ Dashboard & Interface
- Real-time blueprint editing with drag-and-drop UI
- Interactive power and wire calculation
- Mobile-friendly with cross-platform sync

---

## 🖼️ Sample User Flow

```mermaid
graph TD
A[Start] --> B[Upload Floor Plan / Input Room Details]
B --> C[Add Appliance Info Per Room]
C --> D[Auto Load & Wire Calculation]
D --> E[Get Electrical Layout + Circuit Protection]
E --> F[Enter Roof Info (Optional)]
F --> G[Receive Solar Design + ROI Report]
G --> H[Export Final Reports & Layouts]
