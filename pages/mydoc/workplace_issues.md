---
title: Workplace Issues
permalink: workplace_issues_layout.html
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
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#does-not-provide-disability-accomodations">Does not provide disability accomodations</a>
            </h4>
        </div>
        <div id="does-not-provide-disability-accomodations" class="panel-collapse collapse noCrossRef">
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
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#familial-constraints">Does not acknowledge parental/familial constraints</a>
            </h4>
        </div>
        <div id="familial-constraints" class="panel-collapse collapse noCrossRef">
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
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#excessive-expected-work-hours">Excessive expected work hours</a>
            </h4>
        </div>
        <div id="excessive-expected-work-hours" class="panel-collapse collapse noCrossRef">
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
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#unsafe-work-conditions">Unsafe work conditions</a>
            </h4>
        </div>
        <div id="unsafe-work-conditions" class="panel-collapse collapse noCrossRef">
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
