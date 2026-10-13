# 5kW Photovoltaic-Based EV Charging Power Stage

## 🎯 Project Overview
Designed and validated the power conversion stage for a 5kW solar PV-powered Electric Vehicle (EV) charging station. The primary focus was on achieving high efficiency, ensuring thermal reliability through rigorous Worst-Case Analysis (WCA), and optimizing the Bill of Materials (BOM) for commercial viability.

## ⚡ Key Engineering Achievements
- **Circuit Simulation (LTspice):** Modeled DC-DC converter switching stages, optimized inductor and capacitor ripple ratings, and evaluated MOSFET switching losses under variable solar irradiance inputs.
- **Worst-Case Analysis (<70% WCA Derating):** Enforced strict derating criteria. All semiconductor junction temperatures, voltage breakdown margins, and capacitor ripple currents were restricted to below 70% of their absolute maximum ratings to ensure long-term field reliability.
- **BOM Optimization:** Formulated a commercial-grade BOM utilizing high-reliability automotive/industrial grade passives, balancing component sourcing costs with safety derating guidelines.

## 🛠️ Technical Stack & Tools
- **Simulation:** LTspice XVII
- **Domain:** Power Electronics, DC-DC Converters, Renewable Energy Integration
- **Analysis:** Thermal Derating, Transient Response, Ripple Current Calculation

## 📂 Repository Structure
- `5kW_EV_Charger_Schematic.asc` - The main LTspice simulation file.
- `BOM_Optimization.xlsx` - Detailed Bill of Materials with component ratings and cost analysis.
- `Simulation_Waveforms/` - Folder containing screenshots of switching ripple, transient response, and thermal derating plots.

## 📸 Simulation Results
*(Add screenshots of your LTspice waveforms here - e.g., MOSFET Vds/Vgs, inductor current ripple, output voltage transient response)*

---
*Designed by Janaki Raman K | Hardware Validation & Power Electronics Engineer*
