# COCOMO Model: Software Cost Estimation

## **1. User Story**
A **User Story** is a short, simple description of a feature or functionality from the perspective of an end user. It is commonly used in **Agile Development** to define what needs to be built.

### **Format:**
_"As a [type of user], I want [some feature] so that [benefit]."_

### **Example:**
_"As a customer, I want to reset my password so that I can regain access to my account if I forget it."_

---

## **2. Estimation**
**Estimation** refers to predicting the effort, time, and resources required to complete a project or task.

### **Common Estimation Techniques:**
- **Story Points** (Agile projects)
- **Time-based (Hours, Days, Weeks)**
- **Function Point Analysis (FPA)**
- **COCOMO Model** (for software effort estimation)

---

## **3. Budget**
The **Budget** of a project is the total amount of money allocated to complete the project. It includes:
- Development costs
- Resource costs (workforce, tools, etc.)
- Maintenance costs
- Overhead expenses (office, utilities, etc.)

### **Budget Planning:** Ensures the project stays financially viable.

---

## **4. Duration of Project**
**Duration** refers to the total time required to complete the project from start to finish. It depends on:
- Complexity of the project
- Availability of resources
- Workforce efficiency
- Dependencies and risks

### **Measured in:** Days, Weeks, Months, or Years.

---

## **5. Workforce Needed**
The **Workforce Needed** refers to the number of developers, testers, designers, project managers, and other personnel required to complete the project.

### **Factors Affecting Workforce:**
- Project complexity
- Skills required
- Timeline constraints
- Budget availability

---

# **6. COCOMO Model (Constructive Cost Model)**
COCOMO is a **software cost estimation model** developed by Barry Boehm that estimates:
- **Effort (in Person-Months)**
- **Development Time (TDEV)**
- **Cost**
- **Workforce Requirements**

## **Key COCOMO Formulas**

### **1. Effort (E) in Person-Months (PM)**
```
E = EAF × a₁ × (KLOC) ^ b₁
```
- **EAF (Effort Adjustment Factor)** = Adjusts effort based on project complexity.
- **a₁, b₁** = COCOMO constants depending on the project type.
- **KLOC** = Size of the project in **Kilo Lines of Code** (thousands of lines).

### **2. Development Time (TDEV) in Months**
```
TDEV = a₂ × (Effort) ^ b₂
```

### **3. Number of Persons Required**
```
People Required = Effort / TDEV
```

### **4. Cost Calculation**
```
Total Cost = Effort × Cost per Person-Month
```

---

## **7. COCOMO Model Parameters for Different Project Types**
| **Project Type** | **a₁ (Effort)** | **b₁ (Effort Exponent)** | **a₂ (TDEV Coefficient)** | **b₂ (TDEV Exponent)** |
|----------------|--------------|------------------|------------------|------------------|
| **Organic** | 2.4 | 1.05 | 2.5 | 0.38 |
| **Semi-Detached** | 3.0 | 1.12 | 2.5 | 0.35 |
| **Embedded** | 3.6 | 1.20 | 2.5 | 0.32 |

---

## **8. Use of EAF in Effort Calculation**

### **Revised Effort Formula (with EAF)**
```
E = EAF × a₁ × (KLOC) ^ b₁
```

### **How is EAF Calculated?**
The **EAF** is derived from **15 cost drivers** grouped into four categories:
1. **Product Attributes** (e.g., complexity, reliability)
2. **Hardware Attributes** (e.g., memory constraints, response time)
3. **Personnel Attributes** (e.g., team experience, capability)
4. **Project Attributes** (e.g., development tools, schedules)

Each cost driver has a rating (Very Low to Extra High), and the corresponding multiplier values are multiplied together to compute the final **EAF**:
```
EAF = (Multiplication of all cost driver multipliers)
```

### **EAF Value Range**
- Typically ranges between **0.9** (less effort) to **1.4+** (more effort).

---

## **9. Example Calculation (Including EAF)**
Let's consider an **Organic** project with:
- **KLOC = 10**
- **EAF = 1.2** (due to moderate complexity)
- **a₁ = 2.4**, **b₁ = 1.05** (for Organic projects)

### **Step 1: Calculate Effort with EAF**
```
E = 1.2 × 2.4 × (10) ^ 1.05
```
```
E = 1.2 × 2.4 × 10.99
```
```
E = 1.2 × 26.38
```
```
E = 31.66 Person-Months
```
This means the project will require **31.66 PM** instead of **26.38 PM** due to the **EAF impact**.

---

### **Key Takeaways**
- **EAF adjusts the effort** required based on project complexity, team experience, and other factors.
- **Higher EAF → More effort required** (e.g., complex projects, inexperienced teams).
- **Lower EAF → Less effort required** (e.g., skilled teams, well-defined requirements).
- **Without EAF, the model assumes an average project difficulty**.

---

### **COCOMO Project Types Explained**
| **Project Type** | **Characteristics** |
|-----------------|--------------------|
| **Organic** | - Small, simple projects<br>- Small development team<br>- Well-understood requirements<br>- Example: Payroll system, small inventory software |
| **Semi-Detached** | - Medium complexity<br>- Larger team with mixed experience<br>- Some requirements may change<br>- Example: Database management system, compiler |
| **Embedded** | - Highly complex, real-time systems<br>- Hardware/software constraints<br>- Stringent requirements & regulations<br>- Example: Spacecraft software, real-time medical systems |

---
### 🚀 Developed by **Ehsaas Chaudhary**
