---
layout: post
title:  "The Nature of Build Changes - An Empirical Study of Maven-based Build Systems"
categories: publication
conference: EMSE (to appear)
acceptancerate: "-"
authors: "Christian Macho, Stefanie Beyer, Shane McIntosh, Martin Pinzger"
order: 8
---
<h2>Abstract</h2>
<div style="text-align:justify">Build systems are an essential part of modern software projects. As software projects change continuously, it is crucial to understand how the build system changes be- cause neglecting its maintenance can, at best, lead to expensive build breakage, or at worst, introduce user-reported defects due to incorrectly compiled, linked, packaged, or deployed official releases. Recent studies have investigated the (co-)evolution of build configurations and reasons for build breakage; however, the prior analysis focused on a coarse-grained outcome (i.e., either build changing or not). In this paper, we present BUILDDIFF, an approach to extract detailed build changes from MAVEN build files and classify them into 143 change types. In a manual evaluation of 400 build-changing commits, we show that BUILDDIFF can extract and classify build changes with average precision, recall, and f1-scores of 0.97, 0.98, and 0.97, respectively. We then present two studies using the build changes extracted from 144 open source Java projects to study the frequency and time of build changes. The results show that the top-10 most frequent change types account for 51% of the build changes. Among them, changes to version numbers and changes to dependencies of the projects occur most frequently. We also observe frequently co-occurring changes, such as changes to the source code manage- ment definitions, and corresponding changes to the dependency management system and the dependency declaration. Furthermore, our results show that build changes frequently occur around release days. In particular, critical changes, such as updates to plugin configuration parts and dependency insertions, are performed before a release day. The contributions of this paper lay in the foundation for future research, such as for analyzing the (co-)evolution of build files with other artifacts, improving effort estimation approaches by incorporating necessary modifications to the build system specification, or automatic repair approaches for configuration code. Furthermore, our detailed change in-formation enables improvements of refactoring approaches for build configurations and im- provements of prediction models to identify error-prone build files.</div>
<!-- 
<h2>Tools and Data</h2>
<div>
<a href="{{ site.url }}/preprints/ExtractingBuildChangesWithBuildDiff.pdf" target="_blank">Preprint</a>, 
<a href="{{ site.url }}/preprints/differ-maven-differ-0.0.6.jar" target="_blank">Executeable</a>, 
<a href="{{ site.url }}/preprints/BuildChangeTaxonomy.pdf" target="_blank">Build Change Taxonomy</a>, 
<a href="{{ site.url }}/preprints/evaluationP1.xls" target="_blank">Evaluation 1</a>,
<a href="{{ site.url }}/preprints/evaluationP2.xls" target="_blank">Evaluation 2</a>

</div>
 -->
<h2>Bibtex</h2>
@inproceedings{macho2021emse,
  Author = {Christian Macho and Stefanie Beyer and Shane McIntosh and Martin Pinzger},
  Title = {{The Nature of Build Changes - An Empirical Study of Maven-based Build Systems}},
  Year = {2021},
  Booktitle = {Springer Empirical Software Engineering},
  Pages = {to appear}
}
