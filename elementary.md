---
layout: program-page
title: Elementary (1st - 4th)
permalink: /elementary/
show_front: true
header_image: /assets/wide/elementary1.jpg

---

### Overview
**Ages:** 6 – 10 years old  
**Dates:** {{ site.date_range }}

**Times:** 9:00am – 3:00pm (Drop-off starts at 8:30am, Pick-up ends at 3:30pm)  
**Location:** Canyon Crest Academy  
{% if site.registration_open %}
**Rates:** $410 – [Register Now!]({{ site.elementary_form_url }})  
{% else %}**Rates:** $410 – [Interested? Get notified when we open.]({{ site.interest_form_url }})  {% endif %}
**Includes:** Daily snacks and lunches, camp t-shirt, and a week of awesome fun.  

This summer, we have an awesome new camp for our elementary students! Get started by building simple machines that come together to create an awesome robot that you can control through a joystick.   

All week, campers will be engaged in learning about science, technology, engineering, and mathematics using VEX IQ robot kits. During the week, we will build simple machines powered by motors. Then, students will bring those separate parts together to create a bigger robot that they can control via a joystick. We'll be building different robots on different days, so come and join us!

### Week Information
The weeks currently offered are:

{% for week in site.data.weeks-elementary %}
- {{ week.name }}: {{ week.start_date }} - {{ week.end_date }} ({{ week.price }}) {{ week.notes }}{% endfor %}

### Registration
{% if site.registration_open %} Registration is now open. Please use our [registration form]({{ site.elementary_form_url }}) to get started. {% else %} The registration period has not yet begun. However, if you are interested in enrolling campers this summer, [let us know]({{ site.interest_form_url }}) and we will alert you as soon as registration is open! {% endif %}

Also check out our registration policies for information on payments, cancellations, etc.

### Aftercare
Camper pickup is at 3:00p, but sometimes your campers need to stay a bit later. We get it; that's why we have aftercare. Your campers can stay with us until 5:00 PM. [Learn more.](/camp/aftercare/)
