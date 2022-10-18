---
title: Graduation Progress
permalink: graduation_progress_layout.html
sidebar: mydoc_sidebar
# tags: [special_layouts]
keywords: intimidating, threatening, unreasonable, retaliation, review
# summary: "You can use an accordion-layout that takes advantage of Bootstrap styling. This is useful for an FAQ page."
toc: false
folder: mydoc
---

<div class="panel-group" id="accordion">
    <div class="panel panel-default">
        <div class="panel-heading">
            <h4 class="panel-title">
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#disagreements-about-proposal">Disagreements about proposal (timeline, content, etc)</a>
            </h4>
        </div>
        <div id="disagreements-about-proposal" class="panel-collapse collapse noCrossRef">
            <div class="panel-body">
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
            </div>
        </div>
    </div>
    <!-- /.panel -->
    <div class="panel panel-default">
        <div class="panel-heading">
            <h4 class="panel-title">
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#disagreements-about-dissertation">Disagreements about what is required for dissertation</a>
            </h4>
        </div>
        <div id="disagreements-about-dissertation" class="panel-collapse collapse noCrossRef">
            <div class="panel-body">
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
            </div>
        </div>
    </div>
    <!-- /.panel -->
    <div class="panel panel-default">
        <div class="panel-heading">
            <h4 class="panel-title">
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#disagreements-about-graduation-date">Disagreements about graduation date</a>
            </h4>
        </div>
        <div id="disagreements-about-graduation-date" class="panel-collapse collapse noCrossRef">
            <div class="panel-body">
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
            </div>
        </div>
    </div>
    <!-- /.panel -->
    <div class="panel panel-default">
        <div class="panel-heading">
            <h4 class="panel-title">
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#disagreements-about-classes-and-performance">Disagreements about classes to take and course performance</a>
            </h4>
        </div>
        <div id="disagreements-about-classes-and-performance" class="panel-collapse collapse">
            <div class="panel-body">
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
            </div>
        </div>
    </div>
</div>

<script>
    if(location.hash !== null && location.hash !== "")
    {
        var url = location.hash.endsWith("-1") ? location.hash.substring(0, location.hash.length-2) : location.hash;
        $(url + ".collapse").collapse("show");
    }
</script>