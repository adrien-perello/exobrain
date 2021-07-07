---
tags: 📥️/🌐/💤
---

Title: How can we develop transformative tools for thought?
URL:  https://numinous.productions/ttft/
Author: [[Andy Matuschak]] [[Michael Nielsen]]

---

# Introduction 

>   The very use of \[personal computer\] would actually change the thought patterns of an entire civilization
>  <div class=signature>Alan Kay, User Interface: A Personal View(1989) </div>


- 60s and 70s computer scientists pioneers envisions computers as [[tool for thought]]
	- see also:
		- [[Alan Kay]]
		- [[Douglas Engelbart]]
		- [[Seymour Papert]]
		- [[Ivan Sutherland]]
		- [[Vannevar Bush]]
- but computers have not been as transformative as hoped (like other [[Examples of tools that augmented our intelligence]])
- tool (for thought) vs medium (for thought) [^1]
	- 


---

# Augmenting memory

## Mnemonic medium

### space repedition

- *How could you build a medium to better support a person’s memory of what they read?**
- *What interactions could easily and enjoyably help people consolidate memories?*
- *Can we increase what people remember by 2x? by 10x?*
- **mnemonic medium** as an attempt to make easy for users to remember what they read
- Authors designed a prototype  [Quantum Computing for the Very Curious](https://quantum.country/qcvc)
- an article which integrates old-fashioned flashcards with [[space repetition memory systems]]
- [[space repetition memory systems]] are mainly used for declarative knowledge
	- could they be used for abstract, conceptual knowledge?
	- what are the barriers that prevent their use to spread?
- the authors believed these techniques to be really valuable, asking the questions:
	- How deep can the understanding developed through a memory system be?
	- What patterns will help users deepen their understanding as much as possible?
	- How far can we raise the human capacity for memory? And with how much ease?
	- What are the benefits and drawbacks of raising memory capacity?
	- Might it be that one day most human beings will have a regular memory practice, as part of their everyday lives?
	- what could developing such tools teach us about designing tool for thought?
- the authors are NOT saying that good memory system = spaced repetition


### Making good space repetition flashcards?

- see [[Augmenting Long-term Memory]] for discussion about good principles of card construction
- **garbage in, garbage out**
- Most questions and answers should be **atomic**
	- Example:
		- Q: “How to create a soft link from linkname to filename?”
		- A: “ln -s filename linkname”
		- VS
		- Q “What’s the basic command and option to create a soft link?”
		- Q “When creating a soft link, in what order do linkname and filename go?”
		- A: “ln -s”
		- A: “filename linkname”
		- Keeping those 3 questions (higher level for integration, atomic for focus)
- **avoid orphan cards** (cards bit closely connected to anything else)
- \[there are other principles but they are not detailed in the article]
- ** make your own cards** (vs using someone else card)
	- users often report dissatisfaction and poor results when working with cards made by others
	- Their prototype does not seem to suffer from this
	- this is maybe because of the good flashcard design skills --> deserves more research according to authors
- Ensure users don’t just learn **surface features of questions?**
	- Example:
		- There is only one "Who ... ?" question
		- --> readers don't need to engage with the question and can parrot the answer
		- instead, vary the form of the question:
		- "who has done ... ?" + " __ has done ... ?"
	- Authors aim at developing a library of techniques for identifying learning-the-surface features pattern occur
- **help users when they forget** the answer to a question
	- currently, wrong answer = reduce time space
	- what if instead, they were **follow up questions** to simultaneously encode the context?
- **Encode stories and narrative**
	- ! this could violate the principle of atomicity


### Elaborative encoding

- the richer the associations we have to a concept --> the better we will remember it
	- it's easier to learn something related to our field of expertise (we can build more associations)
	- see [[scaffolding]]?
- **Provide questions and answers in multiple forms:**
	- combine different modalities (sound, image, symbol, ...)
	- see [[Paivio's dual-coding theory]]
- **Vary the context** (requires more testing)
	- based on Steven M. Smith, Arthur Glenberg, and Robert A. Bjork, [Environmental context and human memory](https://numinous.productions/ttft/assets/Smith1978.pdf) (1978)
	- for example
		- changing the location of review
		- changing the time of day of review
		- changing the background sound
- Consider the knowledge network structure (how the cards are interrelated)
	- What happens to people’s observed recall if you remove a card?
	- Are there crucial linchpin [^2] cards?
	- Are there particularly effective network structures?
	- Are there particularly effective types of relationship between cards?
	- Are there general principles we can identify about finding the deepest, most powerful ways of representing knowledge in this system?

### Mnemonic techniques

- Example:
	- "Roy G. Biv" = order of colors in rainbow
	- using a song to remember the periodic table element
	- the [[Method of loci|memory palace]]
- however, they have limits
	- require heavy time investment
	- they are rather specialized
		- concrete objects (rather than abstract conceptual knowledge)
	- they also rely on associations, but NOT all associations are equals
		- experts create meaningful connections to what they already know
		- those connections are useful in themselves
- but they can still be very useful (they have not been explored much in their prototype)
	- especially for information that have an arbitrary ad hoc structure (ex color of rainbow)


## the importance of memory

- memory is sometimes disregarded (vs problem solving, understanding, creativity, ...)
- this comes from misunderstanding:
	- student often struggle with quantum mechanics because of basic notation and terminology
		- NOT because of high level complexity
		- based on author's personal experience
	- fake opposition between memorizing details vs conceptual mastery
		- broad conceptual understanding requires detail mastery
		- automating away the problem of memory makes it easier to focus on other parts of learning
	- we naturally learn things when we regularly apply them
		- but authors are not claiming for learning detail "just in case", or for a "just one time" project
		-  yet having learnt a topic, makes it more likely to apply it
		-  mnemonic medium are about accelerating the awkward early phase 
		-  highlight an important question: one size fits all is maybe not always relevant
- memory shape perception [^3] [^4]
	- chess masters don't see individual pieces
	- instead they recognize "chunks" (high abstraction of a combinations of pieces)
- Authors hypothesis that memory is disregarded because association with rote learning
- however, some criticisms are useful:
	- how can memory system decide what is important / beneficial to memorize?
	- how does mnemonic medium impact people's behavior?


## design process for paradigm shift

- the example of roman numerals to Hindu-Arabic numerals
- would current design practice lead to such a transition? Not sure
- current tech industry are more linked to pop culture than research culture
- making new tools can lead to new subject matter insights for humanity as a whole

---

# Broader tool for thought

## the role of emotions
- emotional connection is at the basis for effective learning / action
- emotional connection easier created through video rather than text
- what would a mnemonic video look like?
	- attempt with MOOCs
		- dry questions
		- break of flow
	- how to ensure a good balance of emotional and intellectual experience
		- frequency and density of questions
		- work on [[tool for thought]] needs to take seriouly the question of [[emotions]]


## why so little progress
- the question of business models around developing new tools for thought
	- expensive to develop
	- easy to copy, and duplicate in better
	- follow the same path as public good
	- it's not the case in certain industries
		- where really big investment is required
			- ex: hard tech industries
		- where profit comes from a novelty-based short-term revenue approach
			- video games whose profit is mainly made within few months of release
			- --> new development remain a competitive advantage over that small time span
			- this contrast with long term lock-in investment
		- based on patents
			- but drifting from original intent
			- value now comes from vagueness of the patent’s claims and the ability to enforce it
	- inspiration from companies like
		- google
		- twitter
			- network effect
		- hardware devices
			- harder to copy than software
			- market advantage often lie in:
				- distribution
				- marketing
				- customer relationship
	- looking toward philantropic funding for research
	- what if profit is not derived from the tool itself, but build around training, marketing, documentation...
		- [[neo4j]] ?


## assumptions

### many more transformative tools for thought are yet to be discovered
...

### work on tools for thought is stalled
...

### work on tools for thought as worth doing as AI or BCI

- work on tool for thought is much more vague and an open-question exploration
- AGI and BCI have much clearer goal
- but breakthrough often happen from "random" exploration
	- original computers started with Church and Turing exploring ideas like the nature of what is provable
- authors believe the field will become much more important
- maybe possible the 3 fields will merge somehow
	- AI has a way to discover tools for thought in [[Using Artificial Intelligence to Augment Human Intelligence]]
	- BCI even more strongly related


## Executable books

- Authors very enthusiast by the jupyter notebook trend
	- but they believe it has not been pushed hard enough
	- what about rewriting the IPPC climate assessment report in Jupyter?
- low floor high ceiling tool
	- low floor: easily accessible to novice
	- high ceiling: useful to experts too
- top down explanation vs bottom up to create emotion connections with the topic



[^1]: see for example Alan Kay, [User Interface: A Personal View](https://numinous.productions/ttft/assets/Kay1989.pdf) (1989)
[^2]: a person or thing vital to an enterprise or organization.
[^3]: William G. Chase and Herbert A. Simon, [Perception in Chess](https://numinous.productions/ttft/assets/Chase197s.pdf) (1973).
[^4]: Some fascinating earlier work in a related vein was done by Adrian D. de Groot, and summarized in his book _Thought and Choice in Chess_ (1965).