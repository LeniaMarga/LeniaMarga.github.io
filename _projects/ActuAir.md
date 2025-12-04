---
title: ActuAir
subtitle: A soft robotic installation that displays CO2 level changes in the workplace
timeline: 2022-2023
description: Interactive Installation, Soft Robotics, Electronics, Fabrication, Web app, PhD, OpenLab
featured_image: '/images/content/PhD/ActuAir/ActuAir-demo.png'
---
With workplace buildings becoming increasingly sensor-rich environments and amidst climate change and global pandemic pressures, there is novel opportunity for utilizing CO2 data within buildings for awareness and wellbeing purposes. Soft robotics applications have unexplored potentials in this context, with new opportunities emerging for soft robotic architectures to utilize environmental sensory data to support health and wellbeing in the built environment. Example projects involve soft robotics in architectural facades e.g. pneumatic elements that actuate based on external environmental data to improve building’s microclimate. 

The project physicalizes changes in CO2 levels through shape and color-changing silicon and fabric modules, with integrated LED strips. These modules can be put together and be re-arranged by the building users to form soft barriers in the workplace. Each module operates with a wireless Arduino connected to a local server built on Raspberry Pi. The server is fetching AQ data (CO2, VOC, temperature, humidity) from the building's open [API](https://3d.usb.urbanobservatory.ac.uk/) and wirelessly communicates with the Arduinos which control the LED's intensity and color (green-yellow-red gradient), and the air-pumps and valves for each module e.g. the amount of air pumped in and out, and the time they stay inflated or pulsing. All hardware (Arduinos, air -pumps and valves) are integrated in each module, enabling them to act as stand-alone and in coordination with other modules. 

<br><br>
![](/images/content/PhD/ActuAir/ActuAir-demo.png)
Above: Building users observing and interacting with the display.
<br><br>
![](/images/content/PhD/ActuAir/Fig01.jpg)
Above: A. The display's modules in the default set up in a circular arrangement. Green is an indication of good air quality. The changes in CO2 are depicted with inflation/deflation and color change (green-yellow-red scale). The combination of using light color and inflation as parameters to communicate CO2 levels were subject to user testing. 
<br><br>

AQ data include both real time and historical (24-hour timeframe) sensory readings (CO2, temperature, humidity) of the building’s rooms. The software we developed (Webapp in React, Axios) with the help of [Jan Kučera](https://openlab.ncl.ac.uk/people/jan-kučera/#projects) offers three main options: A. it allows users to select the room and data stream (CO2, temperature, humidity) they wish to physicalize using one or multiple components; B. it allows users to select a room and a number of components,  and displays the historical data (measurements over the past 24hours) in these components; and C. Allows the researcher and/or users manually customize parameters such as the RGB color of the LEDs, the LED intensity, the duration of inflation/deflation and the pulsing or pausing of inflation, in order to investigate feedback combinations. Additionally, we used [Luftio](https://luftio.cz/#) table sensor and their API to be able to use the modules at home or at a remote desk. 

<br><br>
![](/images/content/PhD/ActuAir/Fig02_B.jpg)
Above: The electronics exposed in the back of the modules.
<br><br>
![](/images/content/PhD/ActuAir/Fig02.jpg)
Above: Testing different modular arrangments and LED/inflation customizations with participants.
<br><br>

Beyond implementation, I deployed and evaluated ActuAir with the building occupants of a smart building. To-date, there are limited studies evaluating large scale soft robotic interventions in the context of communicating CO2 data in the workplace. Responding to this research gap, three prototype-led studies were conducted with 21 occupants of a smart office building over June-August 2022, evaluating occupants’ experiences of a large shape- and color-changing display responding to AQ data. Different arrangements and customizations of the modules (inspired by biomimetic metaphors) were presented to participants; which were then asked to reflect on what the display communicates to them, how do they interpret the feedback, and what spatial associations do they see. A thematic analysis resulted in design implications for improving shape- and color-changing large scale soft robotic displays for communicating CO2 data; linking biomimicry and spatial cognition to feedback interpretation.

Contributing to Human-Building Interaction (HBI) research in the Human-Computer Interaction (HCI) field, we provide design directions for future shape-changing and responsive architectures for climate awareness in smart buildings.

This research was published at the 2024 CHI conference and received an honourable mention. See the relevant publication [here](https://dl.acm.org/doi/10.1145/3613904.3642396), and a short academic presentation [here](https://www.youtube.com/watch?v=ezX6QCKcnlA&feature=youtu.be).


<br><br>
![](/images/content/PhD/ActuAir/Fig05.jpg)
Above: Participants co-designing their preferred display arrangments using paper modules.
<br><br>
![](/images/content/PhD/ActuAir/Fig04.jpg)
Above: Different display arrangments and LED/inflation combinations that were tested with participants, and some of their responses (in quotes). Participants were asked to reflect on what they understand in terms of feedback, what spatial-data associations do they conceive, and what is their preferred display arrangement. 
<br><br>


