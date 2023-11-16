# DAD-CDM Charter

## 1. Project Name

### 1.1 Full Name

Common Data Model for Defending Against Disinformation

### 1.2 Short Name

dad-cdm

## 2. Abstract

The DAD-CDM open project will address disinformation[^1] and related subjects (e.g., ‘MDM’ (misinformation, disinformation, malinformation), influence operations, online harm campaigns, and ‘FIMI’ – Foreign Information Manipulation and Interference).   ‘Defending’ includes taking the fastest and most effective action in real time, as well as building strategies, plans and capabilities to manage disinformation risks.

The project is born from the need to defend against this existential, ‘whole of society’ problem with collective and coordinated action.  Standards, in common approaches and language, are critical resources to achieving the coordination required.  As an illustration, it is easy for a single person to walk into a building and maliciously and falsely shout “Fire”.  Responding to this involves many people working together to resolve the disruption. This project seeks to address the similar attacker-defender asymmetry in the arena of large-scale disinformation, which is increasingly subject to creation and propagation by artificial intelligence and other automated means.

The project is committed to  providing recommendations to extend the STIX[^2] standard with disinformation-related objects and relationships, in order to model disinformation and hybrid cyber-disinformation threats. The project might also – in the longer term - provide recommendations to extend STIX with objects and relationships to model mitigations by defenders, but will have the option to consider adopting other open standards or creating a new standard for this purpose, if absolutely necessary.     

The project outputs will include a sufficient set of data objects, taxonomies, data operators and exchange messages to support robust and secure exchanges of threat and mitigation information.  The output is expected to complement and work in concert with larger efforts to guide, coordinate and promote sharing of disinformation mitigation resources offered and planned by others across the global ‘disinformation defender’ community. 

As an open standard, the project's outputs should be freely available for use by any parties seeking disinformation threat data exchange and risk management and should be capable of deployment by diverse independently-developed systems and software including open source software.  

## 3. Statement of Purpose

The relatively new phenomenon of internet-enabled disinformation, and other related areas – delivered in highly-targeted ways and at unprecedented scale – threatens peace and democracy, and how we manage macro policy matters such as pandemics and climate change.

Parties defending against disinformation attacks – or managing/mitigating the risks – will benefit from neutral, shared taxonomies, data structures, and shared remediation tactics.  The technical challenge is similar to that faced by defenders against cybersecurity threats:

* Firstly, to define the Tactics, Techniques, and Procedures (TTPs) used in disinformation campaigns with shared definitions/descriptions.  TTPs serve as, among other things, key detectable elements or ‘signatures’ of disinformation efforts.
* Secondly, to correlate these TTPs and related data objects to corresponding defender tasks, such as the tagging of behaviors detected online, sharing data, analyzing data, producing reports, and identifying available countermeasures.

The field of cybersecurity – being both more mature than defending against disinformation, as well as being related within wider ‘hybrid’ threats – provides existing models, protocols, policies, systems etc. which can be leveraged for proven pathways and accelerated development.
To-date, the DISARM Framework has standardized the codification of adversary behavior TTPs.  These behaviors are the ‘B’ in the ‘ABCDE’ model, which also includes Actors, Content, Distribution and Effect.  A behavior TTP is represented in machine readable form as the STIX Domain Object (SDO) ‘Attack Pattern’[^3]. Taking other examples – e.g. Content (analyzing narratives using NLP or fact-checking content against knowledge databases), or Distribution (analyzing the provenance, dissemination and targeting of disinformation through online channels such as social media, messaging apps etc.) – we want narrative frameworks, fact-checking tools and social media monitoring tools to be able to interoperate with DISARM's Behavioral framework and other frameworks and other tools, so that the community can bring all threat data together in machine readable format at speed and scale.

A primary purpose for this Open Project is to define the broader data model for characterizing disinformation threats so that we can leverage what exists in STIX today and extend it as necessary and so that we can model hybrid cyber-disinformation threats.

The project committee might – in the longer term – also look at risk, countermeasure and playbook extensions of the data model, as well as knowledge representation and semantic modeling[^4].  However, the intention of this Charter is to ensure we ‘walk before we run’ and build a solid foundation for further development of the model.

As a parallel purpose and output from the DAD-CDM project, the intention is to clarify terminology; from ‘disinformation’ itself at the highest level, down to a taxonomy that underpins all aspects of the data model.  The project will aim to bring the defender community together to create a common lexicon or dictionary of terms that we can all agree on.

The project will aim to bring the best minds of the community together on this question. The community can decide collectively the best way to govern such a lexicon going forward.

Two further key aspects of the project purpose:

(a) there is a need for defenders to act quickly.  To identify and respond to disinformation that is generated rapidly (e.g. using generative AI) and/or spread rapidly (e.g. using botnets or exploitation of recommendation algorithms) in time for responses to be effective (eg. filling information voids; pre-bunking; inoculating) because cognitive dissonance in ‘unlearning’ is just too high.   We therefore need to martial the data objects and relationships to model an adversarial campaign and propose STIX amendments or extensions to the CTI TC; making sure this helps the entire counter-disinformation community, and we can capture all the behaviors and observables of an adversary's campaign and characterize the threat actor[^5].

(b) to be able to model hybrid threats such as cyber-enabled influence (e.g. hack and leak) or internet-enabled cyber (e.g., clickbait) with as little redundancy as possible – i.e., we want to be able to leverage the existing data model for cyber as much as possible aka STIX and complement the data model for cyber where necessary.

In summary, the primary goal of this project is to prepare the data model for proposals to the CTI TC, and leverage and/or extend STIX, working in phases, walking before we run, and biting off bits of the data model at a time according to the most pressing needs.

## 4. Business Benefits 

As already said, there is a significant asymmetry between attackers and defenders, given the time, cost, effort and complexity involved in coordinating counter-disinformation efforts, across disciplines, sectors, national borders and spoken languages.  The common data model for defending against disinformation is a critical dependency to enabling this coordination.   

Specific benefits flowing from the DAD-CDM project include:

* Reduced friction and confusion caused by the lack of ‘common language’
* Enabling machine readability for data sharing with speed and at scale
* Increased capability for cooperation and coordination across organizations
* Faster sharing of rapid alerts to initiate ‘whole of society’ coordination
* Easier sharing of relevant countermeasures to coordinate responses
* Enabling cross-border and multi-language response coordination
* More reports tagged and analyzed in a consistent manner
* Increased sharing of reports more easily understood – individually and in aggregate
* Ability to compare/contrast actor(s) behavior between actors and/or over time.


All of the above, taken together, deliver higher-level benefits, including:

* Greater speed in responding to live disinformation attacks
* Increased ability to select more appropriate, relevant and effective countermeasures
* Enabling the selection of more strategic (and less ‘whack-a-mole’) countermeasures
* Earlier identification of disinformation attacks, improving defensive outcomes
* Greater consistency of approach across platform in-house trust & safety teams
* Increased clarity for operating arrangements between platforms and their regulators
* Enabling the development of shared infrastructure, such as disinformation ISAC/ISAOs.

Given the ‘whole of society’ approach that is required, the benefits will be applied in different ways across the primary audiences[^6] for DAD-CDM.

## 5. Normative Scope

The DAD-CDM data standard outputs will support a broader set of guidance tools, frameworks, and supporting resources, which may be supplied by multiple parties.  

The standards outputs of DAD-CDM will:

* be agnostic as to system, software platforms and toolsets
* be extensible, so as to permit local adaptation
* re-use and adapt suitable elements of existing open standards for threat information and mitigation – primarily STIX 
* consider leveraging existing adaptations of cybersecurity threat data tools to the disinformation space, where feasible, in preference to reinventing the wheel
* potentially, initially conduct a review and gap analysis of the relevant data elements of STIX, for use or adaptation
* incorporate existing frameworks and/or elements of frameworks[^7] into the wider model – generally building with and/or on the more complete/mature assets that already exist
* assume, and be designed to interact with, the development of broader voluntary networks of shared data and resources among good faith actors and defenders against disinformation
* be designed to facilitate and encourage sharing of data, signals and tactics among and across user and defender communities
* be designed to work with and support multiple sources of best practices and mitigation methods, understanding that a variety of voluntary sharing communities may evolve, each with their own guidance and information sharing partners and patterns
* consider the development of ancillary and training material on the standard's contents.
* potentially evaluate and incorporate semantic knowledge representation standards into the committee’s work, and may choose to specify optional or canonical methods for their use within the committee’s specifications.

Areas of work that are out of scope for this project:

* Primary authorship of software:  the project may support and welcome testing of code and software tools that use and assist with use of DAD-CDM's elements, but will not act as the primary author of such software.
* Adjudicating specific threat data:  populating DAD-CDM’s data elements, by declaring specific identities of Actors, Threats, and so forth, will be left to the users of the standard, and will not be managed or arbitrated by this project.  As with STIX, different user bases may develop their own different sets of shared data objects.
* Adjudicating fact versus fiction:  attempts to discern truth from falsehood, through fact-checking or other means, will be left to the users of the standard, and will not be managed or arbitrated by this project. 
* Sharing community formation:  it is anticipated that additional guidance on threat sharing, and the formation of threat sharing communities – such as Information Sharing Analysis Organizations (ISAOs) – will be accelerated by the standard.  This project will encourage and welcome feedback from such efforts, and may cooperate in developing vendor-neutral tool guidance, but will not host, endorse, or prefer specific ISAOs or threat sharing networks.  

## 6. Relationship to Other Projects

Given the nature of this project, there is a potential relationship to most – if not all – members of the wider disinformation defender community.  All of these organizations and individuals are likely connected to one or more projects of some type and size.  

There are already thousands of organizations across most sectors and disciplines, and often gathered in local/interest communities.  Most immediately, DAD-CDM needs to work with leaders across the ‘Network of networks’ and those with directly-relevant skills, experience and assets (in the IP of other frameworks and/or technologies).

This project asks those who participate in this Open Project to come with open minds, open hands and open hearts.   Building common standards relies on a collective willingness to raise our eyes above certain levels to the goal of addressing the attacker-defender asymmetry – we are all, effectively, one team against those who attack our collective understandings, our trust in our institutions, our democracies and our collective peace.

Within the project, disagreements will be inevitable.  In order to keep moving forward, disagreements will be resolved by a clear governance process.  This will allow for more time to be taken over questions that materially affect our collective ability to act, rather than questions which are more academic/semantic in nature.  We encourage everyone to stay a part of the process, irrespective of the way that decisions go.

Whichever sector participants belong to, and whether any IP they bring is open or proprietary, collaboration will be essential – even with those who might be seen as competitors.  Further still, reaching out to competitor organizations will be encouraged.

In addition to other framework projects, a significant number of tools have been created, and listed/reviewed by the Disinformation Cloud project under the Global Engagement Center of the US Department of State.  All such tools will benefit from more consistent data standards that will reduce friction in data mobility, increasing their efficiency, effectiveness and interoperability – helping to grow their market as a whole.

In addition to the significant number of existing disinformation frameworks already known to Oasis Open and the project convenors, outreach will continue in order to help ensure we have identified all options that exist in the wider disinformation defender community.

The approach, in building DAD-CDM will be to identify the best of what already exists – as potential elements/modules – and to build with these. 

The project anticipates coordination with the OASIS Cyber Threat Intelligence TC (source of the STIX and TAXII standards). It also foresees possible coordination with other existing and emerging open standards initiatives related to information security and integrity[^8].

## 7. Repositories and Licenses

The project will be conducted under [CC-BY-4.0], the [Creative Commons Attribution 4.0 International](https://github.com/DAD-CDM/dad-cdm-admin/blob/main/LICENSE.md)[^9] under the OASIS Open Project Rules.
 
## 8. Initial Contributions from Existing Work

Contributions will likely include leveraging the work of the [EEAS](https://www.eeas.europa.eu/eeas/1st-eeas-report-foreign-information-manipulation-and-interference-threats_en)  in partnership with OpenCTI in extending STIX (eg. Channel and Narrative).  Existing DISARM data structures relevant to this project are anticipated to be contributed:  including the DISARM OBJECTS within the DISARM [Red and Blue frameworks](https://github.com/DISARMFoundation/DISARMframeworks).

While these contributions are brought together under an overarching conceptual wider framework, the intended outputs are to leverage the existing STIX IP and not to create a fresh standard. This project does not, therefore, rely on contributors relinquishing any IP which they own to OASIS Open or any other project participant.
___

[^1]: When we refer to ‘disinformation’, this is shorthand throughout the document for disinformation and the wider terms and fields related to it, including those stated above 

[^2]: The current version of STIX is Rev. 2.1.  All references in this document are to this version.  Hereafter in this document, it is referred to as 'STIX'.

[^3]: DISARM-specific TTPs, might, for example, be called as ‘external references’, just as the current Mitre Corporation CAPEC (Common Attack Pattern Enumeration and Classification) data objects are called within the Attack Pattern SDO. This would make the use of STIX for expressing DISARM data objects highly extensible and easily adoptable for vendors that have already implemented solutions using the STIX data model. 

[^4]: This might, for example, build on the TAC-TC’s existing work with the semantic technology tools of RDF and OWL.

[^5]: In the medium to long term, the project committee might decide to make informed proposals to the TAC TC. If we decide to incorporate the data modeling of the defense in our charter, then we can also then make an informed proposal to the CACAO TC for implementing playbooks using the DISARM Framework.

[^6]: Audiences include:  Government analysts and policy makers; Platforms; Journalists and the media; Regional responders; the Intelligence community; Law enforcement; Disinformation trainers/simulators and tool providers.

[^7]: In addition to STIX (Threat Actor, Incident, Observable, Target, Campaign, Course of Action, TTP, etc.), existing Frameworks might include: ABCDE model (Actor, Behavior, Content, Degree of Distribution, Effect); DISARM Red, Blue and wider data model (https://github.com/DISARMFoundation/DISARMframeworks); Recorded Future’s Diamond Model for Influence Operations (original model by Caltagirone, Pendergast, Betz); Terp-Breuer Campaign Pyramid (Campaign, Incident, Narrative, Artefact); Atlantic Council's SCOTCH model (Source, Channel, Objective, Target, Composition, Hook); SP!CE (MITRE/Florida International University), NCFG (University of Washington), BEND (Carnegie Mellon University) and RESIST 2 (UK Government).

[^8]: Such as the Open Cybersecurity Alliance (indicators of behavior and automation interoperability), the C2PA or Coalition for Content Provenance and Authenticity (certifying the source and history of media content), the W3C’s Credible Web or Credible Web Community Group of the World Wide Web Consortium (web content credibility indicators), and the JPEG Fake Media initiative.  

[^9]: The ShareAlike license specifically, like a GPL license, would render the data standard work ineligible for ISO or ITU submission.  This will be for discussion by the project, if needed.
