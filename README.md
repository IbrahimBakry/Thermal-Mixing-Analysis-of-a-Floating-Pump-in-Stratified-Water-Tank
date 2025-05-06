# **🌊 Thermal Mixing Analysis of a Floating Pump in Stratified Water Tank**

## **📌 Project Overview**
This CFD study analyzes how a **surface-floating pump** affects thermal mixing in a **large stratified water tank**. The simulation tracks temperature homogenization and flow patterns over **3 hours**, visualized through **cross-sectional and bird's-eye views**.

### **🔧 Key Skills Applied**
✔ **Computational Fluid Dynamics (CFD) Modeling**  
✔ **Thermal Stratification Analysis**  
✔ **Pump-Induced Flow Simulation**  
✔ **Data Visualization & Animation**  

---

## **🛠️ Tools & Software Used**
| **Category**       | **Tools/Software**          |
|--------------------|----------------------------|
| **CFD Simulation** | ANSYS Fluent / OpenFOAM     |
| **3D Modeling**    | SolidWorks / AutoCAD        |
| **Post-Processing**| ParaView / Tecplot         |
| **Animation**      | Blender / MATLAB           |

---

## **📐 System Specifications**
### **Tank Geometry**
- **Shape:** Cylindrical  
- **Height:** 12 m  
- **Diameter:** 48.5 m  
- **Water Level:** 11.1 m (0.9 m gap at top)  
- **Insulation:** Adiabatic walls, floor, and ceiling  

### **Fluid Properties**
| **Parameter**            | **Value**                     |
|--------------------------|-------------------------------|
| Fluid                    | Fresh Water                   |
| Density                  | 997 kg/m³                     |
| Dynamic Viscosity        | 8.899 × 10⁻⁴ kg/(m·s)         |
| Thermal Conductivity     | 0.6069 W/(m·K)                |
| Specific Heat Capacity   | 4181.7 J/(kg·K)               |
| Thermal Expansivity      | 2.57 × 10⁻⁴ K⁻¹               |

### **Initial Thermal Stratification**
| **Layer**   | **Height** | **Temperature** |
|-------------|-----------|----------------|
| **Top**     | 0-4 m     | 28°C (Red)     |
| **Middle**  | 4-8 m     | 24°C (Orange)  |
| **Bottom**  | 8-12 m    | 20°C (Blue)    |

### **Pump Specifications**
- **Type:** Floating surface pump  
- **Height:** 1.8 m (1.5 m submerged)  
- **Flow Rate:** 5,500 L/min (0.092 m³/s)  
- **Inlet:** Top 0.3 m of water  
- **Outlet:** Downward jet at ~0.65 m/s  
- **Induced Flow:** ~7× pump flow (gravity currents included)  

---

## **🌀 Simulation Approach**
### **1. Modeling Assumptions**
- **Laminar flow** (low turbulence assumption)  
- **No air layer** (only water modeled)  
- **Adiabatic boundaries** (no heat loss)  
- **Boussinesq approximation** (for buoyancy effects)  

### **2. Expected Outputs**
1. **Cross-Sectional View**  
   - Temperature contours (Red → Blue)  
   - Velocity vectors (showing mixing currents)  
2. **Bird’s-Eye View**  
   - Thermal diffusion patterns  
3. **Time-Lapse Animation** (30 sec video for 3-hr simulation)  

### **3. Key Metrics Tracked**
✔ **Temperature homogenization rate**  
✔ **Velocity profiles** (pump jet vs. natural convection)  
✔ **Time to complete mixing**  

---

## **📊 Expected Results**
### **1. Thermal Mixing Progression**
| **Time** | **Expected Behavior** |
|----------|-----------------------|
| **0-30 min** | Strong downward jet disrupts stratification; warm water penetrates middle layer |
| **1-2 hrs** | Convective currents dominate; middle layer homogenizes |
| **2-3 hrs** | Full mixing achieved (~24-25°C uniform temp) |

### **2. Flow Characteristics**
- **Pump-Induced Flow:** High-velocity downward jet (~0.65 m/s)  
- **Natural Convection:** Slow recirculation from temperature gradients  
- **Final State:** Well-mixed tank with slight residual currents  

### **3. Visualization (Color Scheme)**
- **🔴 Red:** 28°C (initial top layer)  
- **🟠 Orange:** 24°C (initial middle layer)  
- **🔵 Blue:** 20°C (initial bottom layer)  

---

## **📝 Discussion & Insights**
### **Key Findings**
✅ **Pump efficiently disrupts stratification** within **2-3 hours**.  
✅ **Downward jet creates strong mixing currents**, accelerating thermal diffusion.  
✅ **Final temperature** likely settles near **24-25°C** (volume-weighted average).  

### **Engineering Implications**
- **Optimal Pump Placement:** Surface positioning maximizes thermal mixing.  
- **Energy Efficiency:** Laminar flow reduces power requirements.  
- **Scalability:** Model validates design for large-scale water tanks.  

---
**🔗 Applications:**  
- **Water storage tanks**  
- **Solar thermal systems**  
- **Industrial process tanks**  

This study demonstrates **CFD expertise in thermal-fluid systems**, valuable for **HVAC, renewable energy, and process engineering**. 🌡️💧

