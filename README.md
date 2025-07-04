# IWEBBS Gap Assessment Tool — NIST 800-171 Gap Assessment Platform

## Key Definitions

| Term | Definition |
|------|------------|
| **Customer Record** | Profile containing organization details, contact information, and historical assessment data. |
| **Assessment** | A full set of binary-response questions aligned with the 14 control families in NIST 800-171. |
| **Control Family** | One of 14 NIST-defined areas that group related security requirements. |
| **Engineer** | Technical personnel assigned to review, validate, or revise recorded inputs. |
| **Score** | A numerical indicator based on assessment responses, categorized by control family. |
| **Status** | Indicates current phase of an assessment (e.g., Not Started, In Progress, Completed). |
| **Evaluation Graph** | Bar chart displaying per-family scores derived from user input. |

## Introduction

The IWEBBS Gap Assessment Tool provides a structured interface for completing evaluations based on NIST SP 800-171. Users within an organization answer binary questions across all 14 control families. These inputs are tied to specific controls, recorded to user accounts, and used to calculate scores.

The tool captures assessment progress, tracks response history, and aggregates results in a chart format for review. It functions as both a data collection system and a reference point for internal review cycles or external audit preparation.

<img src="https://i.imgur.com/iLXSvoy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


## What is NIST SP 800-171?

NIST SP 800-171 is a federal framework that outlines technical and administrative safeguards for handling Controlled Unclassified Information (CUI). It is structured around 14 control families. Each family corresponds to a specific category of risk or responsibility.

Organizations working with federal agencies or regulated sectors are expected to implement these controls. Assessing against the framework allows teams to establish a documented record of where each control stands.

## Purpose of the IWEBBS Gap Assessment Tool

The tool consolidates all assessment activities into one system. Each control is presented as a yes/no item. Entries are user-attributed and time-stamped. Inputs are automatically factored into control family scores. Users can revise entries at any time until completion.

Multiple users may participate in the same assessment without data conflict. Each user’s activity is logged. Previous input remains accessible, and changes are versioned. The tool outputs a chart that summarizes control family results, offering a reference for remediation planning.

## How the Platform Works (Step-by-Step)

### Step 1: Add Customer Information
Create a new customer profile. This profile stores the organization’s contact information and serves as the central record for all assessment data.


<img src="https://i.imgur.com/iLXSvoy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


### Step 2: Launch an Assessment
The system includes all 14 control families. Each control is represented by a yes/no field. Customers complete fields in any order. Each response is logged with user metadata.


<img src="https://i.imgur.com/gdd4wSL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


### Step 3: Provide Organizational Input
Client answers based on current configurations or policy. Each entry updates the corresponding control score. Progress is tracked per control family.


<img src="https://i.imgur.com/vKI2Z5k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



### Step 4: Review Evaluation Graph and Scores
The system compiles control family scores based on responses. These are shown in a bar graph. The chart reflects partial and complete implementation levels. This visual summary is available throughout and after the assessment process.


<img src="https://i.imgur.com/pdQ69NB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


## Practical Use Cases

### Small and Midsize Businesses
Use the tool to verify compliance status and maintain a local record of implementation.

### Managed Security Service Providers (MSSPs)
Maintain distinct profiles per client. Track assessments across multiple organizations.

### Internal Compliance and GRC Teams
Coordinate cross-departmental input while maintaining a shared system of record.

### Independent Cybersecurity Consultants
Structure discovery sessions and consolidate findings for delivery.

## User Interface Design

The interface displays control families in a sequential layout. Each question uses binary input. Sections may be completed in any order. Progress is indicated numerically.

Changes are saved automatically. User identity and timestamps are attached to each input. The evaluation graph updates continuously as responses change.

## Why Organizations Use the IWEBBS Gap Assessment Tool

All required NIST control areas are included. Input is stored with history and attribution. No external spreadsheets or scoring formulas are needed. Users can see their impact on scores immediately.

Concurrent input is supported. Each entry is preserved without conflict. Graphical summaries require no configuration.

Results can be reviewed, exported, or used for planning. Full audit trace is preserved for all activity.

## Solution Development Support

Following completion of the assessment, the IWEBBS team can use the recorded data to develop implementation guidance. The IWEBBS team can use the evaluation data to build tailored implementation plans.

Each control family score and its corresponding responses provide a direct input into planning tasks, such as policy creation, technical configuration, training plans, or documentation updates. This ensures that any recommended solution aligns directly with identified gaps and reflects the organization’s current state.

The IWEBBS team can assist in:
- Translating unaddressed controls into actionable requirements
- Designing project timelines for remediation efforts
- Providing documentation packages for internal or external audits
- Recommending technologies or processes based on assessment results

All planning references the existing assessment data. No rework or duplicate data entry is needed. The recorded inputs serve as the baseline for all recommendations, reducing duplicate effort.

## Contact

**Email**: [support@iwebbs.com](mailto:support@iwebbs.com)  
**Website**: [https://iwebbs.com](https://iwebbs.com)# IWEBBS-GAP-ASSESSMENT-TOOL
