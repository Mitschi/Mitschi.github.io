---
layout: post
title:  "Automatically Repairing Dependency-Related Build Breakage"
categories: publication
conference: SANER18
acceptancerate: "39/146 (27%)"
authors: "Christian Macho, Shane McIntosh, Martin Pinzger"
preprint: "AutomaticallyRepairingDependencyRelatedBuildBreakage.pdf"
dataandtools: "repairingdata.zip"
order: 4
---
<h2>Abstract</h2>
<div style="text-align:justify">Build systems are widely used in today's software projects to automate integration and build processes. Similar to source code, build specifications need to be maintained to avoid outdated configurations, and build breakage as a consequence. Recent work indicates that neglected build maintenance is one of the most frequently occurring reasons why open source and proprietary builds break.
In this paper, we propose BuildMedic, an approach to automatically repair Maven builds that break due to dependency-related issues. Based on a manual investigation of 37 broken Maven builds in 23 open source Java projects, we derive three repair strategies to automatically repair the build, namely Version Update, Delete Dependency, and Add Repository. We evaluate the three strategies on 84 additional broken builds from the 23 studied projects in order to demonstrate the applicability of our approach. The evaluation shows that BuildMedic can automatically repair 45 of these broken builds (54%). Furthermore, in 36% of the successfully repaired build breakages, BuildMedic outputs at least one repair candidate that is considered a correct repair. Moreover, 76% of them could be repaired with only a single dependency correction.</div>
<h2>Tools and Data</h2>
<div>
<a href="{{ site.url }}/preprints/AutomaticallyRepairingDependencyRelatedBuildBreakage.pdf" target="_blank">Preprint</a>, 
<a href="{{ site.url }}/preprints/repairingdata.zip" target="_blank">Replication Package</a>
</div>
<h2>Bibtex</h2>
@inproceedings{macho2018saner,
  Author = {Christian Macho and Shane McIntosh and Martin Pinzger},
  Title = {Automatically Repairing Dependency-Related Build Breakage},
  Year = {2018},
  Booktitle = {Proc. of the International Conference on Software Analysis, Evolution, and Reengineering (SANER)},
  Pages = {106–117}
}
