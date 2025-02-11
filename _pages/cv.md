---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Recent positions
- Since 2024: Research scientist in cybersecurity and artificial intelligence
    - Inria (Rennes, France)
    - Intrusion detection and security data generation
    - Also part-time professor at CentraleSupélec
- 2020--2024: Cybersecurity chair as an associate professor
    - CentraleSupélec and Inria (Rennes, France)
    - Intrusion detection and malware analysis
- 2018--2020: Postdoc in cybersecurity
    - LAAS-CNRS (Toulouse, France)
    - Intrusion detection based on machine learning
* 2015--2018: [PhD](https://www.theses.fr/2018TOU30182) in artificial intelligence
    - IRIT (Toulouse, France)
    - Preferences learning and application to e-commerce

## Experience

### Research projects
I am a member of several "PEPR Cybersécurité" projects:
- [Superviz](https://files.inria.fr/superviz/), on supervision for security
- [REV](https://rev.s3.eurecom.fr/), on vulnerability identification and exploitation

I am the Inria’s PI (principal investigator) of the [SecGen](https://files.inria.fr/secgen) associate team with CISPA. This project is dedicated to synthetic data generation for intrusion detection systems.

### Doctoral advisor
I am currently co-supervising 4 PhD students:
- Vincent Raulin on dynamic malware analysis (with Valérie Viet Triem Tong and Yufei Han)
- Grégor Quetel on intrusion detection system by semantics inference based on instrumented parsers (with Laurent Pautet, Thomas Robert and Eric Alata)
- Fanny Dijoud on intrusion detection system from both applications logs and network traffic packets (with Michel Hurfin, Frédéric Majorczyk and Barbara Pilastre)
- Solène Delourme, on automatic detection and response in SOC with generative AI (with Jean-François Lalande, Tony Quertier and Colin Leverger)

Alumni PhD:
- Maxime Lanvin on unsupervised intrusion detection in networks (with Ludovic Mé, Grégory Blanc, Yufei Han and Frédéric Majorczyk), defended in 2024
- Adrien Schoen on network packets generation for IDS evaluation (with Ludovic Mé, Éric Totel, Yufei Han and Frédéric Majorczyk), defended in 2024

I was also involved in various PhD: [Malcolm Bourdon](http://theses.fr/s261687) (defended in 2021), [Aliénor Damien](http://theses.fr/2020ISAT0001) (defended in 2020) and [Jonathan Roux](http://theses.fr/2020TOU30011) (defended in 2020).

### Teaching activity

I am a part-time professor at CentraleSupélec. You can find more details about my teaching [here](/teaching/).

### Expert assessments

I was a member of the working group that lead to the ANSSI publication [Building trust in AI through a cyber risk-based approach](https://cyber.gouv.fr/en/publications/building-trust-ai-through-cyber-risk-based-approach).

### Scientific events and dissemination
- ["Hands-on machine learning for security" event](https://team.inria.fr/cidre/hands-on-machine-learning-for-security/), sponsored by the "GDR Sécurité Informatique"
- Seminars of the CIDRE team (<https://team.inria.fr/cidre/research/seminars/>) since 2020 (about 50 talks) and of the PIRAT team (<https://team.inria.fr/pirat/pirat-biweekly-seminars/>) since 2024
- Doctoral paper reading group "Papers Please" for CIDRE (<https://team.inria.fr/cidre/papers-please/>) since 2022 and for PIRAT (<https://team.inria.fr/pirat/papers-please/>) since 2024
- Youtube page of the team (<https://www.youtube.com/@pirat-research-team>) since 2020
- Various scientific events in the team

### PhD defense jury member
- Hamdi Friji (2024, Télécom SudParis)
- Léo Lavaur (2024, IMT Atlantique)
- Mohamed El Bouazzati (2023, Université Bretagne Sud)
- Malcolm Bourdon (2021, LAAS-CNRS)

### PC member and reviewer

#### Security conferences
- RESSI 2025
- THCon 2022, 2023, 2024, 2025
- ERTS 2024
- EICC 2021, 2023
- DSN 2022
- Doctoral Forum of DSN 2020
- ISSRE 2020

#### Artificial intelligence conferences
- ARTMAN 2023, 2024
- ECAI 2023
- AAAI 2021, 2022
- IJCAI 2020
- RJCIA 2019, 2020

#### Journals
- IEEE Network
- Transactions on Computers
- International Journal of Information Security
- Computers & Security
- Journal of Computer Security

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Recent talks
  {% assign counter = 0 %}
  <ul>{% for post in site.talks reversed %}
    {% if counter < 5 %}
      {% include archive-single-cv.html %}
      {% assign counter = counter | plus: 1 %}
    {% endif %}
  {% endfor %}</ul>

