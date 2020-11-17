---
layout: default
title: Medical Emergency Response
permalink: emergency-management/medical-emergency-response
---

# Medical Emergency Response

## Service: Medical Emergency Response <a id="service-medical-emergency-response"></a>

Much like fire services, current medical emergency response services are subject to certain limitations. Someone must always make the call for an emergency medical response, and this is not always possible. In some case, someone who is alone and becomes injured or sick must manually call 911 – something they may not be able to do before they fall unconscious. Using existing technology, it is possible for first responders to take a more proactive approach to rendering medical assistance and get help to people who need it not only faster, but also more efficiently.

## Applications and Solutions: Gunshot Detection

As municipalities grow and become more urban, injuries due to gun violence may unfortunately become more common. It is be necessary for victims of violent crime to seek out medical attention on their own or have someone manually seek out medical attention for them. Furthermore, because urban gunfire is typically underreported, victims could potentially fall through the cracks when their lives could have been saved.

Automatic gunshot detection tools do not require third party calls to emergency responders. Instead, they use constant monitoring to dispatch emergency services to precise locations once gunshots have been detected. This improves both reporting of gunshots and emergency response times.

## Technologies

**Audio Gunshot Detection** – Uses multiple sensitive microphones placed in urban areas to detect and triangulate gunfire. When a certain number of microphones picks up the sound of gunfire \(which is confirmed by a central monitoring hub to avoid false positives\), medical first responders are automatically dispatched to the location. Microphones may also be configured to record audio once they detect a weapon being discharged in order to gather evidence.

**Optical Gunshot Detection** – Uses multiple cameras to detect the specific light frequency of a muzzle discharge. Like Audio Gunshot Detection systems, when the camera picks up the visual cue of gunfire, medical first responders are automatically dispatched to the location. Cameras may also be configured to record footage once they detect a weapon being discharged in order to gather evidence.

**Real-time road navigation** – Navigation system apps use real-time data on traffic conditions to show congestion areas and best routes for drivers. These systems can crowdsource data, such as the Waze navigation app, in which users provide data on accidents, street damage, congestion, and road blocks which will allow the app to reroute drivers to the fastest route possible.

**Radio Frequency \(RF\) Transmitters and Receivers** – A RF can detect the sound frequency of emergency vehicle sirens within a particular range and send signals to traffic lights’ microcontroller to prioritize traffic flow.

| Privacy |
| :--- |
| **Issues.** |
| ⚠ As with any form of always-on surveillance, continued monitoring of the community could raise issues of privacy. This is especially true if Gunshot Detection systems are configured to begin recording audio or footage after they detect a weapon discharge. |
| **Managing Issues.** |
| ✅ Don’t record anything. While the evidence will likely be useful from a crime fighting perspective, recording audio or footage does not actually have any tangible benefit when it comes to medical response. Systems could therefore be configured to only serve the purpose of detecting gunshots, not identifying who fired the weapon. |
| ✅ Contact Medical Responders first. Gunshot detection is primarily monitored and employed by police services. To de-emphasize invasive policing, medical first responders could administer the system instead, and inform police that a gun discharge had occurred once the victim has been located and attended to. |
| ✅ Use the technology sparingly. Systems should likely only be considered if underreported gun violence is a genuine issue in the community and a real danger of victims going untreated exists. |
| ✅ Scrub data of identifying features. Real-time voice modulation or face blurring could be used to anonymize individuals who are picked up by feeds. |
| ✅ Engage with the community. Prior to installation, absolute transparency should be employed with the community to explain the limitations of the technology and how data will be used. |
| ✅ Follow [good privacy practices](https://cippic-ca.github.io/SmartCityToolkit/privacy.html). |

| Security |
| :--- |
| **Issues.** |
| ⚠ If any data is being recorded and anyone can be identified with that data, then the previously outlined privacy issues also raise issues of security. Data that is stored could potentially be accessed by unauthorized users if proper care isn’t taken to prevent it. |
| **Managing Issues.** |
| ✅ Institute privacy solutions. Many privacy solutions that seek to strip identifying data will also address issues of security. |
| ✅ Hold data in a secure location. If data cannot be anonymized, it should be held in a secure location. This ensures individuals cannot be identified by it except in authorized situations. |
| ✅ Limit access. Any collected audio or footage should only be able to be accessed by those who need to use the information. |
| ✅ Follow [good security practices](https://cippic-ca.github.io/SmartCityToolkit/security.html). |

