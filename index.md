---
layout: default
title: Home
nav_order: 1
description: "Grade 10 Physics at St. John Baptist De La Salle Catholic School."
permalink: /
---

<button class="btn js-toggle-dark-mode">Dark Mode</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Dark Mode';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Return to light mode';
  }
});
</script>


# Grade 10 Physics at St John Baptist De La Salle Catholic School
{: .fs-9 }

The following website contains notes, slides, videos and other resources we use in this course that I deem useful.
{: .fs-6 .fw-300 }

[This Week](#announcements){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Grade Viewer](https://gradeviewer.kebede.org){: .btn .fs-5 .mb-4 .mb-md-0 } [View Older Courses](https://sj.kebede.org){: .btn .fs-5 .mb-4 .mb-md-0 }

---

{: .new }
> **For questions about homeworks, research interests or anything in general, please email [aaron@sjbdcs.org](mailto:aaron@sjbdcs.org?subject="Question from physics.kebede.org") or text [@pysm3bot](https://t.me/pysm3bot) in addition to office hours at school.**

{: .warning }
> Cheating in assignments, homeworks, or any school work is prohibited. You are welcome to discuss, but cheating is punishable.

# Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}




#### Managed by:


<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>


#### Website Mirrors

Mirrors sites are sites that are identical to this site, but hosted on a different server. <br>


[Primary Site](//physics.kebede.org)
{: .label .label-yellow }
[Mirror 1](http://mirror.physics.kebede.org)
{: .label .label-yellow }
[Mirror 2](//sjphys.netlify.app)
{: .label .label-yellow }
