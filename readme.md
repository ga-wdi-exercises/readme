# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Contribution Guidelines

This document is meant to be an all-inclusive contribution guideline to ga-wdi-lessons and ga-wdi-exercises.

- [Getting Started](#getting-started)
- [Use Cases](#use-cases)
- [Creating GitHub Repositories](#creating-repos)
- [Types of Contribution](#types-contributions)


---
<a name="getting-started"></a>
## Getting Started

If you're not yet a member of either of these organizations on github:

- https://github.com/ga-wdi-exercises/
- https://github.com/ga-wdi-lessons/

*You can auto-add yourself as a member by logging in here: http://invite-to-github.wdidc.org/ with a General Assembly email address*

---

<a name="use-cases"></a>
## Use Cases

The use cases for contributions may vary across markets, so it's good to be aware of what you might see in the two orgs. For example you may see resources contributed that fit any of the following scenarios:

1) A lesson that needs work and additional components.
    * In this case, instructors should file an issue on the repo and tag resources as **help-wanted**
    * [agile, help-wanted]

2) Share resources that are outside of the core baseline curriculum
    * In this case, instructors should tag resource as **flex**
    * [php, flex]

3) Share a great resource that's been vetted and tested in classes by your market
    * In this case, instructors should tag resources with just associated topics
    * [agile]



<!-- MarkdownTOC -->

<a name="creating-repos"></a>
## Creating GitHub Repositories

You can create as many repos as you want! We've been doing one repo per lesson and one per exercise with great success. We recommend using a naming convention like language-concept-prerequisite, like js-ajax-jquery-first. Each repository can be easily searched by tags with RepoTagger.

Check the following links for an example:

- http://repotagger.github.io/?name=ga-wdi-exercises
- http://repotagger.github.io/?name=ga-wdi-lessons

You can tag a repo by adding a **comma-separated list** of tags in the repository's description, like this: [tag-one, tag-two, tag-three]

When created, all GitHub repositories should be named using all lowercase letters, except for a course acronym or the letters GA.  The repository title should also use dashes - not underscores - and follow the conventions below:

- For materials, like https://github.com/ga-wdi-lessons/api-intro: [topic/title]-type of resource or api-intro

### Editing existing Resources

You're welcome to make changes to existing lesson plans! Please just make a pull request and the original creator can merge it in.

If you're going to modify the lesson plan heavily (maybe because the prerequisites have changed), please just create a new repository!


<a name="types-contributions"></a>
## Types of Contribution

**Resources should be labeled either labs or lessons**. Lessons can include an introduction to topic, guided Practice (codealongs) and independent Practice (labs, exercises, homeworks). Labs can be interchangeable for exercises and homeworks, but please label them as labs to keep resources consistent.

At a minimum lessons should include:

- Topic and Title
- Timing
- Creator
- Market
- Learning Objectives
- An Outline of Lesson Components (nice to have)

> Check out the [lesson template](lesson-template.md) to see how these should be formatted!

At a minimum labs should include:

- Topic and Title
- Timing
- Creator
- Market
- Goals
- Requirements

> Check out the [lab template](lab-template.md) to see how these should be formatted!
