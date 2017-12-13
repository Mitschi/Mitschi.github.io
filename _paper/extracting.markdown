---
layout: post
title:  "Extracting Build Changes with BuildDiff"
categories: publication
conference: MSR17
acceptancerate: "37/121 (31%)"
authors: "Christian Macho, Shane McIntosh, Martin Pinzger"
preprint: "ExtractingBuildChangesWithBuildDiff.pdf"
---
<h2>Abstract</h2>
<div style="text-align:justify">Build systems are an essential part of modern software engineering projects. As software projects change continuously, it is crucial to understand how the build system changes because neglecting its maintenance can lead to expensive build breakage. Recent studies have investigated the (co-)evolution of build configurations and reasons for build breakage, but they did this only on a coarse grained level. In this paper, we present BuildDiff, an approach to extract detailed build changes from MAVEN build files and classify them into 95 change types. In a manual evaluation of 400 build changing commits, we show that BuildDiff can extract and classify build changes with an average precision and recall of 0.96 and 0.98, respectively. We then present two studies using the build changes extracted from 30 open source Java projects to study the frequency and time of build changes. The results show that the top 10 most frequent change types account for 73% of the build changes. Among them, changes to version numbers and changes to dependencies of the projects occur most frequently. Furthermore, our results show that build changes occur frequently around releases. With these results, we provide the basis for further research, such as for analyzing the (co-)evolution of build files with other artifacts or improving effort estimation approaches. Furthermore, our detailed change information enables improvements of refactoring approaches for build configurations and improvements of models to identify error-prone build files.</div>
<h2>Tools and Data</h2>
<div>
<a href="{{ site.url }}/preprints/ExtractingBuildChangesWithBuildDiff.pdf" target="_blank">Preprint</a>, 
<a href="{{ site.url }}/preprints/differ-maven-differ-0.0.6.jar">Executeable</a>, 
<a href="{{ site.url }}/preprints/BuildChangeTaxonomy.pdf">Build Change Taxonomy</a>, 
<a href="{{ site.url }}/preprints/evaluationP1.xls">Evaluation 1</a>,
<a href="{{ site.url }}/preprints/evaluationP2.xls">Evaluation 2</a>
</div>
<h2>Bibtex</h2>
@inproceedings{macho2017msr,
  Author = {Christian Macho and Shane McIntosh and Martin Pinzger},
  Title = {{Extracting Build Changes with BuildDiff}},
  Year = {2017},
  Booktitle = {Proc. of the International Conference on Mining Software Repositories (MSR)},
  Pages = {368–378}
}
