---
title: "List of Session Border Controllers certified for Direct Routing"
ms.author: crowe
ms.reviewer: NMuravlyannikov
author: CarolynRowe
manager: serdars
audience: ITPro
ms.topic: article
ms.service: msteams
localization_priority: Normal
search.appverid: MET150
ms.collection: 
  - M365-voice
appliesto: 
  - Microsoft Teams
hideEdit: true
f1.keywords:
- NOCSH
description: "Microsoft partners with selected SBC vendors to certify their SBCs work with Direct Routing."
---

# List of Session Border Controllers certified for Direct Routing

Microsoft partners with selected Session Border Controllers (SBC) vendors to certify that their SBCs work with Direct Routing. 

Microsoft works with each vendor to: 

- Jointly work on the SIP interconnection protocols.
- Perform intense tests using a third-party lab. Only devices that pass the tests are certified. 
- Run daily tests with all certified devices in production and pre-production environments. Validating the devices in pre-production environments guarantees that new versions of Direct Routing code in the cloud will work with certified SBCs. 
- Establish a joint support process with the SBC vendors.


  > [!NOTE]
  > Microsoft only supports Phone System if a certified device or devices are connected through Direct Routing. Microsoft reserves the right to reject support cases where a non-certified device is connected to the Phone System through Direct Routing. 

The table below lists devices certified for Direct Routing. 

[Learn more about Direct Routing](https://aka.ms/dr). 
If you have any questions about SBC certification program for Direct Routing please contact drsbccertification@microsoft.com.


|                                                       Vendor                                                        |       Product       | Non-media bypass | Media bypass | Software version | Validated with E911 providers | ELIN capable
|---------------------------------------------------------------------------------------------------------------------|---------------------|------------------|--------------|------------------|-----------------|------------------|
| [Audiocodes](https://www.audiocodes.com/solutions-products/products/products-for-microsoft-365/direct-routing-for-microsoft-teams) |   Mediant 500 SBC   |     &#10004;     |   &#10004;    |  7.20A.250   |
|                                                                                                                     |   Mediant 800 SBC   |     &#10004;     |   &#10004;     |  7.20A.250   |    |    |
|                                                                                                                     |  Mediant 2600 SBC   |     &#10004;     |   &#10004;    |  7.20A.250   |     |    |    
|                                                                                                                     |  Mediant 4000 SBC   |     &#10004;     |   &#10004;     |  7.20A.250   |     |    |    
|                                                                                                                     | Mediant 1000B  SBC  |     &#10004;     |   Pending     |  7.20A.250  |    |    |    
|                                                                                                                     | Mediant 9000  SBC  |     &#10004;     |   &#10004;     |  7.20A.250   |    |    |                                                                       
|                                                                                                                     | Virtual Edition SBC |     &#10004;     |   &#10004;     |  7.20A.250 |    |    |    
|  [Ribbon Communications](https://ribboncommunications.com/solutions/enterprise-solutions/microsoft-skype-business)  |      SBC 5110       |     &#10004;     |   &#10004;    |       V7.2       |  Intrado ERS <br>Intrado EGW |   No |    
|                                                                                                                     |      SBC 5210       |     &#10004;     |  &#10004;    |       V7.2       |   Intrado ERS <br>Intrado EGW  | No   |    
|                                                                                                                     |      SBC 5400       |     &#10004;     |   &#10004;   |       V7.2       |  Intrado ERS <br>Intrado EGW    |No|    
|                                                                                                                     |      SBC 7000       |     &#10004;     |   &#10004;    |       V7.2       |   Intrado ERS <br>Intrado EGW  |  No  |    
|                                                                                                                     |       SBC SWe       |     &#10004;     |   &#10004;   |       V7.2       |   Intrado ERS <br>Intrado EGW |   No |    
|                                                                                                                     |      SBC 1000       |     &#10004;     |   &#10004;    |      v8.0.3 (build 537)     |  Intrado ERS <br>Intrado EGW   |  Pending  |    
|                                                                                                                     |      SBC 2000       |     &#10004;     |   &#10004;   |     v8.0.3 (build 537)     |  Intrado ERS <br>Intrado EGW  |  Pending  |    
|                                                                                                                     |    SBC SWe Lite     |     &#10004;     |  &#10004;    |      v8.0.3 (build 216)    |  Intrado ERS <br>Intrado EGW   |  Pending  |    
|                     [Thinktel](https://www.thinktel.ca/services/think-365/think-365-overview/)                      |    Think 365 SBC    |     &#10004;     |   Pending    |       V1.4       |     |    |    
|                     [Oracle](https://www.oracle.com/industries/communications/enterprise-session-border-controller/microsoft.html)                      |    AP 1100      |    &#10004;     |    &#10004;    |   8.3.0.0.1 |   Intrado ERS <br>Intrado EGW  |    |    
|                                                                                                                    |    AP 3900           |    &#10004;     |    &#10004;   |   8.3.0.0.1  |   Intrado ERS <br>Intrado EGW  |    |    
|                                                                                                                    |      AP 4600         |    &#10004;   |    &#10004;     |     8.3.0.0.1  |   Intrado ERS <br>Intrado EGW |    |    
|                                                                                                                    |      AP 6300         |    &#10004;   |    &#10004;     |     8.3.0.0.1  |  Intrado ERS <br>Intrado EGW  |    |    
|                                                                                                                   |      AP 6350           |    &#10004;   |    &#10004;    |     8.3.0.0.1  |   Intrado ERS <br>Intrado EGW |    |                                            
|                                                                                                                    |      VME           |    &#10004;    |    &#10004;    |     8.3.0.0.1   |   Intrado ERS <br>Intrado EGW  |    |    
|                     [TE-SYSTEMS](https://www.anynode.de/anynode-and-microsoft-teams/)                               |     anynode         |     &#10004;   |  &#10004;   |      v3.16.2      |     |    |    

To give us product feedback about Teams, such as ideas for new features, see [Uservoice](https://microsoftteams.uservoice.com)
Note the certification granted to a major version. That means that firmware with any number in the SBC firmware following the major version is supported.
