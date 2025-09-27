# Ex.No.4 – Scenario-Based Prompt Engineering Report  
**Experiment 4: Comparative Analysis, Experiential Perspective, Everyday Functioning, Universal Prompt Structures, Prompt Size Limitations**

---

### DATE: 27-09-2025
### REGISTER NUMBER: 212222060030

---

## Aim
To create, implement, and evaluate prompts for **five advanced prompt-engineering types**:  
1. Comparative Analysis Prompt  
2. Experiential Perspective Prompt  
3. Everyday Functioning Prompt  
4. Universal Prompt Structures  
5. Prompt Size Limitations  

The experiment involves applying these prompts to a **Unit-5 IoT automation scenario**, comparing outputs across AI tools, and evaluating them using a rubric-based method.

---

## Introduction
Prompt engineering is a critical skill in leveraging AI effectively. Properly crafted prompts enhance:

- **Clarity** – reducing ambiguity in outputs  
- **Depth** – enabling multi-step reasoning  
- **Structure** – facilitating tabular or stepwise presentation  
- **Relevance** – targeting specific audience needs  

This experiment demonstrates **how different prompt types shape model responses** and evaluates their practical applicability in a real-world industrial automation scenario.

---

## Scenario and Use Case

**Scenario**  
A manufacturing company aims to **reduce manual monitoring** and increase efficiency through **IoT-based automation**. Embedded controllers monitor equipment, predict failures, and optimize energy consumption.

**Main Objectives**  
- Increase production efficiency by **30%**  
- Reduce downtime through **predictive maintenance**  
- Enable **real-time monitoring** of production lines  
- Optimize **energy usage** across systems

**Target Audience**  
Manufacturing companies, particularly in **automotive, electronics, and food processing** sectors where automation has high productivity impact.

---
## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
## Prompt Design & Examples

### 1️⃣ Comparative Analysis Prompt
**Definition:** Requests a comparison of two or more concepts to highlight similarities and differences.

**Example Prompt:**  
`Compare IoT-based predictive maintenance and manual maintenance in manufacturing.`  

**Sample Output (LLM)**

| Aspect                 | IoT Predictive Maintenance           | Manual Maintenance                |
|------------------------|------------------------------------|----------------------------------|
| Monitoring Frequency   | Continuous, real-time data         | Periodic manual checks           |
| Downtime               | Minimal, predicted via analytics   | Reactive, often after breakdown  |
| Cost Efficiency        | Long-term savings                  | Short-term lower cost            |
| Human Dependency       | Low                                | High                             |

**Observations:**  
- Highly structured and easy to interpret  
- Facilitates informed decision-making for stakeholders

---

### 2️⃣ Experiential Perspective Prompt
**Definition:** Asks the model to respond from a **specific perspective**, such as a professional or end-user.

**Example Prompt:**  
`From a factory engineer’s perspective, describe benefits and challenges of implementing IoT predictive maintenance.`

**Sample Output:**  
**Benefits:** Reduced unplanned downtime, improved efficiency, better data-driven decisions.  
**Challenges:** High initial investment, employee training, cybersecurity risks.

**Observations:**  
- Adds human-centric reasoning  
- Produces actionable insights for real-world implementation

---

### 3️⃣ Everyday Functioning Prompt
**Definition:** Relates technology to **daily life or familiar applications**.

**Example Prompt:**  
`Explain how IoT automation in factories is similar to smart home devices.`

**Sample Output:**  
- Both use sensors and controllers to automate tasks  
- Send real-time alerts for anomalies  
- Allow remote control via dashboards or mobile apps

**Observations:**  
- Makes complex systems accessible to non-experts  
- Enhances audience understanding through relatable examples

---

### 4️⃣ Universal Prompt Structures
**Definition:** Standardized templates that work across multiple tasks or domains.

**Example Prompts:**  
- `Explain predictive maintenance in simple terms with a real-life example.`  
- `Describe the process of installing IoT sensors step by step.`  

**Sample Output (Stepwise)**  
1. Identify critical machinery  
2. Install sensors and connect to the network  
3. Configure monitoring dashboards  
4. Collect and analyze data  
5. Trigger alerts for anomalies  

**Observations:**  
- Ensures consistent output format  
- Reduces variability between different AI tools

---

### 5️⃣ Prompt Size Limitations
**Definition:** Adjusts large requests to comply with AI model token limits.

**Example Prompt:**  
`List 50 IoT applications in manufacturing.`  
- Refined prompt: `List 10 IoT applications at a time until 50 are complete.`

**Sample Output (First 10):**  
- Machine health tracking  
- Energy optimization  
- Automated quality control  
- Inventory management  
- Robot-assisted assembly  
- Environmental monitoring  
- Predictive maintenance  
- Equipment scheduling  
- Supply chain tracking  
- Worker safety monitoring  

**Observations:**  
- Prevents token overflow  
- Facilitates stepwise generation for large datasets

---

## AI Tool Comparison

| Prompt Type                  | GPT-4        | Claude        | Bard         | Observations                                      |
|-------------------------------|--------------|---------------|-------------|--------------------------------------------------|
| Comparative Analysis          | Detailed     | Slightly brief| Clear       | GPT-4 gives most structured tables              |
| Experiential Perspective      | Rich context | Concise       | Moderate    | GPT-4 provides deeper scenario reasoning        |
| Everyday Functioning          | Simple       | Simple        | Informative | All tools perform similarly for layman examples|
| Universal Prompt Structures   | Consistent   | Slightly variable | Consistent | GPT-4 slightly better at stepwise instructions |
| Prompt Size Limitations       | Excellent    | Good          | Moderate    | GPT-4 handles chunked prompts efficiently      |

**Insights:**  
- GPT-4 consistently produces **structured, detailed, and reliable outputs**  
- Claude and Bard are adequate for **general explanations**  
- Chunking large prompts is essential for all tools

---

## Evaluation Method
**Rubric Scoring (8 Points)**

| Criterion              | Max | Score | Notes                                         |
|------------------------|----:|------:|-----------------------------------------------|
| Relevance             | 2   | 2     | All prompts matched the industrial scenario   |
| Clarity               | 2   | 2     | Outputs were understandable and organized     |
| Creativity            | 2   | 1     | Could include more innovative comparisons     |
| Completeness          | 2   | 2     | Covered all prompt types effectively          |

**Total:** 7/8 → Excellent performance with minor room for enhancement

---

## Process Flow Diagram

```mermaid
flowchart TD
    A[Define Scenario & Objectives] --> B[Design Prompts for Each Type]
    B --> C[Execute Prompts Across AI Tools]
    C --> D[Compare & Analyze Outputs]
    D --> E[Evaluate Using Rubric]
    E --> F[Refine Prompts if Needed]
