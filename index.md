---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

<div class="container">
  <div class="card-deck">
    {% include card.html title="Step by step advocacy guide" subtitle="For health workers" image="/img/healthcare-workers.jpg" %}
    {% include card.html title="Step by step advocacy guide" subtitle="For community workers" image="/img/community-workers.png" %}
  </div>
  <div class="card-deck">
    {% include card.html title="Learn" subtitle="Learn about immigration checks and charging in the NHS" image="/img/learn.jpg" %}
    {% include card.html title="Campaign" subtitle="Start a campaign in your local area" image="/img/campaign.jpg" %}
  </div>
</div>

{% include footer.html %}
