# Doupont Holdings LLC - Data Classification Directive

## 1. Purpose of this Document

The purpose of this document is to establish guidelines for the classification of data processed and/or stored by Doupont Holdings LLC, hereinafter referred to as "DHLLC." The classification of all DHLLC data into specific categories aims to ensure that sensitive information remains inaccessible to unauthorized individuals, thereby safeguarding DHLLC from potential harm.

## 2. Scope

This directive applies to all internal and external personnel associated with DHLLC or entities contracted by DHLLC for the processing of specific or unspecified DHLLC data. Compliance with this directive is mandatory for all DHLLC data. The DHLLC Compliance Department oversees compliance with this directive and may engage external contractors to assist in this process.

## 3. Responsible Authority

The entity contracted by DHLLC, "IMIAM" is responsible for monitoring the implementation of this directive and collaborates closely with DHLLC's Compliance Department.

## 4. Data Classification Levels

All data generated, stored, or otherwise processed by DHLLC must be categorized into one of the following classification levels:

**E1 - PUBLIC**
- Data in this category is considered publicly accessible, and third parties or external entities may access it without restrictions.
- Data in this category may be stored on unencrypted media, unmanaged cloud environments, websites, or platforms of any kind.
- When stored in DHLLC's private or public cloud environments, there are no geographical restrictions on the location of data centers.

**E2 - INTERNAL**
- Data in this category is considered internal and is accessible to all internal and external personnel. Data in this category may reference data in the E1 category, but E2-rated content should not be present in E1 data.
- Data in this category may be stored in DHLLC's managed private and public cloud environments, specifically in "birdCloud" and "aapCloud." Data within these DHLLC cloud environments does not require separate encryption. Data in this category may be shared through DHLLC's managed communication platforms.
- When stored in DHLLC's private or public cloud environments, there are no geographical restrictions on the location of data centers.

**E3 - CONFIDENTIAL**
- Data in this category is accessible to all internal personnel. Data in this category may reference data in the E2 category, but E3-rated content should not be present in E2 data.
- Data in this category may be stored in DHLLC's managed private and public cloud environments, specifically in "birdCloud" and "aapCloud." Data within these DHLLC cloud environments does not require separate encryption. Data in this category may be shared through DHLLC's managed communication platforms.
- When stored in DHLLC's private or public cloud environments, data centers must be located within the European region. Under no circumstances should data in this category be stored or processed in the United States.

**E4 - SECRET**
- Data in this category is accessible only to personnel with OS4 security clearance.
- Data in this category may only be stored in DHLLC's private cloud environment (aapCloud). Data within this environment does not require separate encryption.
- When storing data in DHLLC's private cloud environment (aapCloud), it must specify the data center location as "AAL-BKNET-DC-ZHWI1."
- Data in this category may reference data in the E3 category, but E4-rated content should not be present in E3 data.

**E5 - TOP SECRET**
- Data in this category is accessible only to personnel with TS5 security clearance.
- Data in this category may only be stored in DHLLC's private cloud environment (aapCloud). All data in this category must be encrypted using AES-256 encryption before uploading to DHLLC's private cloud (aapCloud). The corresponding password must be at least 20 characters in length and may only be stored in password management programs approved by DHLLC.
- When storing data in DHLLC's private cloud environment (aapCloud), it must specify the data center location as "AAL-BKNET-DC-ZHWI1."
- No references to E5 data are permitted in data of E1, E2, E3, or E4 classifications.

## 5. Hierarchical Principle

Data classified as E1, E2, E3, or E4 may exist within data classified as E5. Data classified as E1, E2, or E3 may exist within data classified as E4 or E5. Data classified as E1 or E2 may exist within data classified as E3, E4, or E5. Data classified as E1 may exist within data classified as E2, E3, E4, or E5.

Therefore, individuals with TS5 security clearance have access to all DHLLC data, spanning across all classification levels. Individuals with OS4 security clearance have access to data classified as E1, E2, E3, and E4.

## 6. Data Recovery Protection Level

In addition to classification levels, all DHLLC data will receive a data recovery protection level indicating the extent to which a data object should be protected against loss or damage. Different measures will be implemented based on the data recovery protection level to ensure the guaranteed availability of data. The following are the various data recovery protection levels:

**G1 - NO BACKUP**
- Data with this protection level is not backed up. Loss of this data is acceptable, and data backup would be disproportionately burdensome.

**G2 - SIMPLE BACKUP**
- Data with this protection level is backed up using a simple backup process. A copy of this data object is created and stored in the same environment. This backup is intended solely for recovery in case of accidental deletion or failure of a data storage medium or specific cloud resource.

**G3 - DISASTER RESISTANT BACKUP**
- Data with this protection level should be recoverable even in the event of a significant incident. These data objects are replicated multiple times, and copies are stored in different locations.

The creation of backups must always align with the corresponding data classification level assigned to the data object. If this is not possible, the data classification level takes precedence.

## 7. Notation of Classification Level & Data Recovery Protection Level

Data will be labeled with their assigned classification level and data recovery protection level using metadata and, whenever possible, labels within the data object itself. These labels must be in one of the following formats:

- `[Classification Level Abbreviation]-[Data Recovery Protection Level Abbreviation]`
- `[Classification Level Abbreviation]-[Data Recovery Protection Level Abbreviation] // [Classification Level] - [Data Recovery Protection Level]`

For example:
- `E1-G1`
- `E1-G1 // PUBLIC - NO BACKUP`

## 8. Data Classification and Data Recovery Protection Level Assignment

DHLLC expects all employees to independently and responsibly assess the appropriate classification level and data recovery protection level for a given data object. It is important to err on the side of caution and classify data as more sensitive or critical in terms of availability when in doubt.

In case of uncertainty, employees can always seek guidance from DHLLC's Compliance Department. Classification decisions made by DHLLC's Compliance Department or individuals with TS5 security clearance are final and determine the definitive classification of the data.

