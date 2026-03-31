---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The Zdouc Lab strives to be a diverse and inclusive space where individuals can freely exchange ideas, learn, and grow.
We foster an environment where we respect and appreciate our differences, where all team members are treated equally and respectfully.
We stand against any form of discrimination, as laid out in our [Code of Conduct](https://github.com/zdouc-lab/.github/blob/main/CODE_OF_CONDUCT.md).

Meet the wonderful individuals that make up our research group!

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and group != 'alum'" %}

{% include section.html dark=true %}

We are always on the lookout for new and interesting perspectives, both in terms of individuals and collaboration partners.
If you are intrigued by our work, please feel free to reach out to us!

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Get in touch"
  link="contact"
  style="button"
%}

{% include section.html %}

## Alumni

Here are the past members of our group!

{% include list.html data="members" component="portrait" filter="group == 'alum'" style="small" %}

{% include section.html %}