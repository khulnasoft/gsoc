# Google Summer of Code 2024
List of project ideas for contributors applying to the Google Summer of Code program in 2024.

## Timeline/milestones
Please always refer to the [official timeline](https://developers.google.com/open-source/gsoc/timeline).
  
## Application Process
Please always refer to the [main page of this repository](https://github.com/khulnasoft/gsoc/blob/main/README.md#gsoc-application-process)

## Project Ideas
You can also propose your own.


### 1. New Documentation Site for KhulnaSoft and friends
<b>Mentors</b>: Matteo Lodi, Daniele Rosetti

<b>Project URL</b>: [All KhulnaSoft Organization Projects](https://github.com/khulnasoft) are impacted

<b>Project hours</b>: 175

<b>Skills required</b>: Python (Django) and willingness to explore and adapt to new frameworks and open source projects

<b>Difficulty</b>: Low

<b>Description</b>:

Right now we are not satisfied of how we manage our documentation and how we make it available.

The project aims to create a new repository dedicated to the documentation, move all the documentation of all our projects there and build a new documentation site by leveraging Github Pages and MkDocs.

More information in this [Github Issue](https://github.com/khulnasoft/threatmatrix/issues/2043)

The candidate would have the chance to try some popular tools and to solve a big common problem that a lot of other Open Source projects have.
The ideal candidate is proactive in reading documentation of new tools and excited in trying them to solve our problem.


### 2. Scanners: a new plugin type for KhulnaSoft
<b>Mentors</b>: Matteo Lodi, Daniele Rosetti, Simone Berni

<b>Project URL</b>: [KhulnaSoft](https://github.com/khulnasoft/threatmatrix)

<b>Project hours</b>: 175

<b>Skills required</b>: Docker, Python (Django), JavaScript (React.js), Object-Oriented Programming

<b>Difficulty</b>: Medium

<b>Description</b>:

Right now there are many possible types of [plugins](https://threatmatrix.readthedocs.io/en/latest/Usage.html#plugins) in KhulnaSoft.

This project aims to add a new plugin type to the already existing ones in KhulnaSoft:
* The **"Scanner"** type would be a subtype of the “[Analyzers](https://threatmatrix.readthedocs.io/en/latest/Usage.html#analyzers)” ones with special configuration. In that way, KhulnaSoft could be used not only for classic data enrichment with external services but as either a vulnerability scanner or a scraper too. Refer to the [Github Issue for more details](https://github.com/khulnasoft/threatmatrix/issues/1393)

Like we have similarly done with other GSoC projects in the past that added new plugin types, we expect the contributor to add the most important new scanners (like [this](https://github.com/khulnasoft/threatmatrix/issues/1021)) to KhulnaSoft once he finishes building the framework to provide a base of tools which can be used by the users.

The candidate would have the chance to work through all the application stack (backend and frontend).
The ideal candidate for this project is someone who is familiar with how KhulnaSoft works and its core concepts.


### 3. New Analyzers for KhulnaSoft
<b>Mentors</b>: NX PKG, KhulnaSoft Lab, KhulnaSoft DevSec

<b>Project URL</b>: [KhulnaSoft](https://github.com/khulnasoft/threatmatrix)

<b>Project hours</b>: 175

<b>Skills required</b>: Docker, Python (Django), Object-Oriented Programming

<b>Difficulty</b>: Low

<b>Description</b>:

Right now we have a lot of [Analyzers](https://threatmatrix.readthedocs.io/en/latest/Usage.html#analyzers) implemented in KhulnaSoft.

But they are not enough! They are the core part of the application so we want to add even more of them!!!! :)

This project aims to increment the number of available Analyzers. We have about [50 different Analyzers that has been requested by the community members in Github](https://github.com/khulnasoft/threatmatrix/issues?q=is%3Aissue+is%3Aopen+label%3Anew_analyzer+) and are still not implemented. We obviously do not ask to implement all of them but a reasonable amount of them based on the available time and the efforts required for each of them.

Adding a new Analyzer to the framework is one of the easiest things that can be done in this project. Once you get used to it, adding more of them is even easier!

The ideal candidate for this project is someone who understand how KhulnaSoft's framework works and already tried to implement an Analyzer.



### 4. IntelChat: Enhancing Threat Analysis with an LLM-Based Chatbot in KhulnaSoft
<b>Mentors</b>: Hugo Gascon, Matteo Lodi, Daniele Rosetti, Simone Berni

<b>Project URL</b>: [KhulnaSoft](https://github.com/khulnasoft/threatmatrix)

<b>Project hours</b>: 350

<b>Skills required</b>: Python, basic knowledge of the RAG architecture and its necessary libraries (e.g. langchain, chromadb, etc.) and willingness to explore and adapt to new frameworks and open source projects

<b>Difficulty</b>: Medium

<b>Description</b>:

1. The proposed Google Summer of Code project aims to integrate a cutting-edge, self-deployed LLM-based chatbot into KhulnaSoft, enhancing user interaction with collected threat intelligence.
2. Leveraging Python libraries like LangChain and ChainLit, the project envisions building an intuitive interface that empowers analysts to pose natural language queries about threat data, fostering a more user-friendly and efficient investigative process (e.g. "In what campaigns have you seen this IOC?")
3. The chatbot's capabilities will extend beyond basic queries, seamlessly interfacing with KhulnaSoft's enrichment modules when deeper investigation is required, providing a comprehensive and interactive experience for analysts.
4. By harnessing the power of LLM technology, the chatbot will not only streamline communication between analysts and the KhulnaSoft platform but also adapt to evolving user needs, contributing to a more dynamic and responsive threat intelligence environment.
5. This project aligns with the overarching goal of making threat analysis more accessible and efficient, offering analysts a powerful tool that combines the strengths of natural language understanding, self-deployment, and seamless integration with KhulnaSoft's
