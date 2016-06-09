# octet-system
Octet System for categorizing levels of machine intelligence

Original blog post: https://mbrebo.com/2015/12/19/the-octet-system-a-way-to-think-about-ai/

## Contributing

This is an open repository intended to fuel thinking about how to classify intelligent systems. If you have something you'd like to add or change, please submit a pull request and discuss.



## Class Null

The zeroth class is something which does not qualify as an intelligent system whatsoever. While this can cover any manner of programs – be they in software or manifested in processes emerging from hardware – I choose to focus on software for this example.

Programs that fall into class null have the following characteristics:

* They are only able to follow explicit, predetermined / deterministic logic.
* They follow simple rules – “if this then that” – with no capacity to ever learn anything.
* They have no capacity to make nuanced decisions, i.e. based on probability and/or data.
* They have no internal model of the world (this is related to learning).
* They do not have their own agency.
* This is by far the broadest class, as it covers the vast majority of our software systems today. Most of the world’s software is programmed for a specific task and does not really need to be a learning, decision-making system.

## Class I

Programs of this class have the following characteristics that are different from Class Null:

* They have the ability to make rudimentary decisions based on data, based on some trained model.
* They have the ability to learn from the outcomes of their decisions, and thus to update their core model.
* As such, their behavior may vary over time, as the data changes and their model changes.
* They are trained for a small number of narrow tasks, and do not have the capability to go outside those tasks.
* This covers things like fraud detection agents, decent spam detection, basic crawling bots (assuming they’re at least using decision trees or something similar). The decision could be a classification action – marking something as spam, for instance – or it could be deciding how well a website ranks in the universe of websites.

## Class II

Classes I and II are the most similar on this scale, because the distinction is subtle: a Class II program has all of the capabilities of a Class I, but may have more than one core model and more than one domain of action. For instance, the new Google Translate app has natural language and vision capabilities, with different models for each. These models are linked and ‘cooperate’ to translate the words in the field of view of your smartphone’s camera.

Class Is, by contrast, only have one area that they’re focused on, and make decisions only based on the model relevant to that domain.

## Class III

Programs of Class III have a two main distinctions from Class IIs:

* They have a basic memory mechanism, and the ability to learn from their history in those memories. This is more advanced than simply referring to data; these programs are actually building up heuristics from their own behavioral patterns.
They persist some form of internal model of the world. This assists in creation of memories and new heuristics in their repertoire.

## Class IV

This class starts to loosely resemble the intelligence level of insects. Class IVs not only have some kind of internal model of the world, but they gain an ability that was essential to the evolution of all complex life on earth: collaboration.

Thus, their characteristics are:

* They have the ability to collaborate with other agents/programs. That is, they have mechanisms with which to become aware of other agents, and a medium through which to communicate signals. (Think of ants and bees leaving chemical traces, for instance.)
* Like Class IIIs, they have an internal model of the world. However, a Class IV’s model is more closely linked to its goal structure, and not merely ad hoc / bound in one model. Its internal model may be distributed across several subsystems / mathematical models; representations of complex phenomena or experiences are encoded across various components in its cognitive architecture (vision systems, memory components, tactile systems, etc).
* They have the ability to perform rudimentary planning, driven by fairly rigid heuristics but with a little flexibility for learning.
* They have the ability to form basic concepts, schema, and prototypes.

While it is not a prerequisite that Class IVs have multiple distinct sensory modalities – optic, auditory, tactile, olfactory systems – that serves as a good example of the complexity level these programs start to achieve. In an AI setting, a program could have hundreds of different types of inputs, each with their own data type and respective subsystem for processing the input. The key distinction is that in Class IV programs, these subsystems have a high degree of connectivity, and thus generate more complex behavior.

Many robotics software systems could also be placed in Class IV.

## Class V

The capabilities of Class Vs begin to resemble more complex animal behavior, such as rats (but not as intelligent as many apes). The primary characteristics of note are:

* They have the ability to reflect on their own ‘thoughts’. In an AI program setting, this would mean it has the ability to optimize its own metaheuristics. In rats, for example, this is manifested as a basic form of metacognition.
* They have the ability to perform complex planning, especially in which they are able to simulate the world and themselves in it. Which leads to:
* They have the ability, to some degree, to simulate the world in their minds. That is, they can perturb their internal model of the world without actually taking action, and play out the results of hypothetical actions. They can imagine scenarios based on their knowledge of the world, which is intimately related to their memories (recall the memory capability from Class III).
* Related to their planning and internal simulation capabilities, they have the ability to set their own goals and take steps to achieve them. For instance, a rat may see two different pieces of food, decide that it likes the looks of one of them better than the other, set its goal to acquire the better-looking morsel, and subsequently plan a path to get it. The planning part relies on actions it knows it can do – how fast it can or run, how far can it jump – and the terrain ahead of it, as well as memories of how it may have conquered that type of terrain before. Thus goal-setting and planning rely heavily on memory and the internal model.
* They have a rudimentary awareness of their own agency in the environment. That is, when they are planning, they treat themselves as a factor in the environment they are simulating.

By this time, you have a program which is able to reflect, plan, collaborate with other agents, set goals, learn new behaviors and strategies for achieving its goals, and simulate hypothetical scenarios.

## Class VI

You’re a class VI. So am I. Almost every human being is a Class VI – ‘almost’ because, well, this designation is questionable when applied to some politicians.

Programs of this class will start to resemble human-level intelligence and capability, though not necessarily human-like in nature. While in humans a major difference is more complex emotions, this scale does not consider emotions directly.

Artificial intelligence has not yet reached this level, and there are varying predictions as to when it will. The good news is that the expert consensus is clear on the idea that it will happen, it’s just that no one knows exactly when.

Key components of Class VI agents/AIs are:

* Full self-awareness. The agent is fully aware of itself, its history, where the environment ends and it begins, and so on. This is related to consciousness, though Class VIs need not necessarily be conscious in a strict sense.
* They have the ability to plan in the extremely long term, thinking ahead in ways that more basic systems cannot. Specific timescales are relative to its natural domain: for a person, decades; for an AI program, perhaps, seconds or hours.
* Class VIs are able to invent new behaviors, processes, and even create other ‘programs’. In the case of a human, this is obviously an inventor creating a new way of solving a problem, or a software developer programming AIs somewhere in Brooklyn…

## Class VII

This is what might well be referred to as ‘superintelligence‘. While some AI experts are skeptical of whether or not this can be achieved, there does seem to be broad agreement that it is imminent. Nick Bostrom writes elegantly about the subject in his book of the same name.

While nobody knows exactly what this may look like, there are two major distinguishing factors which would almost certainly be present:

* They have the ability to systematically control their own evolution.
* They have the ability to recursively improve themselves, perhaps even at alarmingly minuscule timescales.
* Their first ability is perhaps their most profound. While humans do in some sense control our own fate, we do not yet have fine-grained control over the evolution of our brains and hence our cognitive abilities (though CRISPR may soon change that). With an artificial superintelligence, many limitations are removed. They can arbitrarily copy-paste themselves, ad finitum, and perform risk-free simulations of their new versions. They also will be essentially immortal, so long as their hardware persists and has a supply of energy.

With respect to the second ability, one might imagine an ASI (artificial superintelligence) making multiple clones of itself, each clone independently applying a self-improving strategy, and then each one in turn performing a set of benchmark tests to determine which one improved the most from the original copy. Whichever agent performed the best would become the new master copy, while the others would be taken out of the running.

This is a supercharged evolutionary algorithm, essentially. The tests would be agreed upon in advance, and even perhaps written as a cryptographically secure contract (blockchain-based or otherwise) to prevent cheating. In doing so, the agent would keep improving up to hardware limits or some theoretical asymptote.

The kind of scenario above is not at all unlikely in the near future.
