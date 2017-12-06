---
layout: page
title:  "Comparing the Evolution of Maven and Gradle Build Configurations"
topiccategory: "Build Systems"
categories: buildsystems
preprint: "T4.pdf"
---
Description: <a href="{{ site.url }}/topicsdata/T4.pdf"><img style="height:18px; width=10px;" src="/assets/icon-pdf.png" /></a>
<h2>Context/Introduction</h2>
<div style="text-align: justify">Build systems are widely used in today’s software projects to automate integration and build processes. Similar to source code, build configuration need to be maintained to avoid outdated configurations, and build breakage as a consequence. Recent work indicates that neglected build maintenance is one of the most frequently occurring reasons why builds break. The context of this topic is situated in finding methods and developing tools that support the developers and release engineers in improving the quality of their build configuration.</div>
<br/>
<h2>Problem Description and Target</h2>
<div style="text-align: justify">Gradle is a rapidly developing build tool and currently gaining popularity in the community. However, the recent work in research has mainly been focused on Apache  Ant and Apache Maven, mainly because of their dissemination. For example, studies on the evolution of build systems focused on those two tools, and an approach to extract build changes used a differencing algorithm that is tailored to extract the changes from Maven build files.  However, as Gradle is more and more used, research needs also to consider this tool in their studies. The target of this topic is to improve existing tools, such as BuildDiff and MavenLogAnalyzer (MLA), to support Gradle as well, and to study and compare their evolution.</div>
