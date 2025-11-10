---
title: "Persistence in Linux-Based IoT Malware"
collection: publications
category: manuscripts
permalink: /publication/2020-11-23-paper-title-number-3
excerpt: 'This paper explores the viability of persistence in Linux-based IoT malware, demonstrating the ability of attackers to maintain control of a compromised device even after it has been restarted. Several countermeasures are also identified.'
date: 2020-11-23
venue: 'NordSec: Nordic Conference on Secure IT Systems'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://kar.kent.ac.uk/84209/1/Persistence_in_IoT_Malware_Camera_Ready.pdf'
bibtexurl: 'https://citation-needed.springer.com/v2/references/10.1007/978-3-030-70852-8_1?format=bibtex&flavour=citation'
citation: 'Brierley, C., Pont, J., Arief, B., Barnes, D.J. and Hernandez-Castro, J., 2020, November. <q>Persistence in linux-based iot malware</q>. In <i>Nordic Conference on Secure IT Systems (pp. 3-19)</i>. Cham: Springer International Publishing.'
---
The Internet of Things (IoT) is a rapidly growing collection of “smart” devices capable of communicating over the Internet. Being connected to the Internet brings new features and convenience, but it also poses new security threats, such as IoT malware. IoT malware has shown similar growth, making IoT devices highly vulnerable to remote compromise. However, most IoT malware variants do not exhibit the ability to gain persistence, as they typically lose control over the compromised device when the device is restarted. This paper investigates how persistence for various IoT devices can be implemented by attackers, such that they retain control even after the device has been rebooted. Having persistence would make it harder to remove IoT malware. We investigated methods that could be used by an attacker to gain persistence on a variety of IoT devices, and compiled the requirements and potential issues faced by these methods, in order to understand how best to combat this future threat. We successfully used these methods to gain persistence on four vulnerable IoT devices with differing designs, features and architectures. We also identified ways to counter them. This work highlights the enormous risk that persistence poses to potentially billions of IoT devices, and we hope our results and study will encourage manufacturers and developers to consider implementing our proposed countermeasures or create new techniques to combat this nascent threat.