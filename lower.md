---
layout: program-page
title: Curiosity (5th & 6th)
permalink: /lower/
show_front: true
header_image: /assets/wide/IMG_1340.jpg
---

## Overview
**Ages:** 10 – 12 years old  
**Dates:** July 5th – August 5th  

**Times:** 9:00am – 3:00pm (Drop-off starts at 8:30am, Pick-up ends at 3:30pm)  
**Location:** Canyon Crest Academy  
**Rates:** $450 – (See Below)  
**Includes:** Daily snacks and lunches, camp t-shirt, and a week of awesome fun.  

This summer, we’re proud to offer a week of fun where campers can come and build awesome robots, run around, and have fun. All week we’ll be using VEX IQ robot sets to build robot that complete complex challenges that teach campers mechanical and programming skills, while getting them excited about engineering and technology.

Not only will we get students going on build robots, they’ll also get to compete against each other by trying to score the most points in our end of the week competition. And every step of the way we’ll have counselors and staff alongside them to make sure they get the guidance they need to reach their goal.

## Week Information
The weeks currently offered are:

{% for week in site.data.weeks %}
- {{ week.start_date }} - {{ week.end_date }} ({{ week.price }}){% endfor %}

## Registration
Registration is currently not open. Here are some important dates you should know:

- **Priority Registration** for returning campers will begin on {{ site.priority_register_open_date_string }}.
- **General Registration** will open on {{ site.general_register_open_date_string }}.

You can sign up on our [interest form]({{ site.interest_form_url }}) to get notified when registration is open. Also check out our registration policies for information on payments, cancellations, etc.
