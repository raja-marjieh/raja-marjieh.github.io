---
layout: page
title: Similarity
description: Aspects of Similarity in Natural and Artificial Minds
img: assets/img/similarity_project.jpg
importance: 1
category: Present
related_publications: true
---

Humans construct useful representations to support adaptive behavior in high-dimensional sensory environments. Understanding the structure of those representations has been at the center of decades of psychological research. Human similarity judgments provide an effective way for characterizing the structure of representations by densely mapping the perceived relations between pairs of stimuli. This idea propelled a fruitful research program that yielded many classic results in the literature such as Shepard's universal law of generalization, Tversky's feature model, the helical representation of pitch, and multidimensional scaling analysis.

Despite its success, the similarity research program is not complete, in part because central results such as the universal law of generalization are based on low-dimensional artificial stimuli and small sample sizes that severely limit their generalizability, and in part because recent methodological advances such as the development of large language models, contrastive training, and adaptive experiment designs unlock new sets of questions that were simply not feasible before.

In this set of projects I combine the similarity-based approach with large-scale adaptive experiments, modern machine learning, and Bayesian modeling to address questions pertaining to three key aspects of representations: (i) <em>Scaling</em>: To what extent does representational structure generalize to naturalistic and ecologically valid tasks? {% cite marjieh2024universal marjieh2023pitch %} (ii) <em>Alignment</em> How much of our perceptual representations can be recovered from language? {% cite marjieh2024large marjieh2023words%} and (iii) <em>Abstraction</em>: What form of similarity can support learning abstract representations in humans and machines? {% cite marjieh2025learninghumanalignedrepresentationscontrastive marjieh2025numberlargelanguagemodel %}

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
