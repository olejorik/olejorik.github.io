---
title: Puzzle 1
linktitle: Puzzle 1
toc: true
type: docs
date: 2019-05-05T00:00:00+01:00
math: true
weight: "1"
menu:
  puzzles:
    parent: RED puzzles
    weight: 1

---
<meta name=viewport content="width=device-width,initial-scale=1">  
<meta charset="utf-8"/>

<script src="https://cdn.geogebra.org/apps/deployggb.js"></script>


Let set $\mathcal P$ be defined by a ray originated in point $O$ and passing through point $I$, and $\mathcal Q$ be some bounded convex set (shown as an ellipse here for sake of programming easiness). Let $p_0 \in \mathcal P$, and define iteratively $\\{p_n\\}, \\{q_n\\}, \ n \in \mathbb{N} $ as:

$$p_n \to q_{n+1} = \Pr_{\mathcal Q} p_n,$$
$$ q_n \to p_n : p_n\in\mathcal{P}, (p_n-q_n, q_n) = 0,$$
that is the next $q$ point is obtained by projection the last $p$ point on $\mathcal Q,$ and the next $p$ point is obtained by intersection of the perpendicular to line $O q$ in point $q$ and line $O I$.


Prove that 
1. $\exists\ \hat q = \lim_{n\to\inf}  q_n$ and
2. If $\mathcal P \cap \mathcal Q \neq \varnothing$, then $\hat q \in \mathcal P$; otherwise,  line $O \hat q$ is tangent to $\mathcal Q$.

You can click and drag objects in the illustration below.

<div id="ggb-element"></div> 


<script>  
    var ggbApp = new GGBApplet({"appName": "graphing", "width": 691, "height": 630, "showToolBar": false, "showAlgebraInput": false, "showMenuBar": false, 
    "showZoomButtons": true, "showFullScreenButton": true,
    "enableShiftDragZoom": true, "showResetIcon":true,
    // "allowUpScale": true,
    "material_id":"xbrnhk7r" }, true);
    window.addEventListener("load", function() { 
        ggbApp.inject('ggb-element');
    });
</script>