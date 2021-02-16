# 1 // How should we define AI?

Application 1. Self-driving cars
Application 2. Content recommendation
Application 3. Image and video processing

No agreed-upon definitions of AI
joke: AI == “cool things that computers can’t do.”
: truth to this is that the definition shifts as hard things become easy in CS

Two characteristic properties of AI:
1. autonomy: The ability to perform tasks in complex environments without constant guidance by a user.
1. adaptivity: The ability to improve performance by learning from experience.

'learning', 'understanding','intelligence' are what Martin Minsky called "suitcase words": they come packed with numerous meanings

Don't refer to AI in the singular

# 2 // Related Fields

* Machine learning (ML): subfield of AI which is a subfield of CS. (But in some ways a subfield of stats.) : focuses on improvement of algorithmic performance in a task with more experience or data
* Deep learning: subfield of ML
* Data science: recent umbrella term including ML, stats, algorithms, data storage, web dev. Also requires practical undrstanding of the domain of application.
* Robotics: building & programming robots. Requires combination of various AI subfields (computer vision, speech recognition, NLP, info retrieval, reasoning under uncertainty, cognitive modeling, affective computing). (Robot: sensors + actuators)

# 3 // Philosophy of AI
Example questions:
* Does intelligent behavior imply or require the existence of a mind?
* To what extent is consciousness replicable as computation?

Turing test: computer passes test if human interrogator cannot tell which of the two individuals he's talking to is the computer and which is the human.
  criticism: it may actually measure whether the computer behaves like a human more than whether it is intelligent

Chinese Room thought experiment: take in notes, use giant dictionary to translate it, but doesn't actually understand Chinese. A computer is very similar: input-output that mimics intelligent behavior, but no *intelligence* and no *mind* or *consciousness*. Therefore, AIs are not actually intelligent.

* Narrow AI: AI that handles one task
* General AI / Artificial General Intelligence (AGI): a machine that can handle any intellecutal task

* Strong AI: a “mind” that is genuinely intelligent and self-conscious
* Weak AI: systems that exhibit intelligent behaviors despite being “mere“ computers


#### Writing assignment
##### Prompt
Which definition of AI do you like best? How would you define AI?

Let's first scrutinize the following definitions that have been proposed earlier:

"cool things that computers can't do"
machines imitating intelligent human behavior
autonomous and adaptive systems
Your task:

Do you think these are good definitions? Consider each of them in turn and try to come up with things that they get wrong - either things that you think should be counted as AI but aren't according to the definition, or vice versa. Explain your answers by a few sentences per item (so just saying that all the definitions look good or bad isn't enough).
Also come up with your own, improved definition that solves some of the problems that you have identified with the above candidates. Explain with a few sentences how your definition may be better than the above ones.

##### Answer
> "cool things that computers can't do"

Charitably interpreted, this should be taken to mean something like: 'a system of algorithms is artificially intelligent when it applies algorithms to solve problems that are not at present easy to automate through straightforward computational means'. A trouble with this is that what counts as AI shifts as technologies improve and straightforward computation can accomplish more things. This would make AI unlike any other form of intelligence: all other forms of intelligence remain intelligent regardless of the state of contemporary technology. An application that should be included in AI but might not be under this definition is the example of a spam filter. It is so common and quotidian that it might count as straightforward computational means. However, it is adjusting behavior on the basis of data—learning, in that sense. So, intuitively, it should count as AI, which is problematic for this definition.

> machines imitating intelligent human behavior

Sometimes human behavior is not very intelligent. Notoriously, we have numerous cognitive biases such as those uncovered by the famous research of Daniel Kahneman. For example, humans are susceptible to the "anchoring effect", wherein seeing a number before making a numeric guess influences what we guess. A machine that mimicked this would be less intelligent, not more so.

> autonomous and adaptive systems

This is the best of the three that we have to work with, although it is a slogan rather than a definition. A definition would be something like 'a system of algorithms is artificially intelligent when it performs tasks autonomously (without constant guidance by a traditional intelligence) and adaptively (improving on the basis of novel experience or data)'. A worry about this definition is that adaptiveness may not be essential. Consider a bot that very adeptly sorts bottles into glass vs. plastic vs. metal. If it performs nearly perfectly at this fairly complex task, then perhaps it should count as an AI even if it does not learn—or at least if it used to learn but no longer learns because there is nothing left to learn in the domain.

My definition:
* __
