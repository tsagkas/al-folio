---
layout: about
title: about
permalink: /
subtitle: PhD candidate @ <a href="http://web.inf.ed.ac.uk/ipab" target="_blank">University of Edinburgh</a>, <a href="https://www.edinburgh-robotics.org/" target="_blank">Edinburgh Centre for Robotics</a>
navigation_weight: 10
profile:
  align: right
  image: prof_pic_2.JPG
  address: >
    <p>Informatics Forum,</p>
    <p>10 Crichton Street,</p>
    <p>Edinburgh, EH8 9AB</p>

news: true  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---
<h2>about me</h2>
I am a PhD candidate, at the [MAPS Lab](https://maps-lab.github.io/) and the [School of Informatics - University of Edinburgh](http://web.inf.ed.ac.uk/ipab), sponsored by the [Edinburgh Centre for Robotics](https://www.edinburgh-robotics.org/), under the supervision of [Prof. Chris Xiaoxuan Lu](https://christopherlu.github.io/) and [Prof. Oisin Mac Aodha](https://homepages.inf.ed.ac.uk/omacaod/). My research objective is to ground language into neural implicit spatial representations, for the purpose of enabling open vocabulary queries in mobile robotics.  

In November 2021, I completed with distinction the Artificial Intelligence master's programme at the University of Edinburgh, where I worked under the supervision of [Prof. Chris Williams](https://homepages.inf.ed.ac.uk/ckiw/) on a novel inference and learning algorithm for [generative capsule models](https://github.com/tsagkas/capsules). In August 2019, I was awarded the Diploma of Electrical and Computer Engineering from the University of Patras, in Greece (graduated 4th in my class out of 202 students – GPA: 8.11 out of 10). I completed my ECE Diploma thesis under the supervision of [Prof. Athanassios Skodras](http://www.ece.upatras.gr/skodras/), researching the use of CNNs for [real-time hand-gesture recognition](/projects/2_project/) via sEMG signals.

<!-- In November 2021, I completed with distinction the **Artificial Intelligence master's programme** at the University of Edinburgh. For my master's dissertation project I worked on a novel inference and learning algorithm for [generative capsule models](https://github.com/tsagkas/capsules), under the supervision of [Prof. Chris Williams](https://homepages.inf.ed.ac.uk/ckiw/).

In 2019, I was awarded the **Diploma of Electrical and Computer Engineering**, from the University of Patras, in Greece (graduated 4th in my class out of 202 students – GPA: 8.11 out of 10). I completed my ECE Diploma thesis under the supervision of [Prof. Athanassios Skodras](http://www.ece.upatras.gr/skodras/), researching the use of CNNs for [real-time hand-gesture recognition](/projects/2_project/) via sEMG signals. Our work was presented at the IISA'19 international conference. 

Moreover, working under the supervision of [Prof. Konstantinos Moustakas](http://www.vvr.ece.upatras.gr/members/konstantinos-moustakas/) at the [VVR group](http://www.vvr.ece.upatras.gr/), I researched the use of Haptics in self-driving vehicles, by taking part in the 2nd Student Challenge in Automotive Haptics, at the [WHC'19](http://www.worldhaptics2019.org/) in Tokyo, Japan, where our team received the "Best Student Innovation Challenge Award". -->

<!-- <details>
    <summary>Read more..</summary>
    Foldable Content[enter image description here][1]
</details> -->
<div class="news">

  {% if site.news != blank -%} 
  <div class="table-responsive">
    <h2>news</h2>
    <table class="table table-sm table-borderless">
    {%- assign news = site.news | reverse -%} 
    {% for item in news limit: site.news_limit %} 
      <tr>
        <th scope="row">{{ item.date | date: "%b %-d, %Y" }}</th>
        <td>
          {% if item.inline -%} 
            {{ item.content | remove: '<p>' | remove: '</p>' | emojify }}
          {%- else -%} 
            <a class="news-title" href="{{ item.url | relative_url }}">{{ item.title }}</a>
          {%- endif %} 
        </td>
      </tr>
    {%- endfor %} 
    </table>
  </div>
{%- else -%} 
  <p>No news so far...</p>
{%- endif %} 
</div>

<h2>recent projects</h2>
<div class='row vspace-top'>
  <div class="col-sm-3">
      <img src='../assets/img/thumbnails/vl-fields_3.png' class='img-fluid'>
  </div>
  <div class="col">
    <div class='paper-title'>
        VL-Fields: Towards Language-Grounded Neural Implicit Spatial Representations
    </div>
    <div class='paper-desc'>
        <b><span style="background-color: green;">Spotlight Talk + Poster</span></b>: <i>Workshop on Effective Representations, Abstractions, and Priors for Robot Learning - ICRA 2023</i> 
    </div>
    <div>
    </div>
    <div class='paper-authors'>
        <b>Nikolaos Tsagkas</b>, Oisin Mac Aodha, Chris Xiaoxuan Lu
    </div>
    <div>
      <a href="../vl-fields/">[Project Page]</a>  
      <a href="https://arxiv.org/abs/2305.12427">[Paper]</a>  
    </div>
  </div>
</div>
<br/>

<!-- <div class='row vspace-top'>
  <div class="col-sm-3">
      <img src='../assets/img/9.jpg' class='img-fluid'>
  </div>

  <div class="col">
    <div class='paper-title'>
        Incremental Abstraction in Distributed Probabilistic SLAM Graphs https://tsagkas.github.io/vl-fields/
    </div>
    <div class='paper-desc'>
        ICRA 2022
    </div>
    <div class='paper-authors'>
        <b>Joseph Ortiz</b>, Talfan Evans, Edgar Sucar, Andrew J. Davison
    </div>
    <div>
      <a href="../vl-fields/">[Project Page]</a>  
      <a href="https://arxiv.org/abs/2109.06241">[Paper]</a>  
      <a href="https://www.youtube.com/watch?v=ZoJ9ylb4Ss8">[Video]</a>
    </div>
  </div>
</div>
<br /> -->