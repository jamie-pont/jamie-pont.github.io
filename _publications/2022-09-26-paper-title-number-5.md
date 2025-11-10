---
title: "Hunting High or Low: Evaluating the Effectiveness of High-Interaction and Low-Interaction Honeypots"
collection: publications
category: manuscripts
permalink: /publication/2022-09-26-paper-title-number-5
excerpt: 'This paper presents a detailed analysis of both high-interaction and low-interaction honeypots to allow researchers to better understand and develop such techniques in future research.'
date: 2022-09-26
venue: 'International Workshop on Socio-Technical Aspects in Security'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://kar.kent.ac.uk/102122/1/STAST2022.pdf'
bibtexurl: 'https://citation-needed.springer.com/v2/references/10.1007/978-3-031-83072-3_2?format=bibtex&flavour=citation'
citation: 'Kocaogullar, Y., Cetin, O., Arief, B., Brierley, C., Pont, J. and Hernandez-Castro, J., 2022, September. <q>Hunting high or low: evaluating the effectiveness of high-interaction and low-interaction honeypots</q>. In <i>International Workshop on Socio-Technical Aspects in Security (pp. 14-30)</i>. Cham: Springer Nature Switzerland.'
---
Background. Honeypots are cybersecurity mechanisms that are set up as decoys in networks to lure and monitor attackers trying to compromise vulnerable systems. Two commonly used honeypot designs are high-interaction and low-interaction honeypots, which differ in the amount of interplay that the attackers are allowed to do. So far, the effectiveness of high-interaction and low-interaction honeypots has been understudied, making it difficult for security teams to choose between different honeypot technologies.

Aim. The aim of this paper is to compare the effectiveness of high-interaction and low-interaction honeypots through real-world data.

Method. We deployed multiple Elasticsearch honeypot implementations to collect data: a closed-source high-interaction honeypot developed by the authors, and three types of open-source low-interaction honeypots (namely Elastichoney, Delilah and Elasticpot). The collected data came from 48 instances of high-interaction honeypots and 111 instances of low-interaction honeypots, over a period of 14 days.

Results. We found that low-interaction honeypots captured only a fraction of the attacks that high-interaction honeypots can catch. On the other hand, low-interaction honeypots are simpler, more efficient to run due to their low usage of resources, and easier to deploy. In our dataset, high-interaction honeypots captured 76.12% of the total attack packets and attracted 70.61% of the unique attacker IPs. In comparison, low-interaction honeypots performed a lot worse in collecting attack data; they only managed to capture 23.88% of the total attack packets and attracted 29.39% of the unique attacker IPs.

Conclusions. In this paper, we present an experiment that evaluated and compared the effectiveness of high-interaction and low-interaction honeypots in terms of the amount and the type of information collected from attacks targeting them. It follows from our findings that it would be wiser to either concentrate solely on using high-interaction honeypots, or to increase the effectiveness of low-interaction ones by automatically changing each static value during deployment and/or by increasing the mimicking capabilities of low-interaction honeypots.