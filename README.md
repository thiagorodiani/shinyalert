<p align="center">

<a href="https://github.com/daattali/shinyalert/">
<img src="inst/img/shinyalert-logo-whitebg.png" alt="shinyalert" width=470 height=100 />
</a>

<h3 align="center">

shinyalert

</h3>

<h4 align="center">

Easily create pretty popup messages (modals) in Shiny <br><br>
<a href="https://daattali.com/shiny/shinyalert-demo/">Demo</a> ·
Copyright 2018 <a href="https://deanattali.com">Dean Attali</a>

</h4>

<p align="center">

<a href="https://www.paypal.me/daattali/20">
<img src="https://i.imgur.com/vCIGFrH.png" alt="Donate" /> </a>
<a href="https://travis-ci.org/daattali/shinyalert">
<img src="https://travis-ci.org/daattali/shinyalert.svg?branch=master" alt="Build Status" />
</a> <a href="https://cran.r-project.org/package=shinyalert">
<img src="https://www.r-pkg.org/badges/version/shinyalert" alt="CRAN version" />
</a>

</p>

</p>

-----

`shinyalert` lets you easily create pretty popup messages (modals) in
Shiny.

A modal can contain text, images, OK/Cancel buttons, an input to get a
response from the user, and many more customizable options. The value of
the modal can be retrieved in Shiny using an input or using callback
functions. See the [demo Shiny
app](https://daattali.com/shiny/shinyalert-demo/) online for examples.

**If you find shinyalert useful, please consider supporting my efforts
developing open-source R packages\!**

<p align="center">

<a href="https://www.paypal.me/daattali/20">
<img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" />
</a>

</p>

<h2 id="samples">

Sample modals

</h2>

![basic modal](inst/img/shinyalert-basic.gif "fig:")

![input modal](inst/img/shinyalert-input.gif "fig:")

<h2 id="usage">

How to use

</h2>

In order to be able to call `shinyalert()` in a Shiny app to create
modals, you must first call `useShinyalert()` anywhere in the app's UI.

<h2 id="install">

Installation

</h2>

To install the stable CRAN version:

    install.packages("shinyalert")

To install the latest development version from GitHub:

    install.packages("devtools")
    devtools::install_github("daattali/shinyalert")