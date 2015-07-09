# I - Teaching Statistics Ergonomically

## Method #1: Interactive Visualizations
- Example #1: [How to interpret correlations?](http://rpsychologist.com/d3/correlation/)
- Example #2: [Understanding confidence intervals](http://rpsychologist.com/d3/CI/)
- Example #3: [Type I and Type II errors, β, α, p-values, power and effect sizes](http://rpsychologist.com/d3/NHST/)
- Example #4: [Playing with Fourier transform](http://bl.ocks.org/jinroh/7524988). Another example [here](http://toxicdump.org/stuff/FourierToy.swf).

Most of these visualizations are created using D3.js—a visualization library for javascript. I know a programmer who may be willing to help us with creation of this kind of visualizations.

## Method #2: Animations

Animations below are mostly from geometry (except Fourier transform, which an subject of interest for statistics), but the method of visualization is applicable to statistical concepts and formulas.

- Example #1: Circles and radians 

    ![Circles and radians](https://upload.wikimedia.org/wikipedia/commons/4/4e/Circle_radians.gif)

- Example #2: Transforming time to frequency using Fourier transform. 
    
    An advanced statistics method explained beautifully, which is a subject that is a  nightmare to understand by reading [text books](http://clokman.com/hosting/SVP-Course/2015-UvA/Materials/Misc/fourier_illing.pdf) and mathematical functions. See original web page and text [here](http://1ucasvb.tumblr.com/post/43816237610/the-fourier-transform-takes-an-input-function-f). The ideal teaching approach would be to annotate these animations with audio or text within the animations, and/or provide text below the animation for details, in a manner similar to the web original page the animation is featured on. 

    ![Fourier transform](https://upload.wikimedia.org/wikipedia/commons/5/50/Fourier_transform_time_and_frequency_domains.gif)

- Example #3: How is sine created?

    ![Sine and Cosine](https://upload.wikimedia.org/wikipedia/commons/0/08/Sine_curve_drawing_animation.gif)

- Example #4: How does sine and cosine relate to each other?

    ![Sine and Cosine](https://upload.wikimedia.org/wikipedia/commons/3/3b/Circle_cos_sin.gif)

- Example #5: Another geometry example—very similar style to Bryne's book which will be mentioned below.

    ![A geometry example](https://upload.wikimedia.org/wikipedia/commons/f/fd/Pappus_centroid_theorem_areas.gif)

If you are concerned about whether statistical concepts can be visualized this way, my answer is yes. I would be willing to personally help visualize them.

## Method #3: Visualizations

- Example: [Byrne's classical book](http://clokman.com/hosting/SVP-Course/2015-UvA/Materials/Misc/Euclid-Byrne.zip) on teaching euclides visually. 

    + I am scared of [this](http://clokman.com/hosting/SVP-Course/2014-UvA/Materials/Misc/Euclid-Casey.pdf) book; it is almost saying "you have to be really smart to read me. And you're probably not." This is encrypted knowledge.
        ![](http://clokman.com/hosting/SVP-Course/2015-UvA/Materials/Misc/book-images/casey3-2.png)

    + But I am not scared of this one (Bryne). It's beautiful and inviting (and ancient; the book is from 1850s). Hard to believe it's communicating the same knowledge with the above book.
        ![](http://clokman.com/hosting/SVP-Course/2015-UvA/Materials/Misc/book-images/bryne2.png)
        ![](http://clokman.com/hosting/SVP-Course/2015-UvA/Materials/Misc/book-images/bryne3.png)
    Bryne's book is on geometry, but his approach is compatible with what we'd be doing on statistics. Reading his foreword is highly recommended; it is very much in alignment with our vision and I find it quite inspiring (concise and highlighted version of foreword is [here](http://clokman.com/hosting/SVP-Course/2014-UvA/Materials/Misc/Intro-Byrne.pdf)).

        Bryne's book is a good example showing that everything can be visualized and made more ergonomic (including technical knowlede that would scare most people's attention away otherwise). To best of my knowlede, no one tried to make statistics as accessible this much using Bryne's approach, despite the great need. Once again, I would be willing to personally help visualize statistics in this manner.

## Method #4: Casual Language

- Example: Andy Field's Books — This guy made an attempt to make statistics a bit more fun, and sold millions of books. His method was using clear language (although I find it debatable how clear it was, it at least *tried* to avoid jargon), and humor (which I found distracting). I did not find his approach effective for me, as it was still heavily text-based and only *supposed-to-be-fun* but not really fun in my opinion. However, the popularity of his books is a good indicator of how much a lighthearted and *ergonomic* approach is needed for statistics education.   
    + [Discovering Statistics Using **SPSS** (and Sex, Drugs and Rock'n'roll) (original title)](https://books.google.nl/books/about/Discovering_Statistics_Using_SPSS.html?id=IY61Ddqnm6IC&redir_esc=y)
    + [Discovering Statistics Using **R** (and Sex, Drugs and Rock'n'roll) (original title)](https://books.google.nl/books/about/Discovering_Statistics_Using_SPSS.html?id=IY61Ddqnm6IC&redir_esc=y)

## Other Resources for Teaching Statistics
- [Laerd statistics](https://statistics.laerd.com/) - A website for comprehensive statitics information in undestandable language. 
    We may use it as an example and reasource for creating our text-based content.

---

# II - Doing Statistics Ergonomically

- [JASP](https://jasp-stats.org/) — This can be our homebrew statistics engine for our students:
    A beautifully simple and open-source stats package that is being developed by UvA. "Slimmer than SPSS, more delicious than R". The software has instant gratification and ergonomics built at it's core (the demo video below is a must watch if you have ever used SPSS, and hated it); and has a context-sensitive help panel on the left side which can be customized for educational purposes. It's open source, and as far as I know, can be run on a web server. It's team is ["very keen to support the teaching of JASP"](https://jasp-stats.org/teaching-jasp/), and therefore, would be likely to support us if we would like to implement it to our website for educational purposes.
    [Demo of JASP](https://www.youtube.com/watch?v=CVuzc08_LyY)

- [Tableau](http://get.tableau.com/trial/tableau-9-0.html?cid=70160000000YF0Q&ls=Paid%20Search&lsd=Google%20AdWords%20-%20Tableau%20-%20EMEA%20-%20Other%20-%20Free%20Trial&adgroup=Tableau%20-%20Exact&kw=tableau&adused=67742452822&distribution=search&gclid=CjwKEAjwzuisBRClgJnI4_a96zwSJACAEZKeuYOZ_65BWnMAIomEzEyLJdMw0gn4U-nQZybg9D9GlxoCIsTw_wcB):
    Polished and ergonomic stats package for business analytics. Can be repurposed for stats education.
    [Demo](https://vimeo.com/58727174)

- [Wolfram Alpha](https://www.wolframalpha.com/):
    Fast, efficient, and highly visual statistics engine for basic operations.
    [Example usage scenarios for statistics](https://www.wolframalpha.com/examples/Statistics.html)

---

Please feel free to add your own content to this document.
