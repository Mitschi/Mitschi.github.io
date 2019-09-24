---
layout: post
title:  "What kind of questions do developers ask on Stack Overflow? A comparison of automated approaches to classify posts into question categories"
categories: publication
conference: EMSE
acceptancerate: "-"
authors: "Stefanie Beyer, Christian Macho, Massimiliano Di Penta, Martin Pinzger"
preprint: "emse2019questionCategories.pdf"
order: 7
---
<h2>Abstract</h2>
<div style="text-align:justify">On question and answer sites, such as Stack Overflow (SO), developers use tags to label the content of a post and to support developers in question searching and browsing. However, these tags mainly refer to technological aspects instead of the purpose of the question. Tagging questions with their purpose can add a new dimension to the identification of discussed topics in posts on SO. In this paper, we aim at automating the classification of SO question posts into seven question categories. As a first step, we harmonized existing taxonomies of question categories and then, we manually classified 1,000 SO questions according to our new taxonomy. Additionally to the question category, we marked the phrases that indicate a question category for each of the posts. We then use this data set to automate the classification of posts using two approaches. For the first approach, we manually analyzed the phrases to find patterns. Based on regular expressions, we implemented a classifier, for each of the categories, that determines whether a post belongs to a category. These regular expressions are derived by analyzing patterns in the phrases. In the second approach, we use the curated data set to train classification models of supervised machine learning algorithms (Random Forest and Support Vector Machines). For the machine learning algorithms, we experimented with 1,312 different configurations regarding the preprocessing of the text and the representation of the input data. Then, we compared the performance of the regex approach with the performance of the best configuration that uses machine learning algorithms on a validation set of 110 posts. The results show that using the regular expression approach, we can classify posts into the correct question category with an average precision and recall of 0.90, and an MCC of 0.68. Additionally, we applied the regex approach on all questions of SO that deal with Android app development and investigated the co-occurrence of question categories in posts. We found that the categories API USAGE, CONCEPTUAL, and DISCREPANCY are the most frequently assigned question categories and that they also occur together frequently. Our approach can be used to support developers in browsing SO discussions or researchers in building recommender systems based on SO.</div>
<h2>Tools and Data</h2>
<div>
<a href="{{ site.url }}/preprints/emse2019questionCategories.pdf" target="_blank">Preprint</a>
</div>
<h2>Bibtex</h2>
@article{beyer2019kind,
  title={What kind of questions do developers ask on Stack Overflow? A comparison of automated approaches to classify posts into question categories},
  author={Beyer, Stefanie and Macho, Christian and Di Penta, Massimiliano and Pinzger, Martin},
  journal={Empirical Software Engineering},
  pages={1--44},
  year={2019},
  publisher={Springer}
}
