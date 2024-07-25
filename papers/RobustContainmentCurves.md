---
layout: default
title: Robust Containment Queries over Collections of Rational Parametric Curves via Generalized Winding Numbers
---

## Robust Containment Queries over Collections of Rational Parametric Curves via Generalized Winding Numbers

Jacob Spainhour, David Gunderman, Kenneth Weiss

ACM Transactions on Graphics (SIGGRAPH 2024)

![Graphical Abstract](/resources/robust_containment_curved.png)

### Abstract 
Point containment queries for regions bound by watertight geometric surfaces, i.e., closed and without self-intersections, can be evaluated straightforwardly with a number of well-studied algorithms. When this assumption on domain geometry is not met, such methods are either unusable, or prone to misclassifications that can lead to cascading errors in downstream applications. More robust point classification schemes based on generalized winding numbers have been proposed, as they are indifferent to these imperfections. However, existing algorithms are limited to point clouds and collections of linear elements. We extend this methodology to encompass more general curved shapes with an algorithm that evaluates the winding number scalar field over unstructured collections of rational parametric curves. In particular, we evaluate the winding number for each curve independently, making the derived containment query robust to how the curves are arranged. We ensure geometric fidelity in our queries by treating each curve as equivalent to an adaptively constructed polyline that provably has the same generalized winding number at the point of interest. Our algorithm is numerically stable for points that are arbitrarily close to the model, and explicitly treats points that are coincident with curves. We demonstrate the improvements in computational performance granted by this method over conventional techniques as well as the robustness induced by its application.


Links:
<ul>
<li>
    Paper: <a href="https://arxiv.org/abs/2403.17371">arXiv</a> </li>
<li>
    C++ Code: <a href="https://github.com/LLNL/axom">Axom</a> </li>
</ul>