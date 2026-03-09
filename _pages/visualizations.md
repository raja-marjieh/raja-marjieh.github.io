---
layout: page
permalink: /visualizations/
title: Interactive Visualizations
description: Interactive 3D similarity visualizations.
nav: false
nav_order: 5
---

Below are interactive 3D MDS visualizations of similarity data.  
You can rotate the plots using the mouse.

---
<style>
.navbar { display:none; }
body { padding-top:0 !important; }
</style>

<style>
.vis-frame {
  width: 100%;
  height: 650px;
  border: none;
}
</style>

### Figure 3A — Non-musicians (No Experience)

<iframe class="vis-frame"
src="{{ '/assets/visualizations/fig3a.html' | relative_url }}">
</iframe>

<p style="font-size:0.9rem; color:gray;">
Three-dimensional MDS solution for pitch similarity judgments among
non-musicians with no musical training.
</p>

---

### Figure 3B — Non-musicians (Some Experience)

<iframe class="vis-frame"
src="{{ '/assets/visualizations/fig3b.html' | relative_url }}">
</iframe>

<p style="font-size:0.9rem; color:gray;">
Three-dimensional MDS solution for pitch similarity judgments among
non-musicians with some musical training.
</p>

---

### Figure 3C — Musicians

<iframe class="vis-frame"
src="{{ '/assets/visualizations/fig3c.html' | relative_url }}">
</iframe>

<p style="font-size:0.9rem; color:gray;">
Three-dimensional MDS solution for pitch similarity judgments among
musicians.
</p>