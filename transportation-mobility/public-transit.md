---
layout: sidebar-page
title: Public Transit
permalink: /transportation/public-transit
---

# Public Transit

Public transportation is a major service that cities offer to connect people to the city’s different neighborhoods and resources, including access to employment, recreational facilities, essential services, and more. Smart public transportation plays an important role in reducing pollution and traffic congestion and improving the daily lives of citizens.

## Applications and Solutions: Real time public transit information

Real time public transit information can reduce wait times, travel times, and increase transit use as a result of customers being enabled to make travel plans based on accurate information. Municipalities can use information systems to collect data about traffic and vehicles, mobile apps and new transportation solutions such as low emission vehicles to inform strategic decisions and improve citizen’s overall quality of life.

## Technologies

**GPS sensors in busses** – GPS devices on-board busses can be used to inform smart phone apps about how to plan their routes and can also connect to traffic sensors or smart traffic lights to respond to approaching busses to help the flow of traffic.

**Real time public transit information** – Real-time transit data can include any information collected about the current status of vehicles which typically relies on GPS to provide predictive arrival and departure information. This real-time data can be used to send text/email alerts about route detours or delays and be integrated into mobile apps and dynamic messaging signs.

**Smart phone app for users and route planner** – Smart phone apps with real-time bus location information lets users plan trips that minimizes wait times and missed connections. Apps can be a one-stop shop to set bus arrival reminders and get all bus information including schedules, delays, stops, and announcements.

**Tap card applications for smart phone payment** – Transit fare payment can be made through account-based smart phone applications in which users can purchase bus passes, top up accounts, auto-reload accounts, and transfer balances from lost cards. These apps are paired with card reader where users will tap their phone to pay.

**Digital public transit payment** – Digital or mobile ticketing allows passengers to buy and display their tickets using their mobile device. Similar to the tap card apps for fare payment, digital payment apps can let users purchase bus passes and top up accounts.

**Demand-based microtransit** – Demand-based microtransit is a service that offers flexible routing, stops, and scheduling based on demand. Customers can use request a microtransit service through a mobile app that allows for fare payment, trip planning, and operator requests. The service typically uses smaller vehicles like shuttle busses.

**E-hailing** – E-hailing is a process of ordering a vehicle pick up through a mobile device using GPS technology. Although primarily used for private ride-hailing such as Uber and Lyft, the concept can also be applied to public transportation with demand-based microtransit.

**Low emission vehicles** – Electric and hybrid busses can be used to as an environmentally friendly and quieter option on the road. Existing bus fleets can be converted to be hybrid electric vehicles to reduce greenhouse gas emissions and energy consumption. These low emission vehicles will require charging systems, which can have quick charge or slower overnight charge options. Another option is hydrogen-powered busses that

**Autonomous shuttles** – These vehicles navigate autonomously in lower speed roads along predetermined, learned paths in areas such as industrial campuses, suburbs and city centers. Some existing models use Light Detection and Ranging technology \(LiDARs\), inertial measurement unit \(IMU\), cameras, GPS, and motion sensors.

## Managing Liability Issues

| Privacy |
| :--- |
| **Issues.** |
| ⚠ Public transit technologies will encounter privacy issues where they collect the personal information of an identifiable individual, including identifiers that can be linked to create a profile on a person. This data includes that coming from location-tracking technologies, mobile phone data, mobile app accounts and paid transactions can all be traceable to individuals. |
| **Managing Issues.** |
| ✅ Count, don’t track.  Record numbers and directions of transit routes and volume of passengers instead of tracing routes that can be associated with individuals. Numerical data about high density routes or stops and bus status \(ex. speed and accidents\) will not necessarily track identities. |
| ✅ Inform users of privacy issues related to interactive and payment features. A disclaimer can be provided to users about data collection and its privacy implications when engaging with account-based and GPS apps. |
| ✅ Obtain consent where possible. Consent should be obtained when the user downloads any route planning, e-hailing and transit payment apps, and again when signing up for the service. They should be informed of the purpose of data collection, use and retention of data. |
| ✅ Data-fuzzing. Employ data-fuzzing techniques to preserve privacy. For example, do not include start and end points in route data so that a particular route cannot be traced to an individual. Similarly, fuzzing data of sensitive areas provides an additional layer of security for personal information. |
| ✅ De-identify as soon as possible.  If personal information absolutely must be collected, it should be stripped away as soon as possible. Data should otherwise be reported anonymously where possible. |
| ✅ Limit data collection to only that which is needed. Serious consideration and justification should be made for the collection of sensitive personal information. The minimum information necessary to accomplish transactions should be collected. |
| ✅  Ensure that partners follow collection restrictions. When purchasing data from private companies, ensure that they are upholding their own privacy obligations under relevant legislation. |
| ✅ Follow [good privacy practices](https://cippic-ca.github.io/SmartCityToolkit/privacy.html). |

| Security Issues |
| :--- |
| **Issues.** |
| ⚠  Privacy issues inherent to public transit technologies will include security issues, as data that does not initially identify individuals can do so in combination with other data. The software programs and hardware components will require security measures to prevent unauthorized access to the data. |
| ⚠ There is a potential for a greater vulnerability with a large network of connected devices because a single breached device may expose the entire network to unauthorized access. |
| **Managing Issues.** |
| ✅ Many of the same solutions to privacy issues will address security issues:  e.g., de-identify at source if possible, or as soon as possible if otherwise.  Where personal information is collected, it should be held in a secure location. |
| ✅ Physical, organization and technological measures to limit access to data should be in place to only allow access to those who need to handle the information. |
| ✅ Conduct scheduled security assessments on applications and transmissions for risks and vulnerabilities to ensure security approaches are appropriate and effective. |
| ✅ Online payment systems should use end-to-encryption processes to secure communications and maximize the security of sensitive information in paid transactions. |
| ✅ Where city data is stored on cloud-based servers, the cloud platform should be subject to consistent audits and security patches, with a data recovery strategy in place. |
| ✅ All partners or contractors should have adequate safeguards depending on the sensitivity of the information in their control. |
| ✅  Follow [good security practices](https://cippic-ca.github.io/SmartCityToolkit/security.html). |

| Procurement |
| :--- |
| **Issues.** |
| ⚠  Public transit solutions will involve the procurement of hardware, vehicles and software programs and developers from third parties. This will raise procurement issues of the risk of obsolescence or vendor lock-in, long-term costs of the technology including vehicle maintenance, and choosing between high-tech and low-tech solutions. |
| **Managing Issues.** |
| ✅  Procurement issues should be dealt with by following [sound procurement practices](https://cippic-ca.github.io/SmartCityToolkit/procurement.html) |
| ✅  [Intellectual property issues](https://cippic-ca.github.io/SmartCityToolkit/intellectual-property.html) will arise over ownership and confidentiality of data.  Access and other data entitlements should be addressed at the outset, as part of the conditions of procurement. |
| ✅ Deciding between high-tech and low-tech solutions will depend on several factors: \(a\) What is the use case? Long-term planning, or baseline measurement of activity within the city, may not require the speed, accuracy, and scalability that “smarter” technologies offer. Real-time public transit information for customers, in contrast, will heavily rely on these features. \(b\) Cost - low-tech solutions tend to be cheaper to acquire and maintain. High-tech solutions such as autonomous shuttles may have high costs for risk mitigation such as custom insurance coverages and specialized maintenance services. \(c\) Scalability – Assess bid submissions on the risks of scalability and flexibility to deal with structured and unstructured data. Some considerations include use of consortium models for incremental expansions and non-relational databases. |

