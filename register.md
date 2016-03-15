---
layout: page
---

## Camps
**[5th &amp; 6th Grade Camp](lower/)**  
Our lower camp is aimed at students just starting to peek their heads into robotics. We'll show them basic mechanical design and programming using easy to learn programs and robotics kits that are as simple to use as LEGOs. Find out [more](lower/).

**[7th &amp; 8th Grade Camp](lower/)**  
Our upper camp is aimed at students who want to start learning text-based programming and working in larger groups to create more complex, but awesome robots. Still good for beginners, we use more advanced robotics kits that enable campers to go beyond a basic robot.  Find out [more](upper/).

&nbsp;

## Dates
The weeks currently offered are:

{% for week in site.data.weeks %}
- {{ week.start_date }} - {{ week.end_date }} ({{ week.price }}){% endfor %}
