---
tags: 📥️/🌐/💤
---

Title: Communicating with Interactive Articles
URL:  https://staging.distill.pub/2020/communicating-with-interactive-articles/
Author: [Fred Hohman], [Matthew Conlen], [Jeffrey Heer], [Duen Horng (Polo) Chau]

---

- some visions of computers by pioneers like [[Alan Kay]] or [[Douglas Engelbart]] have not been achieved
- [[interactive articles]] have emerged as computer-assisted cognition technologies
- they have the following characteristics
	- more engaging
	- help improve learning
- they can be applied in the field of:
	- research dissemination
		- opportunities:
			- Engage and excite broader audience with latest research progress
			- Remove research debt, onboard new researchers
			-  Make faster and clearer research progress
		- challenges
			- No clear incentive structure for researchers
			- Little funding for bespoke research dissemination and communication
			- Not seen as a legitimate research contribution (e.g., to the field, or one's career)
		- examples:
			- [Attacking Discrimination with Smarter Machine Learning](https://research.google.com/bigpicture/attacking-discrimination-in-ml/)
				- A companion piece to a traditional research paper that uses interactive visualizations to let readers adjust a machine learning model’s behavior and explore alternative fair strategies for a loan granting scenario.
			- [Coeffects: Context-aware Programming Languages](http://tomasp.net/coeffects/)
				- A PhD thesis that contributes a programming language abstraction for understanding how programs access the context or environment in which they execute, and walks readers through the work using two simple context-aware languages with live in-browser demos.
			- [What is Complexity Science?](https://complexityexplained.github.io/)
				- A crash course in complex systems science, created by leading experts, practitioners, and students in the field, with accompanying interactive sandboxes to simulate, control, and visualize different complex systems.
	- journalism
		- opportunities
			- Tell stories from multiple dynamic perspectives and levels of detail
			- Highlight importance of a story or report
			- Improve reader comprehension of stories
		- challenges
			- Require active reading in a reader that may be expecting bite-sized news
			- Many readers viewing on mobile devices requires responsive design
			- Difficult to produce at the fast pace of news cycles
		- Examples:
			- [What’s Really Warming the World?](https://www.bloomberg.com/graphics/2015-whats-warming-the-world/)
				- A segmented-story that layers different natural and industrial factors recorded since 1880 on the same axis to compare and contrast which factors are correlated with the increase of the global temperature rise.
			- [You Draw It: How Family Income Predicts Children’s College Chances](https://www.nytimes.com/interactive/2015/05/28/upshot/you-draw-it-how-family-income-affects-childrens-college-chances.html)
				- An article with a partially complete visualization that prompts the reader to draw the trendline that completes the relationship between family income and the percentage of children who attend college, challenging one’s prior belief about the data.
			- [The Uber Game](https://ig.ft.com/uber-game/)
				- A choose-your-own-adventure narrative news game that puts the reader behind the wheel and explores the economics and life of being an Uber driver.
	- education
		- opportunities
			- Reinforce learning by presenting content in multiple forms
			- More quickly grapple complex topics that require visual or geometric interpretations
			- Students can directly interact with systems to build intuition
		- challenges
			- How to best incorporate into traditional learning and classroom environments
			- Making interactive articles accessible to all students
			- Educators lack tools and skills for creation
		- example:
			- [Let’s Learn About Waveforms](https://pudding.cool/2018/02/waveforms/)
				- An interactive guide that introduces and explores waveforms without requiring prior knowledge. The article lets readers play with different waveforms using sound to understand their basic physics and relationship to music and harmony.
			- [The Book of Shaders](https://thebookofshaders.com/)
				- A step-by-step guide that walks a reader through the notoriously challenging topic of computer graphics fragment shaders using interactive code examples.
			- [EconGraphs](http://www.econgraphs.org/)
				- While most interactive textbooks are about mathematics, this collection of key concepts from economics using interactive visualization to help econ teachers illustrate important underlying relationships within economic models.
	- policy and decision making
		- opportunities
			- Concretize complex societal issues using experimental sandboxes
			- Inform public of past, present, and future policies and their impact
			- Dynamic reports that respond to changing situations and priorities
		- challenges
			- May require greater numeracy and graphicacy in audience
			- Few existing examples of effective usage by policy makers
			- Danger of information overload with complex societal scenarios
		- Examples:
			- [To Build a Better Ballot](https://ncase.me/ballot/)
				- An explorable explanation that uses direct manipulation to show election outcomes under different voting methods to provide concrete tools for voting reform.
			- [The Atlas Of Redistricting](https://projects.fivethirtyeight.com/redistricting-maps/)
				- Visualizations of the United States and its breakdown on governmental representation and gerrymandering. Interactive toggles that redraw district boundaries compare the makeup of the US House of Representatives under different goals, both partisan and bipartisan, all without a single voter relocating.
			- [Is It Better to Rent or Buy?](https://www.nytimes.com/interactive/2014/upshot/buy-rent-calculator.html)
				- Built into this article is an interactive calculator that suggests if a reader should buy or rent a property based on a collection of user-selected costs.

---

# Interactive articles: theory and practice
- no standard names
	- in research
		-  explorable multiverse analyses [^1]
		-  explainables [^2]
		-  exploranations [^3] 
	- in journalism
		- interactive stories
	- in science popularization:
		-  explorable explanations
		-  interactive games
		-  (web documentaries)

## connecting people and data
- Make data pleasant to work with.
- Happy readers are engaged readers.
- learning outcomes are strongly influenced by:
	- time spent
	- emotional connections to content
- animations to explore
	- state transitions
	- uncertainty
	- causality
	- narratives construction (and empathy building)
		- anthropomorphize data
		- borrow journalistic and rhetoric techniques
- moving away from author guided narratives to **reader-driven narratives**
	- reading as playing a game
- read more here:
	- [Narrative Visualization: Telling Stories with Data](https://ieeexplore.ieee.org/abstract/document/5613452)
	- [Emerging and Recurring Data-Driven Storytelling Techniques: Analysis of a Curated Collection of Recent Stories](https://www.microsoft.com/en-us/research/publication/emerging-and-recurring-data-driven-storytelling-techniques-analysis-of-a-curated-collection-of-recent-stories/)
	- [Visual Narrative Flow: Exploring Factors Shaping Data Visualization Story Reading Experiences](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.13195)

## Making Systems Playful.
- Run interactive simulations directly in the browser. No setup required.
- long / hard setup deter people --> browser
	- downloading packages
	- having right configuration
	- tweaking parameters
- use of multiple representations
	- see also [[Paivio's dual-coding theory]] + [^4]


## Prompting Self-Reflection.
- Help readers learn by asking them to reflect in a low pressure environment
- self explanation (explaining back to yourself) helps learning
	- interactive articles can foster it by prompting:
		- prediction
		- reflection
	- those can be made by inviting reader to draw
- flashcards and testing

## Personalizing Reading.
- Let readers choose the content that is relevant to their own experience.
- Advantages:
	- this increase engagement and learning [^5]
	- also support behavioral change [^6]
- examples:
	- personalized spatial analogies
	- nonlinear story telling [^7]
		- reader chooses its own path
	- segmenting complex lessons into bit-sized parts consumable in parallels
- read more about [guidelines here](http://www.cond.org/persalog.html) and [here](https://www.wiley.com/en-us/e+Learning+and+the+Science+of+Instruction%3A+Proven+Guidelines+for+Consumers+and+Designers+of+Multimedia+Learning%2C+4th+Edition-p-9781119158660)

## Reducing Cognitive Load.
- Use effective representations to make complex topics more intuitive.
- strike a balance between high level overview and low level details
	- details on demand
	- “Overview first, zoom and filter, then details-on-demand” [link](https://ieeexplore.ieee.org/abstract/document/545307)
		- easily made through tooltip (mouse hovers)
	- affordance and experience flow link towards detailed info


---

# challenges for authoring interactives
- more like building a website than a blog post
	- design and coding
	- well written text
	- seamless integration between the 2
- even for web developers, there are very little [[interactive articles#tools|high level tools]]
- require a broad range of skills
	- editing
	- graphic designer
	- journalist
- rapid changing technology
	- might make deliverable obsolete
- incentives / funding
	- number of papers published vs accessibility of research
- accessibility
	- people with disabilities
	- mobile devices (see [here](https://dl.acm.org/doi/abs/10.1145/3313831.3376777), [here](https://ieeexplore.ieee.org/abstract/document/8805428) or [here](https://ieeexplore.ieee.org/abstract/document/8440812) for principles)
- are they even worth it
	- publishing companies do not share internal metrics
	- [[the death of interactive infographics]] vs [this](https://vis4.net/blog/2017/03/in-defense-of-interactive-graphics/) or [here](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.13720)


[^1]: P. Dragicevic, Y. Jansen, A. Sarma, M. Kay, F. Chevalier, *Increasing the transparency of research papers with explorable multiverse analyses* [link](https://explorablemultiverse.github.io) .  Proceedings of the 2019 CHI Conference on Human Factors in Computing Systems, pp. 65. 2019.
[^2]: *Workshop on Visualization for AI Explainability* [link](https://visxai.io/)  VISxAI. IEEE Visualization. 2018.
[^3]: A. Ynnerman, J. Löwgren, L. Tibell.  *Exploranation: A new science communication paradigm*  [link](https://ieeexplore.ieee.org/abstract/document/8370186?casa_token=rvOSVHyPfCcAAAAA:hpGZrF1ytQIJ4x0jS8J99ok7v16vM-OC_keXvKCbQIuHsACTLXxLr-cutvgZ9PyC3MiAEbNb5Q)  IEEE computer graphics and applications, Vol 38(3), pp. 13--20. IEEE. 2018.
[^4]: R.E. Mayer.  *Multimedia learning*  [link](https://www.sciencedirect.com/science/article/pii/S0079742102800056)  Psychology of Learning and Motivation, Vol 41, pp. 85--139. Elsevier. 2002
[^5]: D.I. Cordova, M.R. Lepper.  *Intrinsic motivation and the process of learning: Beneficial effects of contextualization, personalization, and choice.*  [link](https://psycnet.apa.org/doiLanding?doi=10.1037%2F0022-0663.88.4.715)  Journal of Educational Psychology, Vol 88(4), pp. 715. American Psychological Association. 1996.
[^6]: C. Di Marco, P. Bray, H.D. Covvey, D.D. Cowan, V. Di Ciccio, E. Hovy, J. Lipa, C. Yang.   *Authoring and generation of individualized patient education materials* [link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1839536/)  AMIA Annual Symposium Proceedings, Vol 2006, pp. 195. 2006.
[^7]: J.H. Sizemore, J. Zhu.   *Interactive non-fiction: Towards a new approach for storytelling in digital journalism*  [\[link\]](https://link.springer.com/chapter/10.1007/978-3-642-25289-1_37)  International Conference on Interactive Digital Storytelling, pp. 313--316. 2011
