# Doupont Holdings LLC - Data Classification Policy

## Purpose of this Document
The purpose of this document is to establish guidelines for the classification of data processed and/or stored by Doupont Holdings LLC, hereinafter referred to as "DHLLC." The classification of all DHLLC data into specific categories ensures that sensitive information remains protected from unauthorized access, thereby preventing potential harm to DHLLC.

## Scope
This policy applies to all internal and external employees of DHLLC, as well as to individuals or entities contracted by DHLLC for data processing, whether for specific or unspecified data. Compliance with this policy is mandatory for all DHLLC data. DHLLC's Compliance Department is responsible for monitoring compliance and may involve external contractors in this process when necessary.

## Responsible Entity
The contracted firm, "IMAIM Institution," is responsible for overseeing the implementation of this policy and collaborates closely with DHLLC's Compliance Department.

## Data Classification Levels
All data generated, stored, or processed by DHLLC must be categorized into one of the following classification levels:

**DHLLC1-D - PUBLIC**
- Data at this level is considered publicly accessible. Any third parties or entities may have unrestricted access to data of this classification.
- Data of this level may be stored on unencrypted storage media, unmanaged cloud environments, websites, or platforms of any kind.
- No geographical restrictions apply to the storage of data in DHLLC's private or public cloud environments.

**DHLLC2-D - INTERNAL**
- Data at this level is considered internal and is accessible to all internal and external employees. Data at this level may reference data at the E1 level, but no content classified as E2 should be present in E1 data.
- Data at this level may be stored in DHLLC's managed private and public cloud environments, specifically in the "birdCloud" and "aapCloud." Data at this level does not require separate encryption within DHLLC's private or public cloud environments and may be shared through DHLLC's managed communication platforms.
- No geographical restrictions apply to the storage of data in DHLLC's private or public cloud environments.

**DHLLC3-D - CONFIDENTIAL**
- Data at this level is accessible to all internal employees. Data at this level may reference data at the E2 level, but no content classified as E3 should be present in E2 data.
- Data at this level may be stored in DHLLC's managed private and public cloud environments, specifically in the "birdCloud" and "aapCloud." Data at this level does not require separate encryption within DHLLC's private or public cloud environments and may be shared through DHLLC's managed communication platforms.
- Data at this level must be stored or processed exclusively within European data centers when placed in DHLLC's private or public cloud environments. Under no circumstances should data at this level be stored or processed in the United States.

## Access Rights


1. **DHLLC1-UR (User Rights for DHLLC1 - PUBLIC)**:
   - Users with DHLLC1-UR have the authority to access and interact with data classified as DHLLC1 - PUBLIC.
   - These user rights typically grant individuals the ability to view, download, and share publicly accessible data without restrictions.
   - DHLLC1-UR does not provide access to data classified at higher confidentiality levels (DHLLC2 or DHLLC3).

2. **DHLLC2-UR (User Rights for DHLLC2 - INTERNAL)**:
   - Users holding DHLLC2-UR have the privileges to access and manage data classified as DHLLC2 - INTERNAL.
   - These user rights may include permissions to collaborate, modify, and share data at the internal level.
   - Users with DHLLC2-UR can access DHLLC1-UR data as well, as DHLLC2 encompasses DHLLC1.

3. **DHLLC3-UR (User Rights for DHLLC3 - CONFIDENTIAL)**:
   - DHLLC3-UR provides access to the most sensitive data, classified as DHLLC3 - CONFIDENTIAL.
   - Users with DHLLC3-UR have comprehensive access, including the ability to view, edit, and share confidential information.
   - These user rights come with significant responsibilities and obligations to maintain data security and confidentiality.

User rights within Doupont Holdings LLC are granted according to the specific classification levels, ensuring that individuals can access only the data that aligns with their clearance and responsibilities as outlined in the data classification and user rights policies.

## 2.2 Hierarchical Principle
- Data classified as DHLLC1-D, DHLLC2-D, or DHLLC3-D may coexist within data classified as DHLLC3-D.
- Data classified as DHLLC1-D or DHLLC2 may coexist within data classified as DHLLC2-D or DHLLC3-D.
- Data classified as DHLLC1-D may coexist within data classified as DHLLC1-D, DHLLC2, or DHLLC3-D.
- Consequently, individuals with DHLLC3-UR security clearance have access to all DHLLC data across all classification levels.
- Individuals with DHLLC2-UR security clearance have access to data classified as DHLLC1-D and DHLLC2-D

## 3.1 Recovery Protection Level
In addition to classification levels, all DHLLC data are assigned a recovery protection level indicating the extent to which a data object should be protected against loss or damage. Different measures are taken based on the assigned recovery protection level to ensure the guaranteed availability of data. The following recovery protection levels are defined:

**DHLLC-B1 - NO BACKUP**
- Data at this level is not backed up. The loss of this data is acceptable, and data backup would involve disproportionate effort.

**DHLLC-B2 - SIMPLE BACKUP**
- Data at this level is backed up using a simple backup process. A copy of this data object is created and stored in the same environment. This backup is solely for restoring data in case of accidental deletion or failure of a storage device or specific cloud resource.

**DHLLC-B3 - DISASTER RESISTANT BACKUP**
- Data at this level should be recoverable even in the event of a widespread disaster. This data is replicated multiple times, and copies are stored in different locations.

Creating backups must always align with the corresponding classification level assigned to the data object. If alignment is not possible, the classification level takes precedence.

## 4.1 Format of Data Classification & Recovery Protection Level
Data is labeled with the assigned classification level and recovery protection level using metadata and, where possible, within the data object itself.

These labels must follow one of the formats listed below:
- ```[Classification Level Abbreviation]-[Recovery Protection Level Abbreviation]```
- ```[Classification Level Abbreviation]-[Recovery Protection Level Abbreviation] // [Classification Level] - [Recovery Protection Level]```

Examples include:
- ```E1-G1```
- ```E1-G1 // PUBLIC - NO BACKUP```

## 4.2 Data Classification & Recovery Protection Level Assignment
DHLLC assumes that all employees can independently and responsibly determine the appropriate classification level and recovery protection level for a given data object. In case of doubt, data should be classified at a higher level, indicating greater sensitivity and relevance to availability.

In case of uncertainties, employees can always seek guidance from DHLLC's Compliance Department. Assignments made by DHLLC's Compliance Department or individuals with TS5 security clearance are final and