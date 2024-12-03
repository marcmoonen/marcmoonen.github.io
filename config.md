<!--
Add here global page variables to use throughout your website.
-->
@def author = "Marc Moonen"
@def website_title = "Marc Moonen Signal Processing Society Presidential Candidacy"
@def website_descr = "Marc Moonen Signal Processing Society Presidential Candidacy"
@def website_url   = "https://marcmoonen.github.io/"
@def prepath = ""

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
\newcommand{\figenv}[3]{
    ~~~
    <figure style="text-align:center;">
        <img src="!#2" style="padding:0;#3" alt="#1"/>
        <figcaption style="display: table-caption; caption-side: right;">
            #1
        </figcaption>
    </figure>
    ~~~
}

