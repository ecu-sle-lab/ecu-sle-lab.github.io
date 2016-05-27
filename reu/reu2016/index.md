---
layout: page
---

# REU Projects

For the Summer of 2016, these are the REU projects that I am offering. Interested students should contact me as soon as possible. You can review the presentations describing the research background and the projects by downloading them here:

* [Meta-Programming, Program Analysis, and Software Analytics](/presentations/REU-intro-2016.pdf)
* [Research in Meta-Programming, Program Analysis, and Software Analytics](/presentations/REU-research-2016.pdf)

### Project 1: Is JavaScript still Eval?

In a paper published in 2010, [An Analysis of the Dynamic Behavior of JavaScript Programs](http://doi.acm.org/10.1145/1806596.1806598), Richards and his co-authors used dynamic tracing to explore the behavior of JavaScript code used on top websites, explaining how the actual behavior of JavaScript either backed up common assumptions used in program analysis tools or violated these assumptions. In a paper published in 2011, [The Eval That Men Do - A Large-Scale Study of the Use of Eval in JavaScript Applications](http://dx.doi.org/10.1007/978-3-642-22655-7_4), they followed up on this with a study of how one specific feature, `eval`, is used in JavaScript.

A lot has changed in the last 6 years. In this project, you will recreate this experiment, but with modern websites. It may be that many of the same behaviors still exist, but it could also be the case that old problems have gone away (e.g., with `eval` being used in cases where it wasn't needed) and new problems have begun.

For this project you should be interested in JavaScript and willing to learn more about the language. You should also be open to learning a language that will be good for processing the data collected while running the experiment, such as Rascal, Python, or R.

### Project 2: Evolution of Open-Source Activity in the Research Triangle Park

A graduate student in our MS in Software Engineering program has been investigating open-source activity in the Research Triangle Park area of North Carolina. This research, which uses [GHTorrent](http://ghtorrent.org/) as a means of exploring GitHub, provides a snapshot in time of information such as the number of developers and organizations, programming languages used, and followers of projects.

For this project, we will expand this work to add a temporal component, exploring how open-source contributions in this area has changed over time. This should also allow similar studies to be performed for other geographic areas. This is interesting in itself, and also provides information that can be useful for other research aimed at assisting developers and copmanies participating in open-source projects.

### Project 3: Feature Usage in PHP

In earlier work published in the paper [An Empirical Study of PHP Feature Usage: A Static Analysis Perspective](http://www.cs.ecu.edu/hillsma/publications/php-feature-usage.pdf), we explored how language features are used in the PHP programming language by exploring a number of popular open-source systems. This was done using the [Rascal](http://www.rascal-mpl.org/) programming language and the [PHP AiR](https://github.com/cwi-swat/php-analysis) framework for PHP program analysis.

For this project, we would like to expand this work, looking both at additional systems, additional language features, and additional ways to categorize how these features are used. The purpose of this research is to provide a firm foundation for the development of program analysis tools for the PHP language.

### Project 4: Feature Evolution in PHP

An initial start of this work was published in the paper [Evolution of Dynamic Feature Usage in PHP](http://www.cs.ecu.edu/hillsma/publications/php-dynamic-evolution.pdf). In that paper, we looked at two systems, [WordPress](https://wordpress.org/) and [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki), exploring how the use of certain dynamic features changed over time. 

For this project, we would like to expand this work, looking at additional features and additional systems, and also exploring why some of these changes have taken place. The purpose of this work is to provide a firm foundation for the development of program analysis tools for the PHP language, here allowing tool developers to account for features that are being phased out and to prepare for features that are not often used but are becoming more popular.

### Project 5: Exploring Plugin API Usage with Formal Concept Analysis

[Formal concept analysis](https://en.wikipedia.org/wiki/Formal_concept_analysis) provides (at a high level) a method of extracting information about relationships between different entities in source code. For this project, we would like to use the support for formal concept analysis already included in [Rascal](http://www.rascal-mpl.org/) to explore the relationships between different [hooks](https://codex.wordpress.org/Plugin_API/Hooks) in the WordPress plugin API. This is follow-on from recent work we reported in the paper [Navigating the WordPress Plugin Landscape](http://www.cs.ecu.edu/hillsma/publications/icpc-plugins-2016.pdf) which just appeared at the [24th IEEE International Conference on Program Comprehension](http://www.program-comprehension.org/icpc16/).
