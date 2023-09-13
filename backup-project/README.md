# Backup - OrgInv

## Introduction

In this module, we have been assigned the task of implementing a backup solution for a fictional organization called OrgInv. The backup solution needs to comply with the guidelines provided below.

![part1](images/M143-competency-part-1.png)
![part2](images/M143-competency-part-2.png)

These guidelines are divided into six different category which are provided below.

1. **Data security concept:**

    This category focuses on the concept of data security and ensuring that the backup solution incorporates appropriate measures to protect the organization's data from unauthorized access, loss, or corruption.

2. **Feasibility:**

    This category pertains to assessing the feasibility of the backup solution. It involves evaluating factors such as cost, resources, time, and technical requirements to determine if the proposed backup solution is practical and achievable.

3. **Needs assessment:** 

    This category involves conducting a thorough assessment of the organization's backup needs. It includes identifying the critical data that needs to be backed up, determining the frequency of backups, and understanding any specific requirements or constraints.

4. **Security procedures:**

    This category focuses on establishing security procedures for the backup solution. It includes defining access controls, encryption methods, authentication mechanisms, and other security measures to ensure the confidentiality, integrity, and availability of the backed-up data.

5. **System and operational documentation:** 

    This category emphasizes the importance of documenting the backup solution. It involves creating detailed documentation that outlines the system architecture, configuration settings, backup procedures, recovery processes, and any other relevant information for effective operation and maintenance of the backup solution.

6. **Extensions:** 

    This category refers to any additional considerations or extensions that need to be taken into account while implementing the backup solution. These could include integration with existing systems, scalability requirements, disaster recovery planning, or any other specific requirements unique to the organization.

## Task explaination

As previously articulated, the primary objective of this module is to proficiently strategize and execute a backup solution for an organization based on the given guidelines.

To facilitate this project, I have created a imaginary corportaion specializing in warehouse management and customer-centric solutions.

Within this hypothetical context, I have assumed the role of an external contractor working at tasked with orchestrating the migration of the pre-existing on-premises infrastructure into a cloud-based environment.

This imaginary corporation is a mega corporation that is based in Europe. Their name is OrgInv.

OrgInv is a fictional corporation that originated in Geneva, located in central Europe. OrgInv was established by Frédéric Valmouz in the 1950. Since then they grew by approximately 10'000%. With their numbers now boasting 5000 employees world wide.

In 2022 OrgInv finally decided that they would switch from on-premise solutions to cloud-based solutions, however they are facing a problem. The problem being that they don't have adequate IT-professionals which could do this on their own. So they decided to hire an external contractor.

They contacted the external contractor per email with the following business opportunity:

    From: Éric Doulmont, Head of Engineering OrgInv <éric.doulmont@orginv.com>
    Sent: Monday, September 4, 2023 10:00:01 AM
    To: customer service, IMAM Institution <customer.service@imam.com>
    Subject: Business proposal part migration from on-premise to cloud

    Dear IMAM customer service team,

    We contact you, due to a deciscion we made last year during our annual management meeting. Together we have made the executive desicion that it would be more cost effective, to downscale our on-prem infrastructure and migrate to a cloud-based enviornment.

    Since this is a large scale project for us we have made a bulletlist of what needs to be done:

    • Analyzing the current state of the OrgInv Infrastructure
    • Optimizing the OrgInv Infrastructure and creating a plan for the optimized infrastructure.
    • Drafting a cost-estimation
    • The creation of a graphic that allows one to have a high-level overview over the cloud-based infrastructure.
    • The Creation of a graphic that allows one to have a deep-level overview over the cloud-based infrastructure.
    • Overseeing and leading the migration process
    • Documenting the migration process in form of a documentation.
    • Educating the inten IT-staff on the new changes
    • Maintaining and monitor the cloud enviornment for the adjustment period (approx. 4 Weeks)

    We have attached a plan of our existing on-premise infrastructure.  

    If you are interested in our job offer, kindly get in touch with us within 14 business days. Additionally, we kindly request that you provide us with a quota.

    Upon receiving your quota, we will assess your suitability as a candidate for our organization. We will then inform you of our decision and further details. Regardless of the outcome, we wish you the best of luck in your endeavors.
  
    Kind Regards

    Éric Doulmont
    Head of Engineering
    OrgInv Corporation
    Genéve, Rue de Rhône 29

As you can see from this email that Éric Doulmont has sent me I was given a potential job offer, by migrating an existing on premise infrastructure into the cloud.

He also tasked me to create an quota [in ger. Offerte] this means that I have to make a rough estimate of all the cost ± 2500 CHF. <br>
This includes the following things:

* Estimated cost for EC2
    * Estimated cost for application servers
    * Estimated cost for front-end servers
* Estimated cost for S3 Buckets/S3 Selects
    * Estimated cost for S3 Select retrievals
    * Estimated cost for S3 Select 
* Estimated cost for Amazon Aurora MySQL-Compatible DB
* Estimated cost for Amazon Route 53
* Estimated cost for AWS Shield
* Estimated cost for AWS Secrets Manager

These are only the rudementary services that have to be included for the AWS Cloud. However the quota doesn't only contain the cost for the services but the manpower as well.<br>

## Initial planning phase
For the initial planning phase I have to draft a quota, in which I'll list all the costs regarding the part migration as per guidelines of OrgInv Corporation.


    

    
    
 

