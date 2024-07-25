---
layout: default
title: Robust Containment Queries over Collections of Rational Parametric Curves via Generalized Winding Numbers
---

## Robust Containment Queries over Collections of Rational Parametric Curves via Generalized Winding Numbers

![Graphical Abstract](/resources/representative_image.pdf)

### Abstract
Point containment queries for regions bound by watertight geometric surfaces, i.e., closed and without self-intersections, can be evaluated straightforwardly with a number of well-studied algorithms. When this assumption on domain geometry is not met, such methods are either unusable, or prone to misclassifications that can lead to cascading errors in downstream applications. More robust point classification schemes based on generalized winding numbers have been proposed, as they are indifferent to these imperfections. However, existing algorithms are limited to point clouds and collections of linear elements. We extend this methodology to encompass more general curved shapes with an algorithm that evaluates the winding number scalar field over unstructured collections of rational parametric curves. In particular, we evaluate the winding number for each curve independently, making the derived containment query robust to how the curves are arranged. We ensure geometric fidelity in our queries by treating each curve as equivalent to an adaptively constructed polyline that provably has the same generalized winding number at the point of interest. Our algorithm is numerically stable for points that are arbitrarily close to the model, and explicitly treats points that are coincident with curves. We demonstrate the improvements in computational performance granted by this method over conventional techniques as well as the robustness induced by its application.

<div class="quick_links">
    <ul>
    <p> Links: </p>
    <li>
        <a href="https://github.com/jcs15c">github</a> </li>
    <li>
        <a href="https://orcid.org/0000-0001-8219-4360">ORCID</a> </li>
    <li>
        <a href="https://arxiv.org/a/spainhour_j_1.html">arXiv</a> </li>
    <li class="last">
        <a href="http://scholar.google.com/citations?user=6nPym_AAAAAJ">Google Scholar</a> </li>
    </ul>
</div>