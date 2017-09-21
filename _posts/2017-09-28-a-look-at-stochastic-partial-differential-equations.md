---
layout: default
title: "A look at Stochastic Partial Differential Equations"
date: 2017-09-20
author: Peter Demetriou
tags: SPDE
excerpt: "Where $V$ in \eqref{eq:Black-Scholes} means something specific in statistics. Using a change of variables the Black-Scholes equation can be reduced the the familar heat equation."
---

## [](#A look at Stochastic Partial Differential Equations)A look at Stochastic Partial Differential Equations

Where $V$ in \eqref{eq:Black-Scholes} means something specific in statistics. Using a change of variables the Black-Scholes equation can be reduced the the familar heat equation.

$$
\begin{equation}
  \label{eq:Black-Scholes}
  \frac{\partial V}{\partial t} + \frac{1}{2}\sigma^2 S^2\frac{\partial^2 V}{\partial S^2} + rS\frac{\partial V}{\partial S} - rV = 0
\end{equation}
$$

In equation \eqref{eq:IntegralSample}, we find the value of an
interesting integral:

$$
\begin{equation}
  \label{eq:IntegralSample}
  \int_0^\infty \frac{x^3}{e^x-1}\,dx = \frac{\pi^4}{15}
\end{equation}
$$

This is a text with a footnote[^1].

{::comment}
Should have a section with articles or posts wherein one can comment perhaps? Then a some items with links to the articles or tutorials on this page
{:/comment}

* * *
<a href="javascript:history.back()">Back</a>

* * *
## [](#Reference)Reference

[^1]: And here is the definition fo the footnote.