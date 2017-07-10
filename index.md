---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](another-page).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# [](#header-1)Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## [](#header-2)Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### [](#header-3)Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### [](#header-4)Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### [](#header-5)Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### [](#header-6)Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large Bio image

{% include Bio.svg %}


### Large Maths image

{% include Maths.svg %}
<figure><img src="/_includes/Maths.svg"></figure>
<img src="/_includes/Maths.svg">
![](<img src="_includes/Maths.svg">)
![](src="/_includes/Maths.svg")
![](include Maths.svg)

An inline image: ![Maths](/_includes/Maths.svg){:height="36px" width="36px"}

And here is a referenced ![Maths]

![image-title-here](/_includes/Maths.svg){:class="img-responsive"}





![Alt text](https://cdn.rawgit.com/HelloBeastie/HelloBeastie.github.io/master/_includes/Bio.svg)
<img src="https://cdn.rawgit.com/HelloBeastie/HelloBeastie.github.io/master/_includes/Bio.svg">
![Alt text](https://cdn.rawgit.com/HelloBeastie/HelloBeastie.github.io/master/_includes/Maths.svg)
<img src="https://cdn.rawgit.com/HelloBeastie/HelloBeastie.github.io/master/_includes/Maths.svg">

### MathJax

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

### LaTeX in Markdown Attempted
$$
\usetikzlibrary{decorations.pathmorphing}
\begin{tikzpicture}[line width=0.2mm,scale=1.0545]\small
\tikzset{>=stealth}
\tikzset{snake it/.style={->,semithick,
decoration={snake,amplitude=.3mm,segment length=2.5mm,post length=0.9mm},decorate}}
\def\h{3}
\def\d{0.2}
\def\ww{1.4}
\def\w{1+\ww}
\def\p{1.5}
\def\r{0.7}
\coordinate[label=below:$A_1$] (A1) at (\ww,\p);
\coordinate[label=above:$B_1$] (B1) at (\ww,\p+\h);
\coordinate[label=below:$A_2$] (A2) at (\w,\p);
\coordinate[label=above:$B_2$] (B2) at (\w,\p+\h);
\coordinate[label=left:$C$] (C1) at (0,0);
\coordinate[label=left:$D$] (D) at (0,\h);
\draw[fill=blue!14](A2)--(B2)-- ++(\d,0)-- ++(0,-\h)--cycle;
\draw[gray,thin](C1)-- +(\w+\d,0);
\draw[dashed,gray,fill=blue!5](A1)-- (B1)-- ++(\d,0)-- ++(0,-\h)-- cycle;
\draw[dashed,line width=0.14mm](A1)--(C1)--(D)--(B1);
\draw[snake it](C1)--(A2) node[pos=0.6,below] {$c\Delta t$};
\draw[->,semithick](\ww,\p+0.44*\h)-- +(\w-\ww,0) node[pos=0.6,above] {$v\Delta t$};
\draw[snake it](D)--(B2);
\draw[thin](\r,0) arc (0:atan2(\p,\w):\r) node[midway,right,yshift=0.06cm] {$\theta$};
\draw[opacity=0](-0.40,-0.14)-- ++(0,5.06);
\end{tikzpicture}
$$

plots:

$$
  \begin{tikzpicture}[scale=1.0544]\small
    \begin{axis}[axis line style=gray,
  	samples=120,
  	width=9.0cm,height=6.4cm,
  	xmin=-1.5, xmax=1.5,
  	ymin=0, ymax=1.8,
  	restrict y to domain=-0.2:2,
  	ytick={1},
  	xtick={-1,1},
  	axis equal,
  	axis x line=center,
  	axis y line=center,
  	xlabel=$x$,ylabel=$y$]
    \addplot[red,domain=-2:1,semithick]{exp(x)};
    \addplot[black]{x+1};
    \addplot[] coordinates {(1,1.5)} node{$y=x+1$};
    \addplot[red] coordinates {(-1,0.6)} node{$y=e^x$};
    \path (axis cs:0,0) node [anchor=north west,yshift=-0.07cm] {0};
    \end{axis}
  \end{tikzpicture}
$$

plots:

![\\begin{tikzpicture}\[scale=1.0544\]\\small \\begin{axis}\[axis line style=gray, samples=120, width=9.0cm,height=6.4cm, xmin=-1.5, xmax=1.5, ymin=0, ymax=1.8, restrict y to domain=-0.2:2, ytick={1}, xtick={-1,1}, axis equal, axis x line=center, axis y line=center, xlabel=$x$,ylabel=$y$\] \\addplot\[red,domain=-2:1,semithick\]{exp(x)}; \\addplot\[black\]{x+1}; \\addplot\[\] coordinates {(1,1.5)} node{$y=x+1$}; \\addplot\[red\] coordinates {(-1,0.6)} node{$y=e^x$}; \\path (axis cs:0,0) node \[anchor=north west,yshift=-0.07cm\] {0}; \\end{axis} \\end{tikzpicture}]

  [\\begin{tikzpicture}\[scale=1.0544\]\\small \\begin{axis}\[axis line style=gray, samples=120, width=9.0cm,height=6.4cm, xmin=-1.5, xmax=1.5, ymin=0, ymax=1.8, restrict y to domain=-0.2:2, ytick={1}, xtick={-1,1}, axis equal, axis x line=center, axis y line=center, xlabel=$x$,ylabel=$y$\] \\addplot\[red,domain=-2:1,semithick\]{exp(x)}; \\addplot\[black\]{x+1}; \\addplot\[\] coordinates {(1,1.5)} node{$y=x+1$}; \\addplot\[red\] coordinates {(-1,0.6)} node{$y=e^x$}; \\path (axis cs:0,0) node \[anchor=north west,yshift=-0.07cm\] {0}; \\end{axis} \\end{tikzpicture}]: https://tex.s2cms.ru/svg/%5Cbegin%7Btikzpicture%7D%5Bscale%3D1.0544%5D%5Csmall%0A%5Cbegin%7Baxis%7D%5Baxis%20line%20style%3Dgray%2C%0A%09samples%3D120%2C%0A%09width%3D9.0cm%2Cheight%3D6.4cm%2C%0A%09xmin%3D-1.5%2C%20xmax%3D1.5%2C%0A%09ymin%3D0%2C%20ymax%3D1.8%2C%0A%09restrict%20y%20to%20domain%3D-0.2%3A2%2C%0A%09ytick%3D%7B1%7D%2C%0A%09xtick%3D%7B-1%2C1%7D%2C%0A%09axis%20equal%2C%0A%09axis%20x%20line%3Dcenter%2C%0A%09axis%20y%20line%3Dcenter%2C%0A%09xlabel%3D%24x%24%2Cylabel%3D%24y%24%5D%0A%5Caddplot%5Bred%2Cdomain%3D-2%3A1%2Csemithick%5D%7Bexp(x)%7D%3B%0A%5Caddplot%5Bblack%5D%7Bx%2B1%7D%3B%0A%5Caddplot%5B%5D%20coordinates%20%7B(1%2C1.5)%7D%20node%7B%24y%3Dx%2B1%24%7D%3B%0A%5Caddplot%5Bred%5D%20coordinates%20%7B(-1%2C0.6)%7D%20node%7B%24y%3De%5Ex%24%7D%3B%0A%5Cpath%20(axis%20cs%3A0%2C0)%20node%20%5Banchor%3Dnorth%20west%2Cyshift%3D-0.07cm%5D%20%7B0%7D%3B%0A%5Cend%7Baxis%7D%0A%5Cend%7Btikzpicture%7D

### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
