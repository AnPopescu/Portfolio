---
name: AI Tower
tools: [Unity, C# , Old]
image: \Portfolio\images\Projects\AI_Tower\AITower_p1.PNG
description: This is my project for my class regarding AI in Video Games.
---

## AI Tower 

I created an AI for a tower defense game based on Reinforcement Learning / Value Iteration algorithm.

The idea is that the marching enemies do not follow a certain direction every wave and they try to avoid the most dangerous path (the path that has the most towers) in order to reach the final destination (the blue cube) in greater numbers.

The Towers can diminish the reward generated on the grid tiles around them and forces enemies to change marching direction.

We can say the enemies are aware of where the towers were build and try to avoid them in order to reach the final destination. 

---

{% capture carousel_images %}
{{site.baseurl}}\images\Projects\AI_Tower\AITower_p1.PNG
{{site.baseurl}}\images\Projects\AI_Tower\AITower_p2.PNG
{% endcapture %}
{% include elements/carousel.html %}


---

##### Showcase 

<div class="video">
  <iframe src="\Portfolio\images\Projects\AI_Tower\AI_Tower_Showcase.mp4" frameborder="0" allowfullscreen></iframe>
</div>

