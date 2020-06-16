<title>website</title>                              --> <title>Horiseon: Search Engine Optimization</title>

added font white to body, removed from CSS          --> body {color: #ffffff;}

<div class="header">                                -->  <header>
<span class="seo">                                  --> <span id="seo">
header h1 .seo                                      --> #seo
header div ul                                       --> header ul
header div ul li                                    --> header li
deleted header div                                  --> css moved into header ul

<div class="hero">                                  --> <section id="hero">

<div class="content">                               --> <section id="content">

<div class="search-engine-optimization">            --> [x3] <article id="search-engine-optimization" class="content-section">
#search-engine-optimization img                     --> #content img
#search-engine-optimization h2                      --> #content h2
#search-engine-optimization                         --> .content-section
added alt="" to images

<div class="benefits">                              --> <aside id="benefits">
<div class="benefit-lead">                          --> [x3] <section class="benefit-lead">
.benefit-lead h3                                    --> [x3] #benefits h3
combined .benefit-lead img                          --> [x3] #benefits span
deleted from #benefits                              --> height: 100%;
<img src="./assets/images/lead-generation.png" />   --> [x3] <span id="lead-generation"></span>


<div class="footer">                                --> <footer>
added to match h2 style                             -->   footer span {font-weight: bold;}