# Amusement Park Digital Payment and Ticketing System

## Project Estimation

This document provides an estimation of the effort, timeline, required personnel, and total cost for the development of the **Amusement Park Digital Payment and Ticketing System**.

### **Estimation Parameters**

The estimations are based on the following parameters:

- **EAF (Effort Adjustment Factor)** = 1.20 - based on semi-detached category
- **KLOC (Estimated Thousands of Lines of Code)** = 50 - breakdown below
- **Salary per Developer** = Rs 20,000 per month
- **Constants for Effort Calculation for semi-detached:**
  - a1 = 3.2
  - b1 = 1.12
- **Constants for Development Time Calculation for semi detached:**
  - a2 = 2.5
  - b2 = 0.35

---

### **1. Estimated KLOC Breakdown**

| Module                              | Estimated KLOC   |
| ----------------------------------- | ---------------- |
| Frontend (React, HTML, CSS, JS)     | 10 – 15 KLOC     |
| Backend (Java, .NET, or Python API) | 15 – 20 KLOC     |
| Database & ORM Queries (SQL, NoSQL) | 3 – 5 KLOC       |
| Payment Integration & QR Code       | 5 – 8 KLOC       |
| Admin & Analytics Dashboard         | 8 – 12 KLOC      |
| **Total Estimate**                  | **40 – 60 KLOC** |

---

### **2. Effort Calculation**

**Formula:**

$$
Effort = EAF \times a1 \times (KLOC)^{b1}
$$

**Substituting values:**

$$
Effort = 1.20 \times 3.2 \times (50)^{1.12}
$$

$$
Effort = 1.20 \times 3.2 \times 64.62
$$

$$
Effort \approx 248.57 \text{ person-months}
$$

---

### **3. Development Time (TDEV) Calculation**

**Formula:**

$$
TDEV = a2 \times (Effort)^{b2}
$$

**Substituting values:**

$$
TDEV = 2.5 \times (248.57)^{0.35}
$$

$$
TDEV = 2.5 \times 8.75
$$
P
$$
TDEV \approx 21.88 \text{ months}
$$

---

### **4. People Required Calculation**

**Formula:**

$$
People \ Required = \frac{TDEV}{Effort}
$$

**Substituting values:**

$$
People \ Required = \frac{21.88}{248.57}
$$

$$
People \ Required \approx 8.8 \approx 9 \text{ developers}
$$

---

### **5. Total Cost Calculation**

**Formula:**

$$
Total Cost = People \ Required \times Salary \ per \ Developer \times TDEV
$$

**Substituting values:**

$$
Total Cost = 9 \times 20,000 \times 21.88
$$

$$
Total Cost \approx 3,938,400
$$

---

### **6. COCOMO Model Parameters for Different Project Types**

| Project Type  | a₁ (Effort) | b₁ (Effort Exponent) | a₂ (TDEV Coefficient) | b₂ (TDEV Exponent) |
| ------------- | ----------- | -------------------- | --------------------- | ------------------ |
| Organic       | 2.4         | 1.05                 | 2.5                   | 0.38               |
| Semi-Detached | 3.0         | 1.12                 | 2.5                   | 0.35               |
| Embedded      | 3.6         | 1.20                 | 2.5                   | 0.32               |

---

### **7. Project Type Characteristics**

| Project Type      | Characteristics                                           |
| ----------------- | --------------------------------------------------------- |
| **Organic**       | - Small, simple projects                                  |
|                   | - Small development team                                  |
|                   | - Well-understood requirements                            |
|                   | - Example: Payroll system, small inventory software       |
| **Semi-Detached** | - Medium complexity                                       |
|                   | - Larger team with mixed experience                       |
|                   | - Some requirements may change                            |
|                   | - Example: Database management system, compiler           |
| **Embedded**      | - Highly complex, real-time systems                       |
|                   | - Hardware/software constraints                           |
|                   | - Stringent requirements & regulations                    |
|                   | - Example: Spacecraft software, real-time medical systems |

---

## **Final Estimation Summary**

- **Effort Required:** 248.57 person-months
- **Development Time:** \~22 months
- **Team Size:** 9 developers
- **Total Project Cost:** **\Rs 3,938,400**


### 🚀 Developed by **Ehsaas Chaudhary**
