---
layout: post
title:  "Automatically Classifying Posts into Question Categories on Stack Overflow"
categories: publication
conference: ICPC18
acceptancerate: "26/69 (38%)"
authors: "Stefanie Beyer, Christian Macho, Massimiliano Di Penta, and Martin Pinzger"
preprint: "AutomaticallyClassifyingPosts.pdf"
order: 5
---
<h2>Abstract</h2>
<div style="text-align:justify">Software developers frequently solve development issues with the help of question and answer web forums, such as Stack Overflow (SO). While tags exist to support question searching and browsing, they are more related to technological aspects than to the question purposes. Tagging questions with their purpose can add a new dimension to the investigation of topics discussed in posts on SO. In this paper, we aim to automate such a classification of SO posts into seven question categories. As a first step, we have manually created a curated data set of 500 SO posts, classified into the seven categories. Using this data set, we apply machine learning algorithms (Random Forest and Support Vector Machines) to build a classification model for SO questions. We then experiment with 82 different configurations regarding the preprocessing of the text and representation of the input data. The results of the best performing models show that our models can classify posts into the correct question category with an average precision and recall of 0.88 and 0.87 when using Random Forest and the phrases indicating a question category as input data for the training. The obtained model can be used to aid developers in browsing SO discussions or researchers in building recommenders based on SO.</div>
<h2>Tools and Data</h2>
<div>
<a href="{{ site.url }}/preprints/AutomaticallyClassifyingPosts.pdf" target="_blank">Preprint</a>
</div>
<h2>Bibtex</h2>
@inproceedings{beyer2018automaticallyClassifying,
  Author = {Stefanie Beyer and Christian Macho and Massimiliano Di Penta and Martin Pinzger},
  Title = {{Automatically Classifying Posts into Question Categories on Stack Overflow}},
  Year = {2018},
  Booktitle = {Proc. of the International Conference on Program Comprehension (ICPC)},
  Pages = {To appear}
}
