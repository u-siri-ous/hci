# Tasks and Storyboards

During Need Finding, needs have to be identified and prioritised

- Which needs do we want to satisfy with our interface?
- Why should people use it?
- What should it allow to do?

We start by defining tasks
## Tasks

Any specific activity or action that one performs within a system to accomplish a goal

### Task identification

_General activities should be partitioned in several task_, where each one allows the user to achieve a goal to satisfy the selected needs

## **How to represent tasks → Storyboards**

_a Storyboards is an hand-drawn illustration that represents a task_, each task is represented with a storyboard

characteristics:
- simple and efficient
- comprehensible
- communicate the task to the other designers in the team

It represents:
- the context/situation in which the task is needed and performed
- the actors/users
- **not the screens**

It should present 2-4 illustrations for each task

### **Pros and cons of storyboarding**

- showcase the system and how it is used
- allows to share the idea with other members of the team
- doesn’t contain a specific interface (we don’t want to be constrained to a poor interface in this phase)
- allows discussion on how to improve
- are easy to change and adjust

-------------
# Prototyping

A prototype is a model of an interactive system that simulates or animates some aspects/characteristics/functions (not all of them)

Used to validate a concept, to learn and test first versions of an app
### Types of prototypes

- A simple drawing
- The UI of another application, with some functionality similar to what we are designing
- An interface with a “fake” backend
- An interactive application with some functionality
- A full working application
### Steps from storyboards to UI

1. imagine the interaction
2. draw the interface while considering tools available (hardware devices, widgets, types of interactions)
### goal of prototypes

- They are used to evaluate the impact of the UI on users
    - therefore the evaluation criteria must match those used for the final interface
- To try and validate a concept/idea
- To learn
- To test a version of the application (initial, intermediate, final)
### Approaches to prototyping

- Throw away — get the knowledge but discard the prototype
- Incremental — all the different functions are added to the prototype one at a time
- Evolutionary — a prototype is used as the foundation for the next one, improving it

Prototyping is done in an **iterative cycle**

![[Pasted image 20240515211215.png]]

the **steps** of iterative prototyping are:

- Understanding what is wrong
- Thinking on how to improve
- Having a good starting point

## the potential problems of prototyping:

### Time

Making prototypes might be time consuming

**solution** → rapid creation of the prototype, careful evaluation phase

### Planning

Hard to plan the design process with prototyping because it’s hard to estimate the costs and the time. The designer must bargain with the client.

### Non-functional characteristics

prototyping doesn’t consider:

- security
- reliability
- response time

remember:

- wrong decision taken at the beginning have to be revisited to avoid **design inertia**
- Understand the causes of the problems rather then detect the “symptoms."

### Paper prototyping - cheap and fast

Try to keep the same proportion of the actual interface

They are made with **low fidelity** (not much importance given to the aesthetics) in order to:

- reduce time
- immediate testing with users
- user focuses on the tasks rather than the graphics
- cheap to throw away and redo

**paper prototyping is used to test:**

- navigation
- workflow
- terminology
- functionality

### Wizard of Oz

**Interface that simulates the actual behaviour through the intervention of someone behind the scenes**.

The user interacts with the system as they would with a fully automated version, unaware that their actions are being controlled by a human operator.

This method allows designers to gather feedback on the user experience and interface design without investing the time and resources required to develop a fully automated system.

The Wizard “translates" the user input and operates the system as it would act in reality if it was fully functioning (e.g. insert text, continue to the next screen, select a point on the map, etc.)

**pros**

- interactive but with little code to write
- easy to adapt and can be reused
- more realistic than paper prototyping
- involves the user
- designer learns by acting as the wizard

**cons**

- Unfaithful simulation of imperfect technology
- the simulated technology might not work in reality and never be implemented
- some features can’t be simulated
- acting as a wizard is tiring

-----------
# Evaluation

Evaluation is used to test the usability and functionality of a system, using some artifact/product like a prototype, a simulation or an implementation.

### Goals of evaluation

- assess extent of system functionality
- assess effect of interface of the user
- identify problems

### How to perform evaluation

#### **Evaluation through user participation**

The participants (3/5 suggested) should be representatives of possible user and all have similar experiences.

#### **Scenario and tasks**

- The scenario describes a potentially real situation in which the participants will be put during the evaluation
- Tasks are the objectives that the participants are asked to accomplish
    - evaluation can be done also by just observing the user interacting with the system

The **evaluator** should **explain the scenario and the task**, and without helping they should evaluate how the user performs the task → if the user is not succeeding in performing the task, then the interface doesn’t work.

The evaluator should:

- observe what they are doing
- gather thoughts/reasoning process from the user and see if they align with how the task should be performed

### Evaluation in the lab vs in the field

#### **on the field →** in the real situation in which the app would be used

- Appropriate where context is crucial for longitudinal studies

+Natural environment
+Context retained (though observation may alter it)
+Longitudinal studies possible (studies prolonged for long periods of time)

-Distractions
-Noise
#### **in the lab**

is difficult to observe the user in the specific situation especially you can’t see users cooperate

- Appropriate if system location is dangerous or impractical, sometimes lab testing is necessary

+Specialist equipment available
+Uninterrupted environment

-Lack of context
-Difficult to observe several users cooperating

![[Pasted image 20240515215924.png]]
## observational methods

they are subjective and depend on the knowledge and skills of the evaluator

**The evaluator should recognise the problems and understand what the user is doing**

the evaluator bias must be taken into account → it can be diminished by having multiple evaluators

Also the user response is subjective

**it’s subjective both on the evaluator and the user side**

**they give back qualitative measures**

- these methods give back **qualitative non-numeric measures**
    - it is useful to reveal details otherwise hard to find with numeric measures

### Think aloud

- The user is observed while performing the task and has to describe what they are doing, why, what they think is happening and what they expect as result.

**pros and cons**

+Simplicity - requires little expertise
+Can provide useful insight
+Can show how system is actually used

-subjective
-describing may alter task performance (locus of attention)

### cooperative evaluation

* Variation on think aloud, where user collaborates in evaluation by asking questions to the evaluator and viceversa

+Less constrained and easier to perform
+the user is encouraged to criticise the system
+clarification possible

### protocol analysis

Protocol analysis stands for the **analysis of the data collected during the interactions** of the user with the system

**protocol →** recording of the evaluation session, irl a mix of them is used

**types of protocols**

- pen and paper
    - cheap but limited to the writing speed
- audio recordings
    - good for think aloud evaluations but difficult with the other methods
- video
    - needs specific equipment and it’s obtrusive but it’s accurate and realistic
- computer logging
    - automatic and unobtrusive but it’s a big amount of data hard to analyse
- user notebooks
    - coarse (rough) and subjective but good for longitudinal studies

### post-task walkthrough

A post-task walkthrough involves replaying the transcript, whether written or recorded, to the participant and inviting them to comment or directly questioning them, in order to identify reasons for actions and alternatives considered

They are useful when think aloud is not possible.

it can be done in different times:

- immediately → the user has fresh memories
- delayed → the evaluator can think about questions to ask to the user

## Experiments

### Experimental evaluation

- Controlled evaluation of specific aspects of interactive behavior
- Evaluator chooses hypothesis to be tested (determined measuring participant behavior)
- A number of experimental conditions are considered which differ only in the value of some controlled variable.
- Changes in behavioral measure are attributed to the different conditions

### Experimental factors

- Subjects: who – representative, sufficient sample
- Variables: things to modify and measure
- Hypothesis: what you’d like to show (a temporary idea whose value needs to be assessed)
- Experimental design: how you are going to do it

- **Independent variable (IV)**:

characteristic changed to produce different conditions

e.g. interface style, number of menu items

- **Dependent variable (DV)**:

characteristics measured in the experiment

e.g. time taken, number of errors

e.g. the number of the products that i sell depends on the color of the button

#### Hypothesis

- Prediction that a variation of IV will cause a difference in the DV

e.g. “When font size decreases error rate will increase”

- Null hypothesis:
	- states there will be no difference in the DV
	- aim is to disprove this
	- e.g. null hyp. = “same error rate when changing font size”

#### Experimental design

- Choose the hypothesis
- Choose the dependent and independent variables
- Choose the participants
- Choose the experimental method: between subjects or within subjects

#### Conditions

- Control conditions
- Experimental conditions: only one IV modified with respect to the control condition

**The control condition is needed to be sure that the change of the IV is responsible for the (possibly) measured change of the DV**

##### Between subjects

- Each participant is assigned a single condition, so they execute the test only once

-More participants are required
-Variation between users can alter the evaluation results

+Doesn’t suffer from the “transfer learning” effect 

##### Within subjects

* Each participant is assigned all of these conditions so they execute the test 2 or more times

+This experimental method requires less participants, therefore is less expensive
+Differences between users do not affect the evaluation so much

-Suffers from the “transfer learning” effect

##### Mitigating the transferring of learning

- Half of the participants perform the test with the control condition first, then with the experimental condition
- The other half performs the test with the experimental condition first, then with the control condition

#### Statistical analysis of the data

- Save the original data (could be useful later on)
- Analyze the data (DV)
- Possibly on a graph
- Find the outliers

#### Statistical analysis

- If the data satisfies the normal distribution:
	- Parametric tests (very robust techniques of standard statistical analysis)
- otherwise:
	- Non-parametric tests, contingency table,...
- Hypothesis checks:
	- No for the "yes" answer / No for the null hypothesis
	- “we can, with 99% of possibilities, invalidate the null hypothesis”

## Expert-based

**The later an error is found, the more expensive it is to fix it.**

However involving users in all evaluations is expensive too → **evaluate without users**

- One ore more experts evaluate the impact of the design on the “typical user"
- To identify aspects that can be problematic:
	- Because they violate known cognitive principles
	- Because they ignore validated empirical results

**pros**

cheap
usable in all design and development phases

**cons**

they don’t evaluate the usage of the system but rather is it follows the known principles

### cognitive walkthrough

_(Proposed by Polson et al., 1992)_

**It evaluates design based on how well it supports the user in learning a task - how easy is it to learn a task**

It is usually performed by expert in cognitive psychology who are meant to identify potential problems using psychological principles

**we need**:

- System specifications
- Task description
- Sequence of steps required to complete the task
- Description of the typical user

**how to do it**:

For each step, the expert tries to answers the questions:

- Will the user understand what is the action that they need to take?
- Can the user see that the action is available?
- Is the effect of the action the same of the user’s objective?
- After such action, will they understand the received feedback?

The expert reports all the problems on a form, indicating also the severity for each one

### heuristic evaluation

**heuristics →** _guideline/rule/principle that is in principle simpler and more efficient_

In the heuristic evaluation, the evaluators examine the project to see if it violates one or more heuristics (e.g. Nielsen’s heuristics)

**Nielsen’s heuristics**

1. Visibility of the system’s state
2. Match between the real world and the system
3. Freedom and controls by the users
4. Coherence and standards
5. Error prevention
6. Recognize rather than recall
7. Flexibility and usage efficiency
8. Minimalistic design
9. Helping the users recognize, diagnose and fix the errors
10. Guides and documentation

### model-based evaluation

Consists in the **usage of existing models** to evaluate the interaction

These models provide frameworks for understanding and predicting the user’s behaviour and system performance

1. **GOMS (Goals, Operators, Methods, and Selection rules)**:
    - **GOMS is a cognitive model used to predict user performance while interacting with an interface**.
    - It breaks down user tasks into goals, subgoals, operators (actions), methods (sequences of actions), and selection rules (decisions).
    - By analyzing the structure of user tasks and the cognitive processes involved, GOMS can estimate how long it will take a user to complete a task, how many steps are involved, and potential points of error.
    - For example, GOMS might be used to predict how long it takes for a user to complete a specific task in a software application based on the sequence of actions required.

2. **KLM (Keystroke-Level Model)**:
    - **KLM is a model used to predict the amount of time needed to complete low-level physical tasks, such as using the keyboard and mouse**.
    - It assigns fixed times to basic actions like pressing a key, moving the mouse, or clicking a mouse button.
    - By summing up the times for each action required to complete a task, KLM can estimate the total time it will take a user to perform the task.
    - For example, KLM might be used to predict how long it will take a user to perform a specific sequence of actions in a graphical user interface (GUI).

3. **Dialog models**:
    - Dialog models are used to **evaluate the sequence of dialogues between a user and a system**, considering factors like user inputs, system responses, and potential dialogue paths.
    - These models can help identify issues such as unreachable states (situations where the system cannot respond appropriately to user input) or inefficient dialogue flows.
    - By analyzing the structure and logic of dialogues, designers can ensure that interactions with the system are intuitive, efficient, and error-free.
    - For example, a dialog model might be used to evaluate the effectiveness of a chatbot's conversation flow or the navigation structure of a voice-controlled interface.

### review-based evaluation

Consists in using results from previous studies to support or reject parts of designs (given that the results are transferable to your design).

It is important to make sure that the correct assumptions are made in the studies.

## LLMs in evaluation

LLMs can automate and speed up the evaluation process by performing heuristics evaluations and identifying strengths, weaknesses, and opportunities for improvement.