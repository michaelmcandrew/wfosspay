# What free and open source software project are you?

*A personality quiz to explore sustainability in free and open source software projects*

* tell the world about your  project
* find and learn from projects similar to yours
* understand sustainability in free and open source
* choose a sustainability strategy for your project

# Why?

A great diversity of projects exist under the banner of free and open source software. But when we talk about the group as a whole, it is easy to gloss over this diversity, and ask questions like: 

> What is the best way for free and open source software projects to sustain themselves?

The problem with this question is that what works for one project might not work for another. A better question to ask is probably:

> How should our free and open source software project sustain itself?

One approach to answering this question is to find *similar* open source projects, and see what they are doing - learn from their successes and their mistakes.

Of course, this approach assumes that open source projects with a lot in common will benefit from similar approaches to sustainability. If we accept this assumption, how can we find similar projects amongst the vast and uncharted seas of free and open source?

# How?

One approach would be to go to a conference with lots of free and open source software projects interested in talking about sustainability, and talk to as many people as you can.

Another approach is to:

1. Come up with a set of questions and answers that allows people build up a picture of the diversity of free and open source projects
2. Provide an simple method for people from projects to answer the questions
3. Create a tool to analyse the similarities (maybe using some machine learning?) and visualise them in some pleasing form
4. Get some pilot data in
5. Iterate 1 to 3 based on feedback to ensure utility, usability, etc.
6. Publicise more widely and collect more data

# The questions

Here's a rough list of topics / questions to ask. Please submit issues / PRs with more questions.
 
* Our software is licensed under [pick one or more licenses]
* We were founded in [year]
* The project used to be propietary
* We have a BDFL / We used to have a BDFL
* The project started life in a corperation who then decided to release it as open source
* We are hosted on github
* We are an application / library / operating system
* Our end users are also our contributors
* It is easy to get commit access
* People need to sign a contributor license agreement
* We have a paid core team
* By far our biggest contributor of code comes from people within a single corporation
* Our contributions come from many different corporations
* There is a community of service providers around the project that make money from the project
* We get a lot of contributions from hobbiests
* There are [N] people with push access
* The project is aimed at other developers who want to build things / The project is aimed at end users
* We are a general use project / We target a specific sector, e.g. medical, education, finance, non profit
* We are  application, a library, an OS

It might make sense to create a high level categorisation of these questions which can be used as a a filter when looking for similar projects, e.g. I want to see projects that are similar in terms of legal structure, size, audience, etc.

# Visualisation

 A few examples of methods and tools to use to visualise the results.

 * [visualizing high-dimensional space](https://www.youtube.com/watch?v=wvsE8jm1GzE)
 * [clustering by characteristics](https://bl.ocks.org/SpaceActuary/d6b5ca8e5fb17842d652d0de21e88a05)
 * the [unconference spectrogram method](http://unconference.net/unconference-methods-spectrogram/) (just for inspiration)

# Technical

Some tools that might be useful for autogenerating a survey from a json definition.

* https://github.com/mozilla-services/react-jsonschema-form

# Feedback

Let me know what you think in the issues.
