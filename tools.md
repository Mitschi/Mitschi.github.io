---
layout: page
title: Tools
permalink: /tools/
menurank: 1
---
<div style="text-align: justify;">
This page presents the tools that were developed during the research. I try to provide as much information as possible and to open source the projects on GitHub as time allows. If you have problems with the tools, please <a href="/">contact me</a>.
</div>

<h2>BuildMedic</h2>
<div style="text-align: justify;">BuildMedic is a tool for automatically repairing broken builds in projects that use Apache Maven as build tool. Currently, BuildMedic can repair dependency-related build breakage but will be extended to other types of build breakage. If you use  MLA, please cite the corresponding paper mentioned below.</div>
<div>
<a href="{{ site.url }}/paper/repairing.html">Paper</a>, 
other artifacts will be available soon...
</div>

<h2>BuildDiff</h2>
<!--<div>Download | GitHub</div> -->
<div style="text-align: justify;">BuildDiff is a differencing tool that extracts the changes that were performed between two Maven configuration files (pom.xml) and provides a taxonomy of build changes. It can be used to analyze build configuration of projects that use Maven as build tool. 
If you use BuildDiff, please cite the corresponding paper mentioned below.
</div>
<div>
<a href="{{ site.url }}/paper/extracting.html">Paper</a>, 
<a href="{{ site.url }}/preprints/differ-maven-differ-0.0.6.jar">Executeable</a>, 
<a href="{{ site.url }}/preprints/BuildChangeTaxonomy.pdf">Build Change Taxonomy</a>, 
<a href="{{ site.url }}/preprints/evaluationP1.xls">Evaluation 1</a>,
<a href="{{ site.url }}/preprints/evaluationP2.xls">Evaluation 2</a>
</div>

<h2>MavenLogAnalyzer (MLA)</h2>
<!--<div>Download | GitHub</div>-->
<div style="text-align: justify;">MavenLogAnalyzer (MLA) parses the log files that are produced during a build run with Maven. It extracts the build result, the time the build ran, and other build details from the log file. MLA can be used to enable the structured analysis of Maven builds.
If you use  MLA, please cite the corresponding paper mentioned below.
</div>
<div>
<a href="{{ site.url }}/paper/repairing.html">Paper</a>, 
other artifacts will be available soon...
</div>