# Resilience engineering: Where do I start?

(*This doc is a work in progress. PRs welcome! *).

This doc is an attempt at an introductory guide to readings in *resilience engineering*, aimed at software engineers. I've tried to organize a few key papers into themes.

## Complex systems

A recurring theme in resilience engineering is about reasoning holistically about *systems*, as opposed to breaking things up into components and reasoning about components separately. This perspective is known as *systems thinking*, which is
a school of thought that has been influential inthe resilience engineering
community.

[How complex systems fail](http://web.mit.edu/2.75/resources/random/How%20Complex%20Systems%20Fail.pdf) by 
Richard I. Cook is a great starting point. It's a short paper and very easy to read.

[Drift into failure](https://www.goodreads.com/book/show/10258783) by Sidney Dekker 
is a book written for a lay audience, so it is also very readable. Dekker draws
heavily from systems thinking to propose a theory about how complex systems
can evolve into unsafe states.

## Changing perspectives on accidents and safety

Resilience engineering as a field emerged from the safety science community.
That's why you'll often see examples from aviation and medicine, as well as
other safety critical areas like maritime, space flight, nuclear power, and rail.

Because of this history, the earlier papers that we associate with resilience
engineering are reactions to previous ways of thinking about accidents in 
particular and safety in general.

### New look / new view

The "new look" or "new view" refers to a change in perspective on how accidents
happen, which focuses on understanding how actions taken
by actors involved in the incident were rational, given what information those
actors had at the time that events were unfolding.

[Reconstructing human contributions to accidents: the new view on error and performance](https://www.sciencedirect.com/science/article/pii/S0022437502000324) 
by Dekker is a good place to start here.

### Safety-II

Safety-II is a perspective on the role that humans play in safety-critical 
critical systems, proposed by Erik Hollnagel. In the Safety-II perspective,
it is the everyday, normal work of the humans in the system that create the safety,
as opposed to the errors of humans that erode it.

Hollnagel's [From Safety-I to Safety-II: A White Paper](https://www.skybrary.aero/bookshelf/books/2437.pdf) is a very readable
introduction to Safety-II concepts.


## Themes

Some general themes are:

* changing perspective on accidents and safety
* automation
* coordination
* adaptation
* coping
* learning

These themes overlap, and so a paper may touch on multiple themes. For eample, automation and coordination
overlap in papers that deal with "automation as a team player".



## If you read only one paper


## Classics

These are older papers that are often referenced:

* Bainbridge's [Ironies of automation](https://doi.org/10.1016/0005-1098(83)90046-8) (1983)
* Rasmussen's [Risk management in a dynamic society: a modelling problem](https://doi.org/10.1016/S0925-7535(97)00052-0) (1997) (paywalled)

Bainbridge's paper on automation is as relevant today as when it was written
almost 40 years ago.

Rasmussen's body of work is extremely influential in the resilience engineering
community.  In this widely cited paper, Rasmussen advocates for a cross-disciplinary,
systems-based approach to thinking about how accidents occur. He argues that
accidents occur because the system migrates across a dangerous boundary, and
this migration occurs during the course of normal work.

## Changing perspective on accidents and safety

Over the past few decades, there has been a change in the safety science community about how to understand
accidents in particular, and safety in general. You may hear terms such as "new look", "new view", or "Safety-II".


* Dekker, [Reconstructing human contributions to accidents: the new view on error and performance](https://www.sciencedirect.com/science/article/pii/S0022437502000324) (paywalled)
* Hollnagel [From Safety-I to Safety-II: A White Paper](https://www.skybrary.aero/bookshelf/books/2437.pdf)
* Woods & Cook, [The New Look at Error, Safety, and Failure: A Primer for Health Care]
* Wears, [The error of counting "errors"](https://linkinghub.elsevier.com/retrieve/pii/S0196064408006070) 

## Automation

[Ironies of automation](https://doi.org/10.1016/0005-1098(83)90046-8) is discussed in the [classics](#classics) section.



* [Ten challenges for making automation a team player]
* [Cognitive consequences of clumsy automation on high workload, high consequence human performance]
* [Implications of automation surprises in aviation for the future of total intravenous anesthesia (TIVA)]


[Ten challenges for making automation a team player]: https://ieeexplore.ieee.org/abstract/document/1363742
[Cognitive consequences of clumsy automation on high workload, high consequence human performance]: https://ntrs.nasa.gov/search.jsp?R=19910011398
[Implications of automation surprises in aviation for the future of total intravenous anesthesia (TIVA)]: https://doi.org/10.1016/S0952-8180(96)90009-4

## Coordination

[Common Ground and Coordination in Joint Activity] is an often-cited paper on how people coordinate to perform
tasks together.

[Common Ground and Coordination in Joint Activity]: http://jeffreymbradshaw.net/publications/Common_Ground_Single.pdf

## Adaptation

## Coping


[Being bumpable](http://csel.eng.ohio-state.edu/productions/woodscta/media/beingbump.pdf) looks at how medical professionals cope with increasing load in environments such as an intensive care unit.

## Learning

