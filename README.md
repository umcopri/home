Welcome to the UMCOPRI (University of Maine - Coasts, Oceans, Ports, and Rivers Institute) wiki!  We will have a lot of stuff going on in the future, so hopefully this will become a helpful resource.

## Links

To stay in touch with the people of COPRI, join our slack channel: <http://umcopri.slack.com>

If you want to invite new members, we recommend using this link: <http://bit.ly/umcopri>

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
