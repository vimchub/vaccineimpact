---
title: Advisory Board
---

Scientific Advisory Board (SAB) acts as a consulting body to the VIMC Management group and the Consortium overall.  The SAB members are sought to represent a variety of international health and policy organisations as well as research institutions with a breadth of experience relevant to the Consortium key objectives. The SAB members were nominated during the first year of the Consortium operations for a five year term. The SAB consists of the following members:

<div id="advisory-board-list">
  {% for person in site.data.advisory-board %}
    {% if person.url %}
	  <a href="{{ person.url }}">
        <strong>{{ person.name }}</strong>
	  </a>
	{% else %}
	  <strong>{{ person.name }}</strong>
	{% endif %}
	
	{% if person.title %}
	  <br/>
	  {{ person.title }}
	{% endif %}
	<br/><br/>
  {% endfor %}
</div>

*Additional members pending*