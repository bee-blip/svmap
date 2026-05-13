# Social Vulnerability Map (SVMap)

The SVMap is a relational architecture with 240 endogenous AI variables plus exogenous SVM-E001 to E030 covering ecological, economic, physical, and governance layers. The schema includes Domain, Ecosystem Layer, Stage, Origin, Propagates To/From, Affected Actors, and a Regulatory STRAPS Status.`dataset/social_vuln_risk-prop.csv`

Regulatory STRAPS is a security-first, intersectional framework for upstream regulatory design comprising six principles: 
- Streamlined: no jurisdictional friction, no duplication, no ambiguity about who is responsible. 
- Transparent: decisions, classifications, enforcement outcomes, and infrastructure costs are visible to those affected by them.
- Risk-based enforcement: enforcement intensity that matches the severity and irreversibility of potential harm.
- Accountable: there is always a named, reachable body responsible for every decision that affects a person.
- Preemptive intervention: governing for foreseeable harm before it materialises, not after.
- Systemic coherence: governance system that does not operate in isolation from governance of any governance or commitments that are upstream to the output.

It's a case for effective regulation requirements to govern the conditions under which a system operates. It emphasises on tracing root-cause burden displacement rather than just cataloging problems, and gives you permission to be partial, focused, and diagnostic rather than comprehensive and prescriptive. *paper is in progress*

Additionally, to the SVMap, I have added some authoritative public datasets like the UN Universal Human Rights Index (UHRI) from OHCHR, which catalogues recommendations from Treaty Bodies, Special Procedures, UPR cycles tagged by right, theme, affected persons, and SDG. Other relevant inequity sources: World Bank Poverty & Inequality Platform, OECD inequality indicators, UNDP HDI/MPI, CEDAW and CRPD thematic indices.

The consolidated the schema of the SVMap architecture holds both AI-origin variables and human-rights-origin variables in one shared relational model. Currently it's without UIDs and uses a portable structural schema. This is a work in progress. `dataset/svmap_consolidation-WIP.csv`

`dataset/ai_risk_variables.csv` is the outcome of a different study that initiated this project. 
`dataset/WID_countries.csv` is the list of countries who's data was available at WID. 
