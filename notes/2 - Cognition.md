# Attention and interaction

## Locus of attention

The thing we're putting attention on, and may not coincide with the interface focus
Something we're thinking , and is cannot be controlled in its entirety

![[Pasted image 20240509111957.png]]

Generally, the locus is **singular**, meaning that, most of the times, the execution of two or more tasks at a time is not optimal, and, typically:
* performance worsens
* the execution is not concurrent, but rather performed alternatively

An event (interal or external) can still shift the locus of attention, even though we're deeply **engaged** in something, if it's noticeable

We have to predict and exploit the locus of attention of the user, because that would mead that our work is **able to take the attention of the user**

It's also worth noting that some tasks are **automatic** (e.g. muscular memory, writing on a keyboard without looking, etc etc), and developed through **habits**

Habits can also be dangerous and are hard to break! We don't want users to develop a bad habit from using our products, we want, instead, the user to develop positive habits and make it use the apps to facilitate everyday life

## Change of context

A change of context happens when a task is interrupted and then resumed, the key in the example below is to prepare for the previously interrupted task vs starting a new task

![[Pasted image 20240509114048.png]]

### Resuming a task

A UI helps in this by:
* showing the last displayed screen (when we hang up after a call),
* moving the cursor where it was left off (browser that opens all the tabs from the latest session)
### Start a new task

A UI can help in this by:
* allowing to change place easily or to start over (e.g., to go back, to the home page, or to a main view, etc.)

----------
# Modes

In different **modes**, the same gestures can lead to different outcomes (e.g., the return key/button can be interpreted as “new line” or “enter”):

* Gesture does not univocally determine action
* The user must check the system state and understand in which mode the system is

Many times, the mode is signaled in some way (e.g. the caps lock button often has a small LED), but it has to be in the locus of attention to be noticed
### How can we help the users in avoiding mistakes?

1. Do not have modes
2. Make sure that the modes are distinctively marked
3. Make sure that the commands required by different modes are not the same so that a command issued in the wrong mode will not lead to difficulty
### When is a UI "modal" regarding a given gesture?

1. The current state of the UI is not the locus of attention of the user
AND
2. The UI will react to the gesture with one between *N* possible replies, depending on the state

**A non-modal interface is non-modal wrt all possible gestures**
### What can we use to get around modes?

* Temporary modes
	* a mode that disappears after use (e.g. brush in Word, activated with only one click)
* Quasi-modes
	* a mode obtained activating and maintaining physically a control (e.g. capital letter buttons, CTRL button)
* Prioritize tasks

## Verb-Noun vs Noun-Verb

Executing actions (verbs) on objects (nouns):

* **Noun-verb**: first you select the object
	- You select an object while it is in the locus of attention
	- The locus of attention moves on the action and then
	- Interrupting the action doesn’t require another action (cancel or escape)
* **Verb-noun**: first you select the action
	* This creates a mode, as we create a state to **do** something, and same interaction may lead to different result (the locus is not fixed)

---------------
# Implicit interaction

The user is to be able to use the system:
* Effectively
* Efficiently
* In a satisfactory way (usage has to be not frustrating)

These characteristics improve **usability**, and they depend on the **context** 

Contexts change continuously with the usage of multiple devices, so systems must be **context-aware**: these systems collect data from the outside to make decisions or offer better services to the user. Examples of this are:

* Automatic lights and brightness
* GPS navigation devices

Therefore, context-aware systems need:

1. **Sensors** - to collect data
2. **Perception algorithms** - to understand the data
3. **A way to act** - depending on the observed context
4. **Transparency** - they should not require too much active attention and should anticipate the needs 

![[Pasted image 20240510102713.png]]

Anticipating a user's needs is quite difficult: there is a **gap** between the user's expectations and the system's behavior (aka **awareness mismatch**)

![[Pasted image 20240510103508.png]]

When building a context-aware system, first create a (hierarchical) **feature space** with factors that will influence the system behaviour

With this, we aim to **close the gap** as much as possible:

1. The user has to understand which factors have an influence on the system
	* It needs a clear idea of what's happening in a simple way
	* Convey a mental model to the user
2. We need to understand how to implement the features in the feature space
3. In the user interface, provide information about the sensory information that is used to determine the context in order to minimize the awareness mismatch
4. Find parameters [features] which are characteristics for a context you want to detect
5. Find means to measure those parameters [sensors]
--------
## Useful recap c:

1. sensory input available
2. determine context
3. system acts differently in different contexts
4. match the user’s expectation in each context
5. minimize awareness mismatch

---------
## Implicit vs Explicit human interaction

The concept of context awareness is generalized in **Implicit Human Interaction**, where the computer virtually disappears, but also makes the user's life easier

**Explicit Human Interaction** finds its place in buttons and widgets, stuff the user has to interact with

### **Implicit input**

Actions and behaviour of humans which are done to achieve a goal, and which are not primarily regarded as interaction with a computer, but captured, recognized, and interpreted by a computer system as input

### Implicit output

Output of a computer not directly related to an explicit input, and which is seamlessly integrated with the environment and the task of the user

------------
## Range of system actions

* low-level functionalities (e.g. network connection)
* application behaviour and supported functions (e.g. different access privileges from different locations)
* changes on a user interfaces level (e.g. different zoom levels in navigator map)
## Context-Awareness

### Context-adaptive systems and triggers

Designing proactive applications is very difficult because the system has to anticipate what the user wants
**In many cases, it is much easier not to present “the application” and rather to present a set of potential interesting applications which the user can launch**

For example, a context-aware "home screen" may offer a selection of applications that are useful in a given context rather than attempting to choose the right one

* **proactive applications** — detect user intentions and activate an application (or suggest some)
* **adaptive applications** — trigger (activate) a function or part of application based on context

**Use adaptation in the UI with great care and ensure that it is understandable to the user**
Good designs maintain stability and support the user in memorizing the UI while using context to reduce complexity

This also finds a place in **context-aware resource management** and in **context-sharing to improve user experience**

![[Pasted image 20240510121416.png]]






