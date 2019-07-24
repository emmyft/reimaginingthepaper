# Reimagining the paper
A reproducibility discussion

# What is this?
This is the framework of a workshop prepared for a Birds of a Feather session at BOSC 2019. Hopefully it will improved upon and become a reference framework for facilitating discussions for the following purposes...

Current duration is ~ 1 hour.

# Aims
* Identify pain points and user needs in reproduction workflows (in life sciences, esp in bioinformatics), both traditional (from a published paper) and current (e.g. [Binder](mybinder.org), the [Reproducible Document Stack](www.elifesci.org/reprodoc))
* Encourage a deeper, more philosophical discussions around research communication, to identify technological means to encourage interrogation, reuse and incorporation beyond re-execution

# Resources
*[Slides v1](https://bit.ly/bosc19-bof-slides)
*[Accompanying sheets (for researcher stories + rebooting reproducibility discussions)(https://bit.ly/bosc19-bof-sheets)

# Content
## Introduction - what is reproducibility, and why is it important?
* Time: 5 mins
* Lay out definition of reproducibility: same code, same data
* Show of hands: How many people have tried to reproduce other people’s results
* Amongst the raised hands: 
   * Why did you want to reproduce other people’s result? What was the situation?
   * Did you succeed?

## Researcher stories
* Time: 15-20 mins
* If you have failed to reproduce a piece of result: what did you think was the problem? 
   * Method description? Incomprehensiveness, typos
   * Lack of data?
   * Infrastructure?
* If participants have stories to share, we can use those– we can also add them to the existing stack (see slides). These complex user stories are crucial to the development of any reproducibility approaches. 
* Points to discuss
   * Why is the researcher in the story struggling?
   * How could we help them?
* Potential conclusions (or none at all!)
   * The current method section is insufficient for reproduction, even if libraries used and parameters were well specified, often we don’t have full descriptions of library dependencies, system parameters, etc
   * Having code as part of the narration would ease reproduction
   
## Open reproducible approaches
* Time: 10 mins
* Quick intro to 
   * Docker, containers and images
   * Binder: github repo -> docker
   * RDS
* If you’ve heard of them, why would use/not use them? 
   * Steep learning curve
   * Time consuming, too much effort
   * Docker images are too big
   * My code is ugly
* These are also user feedback that we need to collect
* Does the initial effort/steep learning curve/things that they worry about outweigh the benefits of using these approaches? If yes, how can we lower this barrier of entry?
   * A "curriculum" could be helpful? Steps: Share code + data -> Annotate code / use notebooks -> share containers
   * Point to relevant resources like the Turing Way

## Rebooting reproducibility
* Time: 10-15 mins
* Group brainstorm: how to make communicating reproducible research easier for
  * Producers (i.e. researchers who published the code/container/paper)
  * Consumers (i.e. researchers who want to reuse/reproduce published results)
* A template Sheet of how this could be done.

## Re-execution to reuse
* Time: 10-15 mins
* Format: open discussion
* Going back to the beginning: Why do we want to reproduce? Do we just want to know that it’s reproducible? 
* Analogy: Newspaper - live streaming - seeing it with your own eyes
* Building a house: we want to make sure each brick is solid and placed OK, but that’s not our ultimate goal, our goal is to stack bricks on top of each other so we can build a house. 
* How do we get people to reuse and incorporate other people’s work?
* Incentivise reuse, not novelty
* Make it really easy
* ???


# Contributing
Please add yourselves!

(Name / Affiliation / Twitter)
* Emmy Tsang / eLife / @emmy_ft

