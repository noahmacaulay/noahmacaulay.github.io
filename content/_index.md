+++
title = "Noah's Website"
+++

![Picture of me at a race](racepic.jpeg)

Hi, I'm Noah MacAulay, welcome to my website. I'm a computer science doctoral student at [Dalhousie University](https://www.dal.ca/). My main area of research is the theory of deep learning, but I'm also interested in algebraic and scientific computing, as well as mathematics. This site contains various projects I've worked on.



## The Kolakoski Sequence

There is a somewhat famous sequence of 1s and 2s known as the *Kolakoski Sequence*. It begins as follows:

1, 2, 2, 1, 1, 2, 1, 2, 2, 1, 2, 2, 1, 1, 2, 1, 1, 2, 2, 1, 2, 1, 1, ...

See the pattern? Working it out is a fun puzzle. The answer is {{spoiler(id= "The sequence is equal to its own run-length encoding. That is, the sequence begins with a 1 one, then 2 twos, then 2 ones, then 1 one, then 1 two. The sequence of block lengths goes 1, 2, 2, 1, 1, ... and is equal to the sequence itself. The Kolakoski sequence is the unique sequence of 1s and 2s that has this property starting with 1. Try extending it!")}}

Despite the simple definition, mathematicians have been stumped about various properties of this sequence for years. For instance: in the limit, is the proportion of 1s equal to the proportion of 2s? Does every finite substring of the sequence get repeated infinitely many times? Nobody knows.

It turns out that you can view the sequence as being output by an infinite family of automata. People have used this to derive various properties, such as [bounding the density of 1s to within \[0.499, 0.501\]](https://users.encs.concordia.ca/~chvatal/93-84.pdf).

Unfortunately, in full generality, the automata seem no easier to understand than the sequence itself. However! All the automata are invertible, which means they have an associated transformation group, and it turns out these groups *are* possible to understand, although the analysis is somewhat complex. I wrote a preprint about the groups here: [Group Theory of the Kolakoski Sequence](https://arxiv.org/abs/2605.14234). Here's an image of a group element:

![Kolakoski Group Image](tree.png)

Now in theory you could use the understanding of the groups to go back and try to understand the sequence of numbers, but I didn't get around to that part. I've written a small [document](/how-to-prove.pdf) outlining some strategies I thought of. If anyone reading this is interested in trying to do this, feel free to contact me.

## Miscellanaeous

![Heisenberg group image](heisenberg-slice.PNG)

* I wrote [a paper](random-projections-pac-bayes.pdf) proving non-vacuous generalization bounds for MNIST by randomly projecting to a low-dimensional subspace and bounding the KL divergence with a Gaussian there. At the time they were the best bounds known. I don't really consider this a promising line of research now, however.

* There was an [open question in computational geometry](https://mathoverflow.net/questions/156344/blocking-light-with-mirrored-convex-objects) called the 'Enchanted Forest problem': is it possible to trap all the light from a point source with circular mirrors? I realized it was basically a trivial corollary of results in chaotic billiards from the 60s and [wrote this up](forest.pdf)(the answer is no).

* In 2024 I spent a bunch of time trying to understand a bijection between different types of trees and made [this website](trees.html) to illustrate it.

* I semi-won the [2013 Lyttle Lytton contest](https://adamcadre.ac/lyttle/2013.html) for fictitious bad novel openings.

* Some [old](ghost.html) [fiction](pretending.html) from high school and undergrad.

* [Cool](H1.PNG) [pictures](H2.PNG) of [balls](H3.PNG) in the Heisenberg group.


# Contact

I can be reached at nh414938 \[at\] dal dot ca. I also have a non-institutional email at usernameneeded \[at\] gmail dot com.