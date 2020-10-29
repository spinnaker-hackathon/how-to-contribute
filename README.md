# Roadmap: Build your career as a Spinnaker contributor

This document includes all the links featured in my Spinnaker Summit presentation, along with a summary of the content.

### The Spinnaker garden
- Open Source is like a garden. And Spinnaker is a huge garden in the early years of its life -- it offers opportunity,  possibility, and so much area for growth and a rich return. But we need YOU. 
- Just like a garden, the Spinnaker project requires constant input to grow and thrive. We need you to join us to grow, provide feedback on, maintain, and rise to leadership levels in the project. 

## Places to contribute
- Join [Spinnaker Slack](http://join.spinnaker.io), our hub of asynchronous project communication.
  - Learn and get feedback as you discover Spinnaker and begin contributing. 
  - If you have some experience as a Spinnaker user or operator, contribute by answering questions that come up when you know the answer or have some helpful context that may be.

### Spinnaker and extensions stack
- When contributing to Spinnaker repositories, you will use a [fork and pull request workflow](https://gist.github.com/Chaser324/ce0505fbed06b947d962) common to OSS projects
- [Spinnaker's code footprint](https://spinnaker.io/community/contributing/back-end-code/)
- Preferred backend languages: 
  - Kotlin, but using Java is also acceptable.
    - Used for Spinnaker services and [Plugins](https://spinnaker.io/guides/developer/plugin-creators/overview/). 
    - Learn more about plugins in this [workshop](https://youtu.be/K7Ihskerk84).
  - Groovy 
    - Please do not write new Groovy componenets and use Java or Kotlin instead.
    - If you are working on those components, know that transforming the code you touch into Java is very welcome.
  - Typescript and React in [Deck](https://github.com/spinnaker/deck), Spinnaker’s frontend. 
    - Beginner-friendly UI issues are in the [list of issues with that tag in GitHub](https://github.com/spinnaker/spinnaker/issues?q=is%3Aopen+is%3Aissue+label%3A%22beginner+friendly%22).
  - Go, in the [Spin CLI](https://github.com/spinnaker/spin) and some additional tooling.
    - [Kleat](https://github.com/spinnaker/kleat) for managing configuration files.
    - [Operator](https://github.com/armory/spinnaker-operator) for deploying and managing Spinnaker.
 
