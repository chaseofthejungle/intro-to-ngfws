# Intro to Next-Generation Firewalls Overview Guide

**TODO:** A brief introductory guide to next-gen firewalls, and what separates them from other firewalls.

#### Table of Contents

1. [Five Categories of Firewalls](#categories)
2. [NGFW Definition and Features](#definition)
3. [Advantages Over Traditional Firewalls](#advantages)
4. [Comparing Four Vendors: Palo Alto, Fortinet, SonicWall, Sophos](#comparison)
5. [Supplemental Resources](#supplemental)

<hr />

## 1. <a name="categories">Five Categories of Firewalls</a>

**Five categories of firewalls include:**

| *Name* | *Description* |
| :---: | :---: |
| *Packet Filtering* | These are firewalls that examine packets' IP headers and discard the packets that have been flagged.
| *Circuit-Level Gateway* | Instead of investigating packets individually, these firewalls use network protocol session initiation messages (such as TCP handshakes) to flag content if it is malicious.
| *Stateful Inspection* | These firewalls utilize both session monitoring and packet filtering.
| *Proxy* | Also known as Application-Level Gateway Firewalls, these firewalls rely on HTTP request strings and destination/target ports for their conditional logic.
| *Next-Generation* | Next-Generation Firewalls (NGFWs) rely on context-awareness at the application-level with advanced intelligence, providing support against complex security threats.

<hr />

## 2. <a name="definition">NGFW Definition and Features</a>

(TODO)

<hr />

## 3. <a name="advantages">Advantages Over Traditional Firewalls</a>

Next-Generation Firewall (NGFWs) have more powerful and diverse features than older standard firewalls: while those firewalls have stateful inspection capabilities for both incoming and outgoing traffic, NGFWs include some integrations as intrusion detection and prevention, threat-intelligence (including from cloud sources), and app control and awareness.

Simply put, older firewalls statefully inspect inward and outwrd traffic, rely on admin-configured rules to filter traffic, and provide access control by allowing and denying traffic (based on protocols, ports, and states). While NGFWs also do these things, they have significant additional features:

* The blocking of sophisticated contemporary attacks, such as app-layer threats and complex malware.
* Immediate consultation of industry-renowned threat intelligence sources, and other means of combating advanced security threats.
* Directly-integrated Intrusion Prevent Systems (IPSes).
* App control and awareness (so that problematic apps can be quickly identified and denied access).
* Upgrade paths that account for future security threats and info feeds.
  
<hr />

## 4. <a name="comparison">Comparing Four Vendors: Palo Alto, Fortinet, SonicWall, Sophos</a>

When comparing *Palo Alto*, *Fortinet*, *SonicWall*, and *Sophos* firewalls, Palo Alto's may be seen as the luxury choice: their software is easy to find, industry renowned, and highly secure, but purchase and implementation can be costly. Comparatively, Fortinet may be seen as a 'bang for your buck' option, with beginner-friendly usability and high performance at its lighter price point, SonicWall has value for budget-conscious small-to-medium sized organizations with a need for strong threat detection, and Sophos may also be a strong option for small-to-medium sized businesses with limited funding (plus it has the advantage of requiring less networking/security expertise than some other options). Thus, system complexity, budgeting, and integration/feature needs should be considered if selecting among these four vendors.

| *Consideration* | *Palo Alto* | *Fortinet* | *SonicWall* | *Sophos* |
| :---: | :---: | :----: | :----: | :----: |
| Target Audience | Large organizations needing comprehensive, deeply-integrated/granular security controls and high app visibility. | Budget-conscious organizations with considerable system integration and high performance needs. | Budget-conscious and small organizations in need of a solution with strong threat detection capability. | Small-to-medium sized organizations with limited budgets and resources, and possibly less expertise. |
| Advantages | Zero-day threat and other malware detection and prevention (WildFire), threat and incident response (Unit 42), characteristic-based app identification (App-ID), and deep inspection capabilities. | Potential for quickly integrating security devices (using Security Fabric platform). Strong performance and scalability, can support advanced configurations (via FortiGate NGFW). Organized threat intelligence and incident response (FortiGuard Labs research). | Low cost, excellent threat detection, highly unlikely to register false positives (as tested by ICSA Labs). | Sophos Central provides a beginner-friendly management GUI. Less expensive than other options, yet has high availability and security for both networks and endpoints. |
| Disadvantages | Expensive, may need expertise for advanced configurations, may require support for implementations and learning of centralized management platform. | Possible licensing needs for complex features, setup and policy management can be confusing for newer networkers, logging can be limited in comparison to other options. | User interface can be challenging for beginners, may not be as resourceful of an option for enterprises as some other options. | Capacity for advanced configurations may be limited, lacks the polish of Palo Alto and Fortinet solutions, and may not be a good fit for larger organization's needs (in comparison to Palo Alto's complex features and Fortinet's Security Fabric). |

<hr />

## 5. <a name="supplemental">Supplemental Resources</a>

* *[Palo Alto Next Generation Firewalls Official Webpage](https://www.paloaltonetworks.com/network-security/next-generation-firewall)*
* *[Fortinet Next Generation Firewalls Official Webpage](https://www.fortinet.com/products/next-generation-firewall)*
* *[SonicWall Firewalls Official Webpage](https://www.sonicwall.com/products/firewalls)*
