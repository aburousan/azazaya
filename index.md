@def title = "Azazaya"
@def tags = ["syntax", "code"]

# Idea behind this website
**Mathematics** and **Physics**... this two are really something I enjoy. Eachtime I read something of maths or physics, It really force me to think how beautiful and elegant things are. How can something born from our mind can describe this world!!...\\
This fascination force me to always try to find patterns and beauty in the theories. Through this website, I want to show others how beautiful these are.
Visit
* [Physics Main Page](/Pages/Physics/Physics_Home/)
* [Mathematics Main Page](/Pages/Maths//Maths_Home/)
for more info.

Hi!!... I am **Kazi Abu Rousan**, a student of [Indian Association for The Cultivation of Science](https://en.wikipedia.org/wiki/Indian_Association_for_the_Cultivation_of_Science), doing my master's degree in Physics. I also teaches Maths and Physics for olympiad in [Cheenta Ganit Kendra](https://www.cheenta.com/).
~~~
<img src="/assets/me.jpeg" alt="It's a me! Rousan" width="500">
<div class="caption">It's a me! Rousan. If someone has some crush do let me know</div>
~~~

Ohh and here is my catto! Mr. **Gino**!
~~~
<img src="/assets/gino.png" alt="It's Gino" width="500">
~~~
# Some of my Works
I have written few articles all over web. Some of them are,
* [What is Fourier Series? and It's Beauty](https://medium.com/swlh/what-is-fourier-series-and-its-beauty-ce2410012329). You can also watch a [video](https://youtu.be/0y8UsIFcvPs) on this.
![Joaquin Phoenix Joker using 6000 epicycles](https://miro.medium.com/v2/resize:fit:720/format:webp/1*YkraGeZW9la2P7sDetBpFQ.png)
* [Trapezoidal Rule: A Method of Numerical Integration](https://www.cantorsparadise.com/trapezoidal-rule-a-method-of-numerical-integration-5772838657b3)
![](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*2jcjgSAw_qoimpVm_2JNrg.png)

* [Introduction to Anyons and Generalized Distribution Function](https://www.researchgate.net/publication/352641643_Introduction_to_Anyons_and_generalized_distribution_function)
![](https://www.researchgate.net/profile/Kazi-Abu-Rousan/publication/352641643/figure/fig3/AS:1040709511565313@1625135891075/The-reflection-operation-with-respect-to-one-axis-This-shows-ph-p-and-ph-p-are.ppm)
* [Extension of Gauss circle problem: Lattices for a Triangular grid and discovery of a new formula of $\pi$](https://www.researchgate.net/publication/370161335_Extension_of_Gauss_circle_problem_Lattices_for_a_Triangular_grid)
![](https://www.researchgate.net/profile/Kazi-Abu-Rousan/publication/370161335/figure/fig3/AS:11431281152663383@1682100177142/A-circle-of-Radius-7-has-18-lattice-points-on-it_Q320.jpg)

* [Diffraction patterns by different orientation of rectangular Apertures: Intuitive understanding of Optical Transformations](https://www.researchgate.net/publication/356142815_Diffraction_patterns_by_different_orientation_of_rectangular_Apertures_Intuitive_understanding_of_Optical_Transformations)
![](https://www.researchgate.net/profile/Kazi-Abu-Rousan/publication/356142815/figure/fig2/AS:1098551824265217@1638926573534/Diffraction-pattern-of-the-aperture-in-Fig-2.ppm)

* I have recently been a mentor for a Summer School of Astrophysics. For more see [here](https://sites.google.com/view/intro-2-astro/2023-course).\\
To access notes and assignment visit [here](https://github.com/howardisaacson/Intro-to-Astro2023/tree/main/Week2_packages_plotting) (The ones on matplotlib and numpy, Scipy and Astropy are made by me).
* I am writing a book on [Number Theory](https://www.researchgate.net/project/Number-Theory-with-Python). You can check the draft.
~~~
<img src="/assets/book.jpg" alt="My Book" width="400">
~~~

For more visit my Social Accounts
*
~~~
<a href="https://twitter.com/AustinRousan?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-show-count="false">Follow @AustinRousan</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
~~~

* [LinkedIn](https://www.linkedin.com/in/kazi-abu-rousan-819848198/)
* [Instragram](https://www.instagram.com/azavzya/)
* [Facebook](https://www.facebook.com/K.A.Rousan/)

<!-- We notice what happens in real world, we study things and then we try to find what are the rules this whole world follows.
This is what ~~~
<span style="color:purple;font-weight:700">
    PHYSICS
</span>
~~~really is!

This section is meant as a refresher if you're new to Franklin.
Have a look at both how the website renders and the corresponding markdown (`index.md`).
Modify at will to get a feeling for how things work!

Ps: if you want to modify the header or footer or the general look of the website, adjust the files in
* `src/_css/` and
* `src/_html_parts/`.

## The base with Markdown

The [standard markdown syntax](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) can be used such as titles using `#`, lists:

* element with **bold**
* element with _emph_

or code-blocks `inline` or with highlighting (note the `@def hascode = true` in the source to allow [highlight.js](https://highlightjs.org/) to do its job):

```julia
abstract type Point end
struct PointR2{T<:Real} <: Point
    x::T
    y::T
end
struct PointR3{T<:Real} <: Point
    x::T
    y::T
    z::T
end
function len(p::T) where T<:Point
  sqrt(sum(getfield(p, η)^2 for η ∈ fieldnames(T)))
end
```

You can also quote stuff

> You must have chaos within you to ...

or have tables:

| English         | Mandarin   |
| --------------- | ---------- |
| winnie the pooh | 维尼熊      |

Note that you may have to do a bit of CSS-styling to get these elements to look the way you want them (the same holds for the whole page in fact).

### Symbols and html entities

If you want a dollar sign you have to escape it like so: \$, you can also use html entities like so: &rarr; or &pi; or, if you're using Juno for instance, you can use `\pi[TAB]` to insert the symbol as is: π (it will be converted to a html entity).[^1]

If you want to show a backslash, just use it like so: \ ; if you want to force a line break, use a ` \\ ` like \\ so (this is on a new line).[^blah]

If you want to show a backtick, escape it like so: \` and if you want to show a tick in inline code use double backticks like ``so ` ...``.

Footnotes are nice too:

[^1]: this is the text for the first footnote, you can style all this looking at `.fndef` elements; note that the whole footnote definition is _expected to be on the same line_.
[^blah]: and this is a longer footnote with some blah from veggie ipsum: turnip greens yarrow ricebean rutabaga endive cauliflower sea lettuce kohlrabi amaranth water spinach avocado daikon napa cabbage asparagus winter purslane kale. Celery potato scallion desert raisin horseradish spinach carrot soko.

## Basic Franklin extensions

### Divs

It is sometimes useful to have a short way to make a part of the page belong to a div so that it can be styled separately.
You can do this easily with Franklin by using `@@divname ... @@`.
For instance, you could want a blue background behind some text.

@@colbox-blue
Here we go! (this is styled in the css sheet with name "colbox-blue").
@@

Since it's just a `<div>` block, you can put this construction wherever you like and locally style your text.

### LaTeX and Maths

Essentially three things are imitated from LaTeX

1. you can introduce definitions using `\newcommand`
1. you can use hyper-references with `\eqref`, `\cite`, ...
1. you can show nice maths (via KaTeX)

The definitions can be introduced in the page or in the `config.md` (in which case they're available everywhere as opposed to just in that page).
For instance, the commands `\scal` and `\R` are defined in the config file (see `src/config.md`) and can directly be used whereas the command `\E` is defined below (and therefore only available on this page):

\newcommand{\E}[1]{\mathbb E\left[#1\right]}

Now we can write something like

$$  \varphi(\E{X}) \le \E{\varphi(X)}. \label{equation blah} $$

since we've given it the label `\label{equation blah}`, we can refer it like so: \eqref{equation blah} which can be convenient for pages that are math-heavy.

In a similar vein you can cite references that would be at the bottom of the page: \citep{noether15, bezanson17}.

**Note**: the LaTeX commands you define can also incorporate standard markdown (though not in a math environment) so for instance let's define a silly `\bolditalic` command.

\newcommand{\bolditalic}[1]{_**!#1**_} <!--_ ignore this comment, it helps atom to not get confused by the trailing underscore when highlighting the code but is not necessary.-->

<!-- and use it \bolditalic{here for example}. -->

<!-- Here's another quick one, a command to change the color: -->

<!-- \newcommand{\col}[2]{~~~<span style="color:~~~#1~~~">~~~!#2~~~</span>~~~} -->

<!-- This is \col{blue}{in blue} or \col{#bf37bc}{in #bf37bc}. -->

<!-- ### A quick note on whitespaces -->

<!-- For most commands you will use `#k` to refer to the $k$-th argument as in LaTeX. -->
<!-- In order to reduce headaches, this forcibly introduces a whitespace on the left of whatever is inserted which, usually, changes nothing visible (e.g. in a math settings). -->
<!-- However there _may be_ situations where you do not want this to happen and you know that the insertion will not clash with anything else. -->
<!-- In that case, you should simply use `!#k` which will not introduce that whitespace. -->
<!-- It's probably easier to see this in action: -->

<!-- \newcommand{\pathwith}[1]{`/usr/local/bin/#1`} -->
<!-- \newcommand{\pathwithout}[1]{`/usr/local/bin/!#1`} -->

<!-- * with: \pathwith{script.jl}, there's a whitespace you don't want 🚫 -->
<!-- * without: \pathwithout{script.jl} here there isn't ✅ -->

<!-- ### Raw HTML -->

<!-- You can include raw HTML by just surrounding a block with `~~~`. -->
<!-- Not much more to add. -->
<!-- This may be useful for local custom layouts like having a photo next to a text in a specific way. -->

<!-- ~~~
<div class="row">
  <div class="container">
    <img class="left" src="/assets/rndimg.jpg">
    <p>
    Marine iguanas are truly splendid creatures. They're found on the Gálapagos islands, have skin that basically acts as a solar panel, can swim and may have the ability to adapt their body size depending on whether there's food or not.
    </p>
    <p>
    Evolution is cool.
    </p>
    <div style="clear: both"></div>      
  </div>
</div>
~~~ -->

<!-- **Note 1**: again, entire such blocks can be made into latex-like commands via `\newcommand{\mynewblock}[1]{...}`. -->

<!-- **Note 2**: whatever is in a raw HTML block is *not* further processed (so you can't have LaTeX in there for instance). A partial way around this is to use `@@...` blocks which *will* be recursively parsed. The following code gives the same result as above with the small difference that there is LaTeX being processed in the inner div. -->

<!-- @@row
@@container
@@left ![](/assets/rndimg.jpg) @@
@@
Marine iguanas are **truly splendid** creatures. They're not found in equations like $\exp(-i\pi)+1$. But they're still quite cool.
~~~
<div style="clear: both"></div>
~~~
@@ -->

<!-- ## Pages and structure -->

<!-- Here are a few empty pages connecting to the menu links to show where files can go and the resulting paths. (It's probably best if you look at the source folder for this). -->

<!-- * [menu 1](/Pages/Physics/Physics_Home/)
* [menu 2](/Pages/Maths//Maths_Home/)
* [menu 3](/menu3/)
home/rousan/Coding/Julia/Project/Website/azazaya/Pages/Physics
## References (not really) -->

<!-- * \biblabel{noether15}{Noether (1915)} **Noether**,  Körper und Systeme rationaler Funktionen, 1915.
* \biblabel{bezanson17}{Bezanson et al. (2017)} **Bezanson**, **Edelman**, **Karpinski** and **Shah**, [Julia: a fresh approach to numerical computing](https://julialang.org/research/julia-fresh-approach-BEKS.pdf), SIAM review 2017. -->

<!-- ## Header and Footer -->

<!-- As you can see here at the bottom of the page, there is a footer which you may want on all pages but for instance you may want the date of last modification to be displayed.
In a fashion heavily inspired by [Hugo](https://gohugo.io), you can write things like -->

<!-- ```html
Last modified: {{ fill fd_mtime }}.
``` -->

<!-- (cf. `src/_html_parts/page_foot.html`) which will then replace these braces with the content of a dictionary of variables at the key `fd_mtime`.
This dictionary of variables is accessed locally by pages through `@def varname = value` and globally through the `config.md` page via the same syntax. -->

<!-- There's a few other such functions of the form `{{fname p₁ p₂}}` as well as support for conditional blocks. If you wander through the `src/_html_parts/` folder and its content, you should be able to see those in action. -->
