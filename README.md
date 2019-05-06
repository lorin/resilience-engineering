# Resilience engineering notes

Alias: <http://resiliencepapers.club> (thanks to [John Allspaw](https://twitter.com/allspaw)).

If you're not sure what to read first, check out [Resilience engineering: Where do I start?](intro.md)

This file contains notes about people active in resilience engineering, as well as some influential
researchers who are no longer with us, organized alphabetically. I'm using
these notes to help get my head around the players and concepts.

You might also be interested in my [notes on David Woods's Resilience Engineering short course](https://github.com/lorin/res-eng-short-course-notes).

For each person, I list concepts that they reference in their writings, along
with some publications. The publications lists aren't comprehensive:
they're ones I've read or have added to my to-read list. 

* [John Allspaw](#john-allspaw)
* [Lisanne Bainbridge](#lisanne-bainbridge)
* [Andrea Baker](#andrea-baker)
* [Johan Bergström](#johan-bergström)
* [Todd Conklin](#todd-conklin)
* [Richard I. Cook](#richard-i-cook)
* [Sidney Dekker](#sidney-dekker)
* [John C. Doyle](#john-c-doyle)
* [Bob Edwards](#bob-edwards)
* [Anders Ericsson](#anders-ericsson)
* [Meir Finkel](#meir-finkel)
* [Ivonne Andrade Herrera](#ivonne-andrade-herrera)
* [Erik Hollnagel](#erik-hollnagel)
* [Leila Johannesen](#leila-johannesen)
* [Gary Klein](#gary-klein)
* [Nancy Leveson](#nancy-leveson)
* [Anne-Sophie Nyssen](anne-sophie-nyssen)
* [Elinor Ostrom](#elinor-ostrom)
* [Jean Pariès](#jean-paries)
* [Emily Patterson](#emily-patterson)
* [Charles Perrow](#charles-perrow)
* [Shawna J. Perry](#shawna-j-perry)
* [Jens Rasmussen](#jens-rasmussen)
* [James Reason](#james-reason)
* [Emilie M. Roth](#emilie-m-roth)
* [Nadine Sarter](#nadine-sarter)
* [James C. Scott](#james-c-scott)
* [Steven Shorrock](#steven-shorrock)
* [Barry Turner](#barry-turner)
* [Diane Vaughan](#diane-vaughan)
* [Robert L. Wears](#robert-l-wears)
* [David Woods](#david-woods)
* [John Wreathall](#john-wreathall)

Some big ideas:

* [The adaptive universe](#the-adaptive-universe) (David Woods)
* [Dynamic safety model](#dynamic-safety-model) (Jens Rasmussen)
* [Safety-II](#safety-i-vs-safety-ii) (Erik Hollnagel)
* [Graceful extensibility](#graceful-extensibility) (David Woods)
* [ETTO: Efficiency-tradeoff principle](#etto-principle) (Erik Hollnagel)
* [Drift into failure](#drift-into-failure) (Sidney Dekker)
* Robust yet fragile (John C. Doyle)
* [STAMP: Systems-Theoretic Accident Model & Process](#stamp) (Nancy Leveson)
* Polycentric governance (Elinor Ostrom)

## John Allspaw

Allspaw is the former CTO of Etsy. He applies concepts from resilience engineering to the tech industry.
He is one of the founders [Adaptive Capacity Labs](http://www.adaptivecapacitylabs.com/), a resilience engineering consultancy.

Allspaw tweets as [@allspaw](https://twitter.com/allspaw).

### Selected publications

* [Trade-Offs Under Pressure: Heuristics and Observations Of Teams Resolving Internet Service Outages](https://www.researchgate.net/publication/295011072_Trade-Offs_Under_Pressure_Heuristics_and_Observations_Of_Teams_Resolving_Internet_Service_Outages)
* [Etsy Debrief Facilitation Guide](http://extfiles.etsy.com/DebriefingFacilitationGuide.pdf)
* [Blameless PostMortems and a Just Culture](https://codeascraft.com/2012/05/22/blameless-postmortems/) (blog)
* [Resilience engineering: learning to embrace failure](https://doi.org/10.1145/2366316.2366331)
* [Fault Injection in Production: Making the case for resiliency testing](http://queue.acm.org/detail.cfm?id=2353017)

### Selected talks

* [Incidents as we Imagine Them Versus How They Actually Are](https://community.pagerduty.com/t/incidents-as-we-imagine-them-versus-how-they-actually-are-with-john-allspaw/2708) 
* [Problem detection (papers we love)](https://www.youtube.com/watch?v=NxctiGRI2y8)
  (presentation of [Problem detection] paper)
* [Common Ground and Coordination in Joint Activity (papers we love)](https://paperswelove.org/2016/video/john-allspaw-common-ground/) (presentation of [Common Ground and Coordination in Joint Activity] paper)


## Lisanne Bainbridge

Bainbridge is (was?) a psychology researcher. (*I have not been able to find any recent information about her*).

### Contributions

#### Ironies of automation

Bainbridge is famous for her 1983 [Ironies of automation] paper, which continues to
be frequently cited.

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

## Andrea Baker

[Baker](https://www.thehopmentor.com/) is a practitioner who provides
training services in human and organizational performance (HOP) and learning
teams.

Baker tweets as [@thehopmentor](https://twitter.com/thehopmentor).

### Concepts

* Human and organizational performance (HOP)
* Learning teams
* Industrial empathy

### Selected publications

* [A bit about HOP](https://docs.wixstatic.com/ugd/1a0149_21bcf20f158540098d3d7987ffbf3f58.pdf) (editorial)
* [A short introduction to human and organizational performance (hop) and learning teams](http://www.safetydifferently.com/a-short-introduction-to-human-and-organizational-performance-hop-and-learning-teams/) (blog post)


## Johan Bergström

[Bergström](http://www.jbsafety.se/p/about-me.html) is a safety research and
consultant. He runs the [Master Program of Human Factors and Systems
Safety](http://www.humanfactors.lth.se/msc-programme/) at Lund University.

Bergström tweets as [@bergstrom_johan](https://twitter.com/bergstrom_johan).

### Concepts

* Analytical traps in accident investigation
   - Counterfactual reasoning
   - Normative language
   - Mechanistic reasoning
* Generic competencies

### Selected publications

* [Resilience engineering: Current status of the research and future challenges](https://www.sciencedirect.com/science/article/pii/S0925753516306130)
* [Rule- and role retreat: An empirical study of procedures and resilience](https://www.researchgate.net/publication/50917226_Rule-_and_role_retreat_An_empirical_study_of_procedures_and_resilience)

### Selected talks

* [Three analytical traps in accident investigation](https://www.youtube.com/watch?v=TqaFT-0cY7U)
* [Two Views on Human Error](https://www.youtube.com/watch?v=rHeukoWWtQ8)


## Todd Conklin

Conklin's books are on my reading list, but I haven't read anything by him
yet. I have listened to his great [Preaccident investigation
podcast](https://preaccidentpodcast.podbean.com/).

Conklin tweets as [@preaccident](https://twitter.com/preaccident).

### Selected publications
* [Pre-accident investigations: an introduction to organizational safety](https://www.amazon.com/Pre-Accident-Investigations-Todd-Conklin/dp/1409447820)
* [Pre-accident investigations: better questions - an applied approach to
  operational learning](https://www.amazon.com/gp/product/1472486137)

## Richard I. Cook

Cook is a medical doctor who studies failures in complex systems.  He is one of the founders [Adaptive Capacity Labs](http://www.adaptivecapacitylabs.com/), a resilience engineering consultancy.

Cook tweets as [@ri_cook](https://twitter.com/ri_cook).

### Concepts
* complex systems
* degraded mode
* sharp end (c.f. Reason's blunt end)
* Going solid
* Cycle of error
* "new look"


### Selected publications

* [How complex systems fail](http://web.mit.edu/2.75/resources/random/How%20Complex%20Systems%20Fail.pdf)
* [*Where* complex systems fail](https://www.snafucatchers.com/single-post/2017/11/14/void-Incidents-as-Untyped-Pointers)
* [Distancing through differencing: An obstacle to organizational learning following accidents](https://www.researchgate.net/publication/292504703_Distancing_through_differencing_An_obstacle_to_organizational_learning_following_accidents)
* [Being bumpable](http://csel.eng.ohio-state.edu/productions/woodscta/media/beingbump.pdf)
* [Behind Human Error](https://www.amazon.com/gp/product/B075QFGTNP/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B075QFGTNP&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Incidents - markers of resilience or brittleness?](https://www.researchgate.net/publication/292504952_Incidents_-_markers_of_resilience_or_brittleness)
* [“Going solid”: a model of system dynamics and consequences for patient safety](https://qualitysafety.bmj.com/content/14/2/130)
* [Operating at the Sharp End: The Complexity of Human Error](https://www.researchgate.net/publication/313407259_Operating_at_the_Sharp_End_The_Complexity_of_Human_Error)
* [Patient boarding in the emergency department as a symptom of complexity-induced risks](https://www.researchgate.net/publication/312624891_Patient_boarding_in_the_emergency_department_as_a_symptom_of_complexity-induced_risks)
* [Sensemaking, Safety, and Cooperative Work in the Intensive Care Unit](https://www.researchgate.net/publication/220579381_Sensemaking_Safety_and_Cooperative_Work_in_the_Intensive_Care_Unit)
* [Medication Reconciliation Is a Window into “Ordinary” Work](https://www.taylorfrancis.com/books/e/9781317164777/chapters/10.1201/9781315572529-4)
* [Cognitive consequences of clumsy automation on high workload, high consequence human performance]
* [Implications of automation surprises in aviation for the future of total intravenous anesthesia (TIVA)]
* [The Messy Details: Insights From the Study of Technical Work in Healthcare]
* [Nosocomial automation: technology-induced complexity and human performance]
* [The New Look at Error, Safety, and Failure: A Primer for Health Care]
* [Grounding explanations in evolving, diagnostic situations]
* [A Tale of Two Stories: Contrasting Views of Patient Safety]

[Cognitive consequences of clumsy automation on high workload, high consequence human performance]: https://ntrs.nasa.gov/search.jsp?R=19910011398
[Implications of automation surprises in aviation for the future of total intravenous anesthesia (TIVA)]: https://doi.org/10.1016/S0952-8180(96)90009-4
[The Messy Details: Insights From the Study of Technical Work in Healthcare]: https://doi.org/10.1109%2FTSMCA.2004.836802
[Nosocomial automation: technology-induced complexity and human performance]: https://www.researchgate.net/profile/David_Woods11/publication/224649052_Nosocomial_automation_technology-induced_complexity_and_human_performance/links/59399b1da6fdcc58ae902c49/Nosocomial-automation-technology-induced-complexity-and-human-performance.pdf
[The New Look at Error, Safety, and Failure: A Primer for Health Care]: https://pdfs.semanticscholar.org/67f7/53ec089e5a8879f241e2be867dad0a2026fb.pdf

[Grounding explanations in evolving, diagnostic situations]: https://pdfs.semanticscholar.org/1bed/356b5aa67c701f5bad6d943768622095f418.pdf


[A Tale of Two Stories: Contrasting Views of Patient Safety]: https://www.researchgate.net/publication/245102691_A_Tale_of_Two_Stories_Contrasting_Views_of_Patient_Safety

### Selected talks

* [How Complex Systems Fail](https://www.youtube.com/watch?v=2S0k12uZR14)



## Sidney Dekker

Dekker is a human factors and safety researcher with a background in aviation.
His books aimed at a lay audience (Drift Into Failure, Just Culture, The Field Guide to 'Human Error' investigations)
have been enormously influential. His PhD advisor is [David Woods](#david-woods).

Dekker tweets as [@sidneydekkercom](https://twitter.com/sidneydekkercom).

### Contributions

#### Drift into failure

Dekker developed the theory of *drift*, characterized by five concepts:

1. Scarcity and competition
1. Decrementalism, or small steps
1. Sensitive dependence on initial conditions
1. Unruly technology
1. Contribution of the protective structure

### Just Culture

Dekker examines how cultural norms defining justice can be re-oriented to minimize the negative impact and maximize learning when things go wrong.

1.  Retributive justice as society's traditional idea of justice:  distributing punishment to those responsible based on severity of the violation
2.  Restorative justice as an improvement for both victims and practicioners:  distributing obligations of rebuliding trust to those responsible based on who is hurt and what they need
3.  First, second, and third victims:  an incident's negative impact is felt by more than just the obvious victims
4.  Learning theory:  people break rules when they have learned there are no negative consequences, and there are actually positive consequences - in other words, they break rules to get things done to meet production pressure
5.  Reporting culture:  contributing to reports of adverse events is meant to help the organization understand what went wrong and how to prevent recurrence, but accurate reporting requires appropriate and proportionate accountability actions
6.  Complex systems:  normal behavior of practicioners and professionals in the context of a complex system can appear abnormal or deviant in hindsight, particularly in the eyes of non-expert juries and reviewers
7.  The nature of practicioners:  professionals want to do good work, and therefore want to be held accountable for their mistakes; they generally want to help similarly-situated professionals avoid the same mistake.



### Concepts
* Drift into failure
* Safety differently
* New view vs old view of human performance & error
* Just culture
* complexity
* broken part
* Newton-Descartes
* diversity
* systems theory
* unruly technology
* decrementalism
* generic competencies

### Selected publications

* [Drift into failure](https://www.amazon.com/Drift-into-Failure-Sidney-Dekker/dp/1409422216)
* [Reconstructing human contributions to accidents: the new view on error and performance](https://www.sciencedirect.com/science/article/pii/S0022437502000324)
* [The field guide to 'human error' investigations](https://www.amazon.com/Field-Guide-Understanding-Human-Error/dp/1472439058s://www.amazon.com/Field-Guide-Understanding-Human-Error/dp/1472439058)
* [Behind Human Error](https://www.amazon.com/gp/product/B075QFGTNP/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B075QFGTNP&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Rule- and role retreat: An empirical study of procedures and resilience](https://www.researchgate.net/publication/50917226_Rule-_and_role_retreat_An_empirical_study_of_procedures_and_resilience?enrichId=rgreq-23625e555a0d8e5250c74f24b5fd01ca-XXX&enrichSource=Y292ZXJQYWdlOzUwOTE3MjI2O0FTOjk3MzU5NjY5MjM1NzQ1QDE0MDAyMjM3NjI5NDY%3D&el=1_x_2&_esc=publicationCoverPdf)
* [Anticipating the effects of technological change: A new era of dynamics for human factors](https://www.researchgate.net/publication/247512351_Anticipating_the_effects_of_technological_change_A_new_era_of_dynamics_for_human_factors)
* [Why do things go right?](http://www.safetydifferently.com/why-do-things-go-right/)
* [Six stages to the new view of human error](http://www.humanfactors.lth.se/fileadmin/lusa/Sidney_Dekker/articles/2007/SafetyScienceMonitor.pdf)

## John C. Doyle

[Doyle](http://www.cds.caltech.edu/~doyle/wiki/index.php?title=Main_Page) is a
control systems researcher. He is seeking to identify the universal laws that capture the
behavior of resilient systems, and is concerned with the architecture of such
systems.

### Concepts
* Robust yet fragile
* layered architectures
* constraints that deconstrain
* protocol-based architectures
* emergent constraints
* Universal laws and architectures
* conservation laws
* universal architectures
* Highly optimized tolerance


### Selected publications

* [Universal Laws and Architectures](http://www.cis.upenn.edu/~ngns/docs/Review_2010/Doyle%20MURI%202010.pdf) (slides)
* [Contrasting Views of Complexity and Their Implications For Network-Centric Infrastructures](http://dx.doi.org/10.1109/TSMCA.2010.2048027)
* [Architecture, constraints, and behavior](https://www.pnas.org/content/108/Supplement_3/15624)
* [The “robust yet fragile” nature of the Internet](https://doi.org/10.1073/pnas.0501426102)
* [Highly Optimized Tolerance: Robustness and Design in Complex Systems](http://dx.doi.org/10.1103/physrevlett.84.2529)
* [Robust efficiency and actuator saturation explain healthy heart rate control and variability](https://doi.org/10.1073/pnas.1401883111)

## Bob Edwards

[Edwards](http://hopcoach.net/) is a practitioner who provides
training services in human and organizational performance (HOP).

Edwards tweets as [@thehopcoach](https://twitter.com/thehopcoach).

## Anders Ericsson

Ericsson introduced the idea of *deliberate practice* as a mechanism for
achieving high level of expertise.

Ericsson isn't directly associated with the field of resilience engineering.
However, Gary Klein's work is informed by his, and I have a particular
interest in how people improve in expertise, so I'm including him here.

### Concepts

* Expertise
* Deliberate practice
* Protocol analysis

### Selected publications

* [Peak: secrets from the new science of expertise](https://www.amazon.com/Peak-Secrets-New-Science-Expertise/dp/1531864880/)
* [Protocol analysis: verbal reports as data](https://www.amazon.com/Protocol-Analysis-Revd-Verbal-Reports/dp/0262550237)

## Meir Finkel

Finkel is a Colonel in the Israeli Defense Force (IDF) and the Director of the IDF's Ground Forces Concept Development and Doctrine Department

### Selected publications
* [On Flexibility: Recovery from Technological and Doctrinal Surprise on the Battlefield](https://www.amazon.com/Flexibility-Recovery-Technological-Doctrinal-Battlefield/dp/0804774897/ref=sr_1_3?ie=UTF8&qid=1546046916&sr=8-3&keywords=on+flexibility)

## Ivonne Andrade Herrera

[Herrera](https://www.ntnu.edu/employees/ivonne.a.herrera) is an associate professor in 
the department of industrial economics and technology management at NTNU and a
senior research scientist at SINTEF. Her areas of expertise include safety management and
resilience engineering in avionics and air traffic management.


[List of publications](https://wo.cristin.no/as/WebObjects/cristin.woa/wa/fres?sort=ar&pnr=30556&action=sok)


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

Safety-II: performance variability rather than bimodality
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
* joint cognitive systems

### Selected publications

* [The ETTO Principle: Efficiency-Thoroughness Trade-Off: Why Things That Go Right Sometimes Go Wrong](https://www.amazon.com/ETTO-Principle-Efficiency-Thoroughness-Trade-Off-Sometimes/dp/0754676781/ref=sr_1_1?s=books&ie=UTF8&qid=1545965837&sr=1-1&keywords=etto+principle)
* [From Safety-I to Safety-II: A White Paper](https://www.skybrary.aero/bookshelf/books/2437.pdf)
* [Safety-II in Practice](https://www.amazon.com/Safety-II-Practice-Developing-Resilience-Potentials/dp/1138708925)
* [Safety-I and Safety-II: The past and future of safety management](https://www.amazon.com/gp/product/1472423089/ref=dbs_a_def_rwt_bibl_vppi_i0)
* [FRAM: The Functional Resonance Analysis Method: Modelling Complex Socio-technical System](https://www.amazon.com/gp/product/B010WIDYE8/ref=dbs_a_def_rwt_bibl_vppi_i15)
* [Joint Cognitive Systems: Patterns in Cognitive Systems Engineering](https://www.amazon.com/gp/product/0849339332/ref=x_gr_w_bb?ie=UTF8&tag=x_gr_w_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=0849339332&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Resilience Engineering: Concepts and Precepts]
* [I want to believe: some myths about the management of industrial safety](http://dx.doi.org/10.1007/s10111-012-0237-4)
* [Resilience engineering – Building a Culture of Resilience](http://www.ptil.no/getfile.php/1325150/PDF/Seminar%202013/Integrerte%20operasjoner/Hollnagel_RIO_presentation.pdf) (slides)


[Resilience Engineering: Concepts and Precepts]: https://www.amazon.com/gp/product/B009KNDF64/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B009KNDF64&SubscriptionId=1MGPYB6YW3HWK55XCGG2

## Leila Johannesen

[Johannesen](https://www.linkedin.com/in/leilajohannesen/) is currently a UX researcher and community advocate at IBM.
Her PhD dissertation work examined how humans cooperate, including studies of anesthesiologists.

### Concepts

* common ground

### Selected publications

* [Grounding explanations in evolving, diagnostic situations]
* [Maintaining common ground: an analysis of cooperative communication in the operating room](https://www.abdn.ac.uk/iprc/documents/Communication%20Book%20Chapter.pdf)


## Gary Klein

Klein studies how experts are able to quickly make effective decisions in high-tempo situations. 

Klein tweets as [@KleInsight](https://twitter.com/KleInsight).

### Concepts

* naturalistic decision making (NDM)
* intuitive expertise
* cognitive task analysis
* common ground
* problem detection
* automation as a "team player"

### Selected publications

* [Sources of power: how people make decisions](https://www.amazon.com/gp/product/0262534290/ref=dbs_a_def_rwt_bibl_vppi_i0)
* [Working minds: a practitioner's guide to cognitive task analysis](https://www.amazon.com/gp/product/0262532816/ref=dbs_a_def_rwt_bibl_vppi_i5)
* [Patterns in Cooperative Cognition](https://www.researchgate.net/publication/262449980_Patterns_in_Cooperative_Cognition)
* [Common Ground and Coordination in Joint Activity]
* [Can We Trust Best Practices? Six Cognitive Challenges of Evidence-Based Approaches](https://journals.sagepub.com/doi/abs/10.1177/1555343416637520?journalCode=edma)
* [Conditions for intuitive expertise: a failure to disagree](http://dx.doi.org/10.1037/a0016755)
* [Problem detection]
* [Ten challenges for making automation a team player]
* [Decision making in action: models and methods](https://www.amazon.com/Decision-Making-Action-Cognition-Literacy/dp/0893919438)

[Common Ground and Coordination in Joint Activity]: http://jeffreymbradshaw.net/publications/Common_Ground_Single.pdf
[Problem detection]: https://www.researchgate.net/publication/220579480_Problem_detection
[Ten challenges for making automation a team player]: https://ieeexplore.ieee.org/abstract/document/1363742

## Nancy Leveson

Nancy Leveson is a computer science researcher with a focus in software safety.

### Contributions

#### STAMP

Leveson developed the accident causality model known as STAMP: the Systems-Theoretic Accident Model and Process.

See [STAMP](STAMP.md) for some more detailed notes of mine.

### Concepts

* Software safety
* STAMP (systems-theoretic accident model and processes)
* STPA (system-theoretic process analysis) hazard analysis technique
* CAST (causal analysis based on STAMP) accident analysis technique
* Systems thinking
* hazard
* interactive complexity
* system accident
* dysfunctional interactions
* safety constraints
* control structure
* dead time
* time constants
* feedback delays

### Selected publications
* [A New Accident Model for Engineering Safer Systems](http://sunnyday.mit.edu/accidents/safetyscience-single.pdf)
* [Engineering a safer world](https://mitpress.mit.edu/books/engineering-safer-world)
* [STPA Handbook](http://psas.scripts.mit.edu/home/get_file.php?name=STPA_handbook.pdf)
* [Safeware](https://www.amazon.com/Safeware-Computers-Nancy-G-Leveson/dp/0201119722)
* [Resilience Engineering: Concepts and Precepts](https://www.amazon.com/gp/product/B009KNDF64/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B009KNDF64&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [High-pressure steam engines and computer software](http://dx.doi.org/10.1145/143062.143076)
* [Resilience Engineering: Concepts and Precepts]

## Anne-Sophie Nyssen

[Nyssen](http://www.lecit.ulg.ac.be/equipe/anne-sophie-nyssen/) is a psychology professor at the University of Liège,
who does research on human error in complex systems, in particular in medicine.

A list of publications can be found on her website linked above.


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

## Emily Patterson

[Patterson](https://hrs.osu.edu/faculty-and-staff/faculty-directory/patterson-emily)
is a researcher who applies human factors engineering to improve patient safety
in healthcare.

### Selected publications

* [Patient boarding in the emergency department as a symptom of complexity-induced risks](https://www.researchgate.net/publication/312624891_Patient_boarding_in_the_emergency_department_as_a_symptom_of_complexity-induced_risks)
* [Using observational study as a tool for discovery: uncovering cognitive and collaborative demands and adaptive strategies]

[Using observational study as a tool for discovery: uncovering cognitive and collaborative demands and adaptive strategies]: https://www.researchgate.net/profile/Emily_Patterson2/publication/237138704_USING_OBSERVATIONAL_STUDY_AS_A_TOOL_FOR_DISCOVERY_UNCOVERING_COGNITIVE_AND_COLLABORATIVE_DEMANDS_AND_ADAPTIVE_STRATEGIES/links/0deec52c8e310b385a000000.pdf

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
* Risk management framework
* Boundaries:
    - boundary of functionally acceptable performance
    - boundary to economic failure
    - boundary to unacceptable work load
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
* [Reflecting on Jens Rasmussen’s legacy. A strong program for a hard problem](https://doi.org/10.1016/j.ssci.2014.03.015) ([my notes](https://github.com/lorin/booknotes/blob/master/papers/Reflecting-on-Jens-Rasmussens-Legacy.md))
* [Reflecting on Jens Rasmussen's legacy (2) behind and beyond, a ‘constructivist turn’](https://doi.org/10.1016/j.apergo.2015.07.013)
* [Risk management in a dynamic society: a modelling problem]
* [Coping with complexity](http://orbit.dtu.dk/fedora/objects/orbit:91746/datastreams/file_ecf1b6eb-0b8c-4420-b361-644808e34562/content)
* [“Going solid”: a model of system dynamics and consequences for patient safety](https://qualitysafety.bmj.com/content/14/2/130)
* [Human error and the problem of causality in analysis of accidents](https://www.ida.liu.se/~729A71/Literature/Human%20Error_T/Rasmussen_1990.pdf)

[Risk management in a dynamic society: a modelling problem]: https://doi.org/10.1016/S0925-7535(97)00052-0

## James Reason

Reason is a psychology researcher who did work on understanding and categorizing human error.

### Contributions

#### Accident causation model (Swiss cheese model)

Reason developed an accident causation model that is sometimes known as the *swiss cheese* model of accidents.
In this model, Reason introduced the terms "sharp end" and "blunt end".

#### Human Error model: Slips, lapses and mistakes

Reason developed a model of the types of errors that humans make:

* slips
* lapses
* mistakes

### Concepts

* Blunt end
* Human error
* Slips, lapses and mistakes
* Swiss cheese model

### Selected publications

* [Human error]

[Human error]: https://www.amazon.com/gp/product/0521314194/ref=dbs_a_def_rwt_bibl_vppi_i0

## Emilie M. Roth

[Roth](http://www.rothsite.com/resume.html) is a cognitive psychologist who
serves as the principal scientist at [Roth Cognitive Engineering](http://www.rothsite.com/), a small
company that conducts research and application in the areas of human factors
and applied cognitive psychology (cognitive engineering)

### Selected publications

* [Uncovering the Requirements of Cognitive Work](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.564.2044) (see also [Thai Wood's comments](https://www.getrevue.co/profile/resilience/issues/resilience-roundup-uncovering-the-requirements-of-cognitive-work-issue-30-173410) in his Resilience Roundup newsletter)
* [Using observational study as a tool for discovery: uncovering cognitive and collaborative demands and adaptive strategies]

## Nadine Sarter

[Sarter](https://ioe.engin.umich.edu/people/nadine-sarter/) is a researcher in industrial and operations engineering. 
She is the director of the Center for Ergonomics at the University of Michigan.

### Concepts

* cognitive ergonomics
* organization safety
* human-automation/robot interaction
* human error / error management
* attention / interruption management
* design of decision support systems


### Selected publications

* [Learning from Automation Surprises and "Going Sour" Accidents: Progress on Human-Centered Automation](https://ntrs.nasa.gov/archive/nasa/casi.ntrs.nasa.gov/19980016965.pdf)
* [Behind Human Error](https://www.amazon.com/gp/product/B075QFGTNP/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B075QFGTNP&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Designed-Induced Error and Error-Informed Design: A Two-Way Street](https://www.amazon.com/Cognitive-Systems-Engineering-Expertise-Applications-ebook/dp/B076TDR6H9/ref=sr_1_1?keywords=cognitive+systems+engineering&qid=1554075974&s=gateway&sr=8-1)


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
* [Replacing Hindsight With Insight: Toward Better Understanding of Diagnostic Failures](https://www.semanticscholar.org/paper/Replacing-hindsight-with-insight%3A-toward-better-of-Wears-Nemeth/1bef45cae7375eddc8ee584dff100d200d812a8d)
* [Seeing patient safety ‘Like a State’](http://dx.doi.org/10.1016%2Fj.ssci.2014.02.007)

## James C. Scott

Scott is an anthropologist who also does research in political science. While
Scott is not a member of a resilience engineering community, his book *Seeing
like a state* has long been a staple of the cognitive systems engineering and
resilience engineering communities.

### Concepts

* authoritarian high-modernism
* legibility
* mētis

### Selected publications

* [Seeing like a state: how certain schemes to improve the human condition have failed](https://www.amazon.com/Seeing-like-State-Certain-Condition/dp/0300078153/ref=sr_1_1)


## Steven Shorrock

Shorrock is a chartered psychologist and a chartered ergonomist and human
factors specialist. He is the editor-in-chief of EUROCONTROL
[HindSight](https://www.skybrary.aero/index.php/HindSight_-_EUROCONTROL)
magazine. He runs the excellent [Humanistic Systems](https://humanisticsystems.com/) blog.

Shorrock tweets as [@StevenShorrock](https://twitter.com/StevenShorrock).

* [Human Factors and Ergonomics in Practice: Improving System Performance and Human Well-Being in the Real World](https://www.crcpress.com/Human-Factors-and-Ergonomics-in-Practice-Improving-System-Performance-and/Shorrock-Williams/p/book/9781472439253) (book)

## Diane Vaughan

Vaughan is a sociology researcher who did a famous study of the NASA Challenger accident.

### Concepts

* normalization of deviance

### Selected publications

* [The Challenger Launch Decision: Risky Technology, Culture, and Deviance at
  NASA](https://www.amazon.com/Challenger-Launch-Decision-Technology-Deviance/dp/022634682X/ref=sr_1_1?ie=UTF8&qid=1545966442&sr=8-1&keywords=diane+vaughan)

## Barry Turner

[Turner](https://www.tandfonline.com/doi/pdf/10.1080/10245289508523441) was a sociologist who greatly influenced the field of organization studies. 

### Selected publications

* [Man-made disasters](https://www.amazon.com/Man-Made-Disasters-Second-Barry-Turner/dp/0750620870/ref=sr_1_1)

## David Woods

[Woods](https://complexity.osu.edu/people/woods.2) has a research background in cognitive systems engineering and did work
researching NASA accidents.  He is one of the founders [Adaptive Capacity
Labs](http://www.adaptivecapacitylabs.com/), a resilience engineering
consultancy.

Woods tweets as [@ddwoods2](https://twitter.com/ddwoods2).

### Contributions

Woods has contributed an enormous number of concepts. 

#### The adaptive universe

Woods uses *the adaptive universe* as a lens for understanding the behavior of
all different kinds of systems.

All systems exist in a dynamic environment, and must adapt to change.

A successful system will need to adapt by virtue of its success.

Systems can be viewed as units of adaptive behavior (UAB) that interact. UABs
exist at different scales (e.g., cell, organ, individual, group, organization).

All systems have competence envelopes, which are constrained by boundaries. 

The resilience of a system is determined by how it behaves when it comes near
to a boundary.

See [Resilience Engineering Short Course](http://csel.org.ohio-state.edu/ResilienceEngineering.html) for more details.

#### Charting adaptive cycles

* Trigger
* Units of adaptive behavior
* Goals and goal conflicts
* Pressure points
* Subcycles

### Graceful extensibility

From [The theory of graceful extensibility: basic rules that govern adaptive systems]:

(Longer wording)

1. Adaptive capacity is finite
2. Events will produce demands that challenge boundaries on the adaptive
   capacity of any UAB
3. Adaptive capacities are regulated to manage the risk of saturating CfM
4. No UAB can have sufficient ability to regulate CfM to manage the risk of saturation alone
5. Some UABs monitor and regulate the CfM of other UABs in response to changes
   in the risk of saturation
6. Adaptive capacity is the potential for adjusting patterns of action to
   handle future situations, events, opportunities and disruptions
7. Performance of a UAB as it approaches saturation is different from the
   performance of that UAB when it operates far from saturation
8. All UABs are local
9. There are bounds on the perspective any UAB, but these limits are overcome
   by shifts and contrasts over multiple perspectives.
10. Reflective systems risk mis-calibration

(Shorter wording)

1. Boundaries are universal 
2. Surprise occurs, continuously
3. Risk of saturation is monitored and regulated
4. Synchronization across multiple units of adaptive behavior in a network is necessary
5. Risk of saturation can be shared
6. Pressure changes what is sacrificed when
7. Pressure for optimality undermines graceful extensibility
8. All adaptive units are local
9. Perspective contrast overcomes bounds
10. Mis-calibration is the norm

### Concepts

Many of these are mentioned in Woods's [short course](http://csel.org.ohio-state.edu/ResilienceEngineering.html).

* the adaptive universe
* unit of adaptive behavior (UAB), adaptive unit
* adaptive capacity
* continuous adaptation
* graceful extensibility
* sustained adaptability
* Tangled, layered networks (TLN)
* competence envelope
* adaptive cycles/histories
* precarious present (unease)
* resilient future
* tradeoffs, five fundamental
* florescence: the degree that changes in one area tend to recruit or open up
  beneficial changes in many other aspects of the network - which opens new
  opportunities across the network ...
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
* capacity for manoeuvre (CfM)
* crunches
* sharp end, blunt end
* adaptive landscapes
* law of stretched systems: Every system is continuously stretched to operate at capacity.
* cascades
* adapt how to adapt
* unit working hard to stay in control
* you can monitor how hard you're working to stay in control (monitor risk of saturation)
* reality trumps algorithms
* stand down
* time matters
* Properties of resilient organizations
    - Tangible experience with surprise
    - uneasy about the precarious present
    - push initiative down
    - reciprocity
    - align goals across multiple units
* goal conflicts, goal interactions (follow them!)
* to understand system, must study it under load
* adaptive races are unstable
* adaptive traps
* roles, nesting of
* hidden interdependencies
* net adaptive value
* matching tempos
* tilt toward florescence
* linear simplification
* common ground
* problem detection
* joint cognitive systems
* automation as a "team player"
* "new look"
* sacrifice judgment
* task tailoring
* substitution myth
* directability
* directed attention
* inter-predictability
* error of the third kind: solving the wrong problem
* buffering capacity
* context gap

### Selected publications

* [Resilience Engineering: Concepts and Precepts](https://www.amazon.com/gp/product/B009KNDF64/ref=x_gr_w_glide_bb?ie=UTF8&tag=x_gr_w_glide_bb-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=B009KNDF64&SubscriptionId=1MGPYB6YW3HWK55XCGG2)
* [Resilience is a verb](https://www.researchgate.net/publication/329035477_Resilience_is_a_Verb)
* [Four concepts for resilience and the implications for the future of resilience engineering](https://www.researchgate.net/publication/276139783_Four_concepts_for_resilience_and_the_implications_for_the_future_of_resilience_engineering)
* [How adaptive systems fail](https://www.researchgate.net/publication/284173754_How_Adaptive_Systems_Fail)
* [Resilience and the ability to anticipate](https://www.researchgate.net/publication/285487326_Resilience_and_the_ability_to_anticipate)
* [Distancing through differencing: An obstacle to organizational learning following accidents](https://www.researchgate.net/publication/292504703_Distancing_through_differencing_An_obstacle_to_organizational_learning_following_accidents)
* [Essential characteristics of resilience](https://www.researchgate.net/publication/284328979_Essential_characteristics_of_resilience)
* [Essentials of resilience, revisited](https://www.researchgate.net/publication/330116587_4_Essentials_of_resilience_revisited)
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
* [Beyond Simon’s Slice: Five Fundamental Trade-Offs that Bound the Performance of Macrocognitive Work Systems](https://cmapsinternal.ihmc.us/rid=1K2MHS0D4-1ZT3XRF-HPX/46.%2520Simon's%2520Slice.pdf)
* [Anticipating the effects of technological change: A new era of dynamics for human factors](https://www.researchgate.net/publication/247512351_Anticipating_the_effects_of_technological_change_A_new_era_of_dynamics_for_human_factors)
* [Common Ground and Coordination in Joint Activity]
* [Resilience as Graceful Extensibility to Overcome Brittleness](https://www.irgc.org/wp-content/uploads/2016/04/Woods-Resilience-as-Graceful-Extensibility-to-Overcome-Brittleness-1.pdf)
* [Resilience Engineering: Redefining the Culture of Safety and Risk Management](http://ordvac.com/soro/library/Aviation/Aviation%20Safety/General%20Safety%20Articles/resilience%20engineering%20bulletin.pdf)
* [Problem detection]
* [Cognitive consequences of clumsy automation on high workload, high consequence human performance]
* [Implications of automation surprises in aviation for the future of total intravenous anesthesia (TIVA)]
* [Ten challenges for making automation a team player]
* [The Messy Details: Insights From the Study of Technical Work in Healthcare]
* [Nosocomial automation: technology-induced complexity and human performance]
* [Human-centered software agents: Lessons from clumsy automation](http://www.ifp.illinois.edu/nsfhcs/abstracts/woods.txt)
* [STELLA: Report from the SNAFUcatchers Workshop on Coping with Complexity](https://snafucatchers.github.io/)
* [The New Look at Error, Safety, and Failure: A Primer for Health Care]
* [Grounding explanations in evolving, diagnostic situations]
* [Resilience Engineering: Concepts and Precepts]
* [A Tale of Two Stories: Contrasting Views of Patient Safety]

[The theory of graceful extensibility: basic rules that govern adaptive systems]: https://link.springer.com/article/10.1007%2Fs10669-018-9708-3

### Selected talks

* [The Mystery of Sustained Adaptability](https://www.youtube.com/watch?v=7STcaWjJoww)

## John Wreathall

Wreathall is an expert in human performance in safety. He works at the
[WreathWood Group](http://www.wreathall.com/), a risk and safety studies
consultancy.

Wreathall tweets as [@wreathall](https://twitter.com/wreathall).

### Selected publications
* [Resilience engineering in practice: a guidebook](https://www.crcpress.com/Resilience-Engineering-in-Practice-A-Guidebook/Paries-Wreathall-Hollnagel/p/book/9781472420749)

