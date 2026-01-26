---
title: Contact Us
nav:
  order: 5
  tooltip: email,address and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact


&ensp;&ensp;&ensp;&ensp;我们珍视每一次相遇——无论是学术观点的切磋、研究合作的邀约，还是对团队动态的关切、对成果的反馈建议，都欢迎通过此渠道坦诚相告。不设门槛，唯愿以开放之姿倾听专业声音，分享探索足迹，让不同视角的碰撞为科研添一份可能。

&ensp;&ensp;&ensp;&ensp;期待与你在此开启对话，共织更紧密的学术联结。

{%
  include button.html
  type="email"
  text="jane@smith.com"
  link="jane@smith.com"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
