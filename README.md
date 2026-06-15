# IT System and Data Classification Policy
Created by: Abraham Ampong
![Effective Date](https://img.shields.io/badge/Effective%20Date-07%2F01%2F2025-blue)
![Version](https://img.shields.io/badge/Version-5.0-green)
![Compliance](https://img.shields.io/badge/Compliance-SEC501-orange)

## 📌 Purpose
The purpose of this policy is to create a prescriptive set of processes and procedures, aligned with applicable COV IT security policy and standards, to ensure that **Abraham IT Consult (AITC)** develops, disseminates, and updates the IT System and Data Classification Policy. 

This policy and procedure establish the minimum requirements for the IT System and Data Classification Policy and are intended to meet the requirements outlined in **SEC501, Section 4 (IT System and Data Sensitivity Classification)**.

## 👥 Scope
This policy applies to all **Abraham IT Consult** employees (including classified, hourly, or business partners) as well as all sensitive Abraham IT Consult systems.

## 🔤 Acronyms
| Acronym | Definition |
| :--- | :--- |
| **AITC** | Abraham IT Consult |
| **CIO** | Chief Information Officer |
| **CSRM** | Commonwealth Security and Risk Management |
| **HIPAA** | Health Insurance Portability and Accountability Act |
| **IRS** | Internal Revenue Service |
| **ISO** | Information Security Officer |
| **IT** | Information Technology |
| **ITRM** | Information Technology Resource Management |
| **PCI** | Payment Card Industry |
| **SEC501** | Information Security Standard 501 |

## 📖 Background
The IT System and Data Classification Policy at Abraham IT Consult is intended to facilitate the effective implementation of the processes necessary to meet the IT System and Data Sensitivity Classification requirements and security best practices. This policy directs that Abraham IT Consult meet these requirements for all sensitive IT systems.

## 👔 Roles & Responsibility

The matrix below outlines four levels of activity participation:
* 🔵 **Responsible (R)** – The person working on the activity.
* 🟢 **Accountable (A)** – The person with decision authority and the one who delegates the work.
* 🟡 **Consulted (C)** – Key stakeholders or subject matter experts who should be included in decisions or work activity.
* 🟣 **Informed (I)** – The person who needs to know of decisions or actions.

### Roles & Responsibility Matrix (RACI)

| Tasks | Agency Head | Information Security Officer | Data Owner | System Administrator | System Owner |
| :--- | :---: | :---: | :---: | :---: | :---: |
| Identify the types of data handled by each system | I | C | A | R | I |
| Determine whether the type of data is subject to regulatory requirements | | C | A/R | | I |
| Classify sensitivity of data | I | C | A/R | | I |
| Obtain approval of classification | R | C | A | | |
| Verify all systems are classified | | A | R | R | R |
| Communicate classifications | I | R | A | I | I |
| Prohibit posting of sensitive data on publicly accessible medium | I | A | R | R | |
| Require encryption | | A | R | R | R |
| Document each sensitive IT system | | I | I | R | A |
| Assign a system owner, data owner, and system administrator to each sensitive system | A | R | I | I | I |
| Update network diagrams | | A | | R | |

---

## 📜 Statement of Policy
In accordance with **SEC501**, Abraham IT Consult shall identify any sensitive data where a compromise with respect to confidentiality, integrity, and/or availability could have a material adverse effect on Abraham IT Consult, the conduct of Abraham IT Consult programs, or the privacy to which individuals are entitled.

Data sensitivity is directly proportional to the materiality of a compromise of the data with respect to these criteria. Abraham IT Consult must classify each IT system by sensitivity according to the most sensitive data that the IT system handles, stores, processes, transmits, etc.

---

## ⚙️ IT System and Data Classification
Abraham IT Consult’s Information Security Officer (ISO) will execute or oversee the following tasks:

1. **Business Impact Analysis Integration**
   * Use the results of Abraham IT Consult’s Business Impact Analysis as a primary input to classifying the sensitivity of Abraham IT Consult’s IT systems and data.

2. **Data Identification**
   * Identify or require that the Data Owner identify the type(s) of data handled by each Abraham IT Consult IT system.

3. **Regulatory Mapping**
   * Determine or require that the Data Owner determine whether each type of data is also subject to other regulatory requirements.
   * *Examples:* Some AITC IT systems may handle data subject to legal or business requirements such as:
     * Health Insurance Portability and Accountability Act of 1996 (**HIPAA**)
     * **IRS 1075**
     * The **Privacy Act of 1974**
     * Payment Card Industry (**PCI**)
     * The **Rehabilitation Act of 1973, § 508**
     * **Federal National Security Standards**, etc.

4. **Damage & Sensitivity Assessment**
   * Determine or require that the Data Owner determine the potential damages to the agency of a compromise of confidentiality, integrity, or availability of each type of data handled by the IT system and classify the sensitivity of the data accordingly:
     * **Confidentiality:** Addresses sensitivity to unauthorized disclosure.
     * **Integrity:** Addresses sensitivity to unauthorized modification.
     * **Availability:** Addresses sensitivity to outages.

   > 💡 **Example:** Data Owners should construct a table similar to the following illustration to classify sensitivity requirements of all data types.

#### Sensitivity Analysis Results (System ID: ABC123)
| Type of Data | Confidentiality | Integrity | Availability |
| :--- | :---: | :---: | :---: |
| **HR Policies** | Low | High | Moderate |
| **Medical Records** | High | High | High |
| **Criminal Records** | High | High | High |

5. **Sensitivity Classification Rules**
   * Classify the IT system as **sensitive** if any type of data transmitted, stored, or processed by the IT system has a sensitivity of **High** on any of the criteria of confidentiality, integrity, or availability.
   * 📝 *Note:* The ISO and/or Data Owner should consider classifying IT systems as sensitive even if a type of data handled has a sensitivity of **Moderate** across all criteria, based on the materiality of a potential compromise.

6. **Approvals & Validation**
   * Review IT system and data classifications with the ISO or designee, and obtain Agency Head or designee approval of these classifications.
   * Verify and validate that all agency IT systems and data have been classified for sensitivity.

7. **Communication & Restrictions**
   * Communicate approved IT system and data classifications to System Owners, Data Owners, and end-users.
   * Prohibit posting any data classified as sensitive with respect to confidentiality on a public website, FTP server, drive share, bulletin board, or any other publicly accessible medium.
     * *Exception:* A written exception must be approved by the Agency Head identifying the business case, risks, mitigating logical and physical controls, and any residual risk.

8. **Technical Controls**
   * Require encryption during transmission of data that is sensitive relative to confidentiality or integrity.
   * Use the information documented in the sensitivity classification as a primary input to the Risk Assessment process.

9. **System Documentation & Administration**
   * Document each sensitive IT system owned by Abraham IT Consult, including its ownership and boundaries, and update the documentation as changes occur.
   * Assign a System Owner, Data Owner(s), and System Administrator(s) for each sensitive IT system.
     * 📝 *Note:* A sensitive IT system may have multiple Data Owners and/or System Administrators, but **must have a single System Owner**.
   * Maintain or cause its business partner to update network diagrams.

### 🤝 Interconnection Security Agreements (ISA)
As part of the documentation of each sensitive IT system owned by Abraham IT Consult, develop Interconnection Security Agreements with other IT systems with which the sensitive system interconnects or shares data. These agreements must include, but are not limited to:
- [ ] **Data Types:** The types of shared data.
- [ ] **Data Flow:** The direction(s) of data flow.
- [ ] **Contact Information:** Full contact details for the organization owning the interconnected system (including System Owner, ISO/equivalent, and System Administrator).
- [ ] **Security Requirements:** IT security requirements for each interconnected system and type of data shared.
- [ ] **Downstream Interconnections:** Other systems with which the IT systems interconnect or share data.
- [ ] **Change Notification:** A requirement that System Owners inform one another prior to establishing any additional interconnections or data sharing.
- [ ] **Storage Specifications:** Specifications regarding if and how the shared data will be stored on each system.
- [ ] **Legal Compliance:** Specifications that System Owners acknowledge and agree to abide by all legal requirements (e.g., HIPAA) regarding handling, protecting, and disclosing shared data.
- [ ] **Access Authorization:** Each Data Owner’s authority to approve access to the shared data.
- [ ] **Enforcement:** Each System Owner’s responsibility to enforce the agreement.
- [ ] **Sign-off:** Approval of the agreement by each System Owner.

---

## 🔗 Associated Procedures & References

### Associated Procedures
* **Abraham IT Consult Information Security Program Policy**

### Authority Reference
* **Powers and duties of the Chief Information Officer (CIO)**, Abraham IT Consult

### Other References
* **ITRM Information Security Policy (SEC519)**
* **ITRM Information Security Standard (SEC501)**

---

## ⏳ Version History

| Version | Date | Change Summary |
| :---: | :---: | :--- |
| **1** | 09/28/2007 | Original document. Establishes requirements for the classification of IT systems and data according to their sensitivity with respect to Confidentiality, Integrity, and Availability. |
| **2** | 01/22/2009 | Updated “Sensitivity” definition. Under Statement of Procedure clarified Item 9, added Item 10, and re-numbered subsequent items. |
| **4** | 07/01/2014 | Name changed and updated to conform to Information Security Standard SEC501 revision 8. Role matrix added. |
| **5** | 11/22/2021 | Formatting changes. |
