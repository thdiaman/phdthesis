---
layout: page
title: "Part III: Source Code Mining"
category: data
date: 2017-11-20 15:24:20
order: 3
---

### Chapter 5: Source Code Indexing for Component Reuse
This chapter refers to the challenge of indexing source code and proposes
the Code Search Engine AGORA. AGORA is offered as an open source tool.
The documentation page of AGORA, which is available
<a target="_blank" href="https://authecesofteng.github.io/agora/">here</a>,
includes links to all repositories of the tool as well as instructions for installing
and using it. In addition, an an online running version can be found
<a target="_blank" href="http://agora.ee.auth.gr">here</a>.

The index is populated using the list of the 3000 most starred Java projects of GitHub,
cleaned up by removing forked projects and invalid projects (e.g. without java code).
The list of projects is available
<a target="_blank" href="{{ site.baseurl }}/data/partthree/agora/projects.txt">here</a>.

The dataset used for our evaluation in a component reuse scenario, which includes the list
of queries that were performed at the service, is available
<a target="_blank" href="{{ site.baseurl }}/data/partthree/agora/dataset.zip">here</a>.


### Chapter 6: Mining Source Code for Component Reuse
This chapter includes the design of the Test-Driven Reuse system Mantissa.
Mantissa is a system that acceptes queries for class-level software components
and further assesses their functionality using tests. An online running version
of the tool can be found <a target="_blank" href="http://mantissa.ee.auth.gr">here</a>.

The example search scenario (case study) that is built using Mantissa is available
<a target="_blank" href="{{ site.baseurl }}/data/partthree/mantissa/casestudy.zip">here</a>.

In addition, the three datasets used for evaluating Mantissa against other tools in
a component reuse scenario are available
<a target="_blank" href="{{ site.baseurl }}/data/partthree/mantissa/datasets.zip">here</a>.


### Chapter 7: Mining Source Code for API Snippet Reuse
This chapter describes the design of CodeCatch, a system that receives queries in
natural language, and recommends useful snippets from multiple online sources.
CodeCatch further evaluates the readability of the retrieved snippets as well as
their preference/acceptance by the developer community.

An online running version of the tool, which also includes the queries used for
evaluation, can be found <a target="_blank" href="http://codecatch.ee.auth.gr/">here</a>.

Furthermore, the list of projects used to create our API calls index can be found
<a target="_blank" href="{{ site.baseurl }}/data/partthree/codecatch/projects.txt">here</a>.


### Chapter 8: Mining Queries for Snippet Reuse
This chapter describes a methodology for finding solutions in question-answering systems,
using the main elements of a question post, including its title, tags, body, and 
its source code snippets. Our methodology is applied on the official data dump of Stack
Overflow as of September 26, 2014, which is available
<a target="_blank" href="http://2015.msrconf.org/challenge_data/">here</a>.

