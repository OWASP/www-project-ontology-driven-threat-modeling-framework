---

layout: col-sidebar
title: OWASP Ontology Driven Threat Modeling Framework
tags: OdTM
level: 1
type: tool
pitch: OWASP Ontology-driven Threat Modelling (OdTM) framework is a set of means for implementation of an ontological approach into automatic threat modelling of computer systems.

---

## What is OdTM?

OWASP Ontology-driven Threat Modelling (OdTM) framework is a set of means for implementation of 
an ontological approach into automatic threat modelling of computer systems.


### Description

The OdTM framework enables formalization of security related knowledge (architectural components and associated threats and countermeasures)
of different computer system types (architectural domains) in form of domain-specific threat models, or ontologies in the OWL (Web Ontology language) format.
That gives a useful way to collect the knowledge by security professionals and share with software architects, developers and users.
Also, the framework allows to describe a computer system in term of a domain-specific threat model with a DFD (data flow diagram), 
and use automatic reasoning procedures to build a threat model (relevant threats and countermeasures) of the system. 
Such a feature makes it easily automation of the threat modelling process.

Our goals are: 
* to maintain a base threat model (ontology) that enables creation of domain-specific threat models;
* to create different domain-specific threat models (for Web applications, Cloud computing, Internet of Things etc.);
* to develop an ontology-driven threat rule engine, and a GUI editor of domain-specific threat models.

### Roadmap

**Vision**: Involve the ontology-driven approach into automatic threat modelling for collecting, 
sharing and usage of the strict security-related knowledge through creation of domain-specific threat models and development of software tools.

**Initial plan**:
* Milestone 1: To implement a threat rule engine (OdTM Server) as a remote JSON API service.
* Milestone 2: To implement software modules, providing integration of OdTM Server with GUI threat modelling tools.
* Milestone 3: To develop various domain-specific threat models (the cloud computing domain as the first step).
* Milestone 4: To implement a GUI editor of domain-specific threat models (OdTM Studio).

**Technology**: Knowledge engineering, OWL (Web Ontology Language), Java, the OWL API library, the Jackson JSON library.

### Related Projects

from OWASP:
* [OWASP Threat Dragon](https://owasp.org/www-project-threat-dragon/)
* [OWASP PyTM (Pythonic Threat Modeling)](https://owasp.org/www-project-pytm/)

third-party:
* [OWL API](https://github.com/owlcs/owlapi)
* [HermiT Reasoner](http://www.hermit-reasoner.com/)

### Getting Involved

Everyone is welcome and encouraged to participate in the OWASP OdTM project with contributions 
(github pulls, issues, clons etc.), collaboration, feedback, and promotion.
