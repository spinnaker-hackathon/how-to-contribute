# Roadmap: Build your career as a Spinnaker contributor

This document includes all the links featured in my Spinnaker Summit presentation, along with a summary of the content.

### The Spinnaker garden
- Open Source is like a garden. And Spinnaker is a huge garden in the early years of its life -- it offers opportunity,  possibility, and so much area for growth and a rich return. But we need YOU. 
- Just like a garden, the Spinnaker project requires constant input to grow and thrive. We need you to join us to grow, provide feedback on, maintain, and rise to leadership levels in the project. 

## Places to contribute
- Join [Spinnaker Slack](http://join.spinnaker.io), our hub of asynchronous project communication.
  - Learn and get feedback as you discover Spinnaker and begin contributing. 
  - If you have some experience as a Spinnaker user or operator, contribute by answering questions that come up when you know the answer or have some helpful context that may be.
- The Spinnaker.io [contributing page](https://spinnaker.io/community/contributing/) is a work in progress, and pull requests are welcome.

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

### Development environments
- You’ll need a development environment to develop and test technical Spinnaker contributions, and setting one up can be a challenge.
- There are several ways to install Spinnaker:
  - Classic method - [clone and install each Spinnaker service locally](https://spinnaker.io/guides/developer/dev-env/getting-set-up/) using the Halyard installation and management tool. 
    - Viable method but requires a lot of local resources (32 GB of RAM minimum recommended) and can be quite challenging. 
  - Install and manage Spinnaker’s microservices in Kubernetes, in your cloud provider or private cloud of choice. 
    - [Guide for AWS EKS deployment](https://spinnaker.io/community/gardening/spin-contrib/).
  - Minnaker, a Spinnaker instance that runs in a local or remote Linux VM, using K3S under the hood. 
    - Current[instructions on GitHub].(https://github.com/armory/minnaker) are more current.
    - [Video instruction guide](https://github.com/armory/minnaker) from April 2020.
    
We are working on developing more standards and easier methods for getting fully set up to develop against Spinnaker! Please share your feedback on these methods or your own process in the [#gardening-general](https://spinnakerteam.slack.com/archives/CV4A90DPF) or [#dev-toolkit](https://spinnakerteam.slack.com/archives/C011LUJ0UQJ).

### Contribution types
If you are looking for ways to contribute, here are some. Reach out to me (@dnilasor) or in the [#cx](https://spinnakerteam.slack.com/archives/C01BL8MCLA2) channel on Spinnaker Slack for help following up on opportunities, generating content ideas, and getting published

- [Spinnaker Community Blog](https://blog.spinnaker.io/) - anyone can be published here!
  - Make sure you have a Medium account for posting it. 
    - What to blog about? A few ideas:
      - Share your takeaways from Spinnaker Summit or Spinnkaer.Live talks on [YouTube](https://www.youtube.com/channel/UCcxQbw8kT1-FRhFhO2QCetg/). 
      - How and why do you use Spinnaker with Jenkins, or Kubernetes?
- Spinnaker tutorials or videos
  - Special need for short training videos that focus on one specific task or workflow in Spinnaker (beginner user tasks welcome!) that we can string together into training playlists.  
- Apply to become a [CDF Ambassador](https://cd.foundation/ambassador-program-overview-application/community-ambassador-cohort20/) and host meetups, join events, and represent Spinnaker.
- Add your testimonial to Spinnaker.io's [Success Stories](https://spinnaker.io/success-stories/)page by filling out the linked form. 
- Create new content for the [guides area](https://spinnaker.io/guides/) on Spinnaker.io.
