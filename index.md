# Hi, Hai's here

## Thought desk
### Your body won't go where your mind doesn't lead it. Believe in yourself and your abilities, and your mind will pave the way to your success
### Knowing the future is a gift, but knowing how to act on that knowledge is a skill. The true power lies not in the foresight, but in the wisdom to make the right choices in the present moment.
## TODO

# Blog posts

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.date | date: "%B %d, %Y" }}</p>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>



