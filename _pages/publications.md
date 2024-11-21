---
layout: page
permalink: /publications/
title: Research
description: 
nav: true
nav_order: 4
---

This page highlights <span class="spn1">selected publications</span> and <span class="spn1">recently submitted papers (under review & revision)</span>, focusing on topics we aim to expand, generalize, or further explore. The purpose of sharing this list is primarily to foster collaboration and communication. The complete list of all papers and projects is always available upon request.

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div style="padding-top: 50px;">
  <h3 class="my-heading">Selected Publications</h3>
</div>

<div class="publications">

{% bibliography %}

</div>


<div style="padding-top: 100px;">
  <h3 class="my-heading">Recently Submitted Papers (Under Review & Revision)</h3>
</div>

<br>

<div class="publications">

<ol class="bibliography"><li>

<div class="row">
  <!-- Entry bib key -->
  <div id="lee2023understanding" class="col-sm-10">
    <!-- Title -->
    <div class="title">Understanding the Dynamics of COVID-19 Risk Perception: A Two-Year Repeated Cross-sectional Study in Korea</div>
    <!-- Author -->
    <div class="author">
    Minjung Lee, Seongoh Park, <em>Kwan-Young Bak</em>, and
    <span class="more-authors" title="click to view 5 more authors" onclick="
              var element = $(this);
              element.attr('title', '');
              var more_authors_text = element.text() == '5 more authors' ? 'Sujin Seo, Mijin Kim, Seoyeon Kim, Haemin Yong, Myoungsoon You' : '5 more authors';
              var cursorPosition = 0;
              var textAdder = setInterval(function(){
                element.html(more_authors_text.substring(0, cursorPosition + 1));
                if (++cursorPosition == more_authors_text.length){
                  clearInterval(textAdder);
                }
            }, '10');
          ">5 more authors</span>
    </div>
    <!-- Journal/Book title and date -->
    <div class="periodical">
      <em>Journal of Risk Research</em>,  2024
    </div>
  </div>
</div>

</li>
</ol>
</div>


<!--

<div style="padding-top: 50px;">
  <h3 class="my-heading">Selected Research Projects</h3>
</div>

-->
