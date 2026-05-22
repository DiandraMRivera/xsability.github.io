---
# Basic Document Options
title: Markdown Figure Practice
author: Diandra Rivera
lang: en
abstract: 'This pretend homework assignment needs remediation. Using what you learned in the Markdown Tutorial, remediate this document to [AA conformance](https://websiteaccessibilitychecker.com/checker/index.php) to confirm your understanding.'
abstract-title: Purpose of Document
# Pandoc Options. Note the following needs to be in the Pandoc commandline for html output: --toc --toc-depth=#
toc-title: 'Contents' # title of toc.
maxwidth: '95%' # how much of the browser page the document will fill.
fontsize: '14pt' # the default font size. Slightly bigger than 12pt is always easier to read
linkcolor: 'blue' # make links distinguishable (blue)
# Pandoc Crossref Options
#chapters: true #assign number to sections
#chaptersDepth: 3 #the number of numbers in the chapter header, e.g. 3 means 1.2.4 will be numbered as such. 
numberSections: true # automatically numbers sections in and in document (in order with crossref markup)
linkReferences: true # automatically makes references clickable
nameInLink: true # automatically adds prefix to reference - e.g."fig. 3" instead of just just "3"
---

# Problem 1 {#sec:p1}

*Vibing*, in mathematics, means *giving and receiving those steady-state vibes*.

Six friends start *vibing* according to the diagram below. Friends 1, 2, 3, and 4 are chill, but κ and Γ are vibe thieves who slowly drain the vibes from the group. What is the smallest vibe rate ρ that Γ must have to hog more vibes than κ *after a very long time*. Said differently, find

$$
\underset{\rho (t) }{\operatorname{min}} \left [  \left \{ \underset{t \to \infty}{\rho (t)} \ \colon \operatorname{\text{vibe}}(\Gamma) > \operatorname{\text{vibe}}(\kappa) \right \} \right ]
$${#eq:1}

![A directed graph structure with node set $\{1,2,3,4,\kappa,\Gamma \}$, and directed arrows describing the relationship between them. See footnote below for more details[^1].](https://cdn.mathpix.com/cropped/9f40724d-6edc-41ce-890d-8ac4940257ea-1.jpg?height=1165&width=1618&top_left_y=1179&top_left_x=249){#fig:p1 alt="Problem 1 directed graph structure of friends vibing"}

\pagebreak

# Problem 2 {#sec:p2}

Linguistics can tell us whether it is *most correct* to say

>"I butter up your toast."

or

>"I butter your toast up."[^B]

Find the transformation that maps the syntax tree of the former to the latter, and prove that it has no inverse. Finally, *what does this say about which is most correct?*

![A mapping (represented by an arrow) transforms "I butter up your toast." to "I butter your toast up." See footnote for description of tree structures[^2].](https://cdn.mathpix.com/cropped/9f40724d-6edc-41ce-890d-8ac4940257ea-2.jpg?height=923&width=1641&top_left_y=674&top_left_x=242){#fig:p2 alt="Problem 2 syntax tree for 'I butter up your toast'"}


\pagebreak

# Problem 3 {#sec:p3}

Every carpenter knows that if you have a 2x2 grid of tiles and one of the tiles is missing, the remaining tiles will be shaped like an L.

But carpentry can be lonely, and there is a lot of time to think. A carpenter might wonder if it's possible to construct an arbitrarily large $2^{n+1} \ n \in \mathbb{N}$ square grid with such L shaped tiles if a single tile is missing anywhere on the grid.

![A 2^n+1^ square tile grid with one missing tile (shaded).  L shaped sets of 3 tiles are proposed to be able to cover the entire square.](https://cdn.mathpix.com/cropped/9f40724d-6edc-41ce-890d-8ac4940257ea-3.jpg?height=758&width=850&top_left_y=577&top_left_x=369){#fig:p3 width=50% alt="Problem 3: tile grid"}

The carpenter might start by partitioning the entire grid into equally sized sub-grids, and place an L-shaped tile in the middle of the entire grid to create "missing tiles" in the three sub-grids which don't already have a missing tile. With the example below, the carpenter needs to perform two such partitions to understand how to think about tiles[^C].

:::{#fig:p3Subs}
![The 2^n+1^ grid is sequentially partitioned into four 2^n^ sub-grids. Appropriate placement of an L-shaped tile in its center ensure one "mssing" tile in each quadrant.](https://cdn.mathpix.com/cropped/9f40724d-6edc-41ce-890d-8ac4940257ea-3.jpg?height=691&width=547&top_left_y=1572&top_left_x=298){#fig:p3a height=500px alt="Problem 3a Partitioned Grid: L shape in center of grid, one missing tile"}
![The principle of appropriate L-shaped tile placement can be further applied to sub-sub grids. Partitioning a quadrant into four 2^n-1^ sub-sub-grids shows a possible L-tile covering. See footnote for more details[^3].](https://cdn.mathpix.com/cropped/9f40724d-6edc-41ce-890d-8ac4940257ea-3.jpg?height=693&width=707&top_left_y=1572&top_left_x=1160){#fig:p3b height=500px alt="Problem 3b Partitioned Grid: Additional L shape around sub-grid missing tile"}

Principle of L-tile covering
:::

1. How many L-shaped tiles are required to cover the grid on the right hand side of the above figure?

2. If the carpenter needed to perform 5 partitions to make suitable sub-grids, how big does **n** need to be?

3. Prove that any such grid can be covered in L shaped tiles.

# Problem 4 {#sec:p4}

> **Potato Theorem**: For $n \in \mathbb{N}$ sets, it is impossible to draw a proper Venn diagram without at least one set from the potato group $\mathbb{P}$.

Recall that a proper Venn diagram must have a total of 2^n^ intersecting sets. We demonstrate the essence of the proof below:

:::{#fig:p4subs}
![Equidistant equivalently sized sets do not form a venn diagram because some sets don't exist](https://cdn.mathpix.com/cropped/9f40724d-6edc-41ce-890d-8ac4940257ea-4.jpg?height=431&width=514&top_left_y=648&top_left_x=275){#fig:p4a height=400px alt="Problem 4 fig A - impossible Venn diagram of four overlapping sets"}
![In B, the potato theorem is applied to set C to form a proper Venn diagram. See footnote for description of drawn sets and of the application of the potato theorem[^4]](https://cdn.mathpix.com/cropped/9f40724d-6edc-41ce-890d-8ac4940257ea-4.jpg?height=431&width=519&top_left_y=648&top_left_x=876){#fig:p4b height=400px alt="Problem 4 fig B - Venn diagram of 4 sets using the Potato theorem"}

Overlapping sets A,B,C,D
:::

1. Verify that the set of overlapping circles does not contain the set $(A \cap C) \backslash (B \cup D)$.
2. Use the figure on the right to develop a proof by induction of the **Potato Theorem**.

# Problem 5 {#sec:p5}

> **Bugle's Lemma**: The smallest cone $\mathbb{C}$ normal to the Pringle $\mathbb{S}$ containing tangent potato $P$ has a tapering angle equal to the kurtosis in starch distribution about $P$'s principle axis $\mu$ and $||\mu \times \vec{n}||$. We call this cone a Bugle ([*named after the rather unpopular snack*](https://en.wikipedia.org/wiki/Bugles_(snack))).

![A potato is tangent to a hyperbolic paraboloid in $[x,y,z]$-space with surface normal and principle axis identified. Please see footnote for more details[^5].](https://cdn.mathpix.com/cropped/9f40724d-6edc-41ce-890d-8ac4940257ea-5.jpg?height=1753&width=1105&top_left_y=472&top_left_x=298){#fig:bugles width=75% alt="Problem 5 potato tangent to hyperbolic paraboloid"}

1. Find the critical pringle points $\mathbb{S}_c$ where $\mathbb{S}$ and the Bugle are locally tangent. Describe your answer in terms of a free vector $\vec{u}$, the principle axis of $P$ expressed in the $x,y,z$ frame.
2. Is the Bugle a characteristic? Why or why not? Justify your answer.


[^B]: Inspired by McCawley, J.D. "Parentheticals and Discontinuous Constituent Structure," *Linguistic Inquiry* vol 13(1) 1982, pp.91-106. URL: [http://www.jstor.org/stable/4178261?origin=JSTOR-pdf]

[^C]: Inspired by example 6.2.4 of Daniel J. Velleman's textbook "How To Prove It" [available from the publisher](https://www.cambridge.org/highereducation/books/how-to-prove-it/6D2965D625C6836CD4A785A2C843B3DA#overview).

[^1]: [Problem @sec:p1] directed graph of vibe relations needed to solve @eq:1.

      The following table describes the relationship between nodes $\{1,2,3,4,\kappa,\Gamma \}$ and the unitless magnitude of the vibing between them.

      | Node | Directed Towards | Magnitude |
      | :--: | :--: | :--: |
      | 1 | 2 | 0.7 |
      | 2 | 3 | 0.18 |
      | 2 | κ | 0.12 |
      | 2 | Γ | 0.21 |
      | 3 | 2 | 0.72 |
      | 4 | 2 | 0.6 |
      | 4 | 3 | 0.12 |
      | 4 | κ | 0.38 |
      | κ | 1 | 0.23 |
      | κ | 4 | 0.16 |
      | κ | κ | 0.13 |
      | Γ | 2 | 0.13 |
      | Γ | 3 | 0.32 |
      | Γ | Γ | ρ |

      : Problem 1: tabulation of directed vibing among friends

[^2]: [Problem @sec:p2] tree structures. The lists describes the hierarchical relationship in each tree graph.

    "I butter up your toast."

    1. S
       1. NP
          1. I
       2. V'
          1. V
             1. V
                1. butter
             2. P
                1. up
          2. NP
             1. your toast

    "I butter your toast up."

    2. S
       1. NP
          1. I
       2. V'
          1. V
             1. butter
          2. NP
             1. your toast
          3. P
             1. up

[^3]: [Problem @sec:p3] partitioning tiles. This figure outlines the partitioning and subsequent L-tile placement in order to begin the proof. Two iterations of the same 2^n+1^ square are shown, arranged left to right in order of the partitioning sequence.

    Left:

    - The 2^n+1^ grid is partitioned into four 2^n^ sub-grids.
    - A missing tile is near the center of the upper right 2^n^ sub-grid.
    - A single L-shaped tile is placed in the center of the 2^n+1^ grid.
      - This placement is such that 1 of its 3 tiles is in the other three 2^n^ sub-grids.

    Right:

    - The top right 2^n^ sub-grid is partitioned further into four 2^n-1^ sub-sub-grids.
    - In this example, each of the 2^n-1^ sub-sub-grids has four tiles.
    - One of the four 2^n-1^ sub-sub-grids has a single tile missing.
    - A single L-shaped tiling is placed such that 1 of its 3 tiles is in all the other 2^n-1^ sub-sub-grids.
    - Now, each of the 2^n-1^ sub-sub-grids contains exactly 3 free tiles arranged in an L-shape.
    - Placement of an L-shaped tile into each of these sub-sub-grids covers the entirety of the larger 2^n^ sub-grid.
      - Performing the same procedure in the other 3 2^n^ sub-grids will provide full coverage of the entire 2^n+1^ grid.

[^4]: [Problem @sec:p4] overlapping sets. This footnote describes how the potato-set C is arranged with respect to the circular sets A,B,D in the Venn diagram.
   
    - The set C is located just above  A ∩ D.
    -  follows the circumference of A as it intersects other sets, and is split into left and right halves by this circumference where overlap occurs.

    From top to bottom:

    1. Left half of C
       1. C ∩ A
       2. C ∩ A ∩ D
       3. C ∩ A ∩ D ∩ B
       4. C ∩ A ∩ B
    2. Right half of C
       1. C ∩ D
       2. C ∩ D ∩ B
       3. C ∩ B

    The lowest point of C is within the set C ∩ B.

[^5]: [Problem @sec:p5] hyperbolic paraboloid. The hyperbolic paraboloid **S** ∈ [x,y,z] opens towards the positive **z** axis along **x**, and opens towards the negative **z** axis along **y**.

    - **S** is centered at the origin.
    - The tangent potato **P** is located somewhere on the negative **x** axis.
    - A normal vector **n** points from the surface s through **P**.
    - the principle axis of **P** appears in this figure as an axis adjacent to **P**'s longest dimension.

