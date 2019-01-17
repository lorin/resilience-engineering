# Resilience Engineering notes

This file contains notes about people active in resilience engineering, organized
alphabetically. I'm using these notes to help me get my head around the
different players and associated concepts.

For each person, I list concepts that they reference in their writings, along
with some of their publications. The publications listed aren't comprehensive:
they're ones I've read or have added to my to-read list. 

* [John Allspaw](#john-allspaw)
* [Lisanne Bainbridge](#lisanne-bainbridge)
* [Johan Bergström](#johan-bergström)
* [Todd Conklin](#todd-conklin)
* [Richard I. Cook](#richard-i-cook)
* [Sidney Dekker](#sidney-dekker)
* [John C. Doyle](#john-c-doyle)
* [Anders Ericsson](#anders-ericsson)
* [Meir Finkel](#meir-finkel)
* [Erik Hollnagel](#erik-hollnagel)
* [Gary Klein](#gary-klein)
* [Nancy Leveson](#nancy-leveson)
* [Elinor Ostrom](#elinor-ostrom)
* [Jean Pariès](#jean-paries)
* [Emily Patterson](#emily-patterson)
* [Charles Perrow](#charles-perrow)
* [Shawna J. Perry](#shawna-j-perry)
* [Jens Rasmussen](#jens-rasmussen)
* [James Reason](#james-reason)
* [Nadine Sarter](#nadine-sarter)
* [Diane Vaughan](#diane-vaughan)
* [Robert L. Wears](#robert-l-wears)
* [David Woods](#david-woods)
* [John Wreathall](#john-wreathall)

## John Allspaw

Allspaw is the former CTO of Etsy. He applies concepts from resilience engineering to the tech industry.
He is one of the founders [Adaptive Capacity Labs](http://www.adaptivecapacitylabs.com/), a resilience engineering consultancy.

### Selected publications

* [Trade-Offs Under Pressure: Heuristics and Observations Of Teams Resolving Internet Service Outages](https://www.researchgate.net/publication/295011072_Trade-Offs_Under_Pressure_Heuristics_and_Observations_Of_Teams_Resolving_Internet_Service_Outages)
* [Incidents as we Imagine Them Versus How They Actually Are](https://community.pagerduty.com/t/incidents-as-we-imagine-them-versus-how-they-actually-are-with-john-allspaw/2708) (video)
* [Debrief Facilitation Guide](http://extfiles.etsy.com/DebriefingFacilitationGuide.pdf)
* [Fault Injection in Production: Making the case for resiliency testing](http://queue.acm.org/detail.cfm?id=2353017)

## Lisanne Bainbridge

Bainbridge is (was?) a psychology researcher. (*I have not been able to find any recent information about her*).

### Contributions

#### Ironies of automation

Bainbridge is famous for her [Ironies of automation] paper, which continues to
be cited.

## Concepts
* automation
* design errors
* human factors/ ergonomics 
* cognitive modelling 
* cognitive architecture 
* mental workload 
* situation awareness
* cognitive error 
* skill and training 
* interface design 

## Selected publications
* [Ironies of automation]


[Ironies of automation]: https://doi.org/10.1016/0005-1098(83)90046-8

## Johan Bergström

[Bergstrom](http://www.jbsafety.se/p/about-me.html) is a safety research and
consultant. He runs the [Master Program of Human Factors and Systems
Safety](http://www.humanfactors.lth.se/msc-programme/) at Lund University.

### Concepts

* Analytical traps in accident investigation
   - Counterfactual reasoning
   - Normative language
   - Mechanistic reasoning

### Selected publications

* [Resilience engineering: Current status of the research and future challenges](https://www.sciencedirect.com/science/article/pii/S0925753516306130)
* [Rule- and role retreat: An empirical study of procedures and resilience](https://www.researchgate.net/publication/50917226_Rule-_and_role_retreat_An_empirical_study_of_procedures_and_resilience)

### Videos 
* [Three analytical traps in accident investigation](https://www.youtube.com/watch?v=TqaFT-0cY7U)


## Todd Conklin

Conklin's books are on my reading list, but I haven't read anything by him
yet. I have listened to his great [Preaccident investigation
podcast](https://preaccidentpodcast.podbean.com/).

### Selected publications
* [Pre-accident investigations: an introduction to organizational safety](https://www.amazon.com/Pre-Accident-Investigations-Todd-Conklin/dp/1409447820)
* [Pre-accident investigations: better questions - an applied approach to
  operational learning](https://www.amazon.com/gp/product/1472486137)

## Richard I. Cook

Cook is a medical doctor who studies failures in complex systems.  He is one of the founders [Adaptive Capacity Labs](http://www.adaptivecapacitylabs.com/), a resilience engineering consultancy.

### Concepts
* complex systems
* degraded mode
* sharp end / blunt end
* Going solid
* Cycle of error


### Selected publications

* [How complex systems fail](http://web.mit.edu/2.75/resources/random/How%20Complex%20Systems%20Fail.pdf)
* [Distancing through differencing: An obstacle to organizational learning following accidents](https://www.researchgate.net/publication/292504703_Distancing_through_differencing_An_obstacle_to_organizational_learning_following_accidents)
* [Being bumpable](http://csel.eng.ohio-state.edu/productions/woodscta/media/beingbump.pdf)
* [Behind Human Error](https://www.amazon.com/gp/product/B075QFGTNP/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B075QFGTNP&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Incidents - markers of resilience or brittleness?](https://www.researchgate.net/publication/292504952_Incidents_-_markers_of_resilience_or_brittleness)
* [“Going solid”: a model of system dynamics and consequences for patient safety](https://qualitysafety.bmj.com/content/14/2/130)
* [Operating at the Sharp End: The Complexity of Human Error](https://www.researchgate.net/publication/313407259_Operating_at_the_Sharp_End_The_Complexity_of_Human_Error)
* [Patient boarding in the emergency department as a symptom of complexity-induced risks](https://www.researchgate.net/publication/312624891_Patient_boarding_in_the_emergency_department_as_a_symptom_of_complexity-induced_risks)


## Sidney Dekker

### Contributions

#### Drift into failure

Dekker developed the theory of *drift*, characterized by five concepts:

1. Scarcity and competition
1. Decrementalism, or small steps
1. Sensitive dependence on initial conditions
1. Unruly technology
1. Contribution of the protective structure


### Concepts
* Drift into failure
* New view vs old view of human performance
* Just culture
* complexity
* broken part
* Newton-Descartes
* diversity
* systems theory
* unruly technology
* decrementalism

### Selected publications

* [Drift into failure](https://www.amazon.com/Drift-into-Failure-Sidney-Dekker/dp/1409422216)
* [Reconstructing human contributions to accidents: the new view on error and performance](https://www.sciencedirect.com/science/article/pii/S0022437502000324)
* [The field guide to 'human error' investigations](https://www.amazon.com/Field-Guide-Understanding-Human-Error/dp/1472439058s://www.amazon.com/Field-Guide-Understanding-Human-Error/dp/1472439058)
* [Behind Human Error](https://www.amazon.com/gp/product/B075QFGTNP/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B075QFGTNP&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Rule- and role retreat: An empirical study of procedures and resilience](https://www.researchgate.net/publication/50917226_Rule-_and_role_retreat_An_empirical_study_of_procedures_and_resilience?enrichId=rgreq-23625e555a0d8e5250c74f24b5fd01ca-XXX&enrichSource=Y292ZXJQYWdlOzUwOTE3MjI2O0FTOjk3MzU5NjY5MjM1NzQ1QDE0MDAyMjM3NjI5NDY%3D&el=1_x_2&_esc=publicationCoverPdf)

## John C. Doyle

[Doyle](http://www.cds.caltech.edu/~doyle/wiki/index.php?title=Main_Page) is a
control systems researcher. He is seeking to identify the universal laws that capture the
behavior of resilient systems, and is concerned with the architecture of such
systems.

### Concepts
* Robust yet fragile
* Universal laws and arcthitectures
* conservation laws
* universal architectures
* layered architectures
* Highly optimized tolerance
* constraints that deconstrain


### Selected publications

* [Universal Laws and Archiectures](http://www.cis.upenn.edu/~ngns/docs/Review_2010/Doyle%20MURI%202010.pdf) (slides)
* [Contrasting Views of Complexity and Their Implications For Network-Centric Infrastructures](http://dx.doi.org/10.1109/TSMCA.2010.2048027)
* [The “robust yet fragile” nature of the Internet](https://doi.org/10.1073/pnas.0501426102)
* [Highly Optimized Tolerance: Robustness and Design in Complex Systems](http://dx.doi.org/10.1103/physrevlett.84.2529)
* [Robust efficiency and actuator saturation explain healthy heart rate control and variability](https://doi.org/10.1073/pnas.1401883111)
* [Architecture, constraints, and behavior](https://www.pnas.org/content/108/Supplement_3/15624)


## Anders Ericsson

Ericsson introduced the idea of *deliberative practice* as a mechanism for
achieving high level of expertise.

Ericsson isn't directly associated with the field of resilience engineering.
However, Gary Klein's work is informed by his, and I have a particular
interest in how people improve in expertise, so I'm including him here.

### Concepts

* Expertise
* Deliberative practice
* Protocol analysis

### Selected publications

* [Peak: secrets from the new science of expertise](https://www.amazon.com/Peak-Secrets-New-Science-Expertise/dp/1531864880/)
* [Protocol analysis: verbal reports as data](https://www.amazon.com/Protocol-Analysis-Revd-Verbal-Reports/dp/0262550237)

## Meir Finkel

Finkel is a Colonel in the Israeli Defense Force (IDF) and the Director of the IDF's Ground Forces Concept Development and Doctrine Department

### Selected publications
* [On Flexibility: Recovery from Technological and Doctrinal Surprise on the Battlefield](https://www.amazon.com/Flexibility-Recovery-Technological-Doctrinal-Battlefield/dp/0804774897/ref=sr_1_3?ie=UTF8&qid=1546046916&sr=8-3&keywords=on+flexibility)

## Erik Hollnagel

### Contributions

#### ETTO principle

Hollnagel proposed that there is always a fundamental tradeoff between
efficiency and thoroughness, which he called the *ETTO principle*.

#### Safety-I vs. Safety-II

Safety-I: avoiding things that go wrong
* looking at what goes wrong
* bimodal view of work and activities (acceptable vs unacceptable)
* find-and-fix approach
* prevent transition from 'normal' to 'abnormal'
* causality credo: believe that adverse outcomes happen because something goes
  wrong (they have causes that can be found and treated)
* it either works or it doesn't
* systems are decomposable
* functioning is bimodal

Saefty-II: performance variability rather than bimodality
* the system’s ability to succeed under varying conditions, so that the number
  of intended and acceptable outcomes (in other words, everyday activities) is
  as high as possible
* performance is always variable
* performance variation is ubiquitous
* things that go right
* focus on frequent events
* remain sensitive to possibility of failure
* be thorough as well as efficient

#### FRAM

Hollnagel proposed the Functional Resonance Analysis Method (FRAM) for modeling
complex socio-technical systems.

### Concepts
* ETTO (efficiency thoroughness tradeoff) principle
* FRAM (functional resonance analysis method)
* Safety-I and Safety-II
* things that go wrong vs things that go right
* causality credo
* performance variability
* bimodality
* emergence
* work-as-imagined vs. work-as-done

### Selected publications

* [The ETTO Principle: Efficiency-Thoroughness Trade-Off: Why Things That Go Right Sometimes Go Wrong](https://www.amazon.com/ETTO-Principle-Efficiency-Thoroughness-Trade-Off-Sometimes/dp/0754676781/ref=sr_1_1?s=books&ie=UTF8&qid=1545965837&sr=1-1&keywords=etto+principle)
* [From Safety-I to Safety-II: A White Paper](https://www.skybrary.aero/bookshelf/books/2437.pdf)
* [Safety-I and Safety-II: The past and future of safety management](https://www.amazon.com/gp/product/1472423089/ref=dbs_a_def_rwt_bibl_vppi_i0)
* [FRAM: The Functional Resonance Analysis Method: Modelling Complex Socio-technical System](https://www.amazon.com/gp/product/B010WIDYE8/ref=dbs_a_def_rwt_bibl_vppi_i15)
* [Joint Cognitive Systems: Patterns in Cognitive Systems Engineering](https://www.amazon.com/gp/product/0849339332/ref=x_gr_w_bb?ie=UTF8&tag=x_gr_w_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=0849339332&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Resilience Engineering: Concepts and Precepts](https://www.amazon.com/gp/product/B009KNDF64/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B009KNDF64&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [I want to believe: some myths about the management of industrial safety](http://dx.doi.org/10.1007/s10111-012-0237-4)

## Gary Klein

Klein studies how experts are able to quickly make effective decisions in high-tempo situations. 

### Concepts

* naturalistic decision making (NDM)
* intuitive expertise
* cognitive task analysis

### Selected publications

* [Sources of power: how people make decisions](https://www.amazon.com/gp/product/0262534290/ref=dbs_a_def_rwt_bibl_vppi_i0)
* [Working minds: a practitioner's guide to cognitive task analysis](https://www.amazon.com/gp/product/0262532816/ref=dbs_a_def_rwt_bibl_vppi_i5)
* [Patterns in Cooperative Cognition](https://www.researchgate.net/publication/262449980_Patterns_in_Cooperative_Cognition)
* [Can We Trust Best Practices? Six Cognitive Challenges of Evidence-Based Approaches](https://journals.sagepub.com/doi/abs/10.1177/1555343416637520?journalCode=edma)
* [Conditions for intuitive expertise: a failure to disagree](http://dx.doi.org/10.1037/a0016755)

## Nancy Leveson

Nancy Leveson is a computer science researcher with a focus in software safety.

### Contributions

#### STAMP

Leveson developed the accident causality model known as STAMP: the Systems-Theoretic Accident Model and Process.

See [STAMP](stampm.d) for some more detailed notes of mine.

### Concepts

* Software safety
* STAMP (systems-theoretic accident model and processes)
* STPA (system-theoretic process analysis) hazard analysis technique
* CAST (causal analysis based on STAMP) accident analysis technique
* Systems thinking
* hazard
* interactivy complexity
* system accident
* dysfunctional interactions
* safety constraints
* control structure
* dead time
* time constants
* feedback delays

## Selected publications
* [A New Accident Model for Engineering Safer Systems](http://sunnyday.mit.edu/accidents/safetyscience-single.pdf)
* [Engineering a safer world](https://mitpress.mit.edu/books/engineering-safer-world)
* [STPA Handbook](http://psas.scripts.mit.edu/home/get_file.php?name=STPA_handbook.pdf)
* [Safeware](https://www.amazon.com/Safeware-Computers-Nancy-G-Leveson/dp/0201119722)
* [Resilience Engineering: Concepts and Precepts](https://www.amazon.com/gp/product/B009KNDF64/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B009KNDF64&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [High-pressure steam engines and computer software](http://dx.doi.org/10.1145/143062.143076)

## Elinor Ostrom

[Ostrom](http://elinorostrom.com/) was a Nobel-prize winning economics and
political science researcher.

### Selected publications
* [Coping with tragedies of the commons](https://www.annualreviews.org/doi/abs/10.1146/annurev.polisci.2.1.493)
* [Governing the Commons: The Evolution of Institutions for Collective Action](https://www.amazon.com/Governing-Commons-Evolution-Institutions-Collective/dp/1107569788)

### Concepts

* tragedy of the commons
* polycentric governance
* social-ecological system framework

## Jean Pariès

Pariès is the president of [Dédale](http://www.dedale.net/dedale_en/), a safety and human factors consultancy.

### Selected publications
* [Resilience engineering in practice: a guidebook](https://www.crcpress.com/Resilience-Engineering-in-Practice-A-Guidebook/Paries-Wreathall-Hollnagel/p/book/9781472420749)

# Emily Patterson

[Patterson](https://hrs.osu.edu/faculty-and-staff/faculty-directory/patterson-emily)
is a researcher who applies human factors engineering to improve patient safety
in healthcare.

### Selected publications

* [Patient boarding in the emergency department as a symptom of complexity-induced risks](https://www.researchgate.net/publication/312624891_Patient_boarding_in_the_emergency_department_as_a_symptom_of_complexity-induced_risks)

## Charles Perrow

Perrow is a sociologist who studied the Three Mile Island disaster.

### Concepts
* Normal accidents
* Common-mode

### Selected publications
* [Normal accidents: living with high-risk technologies](https://www.amazon.com/Normal-Accidents-Living-Technologies-Updated-ebook/dp/B00CHRINUI)

## Shawna J. Perry

Perry is a medical researcher who studies emergency medicine.

### Concepts
* Underground adaptations
* Articulated functions vs. important functions
* Unintended effects
* Apparent success vs real success
* Exceptions
* Dynamic environments

### Selected publications

* [Underground adaptations: case studies from health care](https://doi.org/10.1007/s10111-011-0207-2)
* [Can We Trust Best Practices? Six Cognitive Challenges of Evidence-Based Approaches](https://journals.sagepub.com/doi/abs/10.1177/1555343416637520?journalCode=edma)


## Jens Rasmussen

Jens Rasmussen was a very influential researcher in human factors and safety systems.

### Contributions

#### Skill-rule-knowledge (SKR) model

TBD

#### Dynamic safety model

Rasmussen proposed a state-based model of a socio-technical system as a system
that moves within a region of a state space. The region is surrounded by
different boundaries:

* economic failure
* unacceptable work load
* functionality acceptable performance

![Migration to the boundary](boundary.png)

Source: [Risk management in a dynamic society: a modelling problem]

Incentives push the system towards the boundary of acceptable performance:
accidents happen when the boundary is exceeded.


#### AcciMaps

TBD

#### Risk management framework

Rasmussen proposed a multi-layer view of socio-technical systems:

![Risk management framework](risk-management-framework.png)

Source: [Risk management in a dynamic society: a modelling problem]

### Concepts
* Dynamic safety model
* Migration toward accidents
* Risk maangement framework
* Boundaries:
    - boundary of functionally acceptable performance
    - boundary to economic failure
    - boundary to unnaceptable work load
* Cognitive systems engineering
* Skill-rule-knowledge (SKR) model
* AcciMaps
* Means-ends hierarchy
* Ecological interface design
* Systems approach
* Control-theoretic
* decisions, acts, and errors
* hazard source
* anatomy of accidents
* energy
* systems thinking
* trial and error experiments
* defence in depth (fallacy)
* Role of managers
	- Information
	- Competency
	- Awareness
	- Commitment
* Going solid

### Selected publications
* [Reflecting on Jens Rasmussen’s legacy. A strong program for a hard problem](https://doi.org/10.1016/j.ssci.2014.03.015)
* [Risk management in a dynamic society: a modelling problem]
* [Coping with complexity](http://orbit.dtu.dk/fedora/objects/orbit:91746/datastreams/file_ecf1b6eb-0b8c-4420-b361-644808e34562/content)
* [“Going solid”: a model of system dynamics and consequences for patient safety](https://qualitysafety.bmj.com/content/14/2/130)

[Risk management in a dynamic society: a modelling problem]: https://doi.org/10.1016/S0925-7535(97)00052-0

## James Reason

Reason is a psychology researcher who did work on understanding and categorizing human error.

### Contributions

#### Swiss cheese model

Reason developed the *swiss cheese* model of accidents.

#### Human Error model: Slips, laspses and mistakes

Reason developed a model of the types of errors that humans make:

* slips
* lapses
* msitakes

### Concepts

* Human error
* Slips, lapses and mistakes
* Swiss cheese model

### Selected publications

* [Human error](https://www.amazon.com/gp/product/0521314194/ref=dbs_a_def_rwt_bibl_vppi_i0)

## Nadine Sarter

[Sarter](https://ioe.engin.umich.edu/people/nadine-sarter/) is a researcher in industrial and operations engineering.

### Concepts

* cognitive ergonomics
* organization safety
* human-automation/robot interaction
* human error / error management
* attention / interruption maangement
* design of decision support systems


### Selected publications

* [Learning from Automation Surprises and "Going Sour" Accidents: Progress on Human-Centered Automation](https://ntrs.nasa.gov/archive/nasa/casi.ntrs.nasa.gov/19980016965.pdf)
* [Behind Human Error](https://www.amazon.com/gp/product/B075QFGTNP/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B075QFGTNP&SubscriptionId=1MGPYB6YW3HWK55XCGG2)


## Robert L. Wears

Wears was a medical researcher who studied emergency medicine.

### Concepts
* Underground adaptations
* Articulated functions vs. important functions
* Unintended effects
* Apparent success vs real success
* Exceptions
* Dynamic environments
* Systems of care are intrinsically hazardous

### Selected publications

* [The error of counting "errors"](https://linkinghub.elsevier.com/retrieve/pii/S0196064408006070)
* [Underground adaptations: case studies from health care](https://doi.org/10.1007/s10111-011-0207-2)
* [Fundamental On Situational Surprise: A Case Study With Implications For Resilience](https://books.openedition.org/pressesmines/1122)


## Diane Vaughan

Vaughan is a sociology researcher who did a famous study of the NASA Challenger accident.

### Concepts

* normalization of deviance

### Selected publications

* [The Challenger Launch Decision: Risky Technology, Culture, and Deviance at
  NASA](https://www.amazon.com/Challenger-Launch-Decision-Technology-Deviance/dp/022634682X/ref=sr_1_1?ie=UTF8&qid=1545966442&sr=8-1&keywords=diane+vaughan)

## David Woods

Woods has a resesarch background in cognitive systems engineering and did work
researching NASA accidents.  He is one of the founders [Adaptive Capacity
Labs](http://www.adaptivecapacitylabs.com/), a resilience engineering
consultancy.

### Contributions

Woods seems to have contributed an enormous number of concepts. 

#### The adaptive universe

TBD

#### Theory of graceful extensibility

From [The theory of graceful extensibility: basic rules that govern adaptive systems]

1. Boundaries are universal
2. Surprise occurs, continuously
3. Risk of saturation is monitored and regulated
4. Synchronization across multiple units of adaptive behavior in a network is necessary
5. Risk of saturation can be shared
6. Pressure changes what is sacrificed when
7. Pressure for optimality undermines graceful extensibility
8. All adaptive units are local
9. Perspective contrast overcomes bounds
10. Reflective systems continually risk mis-calibration

### Concepts

Many of these are mentioned in Woods's [short course](http://csel.org.ohio-state.edu/ResilienceEngineering.html).

* the adaptive universe
* unit of adaptive behavior (UAB), adaptive unit
* adapative capacity
* continuous adaptation
* graceful extensibility
* sustained adaptability
* Tangled, layered networks (TLN)
* competence envelope
* adaptive cycles/histories
* precarious present (unease)
* resilient future
* tradeoffs, five fundamental
* adaptive florescence
* reverberation
* adaptive stalls
* borderlands
* anticipate
* synchronize
* proactive learning
* initiative
* reciprocity
* SNAFUs
* robustness
* surprise
* dynamic fault management
* software systems as "team players"
* multi-scale
* brittleness
* decompensation
* working at cross-purposes
* proactive learning vs getting stuck
* oversimplification
* fixation
* fluency law, veil of fluency
* capacity for maneuver (CfM)
* crunches
* sharp end, blunt end
* adaptive landscapes
* stretched systems, law of
* cascades
* adapt how to adapt
* unit working hard to stay in control
* you can monitor how hard you're working to stay in control (monitor risk of saturation)
* reality trumps algorithms
* stand down
* time matters
* goal interactions (follow them!)
* Properties of resilient organizations
    - Tangible experience with surprise
    - uneasy about the precarious present
    - push intiative down
    - reciprocity
    - align goals across multiple units

### Selected publications

* [Resilience Engineering: Concepts and Precepts](https://www.amazon.com/gp/product/B009KNDF64/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B009KNDF64&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Resilience is a verb](https://www.researchgate.net/publication/329035477_Resilience_is_a_Verb)
* [Four concepts for resilience and the implications for the future of resilience engineering](https://www.researchgate.net/publication/276139783_Four_concepts_for_resilience_and_the_implications_for_the_future_of_resilience_engineering)
* [How adaptive systems fail](https://www.researchgate.net/publication/284173754_How_Adaptive_Systems_Fail)
* [Resilience and the ability to anticipate](https://www.researchgate.net/publication/285487326_Resilience_and_the_ability_to_anticipate)
* [Distancing through differencing: An obstacle to organizational learning following accidents](https://www.researchgate.net/publication/292504703_Distancing_through_differencing_An_obstacle_to_organizational_learning_following_accidents)
* [Essential characteristics of resilience](https://www.researchgate.net/publication/284328979_Essential_characteristics_of_resilience)
* [Learning from Automation Surprises and "Going Sour" Accidents: Progress on Human-Centered Automation](https://ntrs.nasa.gov/archive/nasa/casi.ntrs.nasa.gov/19980016965.pdf)
* [Behind Human Error](https://www.amazon.com/gp/product/B075QFGTNP/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B075QFGTNP&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Joint Cognitive Systems: Patterns in Cognitive Systems Engineering](https://www.amazon.com/gp/product/0849339332/ref=x_gr_w_bb?ie=UTF8&tag=x_gr_w_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=0849339332&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Patterns in Cooperative Cognition](https://www.researchgate.net/publication/262449980_Patterns_in_Cooperative_Cognition)
* [Origins of cognitive systems engineering](https://www.researchgate.net/publication/298793082_Origins_of_Cognitive_Systems_Engineering)
* [Incidents - markers of resilience or brittleness?](https://www.researchgate.net/publication/292504952_Incidents_-_markers_of_resilience_or_brittleness)
* [The alarm problem and directed attention in dynamic fault management](https://www.tandfonline.com/doi/abs/10.1080/00140139508925274)
* [Can We Trust Best Practices? Six Cognitive Challenges of Evidence-Based Approaches](https://journals.sagepub.com/doi/abs/10.1177/1555343416637520?journalCode=edma)
* [Operating at the Sharp End: The Complexity of Human Error](https://www.researchgate.net/publication/313407259_Operating_at_the_Sharp_End_The_Complexity_of_Human_Error)
* [The theory of graceful extensibility: basic rules that govern adaptive systems]
* [Simon's Slice: Five Fundamental Tradeoffs that Bound the Performance of Human Work Systems](https://www.researchgate.net/publication/260404967_Simon's_Slice_Five_Fundamental_Tradeoffs_that_Bound_the_Performance_of_Human_Work_Systems)


[The theory of graceful extensibility: basic rules that govern adaptive systems]: https://link.springer.com/article/10.1007%2Fs10669-018-9708-3

## John Wreathall

Wreathall is an expert in human performance in safety. He works at the
[WreathWood Group](http://www.wreathall.com/), a risk and safety studies
consultancy.

### Selected publications
* [Resilience engineering in practice: a guidebook]()

