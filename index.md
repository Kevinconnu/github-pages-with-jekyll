# Welcome to my page

I'm glad you are here. I plan to talk about computer things I am learning with accompanying examples. This will probably be super basic until about 2032. In 2032 it'll be poppin off so hard.

<html>
<body>

<p>Click the button to display the time.</p>

<button onclick="getElementById('demo').innerHTML=Date()">Well isn't this convenient.</button>

<p id="demo"></p>

</body>
</html>

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}



