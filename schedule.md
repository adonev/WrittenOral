---
title: Schedule for Communication in the mathematical sciences (Aleks Donev, Spring 2023, Courant)
layout: default
---

## Site Map
* [Course Overview](https://adonev.github.io/WrittenOral/)
* [Course Schedule](schedule.md)
* [Resources](resources.md) 

# Course Schedule

Every Wednesday 10-11am in room 1314.

See the [Resources Page](resources.md) for links to the books. 

Hand in writing homework by email to donev at cims, on the day (but before the class) for which it is listed as homework.

## (2/1, 2/8, 2/15, 2/22) [Oral presentation skills](Resources/Lecture-Presentation.handout.pdf)

Writing a talk is covered in Chapter 9 in the textbook by Higham. Also look at these tips on the [David Attenborough style of scientific presentation from Will Ratcliff](Resources/David-Attenborough.pdf). Watch it in action in this [5-minute lecture](https://www.youtube.com/watch?v=jVGHr6MHapo) from Ratcliff.

### Talks:

1. (2/8) Aram-Alexandre, "Can the mathematics of moving dirt predict genomic trajectories?"
2. (2/15) Hassan, "Does mixing of the ocean at scales below 10km contribute to the melting of Arctic sea ice?"
3. (2/22) Mariya, "Friction directs the contraction of the cell skeleton."
4. **No class on 3/1**

### Pre-class materials

1.  A short video lesson [How Big is Infinity?](https://www.youtube.com/watch?v=UPA3bwVVzGI) by TedEd.
2.  A 20-min lecture on TED on the [Mathematics of Origami](https://www.youtube.com/watch?v=NYKcOFQCeno). Watch on your own and comment in class.
3.  A mathematical conference lecture on a very technical topic of [Operads](https://www.youtube.com/watch?v=ZquD_VRDFoU) (algebraic geometry).
4.  A [5 minute talk on the rise of multicellular life](https://www.youtube.com/watch?v=jVGHr6MHapo) related to the [David Attenborough style](Resources/David-Attenborough.pdf).

### Post-class materials

As an alternative to my lecture, see this talk by [Uri Alon](https://www.weizmann.ac.il/mcb/UriAlon/): [part I](https://www.youtube.com/watch?v=5OFAhBw0OXs) (the fire alarm will remind you of Courant...), [part II](https://www.youtube.com/watch?v=Fg_Bn8k0uaQ), [part III](https://www.youtube.com/watch?v=zYsHxNiPg7M), [part IV](https://www.youtube.com/watch?v=OhnSSjQCm4c), [part V](https://www.youtube.com/watch?v=FYkdzZgCX4M), [part VI](https://www.youtube.com/watch?v=y-fhwNa7fnQ). There is also an associated article ["How to give a good talk"](https://pubmed.ncbi.nlm.nih.gov/19854123/) which is short and nice to read.

The issue of how to choose a good colormap for plots that render 3D data as 2D images (in python), including a python tool to check how different types of color blindness (a much more common condition that most of us realize), check out the [cmocean project](https://matplotlib.org/cmocean/) and watch this [talk by Kristen Thyng](https://www.youtube.com/watch?v=o9KxYxROSgM).

### Elevator statements

Elevator "talks" are discussed on page 154 in Chapter 13 (The Big Picture) of the book Stylish Academic Writing. Here is what Sword has to say about it:
_'Condensing a complex research project into a pithy abstract is no simple task, to be sure. An even greater challenge is to boil that abstract down into an “elevator statement”: the seemingly off-the-cuff but in fact brilliantly polished single-sentence summary that you offer to the colleague who turns to you in the elevator at an academic conference and asks, “So what are you working on?” You have just a minute or two to respond: the time that it takes for the elevator to arrive at its destination floor...The secret ingredient of an effective elevator statement—or, for that matter, of a persuasive abstract, article, or book—is a strong thesis or argument. Both words are frequently heard in the freshman composition classroom but seldom in the research laboratory. However, identical principles apply in both venues: writers who put forth a bold, defensible claim are much more likely to generate engaging, persuasive prose than those who offer bland statements of fact with which no one could possibly disagree. In the sciences and social sciences, a strong thesis follows naturally from a compelling research question...'_

### Assignment for 2/22

Prepare a 2-3min elevator talk. Choose your topic (e.g., your own research, field of math) and audience. Try one more specialized and one less specialized audience (e.g., a colleague and a neighbor). Present in class for comment.

## (3/1) No class (SIAM CSE23 conference)

## (3/15) Spring break (no class)

## (3/8, 3/22, 4/5) [Computer Tools: LaTex](Resources/Lecture-Tools.handout.pdf)

We will discuss [computer tools for mathematical writing](Resources/Lecture-Tools.handout.pdf) in class. Also get the [AMS Short Math Guide for LaTex](http://tug.ctan.org/info/short-math-guide/short-math-guide.pdf).

To get movies to work in beamer, use the package _multimedia_.
To use an external movie file (makes the PDF much smaller, and updates to the external movie are seamless), use:

_\movie[width=\textwidth,externalviewer]{\includegraphics[width=\textwidth]{StillFigure.png}}{Movies/Movie.mp4}_

Note that it is a good idea to make a directory called Movies (can be a symbolic link) so the movies are in one place and easy to copy when needed. The default OS viewer for the specific movie file type will be used to open the movie. I recommend making VLC your default player. To insert an embedded movie (AFAIK this only works with the okular PDF viewer on ubuntu, in presentation mode), just remove the _externalviewer_.

### Talks:

1. (3/8) Ryan, "The story of how Suki Manabe's work led us to the Paris Agreement."
2. (3/22) Vish, "How we can generate more stable proteins by learning from natural language."
3. (4/5) Sonia, "How to Sample a Probability Distribution in Infinite Dimensions".

### (4/12, 4/19, 4/26, 5/3) [Structure of a paper](Resources/Lecture-Structure.handout.pdf)

We will begin going through some fundamentals of good scientific writing, starting from the structure of a paper. We will use the following samples from (mostly) review articles as examples:

1.  The Introduction and Outlook of an article by Prof. Miranda Holmes-Cerfon on "[Sticky-sphere clusters](https://arxiv.org/abs/1709.05138)."
2.  The Introduction/Overview section I and sections I.1, I.2 and I.3 of this [review article on Randomized Linear Algebra](https://arxiv.org/abs/0909.4061).
2.  First two pages of this "[Introduction to Regularity Structures](http://www.hairer.org/notes/Regularity.pdf)" by Martin Hairer. Observe the structure of the introduction and what different paragraphs do, and write down some notes.
3.  First two pages of the complete article "[A theory of regularity structures](http://www.hairer.org/papers/Structure.pdf)" by Martin Hairier, published in [Invent. Math.](http://dx.doi.org/10.1007/s00222-014-0505-4) 2014 (Hairer won the Fields Medal for this work). Also take a look at the structure of the article and Section 1 in particular and take some notes of what you notice.
4.  The section headings / table of contents in this [preprint on Langevin simulations](https://www.biorxiv.org/content/early/2018/02/16/266619), as well as the [TOC for one of my own papers](Resources/TOC.pdf).
5.  Abstract and first two sections (up to but not including "Theoretical framework", so basically up to page 3) of the article [The Predictive Validity of the GRE Across Graduate Outcomes](https://www.researchgate.net/profile/David-Feldon/publication/369412118_A_Meta-Analysis_of_Trends_Over_Time/links/641a2d4e92cfd54f841b62b5/A-Meta-Analysis-of-Trends-Over-Time.pdf) ((official article)[https://doi.org/10.1080/00221546.2023.2187177]).

### Talks:

1. (5/3)  Mu-Hua Chien, "Radiation Impacts on Hurricane-like Vortices in a Conditionally Unstable Atmosphere."

### (5/10) [Tips for better writing](Resources/Lecture-Language.handout.pdf)

We will discuss some simple tips to improve your writing style / English usage.

# Schedule changes/notes

* March 1st class is cancelled because I will be at the SIAM CSE meeting.
* March 15th is spring break so no class.
* March 29th The class on is cancelled.
* Last class will be on Wednesday May 10th.


