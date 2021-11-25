---
layout: page
title: About Us
permalink: /about/
css: about.css
---

Comedy Society at the University of York provides a platform for all people to
do all types of comedy.
We host shows every week of term, all completely written and performed by our
members. As well as this we run weekly workshops on <span class="red">Stand Up,
Sketch Writing, Sketch Acting and Improv.</span> All of our workshops give you
the chance to try out your ideas or get inspiration from others in a <span
class="red">pressure free</span> environment.

We also go to the Edinburgh Fringe every year in the form of two troupes; our
sketch troupe, [The Dead
Ducks](https://www.youtube.com/watch?v=45sgFnbzS2c)
and our Improv troupe, [The Shambles]({{site.shambles_website}}).

<h3 class="red">I want get involved!</h3>
Fantastic! The easiest way to get involved is to join our mailing list by
emailing [comedysoc@yusu.org](mailto:comedysoc@yusu.org). By joining our
mailing list, you can find out about the locations and times of our weekly
workshops. We also have our own Facebook group which you can join
[here.](https://www.facebook.com/groups/3186019204955042/?fref=ts)

The Facebook groups for our weekly workshops can be found below

{% for workshop in site.data.workshops %}
- #### [{{ workshop.name }}]({{ workshop.group-link }})
{% endfor %}


All of our workshops are free to attend however, if you'd like to perform in
one of our shows, you'll have to pay our low membership fee of <span
class="red">£5!</span> You can pay membership
[here.](https://yusu.org/activities/view/comedy-society)
