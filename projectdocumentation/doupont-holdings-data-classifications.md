# Doupont Holdings LLC - Data Classification Policy

## Purpose of this Document
This document serves the singular purpose of outlining comprehensive guidelines for classifying data that undergoes processing and/or storage within the purview of Doupont Holdings LLC, hereinafter referred to as "DHLLC." The meticulous categorization of all data under the aegis of DHLLC is imperative to ensure the preservation of sensitive information, mitigating the risk of unauthorized access and thereby averting potential harm to DHLLC's esteemed reputation and its clientele.

## Scope
These guidelines are applicable to all DHLLC personnel, both internal and external, including individuals or entities contracted by DHLLC for data processing, whether their involvement pertains to specific or unspecified data. Adherence to this policy is mandatory for any data that DHLLC stores or processes. Oversight of compliance with these regulations falls under the purview of DHLLC's Compliance Department, which retains the authority to conduct unscheduled internal audits at its discretion. In cases requiring external expertise, DHLLC's Compliance Department may engage external contractors. Violations of these compliance guidelines may result in penalties, termination of employment, or even legal actions initiated by DHLLC against the transgressor.

## Internal Responsible Entity
DHLLC's Compliance Department and DHLLC's Data Management Department collectively bear the responsibility of vigilantly overseeing all activities pertaining to DHLLC's customer and internal data. This comprehensive oversight encompasses both external contractors and internal employees. It is crucial to emphasize that any violations against the aforementioned policies will prompt immediate intervention by DHLLC's Compliance and Data Management Departments, without prior notice. The severity of the guideline violation will dictate the ensuing disciplinary actions.

## External Responsible Entity
All external entities and individuals contracted by DHLLC are strictly obligated to rigorously adhere to the aforementioned guidelines. Furthermore, they must be fully prepared to furnish a comprehensive report detailing their historical and ongoing work activities promptly upon request by either DHLLC's Compliance Department or DHLLC's Data Management Department.

It is imperative to emphasize that any breach of the compliance guidelines established by DHLLC will not only lead to reputational damage but also entail financial consequences for the external contractor. The nature and gravity of the guideline violation will determine the subsequent disciplinary actions taken.

## Data Classification Levels and Security Requirements
All data generated, stored, or processed by DHLLC must be categorized into one of the following classification levels:

**DHLLC1-D - PUBLIC**
- Data categorized at this level is deemed publicly accessible, granting unrestricted access to third parties and entities.
- Data falling within this classification may be stored on unencrypted storage media, unmanaged cloud environments, websites, or platforms of any nature.
- Geographical restrictions do not apply to the storage of data within DHLLC's private or public cloud environments.

**DHLLC2-D INTERNAL**
- Data classified at this level is designated as internal and is accessible to all internal and external employees contracted by DHLLC, provided they possess the requisite clearance. Data at this level may reference data at the ***DHLLC1-D - PUBLIC*** level, but it is essential to note that no content or data classified as ***DHLLC2-D INTERNAL*** should be present within the aforementioned data classification level.
- Data at this level may be stored within DHLLC's private and public cloud environments, provided that these environments meet the necessary security standards to ensure the data's safety. In the event of storage in a cloud environment, no separate encryption is required for this data. Alternatively, data of this level can also be stored on storage servers with access rights managed via the Active Directory.
- There are no geographical restrictions imposed on the storage of data within DHLLC's private/public cloud environments or on-premises storage solutions.

**DHLLC3-D - CONFIDENTIAL**
- Data at this level is restricted to specific internal personnel with the requisite data clearance, granting them access to view and modify data classified at the ***DHLLC3-D - CONFIDENTIAL*** level. It is crucial to note that the content of data classified as ***DHLLC3-D - CONFIDENTIAL*** should only exist within the same data classification level. While it can refer to data at a lower level, the reverse is not permissible.
- Users holding a ***DHLLC3-D*** data classification level clearance are granted unrestricted access to all data within lower data classification levels. They have the authority to modify, view, and share data with lower classification levels within the company, as long as these actions are justified.

On the other hand, users with ***DHLLC3-D CONFIDENTIAL*** clearance may also modify, view, and share data at the ***DHLLC3-D - CONFIDENTIAL*** level. However, for superusers at this clearance level, any such actions require prior approval. Approval can be obtained from their supervisor, the DHLLC's compliance department, DHLLC's data management department, or, alternatively, from at least three other superusers who hold the same data clearance level.
- Data classified as DHLLC3-D CONFIDENTIAL must be stored exclusively on servers located within Europe, with a preference for Switzerland. In the case of on-premises storage, the location must be securely situated within a confined space, offering protection against earthquakes, fires, and floods.

The rooms housing the storage servers must be fortified with a steel door measuring at least 30 centimeters in width but no more than 50 centimeters. Access to this door is strictly regulated, requiring a security card linked to the user's data clearance level, a fingerprint scan, and an 8-letter password. Furthermore, the door can only be opened by the simultaneous presence of two authorized personnel, acting as dual authentication keys, thereby ensuring an additional layer of security to prevent data theft via portable drives.
- Servers responsible for housing data classified as ***DHLLC3-D CONFIDENTIAL*** must undergo stringent security measures. Specifically, all ports on these servers must be meticulously closed, sealed, or rendered inoperable to prevent any possibility of external drives being inserted into the storage servers, thus ensuring the utmost protection of sensitive data.
- Additionally, the room must be designed with a sole exit, which is the steel door, and it must be fortified to eliminate any external electronic reception, ensuring the utmost security and confidentiality within the room.

User privileges within Doupont Holdings LLC are allocated in strict accordance with specific classification levels. This meticulous approach ensures that individuals can access only the data commensurate with their clearance and responsibilities at DHLLC, as stipulated in the data classification and security requirements.

## 2.2 Hierarchical Principle
- Data classified as DHLLC1-D, DHLLC2-D, or DHLLC3-D may coexist within data classified as DHLLC3-D.
- Data classified as DHLLC1-D or DHLLC2 may coexist within data classified as DHLLC2-D or DHLLC3-D.
- Data classified as DHLLC1-D may coexist within data classified as DHLLC1-D, DHLLC2, or DHLLC3-D.
- Consequently, individuals with DHLLC3-D security clearance have access to all DHLLC data across all classification levels.
- Individuals with DHLLC2-D security clearance have access to data classified as DHLLC1-D and DHLLC2-D

## Recovery Protection Level
In addition to the classification levels, all DHLLC data are assigned a recovery protection level indicating

 the extent of importance to which data objects should be protected against loss, damage, or misuse. Different measures are taken based on the assigned recovery protection level to ensure the guaranteed availability of data. The following recovery protection levels are defined:

**DHLLC-B1 - SIMPLE BACKUP**
- Data at this level should not undergo regular backups, yet it must still be subject to bi-monthly backup procedures. Although the loss of data at this classification level is considered acceptable, it is essential to maintain a corresponding backup for every piece of data held by DHLLC.

**DHLLC-B2 - ADVANCED BACKUP**
- Data at this level is subjected to a straightforward backup process. This process involves creating a duplicate of the targeted data object and storing it simultaneously in two data centers owned by DHLLC. The primary purpose of this backup is solely for data restoration in the event of accidental deletion or the failure of a storage device or a specific cloud resource.

**DHLLC-B3 - DISASTER RESISTANT BACKUP**
- Data designated with the backup level ***DHLLC-B3 - DISASTER RESISTANT BACKUP*** are of utmost importance to DHLLC's operational functionality and reputation. Consequently, it is imperative to establish comprehensive data backups dispersed across various regions and locations. 

The storage servers responsible for these backups must adhere to the rigorous security requirements detailed earlier, akin to the storage location criteria for data classified at the ***DHLLC3-D CONFIDENTIAL*** level.

Creating backups for these data objects must consistently align with the corresponding classification levels assigned to the data object. In cases where alignment is not feasible, the classification levels must take precedence.

## Format of Data Classification & Recover Protection Level
Data within our organizational ecosystem is systematically annotated with its designated classification level and recovery protection level. This labeling process is implemented through the application of metadata, and where feasible, incorporated directly within the data object itself.

These labels adhere to one of the specified formats:

1. `[Classification Level Abbreviation]-[Recovery Protection Level Abbreviation]`
2. `[Classification Level Abbreviation]-[Recovery Protection Level Abbreviation] // [Classification Level] - [Recovery Protection Level]`

To illustrate these formats further, consider the following examples:

- `DHLLC1-D-DHLLC-B1`
- `DHLLC1-D-DHLLC-B1 // PUBLIC - SIMPLE BACKUP`

These labeling conventions serve as a crucial component of our comprehensive data management strategy, ensuring clarity and precision in the identification and safeguarding of information assets.

## 4.2 Data Classification & Recovery Protection Level Assignment
DHLLC operates under the fundamental assumption that its workforce possesses the capability to autonomously and judiciously evaluate the precise classification tier and requisite level of recovery protection for any given data entity. When confronted with any form of ambiguity or uncertainty in this regard, the prevailing directive is to exercise prudence by categorizing the data at a heightened level. This act signifies a heightened acknowledgment of its sensitivity and consequential importance to the overall availability of information resources.

In the event of such uncertainties, DHLLC's personnel are strongly encouraged to proactively seek guidance and insights from various avenues within the organization. This includes the option to consult with a senior colleague, approach a superior within their hierarchical structure, or engage with DHLLC's dedicated Compliance Department or the specialized expertise offered by the DHLLC's Data Management Department. These resources serve as indispensable reservoirs of knowledge and support, facilitating well-informed decisions that align with the company's overarching data governance strategy.
