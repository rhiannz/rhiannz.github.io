---
layout: archive
title: "Contact"
permalink: /contact/
author_profile: true
---

{% include base_path %}

<hr/>

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSf2rcIOe5JCeeVmf0dyA5T5paxStMnz-KR8zEhDdn7kQveIUA/formResponse?usp=pp_url" target="hidden_iframe" onsubmit="setTimeout(function(){window.location.reload();},10);"> 
  <input type="text" name="entry.1617483516" placeholder="Your name" id="entry.1617483516" style="font-size:15pt;height:40px">
  &nbsp;<br><br> 
  <input type="text" name="entry.1417233657" placeholder="Your email" id="entry.1417233657" style="font-size:15pt;height:40px">
  &nbsp;<br><br>
  <textarea name="entry.1487389352" placeholder="Type your message here" id="entry.1487389352" rows="12" style="font-size:15pt"></textarea>
  <input type="submit" value="Submit" style="font-size: 15pt; color: white; background-color: cornflowerblue; border: 4pt solid cornflowerblue">
</form> 

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>

<br>


{% for post in site.contact %}
  {% include archive-single.html %}
{% endfor %}
