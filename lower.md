---
layout: program-page
title: Curiosity (5th & 6th)
permalink: /lower/
show_front: true
header_image: /assets/wide/IMG_2146.jpg
---

### Overview
**Ages:** 10 – 12 years old  
**Dates:** {{ site.date_range }}

**Times:** 9:00am – 3:00pm (Drop-off starts at 8:30am, Pick-up ends at 3:30pm)  
**Location:** Canyon Crest Academy  
{% if site.registration_open %}
**Rates:** $450 – [Register Now!]({{ site.lower_form_url }})  
{% else %}
**Rates:** $450 – [Interested?]({{ site.interest_form_url }})  
{% endif %}
**Includes:** Daily snacks and lunches, camp t-shirt, and a week of awesome fun.  

This summer, we’re proud to offer a week of fun where campers can come and build awesome robots, run around, and have fun. All week we’ll be using VEX IQ robot sets to build robot that complete complex challenges that teach campers mechanical and programming skills, while getting them excited about engineering and technology.

Not only will we get students going on build robots, they’ll also get to compete against each other by trying to score the most points in our end of the week competition. And every step of the way we’ll have counselors and staff alongside them to make sure they get the guidance they need to reach their goal.

### Week Information
The weeks currently offered are:

{% for week in site.data.weeks %}
- {{ week.start_date }} - {{ week.end_date }} {{ week.display_name }} ({{ week.price }}){% endfor %}

Two games/challenge sets will be available on alternating weeks. These games will be announced at the beginning of June.

### Registration
{% if site.registration_open %}
Registration is now open. Please use our [registration form]({{ site.lower_form_url }}) to get started.
{% else %}
The registration period has not yet begun. However, if you are interested in enrolling campers this summer, [let us know]({{ site.interest_form_url }}).
{% endif %}

Also check out our [registration policies](/camp/about/registration) for information on payments, cancellations, etc.

### Aftercare
Camper pickup is at 3:00p, but sometimes, your campers need to stay a bit later. We get it; that's why we have aftercare. Your campers can stay with us until 5:00 PM. [Learn more.](/camp/aftercare/)
