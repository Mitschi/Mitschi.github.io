---
layout: page
title:  "Improving Build Change Extraction with fine-grained hierarchical changes"
topiccategory: "Build Systems"
categories: buildsystems
preprint: "T3.pdf"
---
Description: <a href="{{ site.url }}/topicsdata/T3.pdf"><img style="height:18px; width=10px;" src="/assets/icon-pdf.png" /></a>
<h2>Context/Introduction</h2>
<div style="text-align: justify">Build systems are widely used in today’s software projects to automate integration and build processes. Similar to source code, build configuration need to be maintained to avoid outdated configurations, and build breakage as a consequence. Recent work indicates that neglected build maintenance is one of the most frequently occurring reasons why builds break. The context of this topic is situated in finding methods and developing tools that support the developers and release engineers in improving the quality of their build configuration.</div>
<br/>
<h2>Problem Description and Target</h2>
<div style="text-align: justify">Prior studies have shown that classifying the changes that are made between two commits can help in studying the evolution and hence, investigating the impact of certain changes on, for example, quality. Recently, a tool named “BuildDiff” that is able to extract changes from Maven build configuration files has been developed and used to study frequent changes. It has been found useful to understand the evolution of build configuration files, for example when the most build changes were performed. The goal of this topic is to improve the existing classification with a set of finer change types (e.g. going deeper into the build specification) and to add the hierarchical dependencies that may exists in certain change types.</div>
