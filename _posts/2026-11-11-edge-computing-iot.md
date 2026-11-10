---
layout: post
title: "Edge Computing in IoT and Smart Manufacturing"
date: 2026-11-11 10:00:00 +0800
categories: [cloud-manufacturing, smart-manufacturing]
permalink: /edge-computing-iot/
---

## 1. Introduction

Edge Computing is an important technology in the development of the Internet of Things (IoT) and smart manufacturing. It refers to a computing approach where data processing and storage take place closer to the devices or machines that generate the data, rather than depending entirely on a centralised cloud platform.

In manufacturing, machines and sensors continuously generate operational information. Processing all this information through a remote cloud platform may introduce communication delays. Edge Computing helps address this issue by allowing certain data processing activities to take place near the production equipment.

According to RFC 9556, Edge Computing supports applications that require short response times, local data processing and reliable operation when network connectivity is limited.

## 2. Main Components of Edge Computing

An Edge Computing environment consists of several components that work together to process and manage data.

**2.1 IoT Devices and Sensors**

IoT devices and sensors collect information from machines and manufacturing processes. Examples include temperature sensors, vibration sensors, pressure sensors and equipment monitoring devices.

**2.2 Edge Devices**

Edge devices are computing or networking resources located between data-producing devices and centralised cloud systems. They process information closer to its source.

**2.3 Edge Gateway**

An edge gateway connects industrial devices and sensors to other networks or computing platforms. It can help collect, organise and transmit information between local equipment and cloud services.

**2.4 Communication Networks**

Communication networks allow information to move between sensors, edge devices and cloud platforms. Reliable communication is important for supporting industrial monitoring and control activities.

**2.5 Cloud Platform**

Cloud platforms provide additional storage and computing resources. They can be used for tasks that require larger-scale data storage, processing and analysis.

## 3. How Edge Computing Works

Edge Computing operates by processing information near the location where it is generated.

The general process involves the following steps:

1. **Data Collection:** Sensors and IoT devices collect information from machines and production equipment.
2. **Data Transmission:** The collected information is transmitted to a nearby edge device or gateway.
3. **Local Data Processing:** The edge device processes the information and identifies important conditions or events.
4. **Immediate Response:** When necessary, the system can generate alerts or support local control actions.
5. **Cloud Data Transfer:** Selected information can be transmitted to a cloud platform for further storage and analysis.
6. **Continuous Monitoring:** The system continues collecting and processing new information from manufacturing equipment.

This approach allows time-sensitive information to be processed locally while other information can be managed through cloud computing resources.

## 4. Applications of Edge Computing in Manufacturing

Edge Computing can support several activities in modern manufacturing.

**4.1 Real-Time Machine Monitoring**

Edge devices can process machine information close to the production equipment. This helps operators monitor machine conditions and identify unusual operating behaviour more quickly.

**4.2 Predictive Maintenance**

Sensors collect machine information such as vibration and temperature. Edge devices can analyse this information locally to identify abnormal conditions and generate maintenance alerts.

**4.3 Automated Production Control**

Edge Computing can support time-sensitive industrial applications by processing information near machines and control systems. This can help reduce communication delays in certain automated operations.

**4.4 Quality Inspection**

Edge devices can process information from cameras and inspection sensors near production lines. This allows manufacturers to identify possible product defects without always sending all inspection data to a remote cloud platform.

**4.5 Environmental Monitoring**

Edge devices can process information from environmental sensors that monitor temperature, humidity and other workplace conditions. Alerts can be generated when measurements exceed specified limits.

**4.6 Robotic Systems**

Industrial robots may require fast communication and control responses. Edge Computing can support local processing for selected robotic applications where response time is important.

## 5. Difference Between Edge Computing and Cloud Computing

Both Edge Computing and Cloud Computing support data processing and storage. However, they differ in terms of where computing activities take place.

| Aspect | Edge Computing | Cloud Computing |
|---|---|---|
| Processing location | Near data sources | Centralised remote infrastructure |
| Response time | Can provide lower latency for local tasks | May involve additional network delays |
| Data handling | Processes selected data locally | Supports centralised data storage and processing |
| Internet dependency | Some local functions may continue during connectivity interruptions | Cloud services generally require network connectivity |
| Computing resources | Usually more limited | Can provide larger and scalable resources |
| Main applications | Local monitoring and time-sensitive processing | Large-scale analytics, storage and data management |

Edge Computing and Cloud Computing are complementary technologies. Manufacturers can combine both approaches according to their operational requirements.

## 6. Benefits of Edge Computing in Manufacturing

The implementation of Edge Computing can provide several benefits:

- **Reduced latency:** Processing data closer to machines can reduce communication delays.
- **Faster response:** Local processing supports applications that require quick responses.
- **Reduced network traffic:** Only selected or processed information may need to be transmitted to cloud platforms.
- **Improved operational continuity:** Certain local processing functions may continue during temporary network interruptions.
- **Better data management:** Data can be filtered and organised before being transferred to centralised systems.
- **Support for automation:** Edge devices can support time-sensitive monitoring and control applications.

## 7. Challenges of Implementing Edge Computing

Although Edge Computing offers several advantages, manufacturers may face challenges during implementation.

**7.1 Limited Computing Resources**

Edge devices generally have fewer computing and storage resources than large cloud data centres. Therefore, manufacturers must select suitable devices based on their processing requirements.

**7.2 Cybersecurity Risks**

Edge devices are distributed across different locations and may become targets for cybersecurity threats. Suitable security controls are required to protect devices, networks and operational information.

**7.3 System Management**

Managing multiple edge devices across a manufacturing facility can be complicated. Organisations need suitable methods to monitor, update and maintain these devices.

**7.4 Integration with Existing Systems**

Integrating edge devices with existing industrial machines, controllers and cloud platforms may require additional technical adjustments.

**7.5 Network Reliability**

Although Edge Computing can reduce dependence on continuous cloud communication for certain local tasks, reliable communication is still important when information must be exchanged between different systems.

## 8. Relationship Between Edge Computing and Cloud Manufacturing

Edge Computing supports Cloud Manufacturing by providing local data processing capabilities within connected manufacturing environments.

In a manufacturing facility, sensors can collect information from production machines and transmit it to nearby edge devices. The edge devices process time-sensitive information, while selected data can be transferred to cloud platforms for long-term storage, advanced analytics and production management.

For example, a factory may use vibration sensors to monitor the condition of its machines. An edge device can analyse vibration measurements locally and generate an alert when unusual conditions are detected. Meanwhile, historical machine information can be stored in the cloud for further analysis.

This combination of Edge Computing and Cloud Computing allows manufacturers to balance local processing requirements with centralised data management.

## 9. Conclusion

Edge Computing is an important technology in IoT and smart manufacturing because it allows data processing and storage to take place closer to industrial machines and connected devices. This approach supports faster responses, reduced communication delays and more efficient handling of manufacturing information.

Its applications include machine monitoring, predictive maintenance, automated production control, quality inspection and environmental monitoring. Although challenges such as limited computing resources, cybersecurity and system integration must be considered, Edge Computing provides valuable support for developing connected and responsive manufacturing environments.

## References

1. Kutscher, D., et al. (2024). *Internet of Things (IoT) Edge Challenges and Functions* (RFC 9556). Internet Engineering Task Force. https://www.rfc-editor.org/rfc/rfc9556.html

2. International Organization for Standardization (ISO) & International Electrotechnical Commission (IEC). (2020). *Internet of Things (IoT) — Edge computing* (ISO/IEC TR 30164:2020).

3. National Institute of Standards and Technology (NIST). (n.d.). *Reliable, High Performance Wireless Systems for Factory Automation*. https://www.nist.gov/programs-projects/reliable-high-performance-wireless-systems-factory-automation
