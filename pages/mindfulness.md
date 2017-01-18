---
layout: page
title: "Mindfulness"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/mindfulness/"
---
Mindfulness is keeping your awareness in the here and the now. Being present.
Many people associate mindfulness with formal meditation. Sitting on your cushion and following your breath.
But you can be mindful everywhere and at any time, simply by focussing your attention on what is going on in the present moment.
You can be mindful of your body, of your thoughts, of your feelings, of what is going on around you. 

<ul>
    {% for post in site.categories.mindfulness %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
