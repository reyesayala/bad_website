---
layout: page
permalink: /publications/
title: publications
style: apa
description: publications by categories in reversed chronological order.
nav: true
---



Journal Articles
--------------------

<div class="publications">

{% bibliography -f papers --query @['@article']%}

</div>

Conference Proceedings and Posters
-------
<div class ="publications">
{% bibliography -f papers --query @['@lecture']%}

</div>

Book Chapters and Edited Volumes
------------------------
<div class ="publications">
{% bibliography -f papers --query @['@incollection']%}

</div>

Technical Reports and other publications
------------------------
<div class ="publications">
{% bibliography -f papers --query @['@techreport' || '@thesis']%}

</div>
