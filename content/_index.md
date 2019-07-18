+++
title = "Ethan S. Young, Ph.D."
description = "Postdoctoral Researcher at Radboud University - Nijmegen, Netherlands "
draft = false
+++ 

<nav data-component="tabs" data-live=".tab-live" id="livetabs" class = "text-center" style="margin: 0 10%;">
  <ul>
    <li class = "big"><a href="#AboutEthan" class="collapse-toggle large text-center ">About Ethan</a></li>
    <li class = "big"><a href="#AboutThisSite" class="collapse-toggle large text-center">About this Site</a></li>
    <li class = "big"><a href="#Navigation" class="collapse-toggle large text-center">Navigating this site</a></li>
  </ul>
</nav>

  <div data-title="About Ethan" class="tab-live" id="AboutEthan">

<br>

I am currently a postdoctoral researcher in the Behavioral Science Institute at Radboud University in The Netherlends. My main research interest is developmental plasticity, or the capacity for the individual to detect and adapt the phenotype to various ecological conditions across development. More specifically, my work explores if and how various cognitive functions, such as executive functions, working memory, learning, and attention, might be shaped and potentially enhanced by growing up in harsh and unpredictable environments.

Another focus of mine is reproducibility and open science practices. I use <a href="https://cran.rstudio.com/" target="_blank">R</a> and <a href = "http://www.rstudio.com/" target="_blank">Rstudio</a> to create reproducible analyses, figures, and reports in hopes to increase transparency and enhance collaboration. I am particularly interested in developing workflows that make every step of the research 100% reproducible, from data collection to publication. This involves using open source software for data collection, such as <a href = "http://www.jspsych.org/" target="_blank">jsPsych</a>, and leveraging <a href="https://cran.rstudio.com/" target="_blank">R</a> and <a href="http://rmarkdown.rstudio.com/" target="_blank">R markdown</a> to clean, analyze, and report on results. On this site, I share some of my techniques and insights from my own experience developing such workflows.

  </div>

  <div data-title="About this Site" class="tab-live" id="AboutThisSite">

<br>

I built this site because I wanted a semi-permanent place to store my publications, work, research tools, and thoughts. First, a frequently updated version of my <a href="/cv/">CV</a> can be found here.  For my work, I created a <a href="/research/">research</a> and <a href="/projects/">projects</a> repository (under construction) that contains descriptions of my broad research goals by topic and (whenever I can) code and data associated with my specific projects. The big idea behind this site is to create a home for all of my research and to use it to organize and document what I have done and when I did it. Hopefully, this will provide a high resolution map of my work and orgainizing it many different ways will help me determine where I should go next.

In my <a href="/posts/">posts</a> section, I document some of tools that I create and code that I write in R and occasionally post case-studies that use them. These are mostly for my own memory and it's nice to have them in one location. Finally, I also use the posts section to write out my thoughts on various topics.

<b>Note:</b> This site was built using <a href="https://gohugo.io" target="_blank">Hugo</a> and <a href="https://bookdown.org/yihui/blogdown" target="_blank">blogdown</a> using the theme <a href="https://themes.gohugo.io/kube/" target="_blank">Kube</a>. I adapted the theme to my taste and update it using <a href="https://cran.rstudio.com/" target="_blank">R</a> and <a href = "http://www.rstudio.com/" target="_blank">Rstudio</a>. The source code for the site can be found on <a href="https://github.com/ethan-young/website" target="_blank">github</a>.

  </div>
  
  <div data-title="Structure & Content" class="tab-live" id="Navigation">

<br>

  <div id="kube-features" style = "margin: 0; padding: 0; border: none;">
    <div class="row gutters text-left" style="border: none; margin: 0;">
      <div class="col col-4 item" style="border: none">
        <h5><a href="/research/">Research Areas</a></h5>
        <p>An obvous way to organize my research is by research topic. Go to the reseach section to view my work sorted by broad topics.</p>
      </div>
      <div class="col col-4 item text-left" style="border: none">
        <h5><a href="/projects/">Projects</a></h5>
        <p>I'm always working on a number of specific projects and I've associated much of the content on this site with a particular project. The projects section lists pages by project.</p>
      </div>
      <div class="col col-4 item text-left" style="border: none">
        <h5><a href="/posts/">Posts</a></h5>
        <p>I've learned that many (most) things don't fit very neatly into predefined boxes or categories. The posts section of this site is a "miscellaneous" box for things that may or may not wind up being helpful.</p>
      </div>
    </div>
    <div class="row gutters text-left" style="border: none;">
      <div class="col col-4 item" style="border: none">
        <h5><a href="/tags/">Tags</a></h5>
        <p> I try to add tags that help group related pages together. Tagging content adds an element of flexible organization and, over time, can organically create useful structure and organization. </p>
      </div>
      <div class="col col-4 item text-left" style="border: none">
        <h5><a href="/archive/">Archive</a></h5>
        <p>In addition to projects and tags, I made a point to chronologically organize my work to see how it evolves over time. The section lists out my work across time for a historical perspectve the development of my research and thinking.</p>
      </div>
      <div class="col col-4 item text-left" style="border: none">
        <h5><a href="#search-by">Search!</a></h5>
        <p>There's a search bar at the top of the page. Use it to search for keywords across all the pages on this site.</p>
    </div>
  </div>
</div>

  </div>

<style>
#livetabs a {
  color: #000;
  text-decoration: none;
  background: white;
  border-radius: 0px;
  padding: 0;
  border: 4px none black; 
  text-align:center;
}
#livetabs a:hover {
    color: #3794de;
    border-bottom-color: #3794de;
    opacity: .7;
}
#livetabs li.active a {
  background: #fff;
  border-color: white white #eee white;
  color: #3794de;
  border-bottom-color: #3794de;
  cursor: default; 
}
  #livetabs li.active a:hover {
    opacity: 1;
}
#livetabs > ul > li{
  margin: auto;
  padding: 0px 10px;
  font-size: 18px;
  border-bottom: 2px solid black;
}
#livetabs > ul > li.active{
  border-bottom-color: #3794de;
}
#livetabs > ul > li:hover{
  border-bottom-color: #3794de;
}
.my-collapse h4 {
  background: white;
  padding: 8px 16px;
  margin: 1px 25% 0 25%;
  font-size: 15px;
  line-height: 24px;
  border-left: none;
  border-right: none;
}
.my-collapse div {
  border: 1px none rgba(0, 0, 0, 0.1);
  padding: 24px 32px 24px;
  margin-bottom: 0;
}
.my-collapse h4 a{
  color: white;
}
</style>