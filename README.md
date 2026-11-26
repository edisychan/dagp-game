# Find the First Fit

**[Play the game](https://edisychan.github.io/dagp-game/)** · [Read the paper on arXiv](https://arxiv.org/abs/2611.26986)

A circle, a rounded square and a rippled curve each form a single loop. If a robot pen draws them and all you see are 300 noisy dots from each path, how simple an equation can fit each one?

This browser game introduces **distributional algebro-geometric persistence (dAGP)** by letting you explore how many independent polynomial equations fit the same dots as you change the polynomial degree and the allowed error.

## Game mode

Guess the lowest polynomial degree that fits each pen trace at a fixed error limit. Each guess draws a curve over the dots so you can see how it fits. Easy gives you three guesses per loop, Medium gives you two and Hard gives you one.

## Explore mode

Pick a trace and a degree, then drag the error limit. The purple band shows where the displayed equation meets the limit point by point. The error plot shows which equations qualify on average across all 300 dots.

**Try this with the rounded square.** Keep the degree at 3. How far do you have to move the slider before the first equation qualifies? Can you get a second one to qualify on the very same dots?

## Play offline

Download `index.html` and open it in your browser. The game, data and graphics are all included in that one file.

## About the research

The game accompanies *Reading Between the Points: Finding Hidden Equations in Data*, a poster for the University of Southampton’s 2026 Doctoral Research Poster Showcase.

Edisy Kin Wai Chan and Andersen Ang (2026). *Distributional Algebro-Geometric Persistence (dAGP): Wasserstein-Stable Polynomial-Relation Signatures*. Accepted at the NeurIPS 2026 Workshop on Geometric Distributional Deep Learning (GDDL).
