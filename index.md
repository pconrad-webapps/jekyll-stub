---
topic: Jekyll Stub Site
---

This site contains information about getting started with building web applications in 

* Python, using Flask
* JavaScript, using Node
* Java, using SparkJava
* Ruby, using Rails

## Topics
<ul>
{% for topic in site.topics %}
 <li><a href="{{topic.url}}">{{ topic.topic }}<a>&mdash;{{topic.desc}}</li>
{% endfor %}
</ul>

