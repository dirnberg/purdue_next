# Purdue Next Model from IKARUS

## Introduction
The Purdue Next Model is a security architecture designed to provide a framework for securing industrial control systems. 
This model was developed by IKARUS as the next generation of the Purdue Reference Model, 
with a focus on modern IT architectures and Industrial Internet of Things (IIoT) environments. 


## Overview
The Purdue Next Model is a comprehensive security architecture that divides an industrial control system into three zones and six levels. 
The three zones are the Enterprise Zone, the DMZ, and the Manufacturing Zone. 
The six levels are the Enterprise Level, Business Planning and Logistics Level, the Site Operations Level, the Area Supervisory Control Level, the Process Control Level, the Basic Control Level, and the Physical Process.

Each level is associated with specific devices, systems, and protocols. The Purdue Next Model aims to provide a clear understanding 
of the relationships and dependencies between these devices, systems, and protocols, 
which can help organizations to better secure their industrial control systems. The model also provides guidance on how to segment networks to protect critical assets and how to implement effective access control.

An important measure within the Purdue model is the establishment of VLAN partitions or more at levels 5, 4, 3.5, 3, and 2.5. This means that, for example, business service 1 should not be able to communicate with business service 2. A business impact analysis can be quickly conducted to derive the service catalog and determine which services should be separated from each other. Unfortunately, it is not easy to represent this in the model without making it unreadable.

## Implementation
To implement the Purdue Next Model, organizations can follow a step-by-step approach that includes the following:

- Define the zones and levels of the industrial control system.
- Determine the devices, systems, and protocols that are associated with each level.
- Identify the critical assets and data that need to be protected.
- Segment the network to protect critical assets and data.
- Implement effective access control policies.
- Deploy appropriate security solutions such as firewalls, managed switches  intrusion detection systems, and OT security sensors like Guardian(tm) from Nozomi Networks.

## Conclusion
The Purdue Next Model is a valuable security architecture that can help organizations to better secure their industrial control systems. 
By providing a clear understanding of the relationships and dependencies between devices, systems, and protocols, the model can help organizations to better protect critical assets and data. The model also provides guidance on how to segment networks and implement effective access control, which can help to prevent unauthorized access and mitigate the risk of cyber threats.
