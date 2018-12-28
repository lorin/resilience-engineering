# Resilience Engineering notes

This file contains notes about the field of resilience engineering, organized
by researcher/author. I'm using these notes to help me get my head around the
different players and associated concepts.

For each author, I list concepts that I associate with that researcher (i.e.,
that they reference in their writings), and some selected publications that
they've written. The publications listed aren't comprehensive: they're either
ones I've read or ones that are currently on my to-read list. 

Authors are listed here in alphabetical order.

* [John Allspaw](#john-allspaw)
* [Lisanne Bainbridge](#lisanne-bainbridge)
* [Todd Conklin](#todd-conklin)
* [Richard I. Cook](#richard-i-cook)
* [Sidney Dekker](#sidney-dekker)
* [Anders Ericsson](#anders-ericsson)
* [Erik Hollnagel](#erik-hollnagel)
* [Gary Klein](#gary-klein)
* [Nancy Leveson](#nancy-leveson)
* [Charles Perrow](#charles-perrow)
* [Shawna J. Perry](#shawna-j-perry)
* [Jens Rasmussen](#jens-rasmussen)
* [James Reason](#james-reason)
* [Nadine Sarter](#nadine-sarter)
* [Diane Vaughan](#diane-vaughan)
* [Robert L. Wears](#robert-l-wears)
* [David Woods](#david-woods)

## John Allspaw

Allspaw is the former CTO of Etsy. He applies concepts from resilience engineering to the tech industry.
He is one of the founders [Adaptive Capacity Labs](http://www.adaptivecapacitylabs.com/), a resilience engineering consultancy.

### Selected publications

* [Trade-Offs Under Pressure: Heuristics and Observations Of Teams Resolving Internet Service Outages](https://www.researchgate.net/publication/295011072_Trade-Offs_Under_Pressure_Heuristics_and_Observations_Of_Teams_Resolving_Internet_Service_Outages)
* [Incidents as we Imagine Them Versus How They Actually
  Are](https://community.pagerduty.com/t/incidents-as-we-imagine-them-versus-how-they-actually-are-with-john-allspaw/2708) (video)
* [Fault Injection in Production: Making the case for resiliency testing](http://queue.acm.org/detail.cfm?id=2353017)

## Lisanne Bainbridge

Bainbridge is (was?) a psychology researcher. (*I have not been able to find any recent information about her*).

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
* [Ironies of automation](https://doi.org/10.1016/0005-1098(83)90046-8)


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


### Selected publications

* [How complex systems fail](http://web.mit.edu/2.75/resources/random/How%20Complex%20Systems%20Fail.pdf)
* [Distancing through differencing: An obstacle to organizational learning following accidents](https://www.researchgate.net/publication/292504703_Distancing_through_differencing_An_obstacle_to_organizational_learning_following_accidents)
* [Behind Human Error](https://www.amazon.com/gp/product/B075QFGTNP/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B075QFGTNP&SubscriptionId=1MGPYB6YW3HWK55XCGG2)

## Sidney Dekker

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

## Erik Hollnagel

### Concepts
* ETTO (efficiency thoroughness tradeoff) principle
* FRAM (functional resonance analysis metho)
* Safety-I and Safety-II

### Selected publications

* [The ETTO Principle: Efficiency-Thoroughness Trade-Off: Why Things That Go Right Sometimes Go Wrong](https://www.amazon.com/ETTO-Principle-Efficiency-Thoroughness-Trade-Off-Sometimes/dp/0754676781/ref=sr_1_1?s=books&ie=UTF8&qid=1545965837&sr=1-1&keywords=etto+principle)
* [Safety-I and Safety-II: The past and future of safety management](https://www.amazon.com/gp/product/1472423089/ref=dbs_a_def_rwt_bibl_vppi_i0)
* [FRAM: The Functional Resonance Analysis Method: Modelling Complex Socio-technical System](https://www.amazon.com/gp/product/B010WIDYE8/ref=dbs_a_def_rwt_bibl_vppi_i15)
* [Joint Cognitive Systems: Patterns in Cognitive Systems Engineering](https://www.amazon.com/gp/product/0849339332/ref=x_gr_w_bb?ie=UTF8&tag=x_gr_w_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=0849339332&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Resilience Engineering: Concepts and Precepts](https://www.amazon.com/gp/product/B009KNDF64/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B009KNDF64&SubscriptionId=1MGPYB6YW3HWK55XCGG2)

## Gary Klein

Klein studies how experts are able to quickly make effective decisions in high-tempo situations. 

### Concepts
* Naturalistic decision making (NDM)
* Cognitive task analysis

### Selected publications

* [Sources of power: how people make decisions](https://www.amazon.com/gp/product/0262534290/ref=dbs_a_def_rwt_bibl_vppi_i0)
* [Working minds: a practitioner's guide to cognitive task analysis](https://www.amazon.com/gp/product/0262532816/ref=dbs_a_def_rwt_bibl_vppi_i5)

## Nancy Leveson

Nancy Leveson is a computer science researcher with a focus in software safety.

## Concepts

* Software safety
* STAMP (systems-theoretic accident model and processes)
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
* [Engineering a safer world](https://mitpress.mit.edu/books/engineering-safer-world)
* [Safeware](https://www.amazon.com/Safeware-Computers-Nancy-G-Leveson/dp/0201119722)
* [A New Accident Model for Engineering Safer Systems](http://sunnyday.mit.edu/accidents/safetyscience-single.pdf)
* [Resilience Engineering: Concepts and Precepts](https://www.amazon.com/gp/product/B009KNDF64/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B009KNDF64&SubscriptionId=1MGPYB6YW3HWK55XCGG2)


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


## Jens Rasmussen

Jens Rasmussen was a very influential researcher in human factors and safety systems.

### Concepts

* Boundaries:
    - boundary of functionally acceptable performance
    - boundary to economic failure
    - boundary to unnaceptable work load
* Cognitive systems engineering
* Skill-rule-knowledge (SKR) model
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

### Selected publications
* [Risk management in a dynamic society: a modelling problem](https://doi.org/10.1016/S0925-7535(97)00052-0)
* [Reflecting on Jens Rasmussen’s legacy. A strong program for a hard problem](https://doi.org/10.1016/j.ssci.2014.03.015)


## James Reason

Reason is a psychology researcher who did work on understanding and categorizing human error.

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

### Concepts

* resilience
* the adaptive universe
* adapative capacity
* continuous adaptation
* graceful extensibility
* sustained adaptability
* Tangled, layered networks
* Borderlands
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


### Selected publications

* [Resilience Engineering: Concepts and Precepts](https://www.amazon.com/gp/product/B009KNDF64/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B009KNDF64&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Resilience is a verb](https://www.researchgate.net/publication/329035477_Resilience_is_a_Verb)
* [Four concepts for resilience and the implications for the future of resilience engineering](https://www.researchgate.net/publication/276139783_Four_concepts_for_resilience_and_the_implications_for_the_future_of_resilience_engineering)
* [Distancing through differencing: An obstacle to organizational learning following accidents](https://www.researchgate.net/publication/292504703_Distancing_through_differencing_An_obstacle_to_organizational_learning_following_accidents)
* [Essential characteristics of resilience](https://www.researchgate.net/publication/284328979_Essential_characteristics_of_resilience)
* [Learning from Automation Surprises and "Going Sour" Accidents: Progress on Human-Centered Automation](https://ntrs.nasa.gov/archive/nasa/casi.ntrs.nasa.gov/19980016965.pdf)
* [Behind Human Error](https://www.amazon.com/gp/product/B075QFGTNP/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B075QFGTNP&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Joint Cognitive Systems: Patterns in Cognitive Systems Engineering](https://www.amazon.com/gp/product/0849339332/ref=x_gr_w_bb?ie=UTF8&tag=x_gr_w_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=0849339332&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
