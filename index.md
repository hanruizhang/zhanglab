---
title: Home
---

<div> 
    <img src="{{ '/images/octocat.jpg' | absolute_url }}" alt="github octocat" style="width:45%;" >
    <img src="{{ '/images/jekyll.png' | absolute_url }}" alt="jekyll icon" style="width:45%;" >
</div>


# The Zhang Laboratory

Macrophage biology and functional genomics in cardiometabolic diseases

						Cardiometabolic Genomics Program
						Division of Cardiology, Department of Medicine
						Columbia University Irving Medical Center



<div class="toc" markdown="1">


{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>
