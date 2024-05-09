# User Interface $\rightarrow$ UI

Design interfaces for the user to interact with a software and shape the goal they want the software to achieve

**The first example of UI was developed in 1973 by Xerox and popularized in 1984 by Apple**

As designers, we aim to develop a satisfactory way to use said interfaces, defining protocols with the aid of psychology and prototyping based off of needs expressed by the user and the ways it interacts with out software

**This takes place in several steps, as user needs change wrt to age group, sex, etc etc, as well as the programmer's needs for choosing different approaches and paradigms**

This also means that UI's take many forms, and that it has to adapt to different and concurrent users (we can think of this like a "universality" of UI's), while ensuring a **consistent user experience across platforms**

Over the years, **de facto standards were developed to regulate UI's** and to enforce the principle mentioned above
### CSCW - Computer-supported cooperative work

Describes how people utilize technology collaboratively, often towards a shared goal, addressing the support of computers in enabiling and encouraging collaborative activities

The field of CSCW seeks to analyze and draw connections between currently understood human psychological and social behaviors and available collaborative tools

![[Pasted image 20240507102737.jpg|500]]
## The concept of Affordance and Signifier (Norman, 1988)

The affordances (invite to use) of an artifact are the possibilities the user assigns to it and the actions that one can perceive by looking at it, and they can be different wrt the ones the designer wanted

The goal is to eliminate the difference between the two

>*Designers needed a word to describe what they were doing, so they chose affordance
>What alternative did they have? 
>I decided to provide a better answer: signifiers
>Affordances determine what actions are possible; Signifiers communicate where the action should take place. 
>**We need both.***

This goes hand-in-hand with the concept of **feedback**, the pivotal aspect of the interaction

Feedback informs the user that, yes, their input was received and is being acted upon - whether that action is successful or fails is also communicated

![[Pasted image 20240507101331.png]]
## Dark patterns

A dark pattern is a deceptive design pattern to fool the user, directly taking on the psychological aspect of the interaction and influencing the user negatively

This takes many forms: extortion from a user, manipulation of user intent, acting on user wants instead of needs (for example, signing up for a "free" service and making it hard to terminate the service)

--------------
# Definitions of first HCI components

## Widgets

Widgets are interactive components to display content and enable user interaction
Has the capability of triggering actions upon interaction and provides feedback upon usage 
## Labels

Labels are descriptive non-editable pieces of text, usually to represent a chunk of information associated with a button
## Types of widgets

### Button

* Basic widget used for triggering actions
* Is labeled to indicate the action
* Has color, shape and shadow for affordance
* Has feedback
### Input Fields (e.g. search bar or form)

* To enter string-like information
* They should offer clear guidance on the expected input format 
* Has feedback
* Autocomplete improves usability by suggesting possible inputs based on the user's partial input
### Single select widgets

* Lets the user choose one and only option from a list:
	* **Radio Buttons** - best for a small number of options visible at once, usually vertical and belonging to a group that *requires a selection*, rather than it being *checked* 
	* **Segmented control** - lets the user pick one choice from a linear set of closely related choices, and immediately apply that selection (very used in *filtering* and *toggles*)
	* **Pull-down menus** - labeled menus for longer lists

### Multi select widgets

* Lets the user choose one or more options from a list with clear indications:
	* **Checkboxes** - straightforward for small lists (like days of the week)
	* **Menus** - better for space conservation with longer option lists, with colorful toggles (usually shows applied *filters*)

#### Visibility

For both SSW and MSW the choice between making options always visible (radio buttons, checkboxes) or hidden (pull-down menus) impacts usability and space utilization
**It's a matter of aesthetics of functionality and both should be considered when designing**

### Progress bars

* Visual indicator of task completion, used for actions with a noticeable duration to set expectations about waiting times
	* **Determinate** - when the exact time (or filled space) is known and tracked (for example, YouTube or Netflix watch time)
	* **Indeterminate** - when the exact time is **not** known (for example, rotating circle when loading an application)

### Chips 

* Compact elements (used for tags), similat to checkboxes
* Clear way to summarize selections
* Clear way to toggle

### Filters

* Filters help users to refine options or select specific criteria for their researches
* Filters must be intuitive and offer clear ranges and interface for selections
* Should give feedback when applied and update the results accordingly

### Lists

Displays informations, dates or results in a clear and uniform way, giving a preview of what will be accessed upon selection

### Action and bottom sheets

* A series of buttons that cover the screen over its width on the bottom or in the center to prompt the user to make a decision about something
* Triggers a background darkening to make the user shift focus

### Tabs and Tab bars

* Let the user change context within an environment
* Labelled to be descriptive
* Change in color or hue upon selection

------------------------
# Terminology

* **Content**: set of informations that are part of the systemand that have meaning and utility for the user

* **GID** (graphical input device): mechanism to communicate with the system a certain location or choice of an object (typically the cursor’s position)

* **GID button**: main button for the GID

* **Tap**: the action of pressing and releasing a button (which automatically goes back to its original state)

* **Click**: choose the position of the GID and then tap the GID button

* **Drag**: press the GID button without releasing it, move the GID, and then release the button

------------
#### Gestures - A gesture is an input for the computer and produces an action
# Fitts' Law

Predicts that the time required to move to a target area is a function of the ratio between the distance to the target and the width of the target

Quantifies the index of difficulty (ID) of a target selection task:$$ID=log_2\biggr(\frac{2D}{W}\biggl)$$where:
* D is the distance to the sentence of the target
* W is the width of the target
* ID is measured in bits

The aim of HCI is to minimize difficulty and error in rapid pointing movements (e.g. pressing a button)

-----------------
# Navigation

## Information architecture - How do we convey information through the UI efficiently?

* The structural design of shared information environments
* The combination of organization, labeling, search, and navigation systems
* The art and science of shaping information products and experiences to support usability and findability

## Information scent

* The user’s estimate of the value that a source of information will deliver based on:
	* What the user sees
	* Its previous knowledge
	* Context
	* Content

**What are the possible sources of information?** $\rightarrow$ **Labels** in the form of:
* Texts
* Links
* Headings
* Descriptions
* etc etc

**Position conveys meaningful informations**, if we perceive a button position as default, we will be more inclined to click it (usually, the "proceed" button is on the right, as most people are right-handed, the other option exists because **the user always needs to be in control**)

## Discoverability

Discoverability, much like how the word sounds, means the ability of something to be discoverable; it’s the ease that users can find their way around a system and locate certain features
If some things are hard to discover on an interface or the user is easily lost, it may mean that the user flow and information architecture should be reevaluated

----------
# Structural Navigation

_Structural navigation patterns_ give users confidence about where they came from, where they are in the hierarchy, and how to navigate back to where they came from.
## Drill-Down (aka hierarchical)

![Illustration of drill-down columns arranged horizontally to show the concept of cascading lists](https://frankrausch.com/media/pages/tutorials/ios-navigation/c00958b6f4-1696255855/drill-down.svg)

- **The drill-down navigation pattern traverses an information [tree structure](https://en.wikipedia.org/wiki/Tree_structure)** as cascading lists—level by level, screen by screen.
- **Animated transitions imply horizontal movement** between columns: Moving right goes deeper into the tree hierarchy, moving left goes back up the hierarchy.
- **Drill-down navigation is modeless:** Traversing the hierarchy is always possible and is never interrupted by questions about whether to save changes.
- **The [Navigation Bar](https://developer.apple.com/design/human-interface-guidelines/components/navigation-and-search/navigation-bars/)** displays the title of the current screen.
- **[Disclosure indicators](https://developer.apple.com/documentation/uikit/uicellaccessory/3600870-disclosureindicator)** (>) on list rows show that it’s possible to drill down deeper into the hierarchy.
- **A Back button** (<) provides an obvious path back up the hierarchy. If space permits, it should be labeled with the title of the parent screen rather than a generic “Back”.
- **Swiping right from the left edge of the screen** does the same thing as pressing the _Back_ button. Custom implementations should mimic the iOS standard and provide an interactive, cancelable transition controlled by a [screen-edge pan gesture](https://developer.apple.com/documentation/uikit/touches_presses_and_gestures/handling_uikit_gestures/handling_pan_gestures).

## Flat
![Illustration of an iPhone with a tab bar at the bottom and an iPad with a sidebar](https://frankrausch.com/media/pages/tutorials/ios-navigation/accc6a3da9-1696255843/flat.svg)
- **The flat navigation pattern divides the hierarchy at the root level** and presents it as a [tab bar](https://developer.apple.com/design/human-interface-guidelines/components/navigation-and-search/tab-bars/)
- **One of the tab bar items is always selected,** and the active selection determines what’s displayed in the main content area of the app.
- **The currently selected tab bar item should _not_ change programmatically** (without user interaction) **or indirectly** (for example, by tapping a button elsewhere in the interface).
- **The tab bar remains visible** on all screens throughout the application, except when it is temporarily covered by a modal sheet (see below).
- **Tabs can be used as filters** or as different entry points for the same large collection of content, such as a library of music, videos, or photos.
- **Each section retains the navigation state** for its own sub-hierarchy.

##  Pyramid

![Illustration of an overview screen with thumbnails and three sibling detail views with page indicators](https://frankrausch.com/media/pages/tutorials/ios-navigation/7ff59c1460-1696255860/pyramid.svg)

- **The pyramid[2](https://frankrausch.com/ios-navigation#tidwell2020) pattern allows you to quickly navigate between sibling views at the same hierarchy level** without having to go back to the parent screen.
- **The horizontal swipe gesture** is a common way to move between sibling views in a media application. Buttons can also be used
- **The iOS _Photos_ app** demonstrates the pyramid pattern: Tap a photo to open it in a full-screen view, then swipe left and right to flip through adjacent images.

---------
# Overlay Navigation

Overlays want your attention. They can appear over any context.
_Modal overlays_ require a user action before they go away, while _Non-modal overlays_ do _not_ block the app.
## High-Friction Modal

![Illustration of iOS modal sheets and a modal alert dialog box](https://frankrausch.com/media/pages/tutorials/ios-navigation/23be25676f-1696255854/high-friction-modal.svg)

- **High-friction modal overlays–such as sheets and alert dialogs with multiple actions–block what’s behind them until the user makes a decision.**
- **A decision is required to dismiss them
- **The _Cancel_ button must never directly discard any state or data.** Always display an additional confirmation dialog as a safety measure when a user taps the _Cancel_ button on a modal sheet. In an alert dialog, _Cancel_ must never be the destructive action.
- Modals focus on **completing a specific, self-contained task,[1](https://frankrausch.com/ios-navigation#wwdc2022)** 

## Low-Friction Modal

![Ilustration a sheet and a full-screen media player, both with a simple close button. Illustration of a context menu and a popover on iPad.](https://frankrausch.com/media/pages/tutorials/ios-navigation/194ceab766-1696255851/low-friction-modal.svg)

- **Low-friction modals—such as sheets, menus, and popovers—block the rest of the app but do not require “either-or” decisions.**
- **They are easy to dismiss:** “Low friction” means not having to think about how to get back. Pressing the close button or swiping down on a sheet, or tapping anywhere outside of a [context menu](https://developer.apple.com/design/human-interface-guidelines/components/menus-and-actions/context-menus/) or a [popover](https://developer.apple.com/design/human-interface-guidelines/components/presentation/popovers/)—low-friction modals are gone with little effort.

![Illustration of a modal alert dialog box with a message and an okay button as the only way to dismiss it](https://frankrausch.com/media/pages/tutorials/ios-navigation/6b3fef77db-1696255842/low-friction-modal-2.svg)

- **Alert dialogs with only an _OK_ button are easy enough to dismiss, but _low friction_ is not the same as _no friction_:** They interrupt the user’s flow and can often be replaced with inline text or non-modal notifications.

## Non-Modal

![Illustration of an iOS system notification, the system volume feedback slider, and a non-modal palette sheet with a search field at the bottom of the screen.](https://frankrausch.com/media/pages/tutorials/ios-navigation/89f0646cb7-1696255858/non-modal-overlay.svg)

- **Non-modal overlays cover a portion of the screen but do not block the interface behind them.** 
- **They can appear in response to a trigger outside the app,** such as a notification from the operating system, **but they are often unnoticed**.
- **There may be optional interactivity** in a temporary non-modal overlay, such as tapping a notification

------------
# Interaction

