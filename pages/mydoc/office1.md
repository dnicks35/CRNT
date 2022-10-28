---
title: Research Advisor
permalink: ResearchAdvisor.html
sidebar: mydoc_sidebar
# tags: [special_layouts]
# summary: "You can use an accordion-layout that takes advantage of Bootstrap styling. This is useful for an FAQ page."
toc: false
folder: mydoc
---

<p><b>Is there a policy against this?</b></p>
   <p class="answer">YES - Policy XYZ</p>
<p><b>Who should I contact about this issue?</b></p>
   <p class="answer">Contact person</p>
<p><b>What is the typical pathway towards conflict resolution?</b></p>
   <ul>
        <li>Step 1</li>
        <li>Step 2</li>
   </ul>
<p><b>What is the typical outcome?</b></p>
   <p class="answer">Outcome will go here</p>
<p><b>How long will this take to get resolved?</b></p>
   <p class="answer">1-2 months</p>
<p><b>Was this accurate to your experience? </b></p>


<script>
    if(location.hash !== null && location.hash !== "")
    {
        var url = location.hash.endsWith("-1") ? location.hash.substring(0, location.hash.length-2) : location.hash;
        $(url + ".collapse").collapse("show");
    }
</script>