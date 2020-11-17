---
layout: default
title: Integration of Cycling into Municipal Traffic Plan
permalink: /transportation/integration-of-cycling
---

# Integration of Cycling into Municipal Traffic Plan

Cycling has come into its own as a method of urban transportation: not only is it environmentally friendly and good exercise, it is cheap, space-efficient, and of minimal impact to rideable surfaces. Accordingly, cycling figures prominently into municipal transportation plans, greenhouse gas emissions reductions strategies, and even public health strategies.

## Applications and Solutions:  Bicycle Counting

Cycle counting by communities encompasses the tracking of cyclists' road usage, numbers, collisions, and more with the intent of both responding to issues and improving usage of cycling areas. When that data is open and shared, populations also become more aware of the transportation possibilities and investments in their area - such as the bicycle community Bike Ottawa's creation of a bicycle routing map based on the City of Ottawa's open data portal. Municipalities can use this data to establish seasonal and diurnal traffic patterns and, correlated with weather data, weather-related correction factors.

## Technologies

**Manual Counting** – Traffic counting is a traditional summer job for many students. This approach can be applied to bicycles as easily as to motor vehicles.

**Pneumatic Tubes** – Air-filled rubber tubes lying across roadways are a time-tested temporary tool for counting traffic.

**Passive Infrared sensors** – Thermal imaging sensors can detect passing objects and classify them as pedestrians or cyclists based on shape.

**Battery-Powered Inductive Loops** - Information collected from these products shows the number of bicycles that have passed and the direction they are going.

**Cameras** – Traffic cameras coupled with algorithms that allow the camera to “see” the road and recognize traffic types – cars, bicycles, pedestrians - and record their actions.

**Lidar cameras** - Lidar – a portmanteau of light detection and ranging, sometimes called “3D laser scanning” - measures distances to a target by illuminating the target with laser light and measuring the reflected light with a sensor. Measured differences in object distances allows algorithms to construct detailed real-time descriptions of street traffic.

**Third party data acquisition** – Fitness app developers have moved into the business of selling participatory or crowd-sourced biking data to municipalities. Apps can collect information from their users’ phone’s embedded accelerometer, microphone, and GPS.

**Cloud-Based Data Platforms** - Some service providers offer internet-based services for accessing and displaying sensor output. These services allow their municipal customers to access the data in a single online space.

## Managing Liability Issues

| Privacy |
| :--- |
| **Issues.** |
| ⚠ Bicycle counting technologies will encounter privacy issues where they collect personal information of individuals.  Since the legal definition of “personal information” in Canada includes information about an identifiable individual – even if the individual is not directly identified – bicycle counting technologies will run into privacy issues where they record recognizable images of individuals or record routes traceable to individuals. |
| **Managing Issues.** |
| ✅ Count, don’t track.  Record numbers and direction instead of tracing routes that can be associated with individuals. |
| ✅Choose the technology appropriate to the task.  Low-tech solutions such as pneumatic tubes may be able to provide the data needed but without the privacy issues that cameras introduce. |
| ✅Data-fuzzing. Employ data-fuzzing techniques to preserve privacy. For example, do not include start and end points in route data so that a particular route cannot be traced to an individual. Similarly, fuzzing data of sensitive areas provides an additional layer of security for personal information. |
| ✅De-identify at the source. Many camera technologies allow for faces to be blurred at collection. |
| ✅De-identify as soon as possible.  If personal information absolutely must be collected, it should be stripped away as soon as possible. |
| ✅Limit data collection to only that which is needed. Collection strategies such as bicycle numbers and heat maps rather than individual-specific routes avoid engaging more serious privacy concerns. |
| ✅Ensure that partners or contractors follow collection restrictions. When purchasing data from private companies, ensure that they are upholding their own privacy obligations under relevant legislation. |
| ✅Follow [good privacy practices](https://cippic-ca.github.io/SmartCityToolkit/privacy.html). |

| Security Issues |
| :--- |
| **Issues.** |
| ⚠ Privacy issues inherent to bicycle counting technologies will include security issues, as data that does not initially identify individuals can do so in combination with other data. |
| **Managing Issues.** |
| ✅Many of the same solutions to privacy issues will address security issues:  e.g., de-identify at source if possible, or as soon as possible if otherwise.  Where personal information is collected, it should be held in a secure location. |
| ✅Access should be limited to those with a need to use the information. |
| ✅Follow [good security practices](https://cippic-ca.github.io/SmartCityToolkit/security.html). |

| Procurement |
| :--- |
| **Issues.** |
| ⚠ Most bicycle counting solutions will involve the purchase of products or services from third parties, which will raise procurement issues: \(a\) who will own the data produced by the solution?  What are the long-term costs of the technology? Do the offerings raise issues around vendor lock-in? \(b\) How does a municipality choose between high technology and low-technology solutions? |
| **Managing Issues.** |
| ✅Procurement issues should be dealt with by following [sound procurement practices](https://cippic-ca.github.io/SmartCityToolkit/procurement.html) |
| ✅ [Intellectual property issues](https://cippic-ca.github.io/SmartCityToolkit/intellectual-property.html) will arise over ownership and confidentiality of data.  Access and other data entitlements should be addressed at the outset, as part of the conditions of procurement. |
| ✅ Deciding between high-tech and low-tech solutions will depend on several factors: \(a\) What is the use case? Long-term planning, or baseline measurement of activity within the city, may not require the speed, accuracy, and scalability that “smarter” technologies offer. Real-time public transit information for customers, in contrast, will heavily rely on these features. \(b\) Cost - low-tech solutions tend to be cheaper to acquire and maintain. High-tech solutions such as autonomous shuttles may have high costs for risk mitigation such as custom insurance coverages and specialized maintenance services. \(c\) Scalability – Assess bid submissions on the risks of scalability and flexibility to deal with structured and unstructured data. Some considerations include use of consortium models for incremental expansions and non-relational databases. |

