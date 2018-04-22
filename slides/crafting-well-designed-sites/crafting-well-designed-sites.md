---
title: Crafting Well-Designed Sites
author: Jake Zimmerman
date: \today
fontsize: 12pt
monofont: Menlo
mainfont: Avenir
header-includes:
- \usepackage{pandoc-solarized}
- \input{beamer-includes}
- \graphicspath{{img/}}
---

# Before we begin

##

\Large{I have a confession to make.}

##

\Huge{I'm not a designer;}

##

\Huge{I'm an engineer.}

##

\Huge{But, I design.}

##

We'll be looking at some **very practical tips** you can put
use to make your sites well-designed.

In particular, we're going to be looking heavily at

- typography, and
- information hierarchy

and how they come together to yield "good design."

## Acknowledgements

80% of the content here comes from:

- [Practical Typography], by Matthew Butterick
- 05-391 Interaction Design Overview, by Karen Berntsen &
  Jenna Date


# Typography

## Typography and grid dominate web design

Everything else on the web is supported by typography and
grid:

- Color palettes
- Iconography
- User interfaces
- Experience design
- Interaction design

## Typography is the visual component of the written word

Good design is both visual **and** verbal.

Consider: would you go to your first interview in sweat
pants?

- No, you'd dress presentably.
- It's not **just** about what you say at the interview.

## Practical Typography

We're going to look at Matthew Butterick's *Typography in
Ten Minutes*:

Five simple rules to capture 70% of good typography.

## Rule 1

The four most important typographic choices you make in any
document are

- point size,
- line spacing,
- line length,
- and typeface,

because those choices determine how the body text looks.

## Rule 2

Point size should be

- **10–12 points** in printed documents,
- **15-25** pixels on the web.

## Rule 3

Line spacing should be **120–145%** of the point size.

## Rule 4

The average line length should be

- **45–90 characters** (including spaces), or
- **2-3 alphabets**.

For example:

abcdefghijklmnopqrstuvwxyzabcdefghijklmnopqrstuvwxyzabc

## Rule 5

The easiest and most visible improvement you can make to
your typography is to **use a professional font**.

Don't know where to start?

- I recommend [Typewolf],
    - especially, [his recommendation lists].


# Information Hierarchy

## Thoughtful information hierarchy makes navigation sensible

> **progressive disclosure**:
>
> an interaction design technique to help maintain the focus
> of a user's attention by reducing clutter, confusion, and
> cognitive workload.

Where should they look...

- first?
- second?
- last?

## Practical Information Hierarchy

We're going to look at Karen Berntsen and Jenna Date's three
rules for designing information hierarchy.

For clarity, I'm going to number them 6, 7, & 8.

## Rule 6

Every design must have a clear **point of entry**.

## Rule 7

Careful attention to **progressive disclosure** can make
even the most complex content easier to navigate.

## Rule 8

**Using whitespace intelligently** joins the visual & verbal
elements of your design.

Designing the *negative* spaces of your design is as crucial
as designing the actual content.


# Case Study: The Joys of the Craft

## The Joys of the Craft

We're going to take a look at "The Joys of the Craft," an
excerpt from Fred Brooks' book *The Mythical Man-Month*.[^1]

Specifically, we're going to focus on the **typographic**
and **hierarchical** elements of this piece of body text.

[^1]: Read the [full excerpt] or [the book].

[full excerpt]: http://www.davar.net/PROGRAM/EXTRACTS/CRAFTJOY.HTM
[the book]: https://en.wikipedia.org/wiki/The_Mythical_Man-Month


## Rule 2: Point size

\begin{center}
  \hspace*{-11mm}
  \includegraphics[keepaspectratio=true,width=1\paperwidth]{case-study-01.png}
\end{center}

## Rule 3: Line height

\begin{center}
  \hspace*{-11mm}
  \includegraphics[keepaspectratio=true,width=1\paperwidth]{case-study-02.png}
\end{center}

## Rule 4: Line length

\begin{center}
  \hspace*{-11mm}
  \includegraphics[keepaspectratio=true,width=1\paperwidth]{case-study-03.png}
\end{center}

## Rule 5: Typeface (Proxima Nova)

\begin{center}
  \hspace*{-11mm}
  \includegraphics[keepaspectratio=true,width=1\paperwidth]{case-study-04.png}
\end{center}

## Rule 5: Typeface (Proxima Nova)

\begin{center}
  \includegraphics[keepaspectratio=true,height=0.9\textheight]{case-study-04-full.png}
\end{center}

## Rule 6: Point of entry

\begin{center}
  \includegraphics[keepaspectratio=true,height=0.9\textheight]{case-study-05.png}
\end{center}

## Rule 7: Progressive disclosure

\begin{center}
  \includegraphics[keepaspectratio=true,height=0.9\textheight]{case-study-06.png}
\end{center}

## Rule 8: Meaningful whitespace

\begin{center}
  \includegraphics[keepaspectratio=true,height=0.9\textheight]{case-study-07.png}
\end{center}

## Original

\begin{center}
  \includegraphics[keepaspectratio=true,height=0.9\textheight]{case-study-01-full.png}
\end{center}

## Final

\begin{center}
  \includegraphics[keepaspectratio=true,height=0.9\textheight]{case-study-07.png}
\end{center}


# Resources & Recommended Readings

## These links are excellent for learning more

- [Practical Typography]
    - Please just go read this
- [Zell Liew] on Grids
    - for a good start: [Why Vertical Rhythm]
- [Typewolf]
    - Best reference on typefaces and pairings on the
      Internet
- If you can, take an HCI class!
    - 05-391 Interaction Design Overview
    - 05-392 Designing Human-Centered Systems

# Workshop

## Sketching allows fast iteration of ideas

- Designers like to **iterate** a ton
- Iteration enables exploration of the design space
- We're looking for the best design solution

## Sample thumbnail sketches

\includegraphics[keepaspectratio=true,width=0.9\linewidth]{pencil-sketches.pdf}

##

So we represent

- type with horizontal lines,
- text alignment with vertical lines,
- and **bold** text with thicker lines,

which

- captures information hierarchy,
- and enables rapid iteration.

## Digital Designs

Some commonly used software for creating digital designs:

- Sketch
- Illustrator
- Photoshop
- InDesign

Pick your poison. I like [Sketch]. It's \$50 one time for
students.

[Sketch]: https://www.sketchapp.com

## Let's hop to it!

Agenda

- Thumbnail pencil sketches
    - ... with critique
- Digital designs
    - ... with critique

## Designing a Homepage/Poster for WDW

- Only change the typography and hierarchy

- Leave the content alone

## Content

\scriptsize

```
Web Dev Weekend
a weekend packed with web development workshops

1:30 p.m. – 3:00 p.m.
HTML & CSS Primer

3:00 p.m. – 4:30 p.m.
Frontend JavaScript Primer

4:30 p.m. – 6:00 p.m.
Crafting Well-Designed Sites

Web Dev Weekend is a series of lectures, workshops, and
exercises that introduce you to the fundamentals of web
development.

If you want to make websites outside of the classroom, get a
head start on later electives, or attend hackathons, Web Dev
Weekend will give you the foundational knowledge you need to
get started.
```

\normalsize


[Practical Typography]: http://practicaltypography.com/
[Typewolf]: https://www.typewolf.com/
[his recommendation lists]: https://www.typewolf.com/recommendations
[Zell Liew]: https://zellwk.com/blog/
[Why Vertical Rhythm]: https://zellwk.com/blog/why-vertical-rhythms/

<!-- vim:tw=60
-->
