# STAMP

## Introduction

STAMP (Systems-Theoretic Accident Model and Processes) is an accident model
developed by Prof. Nancy Leveson of MIT. It was designed for designing
safety-critical systems. 

STAMP views safety as a control problem. Safety is managed by a control
structure embedded in an adaptive socio-technical system. **The goal of the
control structure is to enforce constraints on system development and operation
that result in safe behavior**.

In STAMP, systems are viewed as interrelated components that are kept in a state of dynamic equilibrium by feedback loops of information and control. 

Safety is an emergent property that is achieved when appropriate constraints on behavior of the system and its components are satisfied. 

**In STAMP, accidents and losses result from not enforcing safety constraints on behavior.**

Basic concepts in STAMP 

1. Safety constraints
1. Hierarchical safety control structures
1. Process models


## Main concepts
### Safety constraints
A constraint is the most basic concept in STAMP.

The cause of an accident is viewed as:
- the result of a lack of constraints imposed on the system design and on operations. 
- Inadequate enforcement of constraints on behavior at each level of a socio-technical system

System-level constraints must be identified.

Responsibility for enforcing constraints must be divided up and allocated to appropriate groups.

### Hierarchical safety control structure
Systems are viewed as hierarchical structures

Each level imposes constraints on the activity beneath it

Control processes operate between levels to control processes at lower levels in the hierarchy.

Control processes enforce safety constraints.

Accidents occur when processes provide inadequate control & safety constraints are violated in the behavior of the lower-level components.

By describing accidents in terms of a hierarchy of control based on adaptive feedback mechanism, adaptation plays a central role in the understanding and prevention of accidents.

Inadequate control may result from:
- Missing constraints
- Inadequate safety control commands
- Commands that were not executed correctly at a lower level
- Inadequately communicated or processed feedback about constraint enforcement

Between hierarchical levels, need:
- Downward *reference channel* providing info necessary to impose safety constraints on the level below
- Upward *measuring channel* to provide feedback about how effectively constraints are being satisfied

*Time lags* may affect flow of control actions and feedback and may impact effectiveness of the control loop in enforcing safety constraints

### Process models

Four conditions to control a process:

1. Goal: safety constraints that must be enforced by each controller in the hierarchical safety control structure 
1. Action condition: implemented in the downward control channels
1. Observability condition: embodied in the upward feedback or measuring channels
1. Model condition: any controller needs a model of the process being controlled to control it effectively

Component interaction accidents can usually be explained in terms of incorrect process models.

In general, accidents often occur when the process model used by the controller does not match the process and, as a result:

1. Incorrect or unsafe control commands are given
1. Required control actions (for safety) are not provided
1. Potentially correct control commands are provided at the wrong time (too early or too late), or
1. Control is stopped too soon or applied too long

Process models play an important role:

1. In understanding why accidents occur and why humans provide inadequate control over safety-critical systems
1. In designing safer systems.

## Accidents
Accidents in STAMP are the result of a complex process that results in the system behavior violating the safety constraints. The safety constraints are enforced by the control loops between the various levels of the hierarchical control structure that are in place during design, development, manufacturing, and operations.

Using the STAMP causality model, if there is an accident, one or more of the following must have occurred:

1. The safety constraints were not enforced by the controller.
    a. The control actions necessary to enforce the associated safety constraint at each level of the sociotechnical control structure for the system were not provided.
    b. The necessary control actions were provided but at the wrong time (too early or too late) or stopped too soon
    c. Unsafe control actions were provided that caused a violation of the safety constraints.
2. Appropriate control actions were provided but not followed.

Classification of accident causal factors starts by examining each of the basic components of a control loop and determining how their improper operation may contribute to the general types of inadequate control.

Causal factors in accidents can be divided into three general categories:

1. The controller operation
1. The behavior of actuators and controlled processes
1. Communication and coordination among controllers and decision makers

When humans are involved in the control structure, context and behavior-shaping mechanisms also play an important role in causality.

### Controller operation
Three primary parts:

1. Control inputs and other relevant external information sources
1. Control algorithms
1. Process model

Inadequate, ineffective or missing control actions necessary to enforce safety constraints and ensure safety can stem from flaws in each of these parts.

For human controllers and actuators, context is also an important factor.

#### Unsafe inputs
Control actions and other info required for safe behavior may be missing or wrong. 

#### Unsafe control algorithms
Control algorithms may not enforce safety constraints because:

- Algorithms are inadequately designed originally
- Process may change and algorithms become unsafe
- Control algorithms may be inadequately modified by maintainers if the algorithms are automated or through various types of natural adaptation if they are implemented by humans

**Time delays** are important consideration in designing control algorithms.
Feedback delays generate requirements to predict when a prior control action
has taken effect and when resources will be available again. When time delays
are not adequately considered in the control algorithm, accidents can result.

Many accidents relate to *asynchronous evolution* where one part of the system
changes without the related necessary changes in the other parts.

Communication is a critical factor here as well as monitoring for changes that may occur and feeding back this information to the higher-level control. For example, the safety analysis process that generates constraints always involves some basic assumptions about the operating environment of the process. When the environment ment changes such that those assumptions are no longer true.

#### Inconsistent, incomplete or incorrect process models

Accidents, particularly component interaction accidents, most often result from inconsistencies between the models of the process used by the controllers (both human and automated) and the actual process state. When the controller's model of the process (either the human mental model or the software or hardware model) diverges from the process state, erroneous control commands (based on the incorrect rect model) can lead to an accident.

The most common form of inconsistency occurs when one or more process models is incomplete in terms of not defining appropriate behavior for all possible process states or all possible disturbances, including unhandled or incorrectly handled component failures.

Inconsistency happens when:
- The process model designed into the system is wrong from the beginning
- Missing or incorrect feedback for updating the process model as the controlled process changes state
- Process model is updated incorrectly
- Time lags are not accounted for.

No control system will perform better than its measuring channel.

Feedback is missing inadequate when:
- Not included in the system design
- Flaws exist in the monitoring or feedback communication channel
- Feedback is not timely
- Measuring instrument operates inadequately

### Actuators and controlled processes
Problem: the control commands maintain the safety constraints, but the controlled process does not implement the commands.

Possible reasons:
- failure/flaw in reference channel (transmission of control commands)
- Actuator or controlled component fault or failure
- Safety depends on inputs from other system components (e.g., power) for execution of controlled actions, where these inputs are missing or inadequate
- External disturbances not handled by the controller

### Coordination and communication among controllers and decision makers
When there are multiple controllers (human and/or automated), control actions may be inadequately coordinated, including unexpected side effects of decisions or actions or conflicting control actions. Communication flaws play an important role here.

Accidents are most likely in overlap areas or in boundary areas or where two or more controllers (human or automated) control the same process or processes with common boundaries

#### Context and environment
Human behavior is greatly impacted by the context and environment in which the human is working. These factors have been called "behavior shaping mechanisms".


## Definitions
### Accident
An undesired or unplanned event that results in a loss, including loss of human life or human injury, property damage, environmental pollution, mission loss, etc.

### Hazard
A system state or set of conditions that, together with a particular set of worst-case environmental conditions, will lead to an accident (loss).

Hazards may be defined in terms of conditions, as here, or in terms of events as long as one of these choices is used consistently.

Hazards are not identical to failures: failures can occur without resulting in a hazard and a hazard may occur without any precipitating failures.

Draw the system boundaries
Identify high-level system hazards
Specify system-level safety requirements and design constraints necessary to prevent hazards from occurring

## STPA - hazard analysis
STPA (System-Theoretic Process Analysis) is a *hazard analysis* technique. The goal of hazard analysis is to identify potential causes of accidents so they can  be eliminated or controlled before damage occurs.

Goals of STPA:
- Identify accident scenarios that encompass the entire accident process
- Provide guidance to the users in getting good results

Two main steps:

1. Identify the potential for inadequate control of the system that could lead to a hazardous state.

    Hazardous states result from inadequate control or enforcement of the safety constraints, which can occur because:
    a. A control action required for safety is not provided or not followed.
    b. An unsafe control action is provided.
    c. A potentially safe control action is provided too early or too late, that is, at the wrong time or in the wrong sequence.
    d. A control action required for safety is stopped too soon or applied too long.


2. Determine how each potentially hazardous control action identified in step 1 could occur.

    a. For each unsafe control action, examine the parts of the control loop to see if they could cause it.

       Design controls and mitigation measures if they do not already exist or evaluate existing measures if the analysis is being performed on an existing design.

       For multiple controllers of the same component or safety constraint, identify conflicts and potential coordination problems.


    b. Consider how the designed controls could degrade over time and build in protection, including

        i. Management of change procedures to ensure safety constraints are enforced in planned changes.
        ii. Performance audits where the assumptions underlying the hazard analysis sis are the preconditions for the operational audits and controls so that unplanned changes that violate the safety constraints can be detected.
        iii. Accident and incident analysis to trace anomalies to the hazards and to the system design.


## CAST - accident/incident analysis
CAST - causal analysis based on STAMP

1. Identify the system(s) and hazard(s) involved in the loss
2. Identify the system safety constraints and system requirements associated with that hazard.
3. Document the safety control structure in place to control the hazard and enforce the safety constraints. This structure includes the roles and responsibilities of each component in the structure as well as the controls provided or created to execute their responsibilities and the relevant feedback provided to them to help them do this. This structure may be completed in parallel with the later steps.
4. Determine the proximate events leading to the loss.
5. Analyze the loss at the physical system level. Identify the contribution of each of the following to the events: physical and operational controls, physical failures, dysfunctional interactions, communication and coordination flaws, and unhandled disturbances. Determine why the physical controls in place were ineffective in preventing the hazard.
6. Moving up the levels of the safety control structure, determine how and why each successive higher level allowed or contributed to the inadequate control at the current level.

   For each system safety constraint, either the responsibility for enforcing it was never assigned to a component in the safety control structure ture or a component or components did not exercise adequate control to ensure their assigned responsibilities (safety constraints) were enforced in the components below them.

   Any human decisions or flawed control actions need to be understood in terms of (at least):

    a. the information available to the decision maker as well as any required information that was not available
    b. the behavior-shaping mechanisms (the context and influences on the decision-making making process)
    c. the value structures underlying the decision
    d. any flaws in the process models of those making the decisions and why those flaws existed.
7. Examine overall coordination and communication contributors to the loss.
8. Determine the dynamics and changes in the system and the safety control structure relating to the loss and any weakening of the safety control structure over time.
9. Generate recommendations.


