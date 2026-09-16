# Prompt Engineering Portfolio

## Overview

This repository contains my **Prompt Engineering Portfolio**, developed as part of an academic assessment on **Introduction to Artificial Intelligence and Machine Learning**.

The portfolio demonstrates how prompts can be progressively refined from broad, generic instructions into precise, structured and evidence-aware instructions to produce more **accurate, actionable and hallucination-resistant AI outputs**.

The portfolio applies prompt engineering techniques to real-world management scenarios across four business functions:

* **Finance**
* **Marketing**
* **Human Resources (HR)**
* **Sales**

---

## Objective

The primary objective of this portfolio is to demonstrate the practical application of prompt engineering in business decision-making.

Each section follows a progression from simple prompts to highly specified prompts by gradually adding:

**Role → Context → Task → Constraints → Format → Evidence**

This progression demonstrates how additional information and constraints can improve the quality, relevance and reliability of AI-generated responses.

---

## Business Functions Covered

### 1. Finance

The Finance section demonstrates prompt engineering through scenarios involving financial analysis and business decisions, including:

* Break-even analysis
* Lease vs. buy decisions
* Capital budgeting
* Credit-risk screening
* Seasonal cash-flow risk

The prompts progressively introduce financial context, assumptions, constraints, calculations and structured decision outputs.

### 2. Marketing

The Marketing section uses a D2C fitness apparel brand launching a new moisture-wicking gym-wear line.

Key areas include:

* Campaign planning
* Target audience identification
* Budget allocation
* Content planning
* Marketing KPIs
* Competitor research
* Ethical marketing considerations
* Evidence verification

The section also demonstrates zero-shot and few-shot classification, prompt chaining and hallucination controls.

### 3. Human Resources

The HR section examines employee retention at a manufacturing company experiencing elevated attrition among production supervisors.

Key areas include:

* Employee retention
* Attrition analysis
* Exit-interview analysis
* Career progression
* Workload assessment
* Interview scorecards
* HR KPIs
* AI bias and fairness
* Retention planning

The prompts demonstrate how AI can be guided to distinguish between known facts, assumptions and recommendations.

### 4. Sales

The Sales section focuses on a medical consumables company experiencing declining direct-sales win rates and distributor reorder rates.

Key areas include:

* Sales conversion
* Win/loss analysis
* Distributor performance
* Customer objections
* Sales rebuttal scripts
* Sales KPIs
* Root-cause analysis
* Sales improvement planning
* Ethical incentive design

The section demonstrates how prompt refinement can help separate confirmed information from hypotheses and prevent unsupported business claims.

---

## Prompt Engineering Techniques Demonstrated

The portfolio demonstrates multiple prompting techniques, including:

| Technique                                  | Purpose                                                         |
| ------------------------------------------ | --------------------------------------------------------------- |
| Role Prompting                             | Gives the AI a specific professional perspective                |
| Context Prompting                          | Provides relevant business background                           |
| Data Grounding                             | Anchors responses to supplied facts and numbers                 |
| Constraint Prompting                       | Limits what the AI can recommend or assume                      |
| Structured Output                          | Controls the format of the response                             |
| Zero-Shot Prompting                        | Requests classification or generation without examples          |
| Few-Shot Prompting                         | Provides examples to guide the expected output                  |
| Facts vs. Assumptions                      | Separates known information from uncertain claims               |
| KPI Prompting                              | Converts recommendations into measurable indicators             |
| Risk & Ethics Prompting                    | Identifies potential risks and unintended consequences          |
| Prompt Chaining                            | Breaks complex problems into smaller sequential tasks           |
| Evidence Verification                      | Prevents unsupported benchmarks and factual claims              |
| Uncertainty Flagging                       | Makes limitations and assumptions explicit                      |
| Self-Critique                              | Requires the AI to identify weaknesses in its own response      |
| Iterative Refinement                       | Improves an existing prompt when new constraints are introduced |
| Audience-Specific Prompting                | Adapts outputs for different decision-makers                    |
| Combined R+C+T+Constraints+Format+Evidence | Integrates multiple prompting techniques                        |
| Hallucination Guarding                     | Prevents the AI from inventing missing information              |

---

## Overall Prompt Progression

The portfolio follows a consistent progression:

```text
Broad Prompt
     ↓
Domain
     ↓
Role
     ↓
Context
     ↓
Specific Data
     ↓
Output Format
     ↓
Constraints
     ↓
Evidence / Verification
     ↓
Advanced Prompting Techniques
     ↓
Prompt Chaining
     ↓
Self-Critique
     ↓
Final Production-Ready Prompt
```

This progression demonstrates that effective prompt engineering is not simply about asking an AI a question. It involves **providing the right context, defining the task, controlling assumptions, specifying the output and establishing evidence boundaries**.

---

## Hallucination Control

A major focus of the portfolio is reducing unsupported AI-generated information.

The prompts use techniques such as:

* Explicitly restricting the AI to provided information
* Asking the AI not to invent figures
* Separating facts from assumptions
* Requiring external benchmarks to be verified
* Flagging hypothetical findings
* Identifying uncertainty
* Avoiding unsupported competitor, salary or industry data
* Requiring human review for important business decisions

The final prompts therefore move beyond simply generating an answer and instead specify **what the AI should do when information is missing**.

For example:

> "If a required figure or fact was not provided, write 'Information not provided — requires verification.'"

This prevents the AI from filling information gaps with fabricated numbers or unsupported assumptions.

---

## Key Learning

The portfolio demonstrates that prompt quality strongly depends on the quality of instructions provided to the AI.

A broad instruction may produce a generic response, while a well-designed prompt can provide:

**Relevant context + clear task + constraints + structured output + evidence boundaries**

This makes AI outputs more useful for real-world management applications while maintaining appropriate human oversight.

---

## Repository Structure

```text
prompt-engineering-portfolio/
│
├── README.md
│
├── Finance/
│   └── Finance_Prompt_Engineering_Portfolio.docx
│
├── Marketing/
│   └── Marketing_Prompt_Engineering_Portfolio.docx
│
├── Human_Resources/
│   └── HR_Prompt_Engineering_Portfolio.docx
│
└── Sales/
    └── Sales_Prompt_Engineering_Portfolio.docx
```

*File names and folder structure can be adjusted to match the final uploaded documents.*

---

## Conclusion

This portfolio demonstrates the progression from **generic prompting to structured, evidence-aware prompt engineering** across four major management functions.

The final prompts are designed not only to generate useful outputs, but also to make assumptions visible, prevent unsupported claims and maintain human oversight over important business decisions.

---

## Academic Submission

**Course:** Introduction to Artificial Intelligence and Machine Learning
**Project:** Prompt Engineering Portfolio
**Focus:** Application of Prompt Engineering in Management Functions
