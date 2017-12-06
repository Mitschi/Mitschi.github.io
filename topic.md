---
layout: page
title: Topics
permalink: /topics/
menurank: 3
---
<p style="text-align: justify">We are always interested in current topics concerning Software Engineering. If you have an idea for your thesis that is within our research interests, write me an email suggesting your idea or drop by my office to discuss it.</p>
<p style="text-align: justify">We also offer predefined topics that can be adapted according to your interests. The following topics are currently offered (click for details):</p>

 <ul style="list-style-type: none;">
{% for item in site.topics %}
  <li>
  	<div>
  		<a href="{{ item.url }}">{{ item.title }}</a>
  		<span class="post-meta"><a href="{{ site.url }}/topicsdata/{{ item.preprint }}"><img style="height:18px; width=10px;" src="/assets/icon-pdf.png" /></a></span>
  	</div>
  </li>
{% endfor %}
  </ul>