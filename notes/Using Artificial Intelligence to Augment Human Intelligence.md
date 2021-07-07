---
tags: 📥️/🌐/💤
---

Title: Using Artificial Intelligence to Augment Human Intelligence
Author: [[Michael Nielsen]], [[Shan Carter]]
URL:  https://staging.distill.pub/2017/aia/

---

What re computers for?
- 1940s: calculators for number crunching problems
- 1950s-1960s: [[Douglas Engelbart]] proposed that they could be used for [[Augmenting Human Intellect - A Conceptual Framework|augmenting human intellect]]
- competition between IA (intelligence augmentation) and AI
	- AI is about outsourcing of intellectual tasks to machines
	- calculator (outsource) vs spreadsheet (change mental operations and representations)
	- what about merging the two in AIA (artificial intelligence augmentation)

- input variables = latent variables
- AI (neural net) learns an abstract, higher-level model of what a font is. / a low-dimensional latent space which can be used to represent (say) all font
- That higher-level model makes it possible to generalize beyond the training examples already seen
- a good generative model would be exposed to a relatively small number of training examples, and use that exposure to generalize to the space of all possible human-readable fonts
- this is similar to a scientific theory in that it simplify a complex phenomena
	- by reducing large number of variables to just a few variables
	- we deduce the system behavior from this smaller number of variables
	- we sometimes can generalize from it and discover new phenomena
	- ex: phase transition
		- it is determined by the state of a big number of molecules
- the case of bolding font
	- it's not a trivial process (not as simple as adding pixel all around)
		- this would change the size of the letter
		- it would fill the hole of letter A
	- experts apply many heuristics
	- AI automatically learn (some of) those heuristics
- problem is some heuristics learnt are wrong 
	- spotting those wrong heuristics is difficult
		- bias in your data
		- a single transformation can't be applied to all cases
			- but we could develop ML models to do this
- example of landscapes / shoes
	- AI learns a low-dimensional latent space which can be used to represent (say) all landscapes
	- when the user sketches, this corresponds to picking a subspace of the latent space
		- find a point in the latent space which is near to the current image, so the image is not changed too much
		- while coming close to satisfying the imposed constraints.
		-  This is done by optimizing an objective function which combines the distance to each of the imposed constraints, as well as the distance moved from the current point
- this gives *access to non expert the heuristics that experts apply*
	- access to  **cognitive transformation model** change the *operations and representations we use to think with*
	- AI to be used to explore and discover, to provide new representations and operations
	- those can then be internalized as part of the user’s own thinking
	- examples:
		- in this paper the focus is on exploring the latent space
		- check [here](https://arxiv.org/abs/1704.03477) for neural network assisted drawing
		- [this](https://dl.acm.org/doi/book/10.5555/2125776) enables users to rapidly build new musical instruments and artistic systems
		-  [here](https://nips2017creativity.github.io/doc/TopoSketch.pdf) developing animations by exploring latent spaces;
		-  a [generative model](https://nips2017creativity.github.io/doc/Hierarchical_Variational_Autoencoders_for_Music.pdf) which enables interpolation between musical phrases
	-  also related to [[compûtational creativity]]
		-  see [here](https://ebooks.iospress.nl/publication/6941)
		-  and [here](https://www.cs.waikato.ac.nz/~ml/publications/2000/00MW-etal-Interactive-ML.pdf)
- new representations are often difficult to understand and appear strange
	- Examples of early rejection
		- Feynman's diagram
		- Picasso cubist works
	- does this contradict UX principles of user friendly ?
		- user friendly = build from conventional elements combined in standard 
		- user friendly not as easy to use but as broadening mastery
- AI should be able to:
	- **discover and recognize deep principles** about the world
	- **surface** those **as vividly as possible** in an interface
	- **convert** those principles in a way **comprehensible** by the user
- 2 modes of creativity (simplification)
	- craftsmanship: recombination of best existing practices
		- don't necessarily involve developing new principles
		- for this, approach GANs described in this paper could be useful
	- developing new principles that transform the range of creative expression
		- ex Picasso or Monet
		- GANs seem more limited here
			- but what if GANs were intentionally "imperfect"
				- see  [Mario Klingemann](http://quasimondo.com/) and [Mike Tyka](http://www.miketyka.com/)
			- what if GANs were not only for (human) latent space?
			- ==what if we combine with genetic algo?==

Conclusion
what if we aimed at:
