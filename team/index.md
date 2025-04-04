---
title: Team
nav:
  order: 5
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
<!-- FOUNDERS -->
{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'founder'" %}

{% include section.html background="images/background.jpg" dark=true %}

And where would we be without the love and support from those who choose to use the equipment that we have designed? While we wish that we could list everyone who has helped us along our path, that would make this list truly un-ending. So here are some of the more notable of those who have offered us their continued support, input, and dedication.
<!-- MUSICIANS -->
{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'musician'" %}