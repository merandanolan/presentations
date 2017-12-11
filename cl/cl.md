<section data-background="cl/michal-lomza-338227.jpg">
<div align="right"><font color="black">

### "Leader":
####Data-Driven Works of Art

#### Hillary, Amanda, Leslie, Shawn
####shawngraham.github.io



---

** The Plan **

+ A Visualization
+ How the Visualization was Built
+ What the Visualization _Means_
+ Leadership at Carleton: A Data Driven Perspective

---
<section data-background="cl/neil-cooper-318875.jpg">

**A Website Contains _libraries_ of Information.**

**You Need a Computer to Read 'em All.**


---
<section data-background="cl/chris-barbalis-186421.jpg">
<div align="right"><font color="black">
>** Creativity is just connecting things...The broader one’s understanding of the human experience, the better - Steve Jobs **
</font></div>
<section>

---
[![A Brief Video on Topic Models](https://img.youtube.com/vi/l_oX4ua35Ec/0.jpg)](https://www.youtube.com/watch?v=l_oX4ua35Ec)

Note:
how TM works - informal description

--

![gettysburg](cl/gettysburg.png)
Find, and count, the "war" words, and the "governance" words

[then we'll go to Voyant Tools](http://voyant-tools.org/?corpus=985b82cc0fc06a1b6b43e06a21838d9f&view=Topics)


Note:
TM by hand exercise. 293 unique words

--

![ted underwood](https://tedunderwood.files.wordpress.com/2012/04/ldaformula.png)

Note:
"Suppose we knew which topic produced every word in the collection, except for this one word in document D. The word happens to be “lead,” which we’ll call word type W. How are we going to decide whether this occurrence of W belongs to topic Z?
We can’t know for sure. But one way to guess is to consider two questions. A) How often does “lead” appear in topic Z elsewhere? If “lead” often occurs in discussions of Z, then this instance of “lead” might belong to Z as well. But a word can be common in more than one topic. And we don’t want to assign “lead” to a topic about leadership if this document is mostly about heavy metal contamination. So we also need to consider B) How common is topic Z in the rest of this document?
Here’s what we’ll do. For each possible topic Z, we’ll multiply the frequency of this word type W in Z by the number of other words in document D that already belong to Z. The result will represent the probability that this word came from Z. "
-the underwear example, re bayes

--

- topics have a distribution over words
- documents have a distribution over topics
- since we don't know the number of topics, we guess
- the model uses that guess to estimate the probabilities
- you can end up with a model and estimated likelihood that its a good model

[you could do worse than to look at the Wikipedia page on LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)

Note:
mathematics of how TM works


---

![](cl/xkcd.jpg)

---

> It doesn't stop being magic just because you know how it works. - T. Pratchett

_Thank You_


---

## Photo/Art Credits

+ Paul Kidby
+ Neil Cooper, unsplash.com
+ Projekt Troia. Photographer Gebhard Bieg; with permission.
+ Chris Barbalis, unsplash.com
+ Teddy Kelley, unsplash.com
+ daoyiliu
+ xkcd