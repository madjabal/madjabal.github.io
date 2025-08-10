---
layout: default
title: Testing LaTeX and Plotting
date: 2025-08-09
---

# Testing LaTeX Rendering

Here's some inline math: $$E = mc^2$$

And here's a display equation:

$$\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}$$

More complex math:

$$f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n$$

Regular text continues here. You can also do inline math like $$\alpha = \beta + \gamma$$ in the middle of sentences.

## Multiple equations

$$\begin{align}
\nabla \times \vec{\mathbf{B}} - \frac{1}{c} \frac{\partial\vec{\mathbf{E}}}{\partial t} &= \frac{4\pi}{c}\vec{\mathbf{j}} \\
\nabla \cdot \vec{\mathbf{E}} &= 4 \pi \rho \\
\nabla \times \vec{\mathbf{E}} + \frac{1}{c} \frac{\partial\vec{\mathbf{B}}}{\partial t} &= \vec{\mathbf{0}} \\
\nabla \cdot \vec{\mathbf{B}} &= 0
\end{align}$$


# Interactive Plotly Graph

Here's some regular markdown text with math: $$f(x) = x^2$$

<div id="plotly-div" style="width:100%;height:400px;"></div>

<script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
<script>
var trace1 = {
  x: [1, 2, 3, 4],
  y: [10, 11, 12, 13],
  type: 'scatter',
  name: 'Data 1'
};

var trace2 = {
  x: [1, 2, 3, 4],
  y: [16, 15, 14, 13],
  type: 'scatter',
  name: 'Data 2'
};

var data = [trace1, trace2];
var layout = {title: 'My Interactive Plot'};

Plotly.newPlot('plotly-div', data, layout);
</script>