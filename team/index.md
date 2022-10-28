---
title: Team
nav:
  order: 3
  tooltip: Lab memebers
---

# <i class="fas fa-users"></i>Team

I'm excited to have just started my lab at RIT and am looking for new students, especially on the bioinformatics side - there are always more ideas than hands to work on the projects! 

{%
  include link.html
  link="contact"
  text="Contact me if you are interested in joining the lab."
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}


{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer"
%} 
{:.center}

