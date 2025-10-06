# Intro to Next-Generation Firewalls Overview Guide

**TODO:** A brief introductory guide to next-gen firewalls, and what separates them from other firewalls.

#### Table of Contents

1. [Five Categories of Firewalls](#categories)
2. [NGFW Definition and Features](#definition)
3. [Advantages Over Traditional Firewalls](#advantages)
4. [Comparing Three Vendors: Palo Alto, Fortinet, Sophos](#comparison)
5. [Supplemental Resources](#supplemental)

<hr />

## 1. <a name="categories">Five Categories of Firewalls</a>

**Five categories of firewalls include:**

*Packet Filtering Firewalls:* These are firewalls that examine packets' IP headers and discard the packets that have been flagged.

*Circuit-Level Gateway Firewalls:* Instead of investigating packets individually, these firewalls use network protocol session initiation messages (such as TCP handshakes) to flag content if it is malicious.

*Stateful Inspection Firewalls:* These firewalls utilize both session monitoring and packet filtering.

*Proxy Firewalls:* Also known as Application-Level Gateway Firewalls, these firewalls rely on HTTP request strings and destination/target ports for their conditional logic.

*Next-Generation Firewalls:* Next-Generation Firewalls (NGFWs) rely on context-awareness at the application-level with advanced intelligence, providing support against complex security threats.

<hr />

## 2. <a name="definition">NGFW Definition and Features</a>

<hr />

## 3. <a name="advantages">Advantages Over Traditional Firewalls</a>

<hr />

## 4. <a name="comparison">Comparing Three Vendors: Palo Alto, Fortinet, Sophos</a>

When comparing *Palo Alto*, *Fortinet*, and *Sophos* firewalls, Palo Alto's may be seen as the luxury choice: their software is easy to find, industry renowned, and highly secure, but purchase and implementation can be costly. Comparatively, Fortinet may be seen as a 'bang for your buck' option, with beginner-friendly usability and high performance at its lighter price point, and Sophos may be a strong option for small-to-medium sized businesses with limited funding and less networking/security expertise. Thus, system complexity, budgeting, and integration/feature needs should be considered if selecting among these three vendors.

| *Consideration* | *Palo Alto* | *Fortinet* | *Sophos* |
| :---: | :---: | :----: | :----: |
| Target Audience | Large organizations needing complex, deeply-integrated security and high app visibility. | Budget-conscious organizations with considerable system integration and high performance needs. | Small-to-medium sized organizations with limited budgets and resources, and possibly less expertise. |
| Advantages | Zero-day threat and other malware detection and prevention (WildFire), threat and incident response (Unit 42), characteristic-based app identification (App-ID). | Potential for quickly integrating security device (using Security Fabric platform), strong performance, and organized threat intelligence and incident response (FortiGuard Labs research). | Sophos Central provides beginner-friendly management interface. Less expensive than other options, yet has high availability. |
| Disadvantages | Expensive, may need expertise for advanced configurations, may require support for implementations and learning of centralized management platform. | Possible licensing needs for complex features, logging can be limited in comparison to other options. | Capacity for advanced configurations may be limited, and may not be a good fit for larger organization's needs (in comparison to Palo Alto's complex features and Fortinet's Security Fabric). |

<hr />

## 5. <a name="supplemental">Supplemental Resources</a>

* *[Palo Alto Next Generation Firewalls Official Webpage](https://www.paloaltonetworks.com/network-security/next-generation-firewall)*
* *[Fortinet Next Generation Firewalls Official Webpage](https://www.fortinet.com/products/next-generation-firewall)*
* *[SonicWall Firewalls Official Webpage](https://www.sonicwall.com/products/firewalls)*
