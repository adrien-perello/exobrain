---
tags: 📥️/🌐/⌛
---

Title:  up and down the ladder of abstraction
URL:  http://worrydream.com/#!2/LadderOfAbstraction
author: [[Bret Victor]]

---

### [[Why and how to improve our understanding of systems]] ?

![[Why and how to improve our understanding of systems]]

---

# method

- start with simplest possible design (i.e, a road and a car)
- let user control the *time* and *independent variables* of the system
- let user control the *parameter of the algorithm*  (i.e. the turning angle)
- **abstract over time** *(step up on the ladder of abstraction)*
	- don't limit the representation at one particular time (i.e. show the full trajectory vs current position)
- allow for **stepping down the ladder of abstraction** (i.e represent both current position AND trajectory)
- **abstract the algorithm** *(step up on the ladder of abstraction)*
	- single representation that depicts the system for many parameters (instead of any particular one)
	- play with metrics and offer multiple ways of abstracting over a given set of variables
	- the more ways we have of looking at the system, the most insights we can gather.
-  allow for **stepping down the ladder of abstraction**  again
	-  repeating the process of up and down the ladder allows to **see a high level pattern** and then **discover the explanation** for that pattern
- let user control the data / environment (i.e. the shape of the road)
	- focus on significant aspect of the data / environment that showcase challenges
- **abstract the data** *(step up on the ladder of abstraction)*
	- one option being multiple datas represented with previous abstractions (multiple road shapes)
	- or to abstract behavior in one single abstract representation
- allow for **stepping down the ladder of abstraction**  again
- etc.

In a 2nd stage:
- iterate by improving the model
- restart the process of up / down the ladder to explore the new system
	- climb up to **see a high level pattern**
	- climb down to **discover the explanation** for that pattern


# anatomy of interactive articles
- **independent variable** (usually time) to explore [[causality]]
- **structure** = set of rules that the system obeys (algorithm, equation ...).
	- We can control the part by:
		- rearranging the structure
		- adjusting values within the structure
- **data** is what is fed to the rules
	- controling the data help understand how it influences behavior

# model of interaction
- take control over specified parameters to understand how it influences the system
	- interactive control of each parameter should allow to:
		- go forward
		- go backward
		- jump to arbitrary position
- step up to an abstraction with a representation across all value of parameter
	- this allow to discover **high level patterns**
- step down an abstraction by interactively selecting one particular value for the abstracted parameter

