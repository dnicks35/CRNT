---
title: Committee
permalink: committee_layout.html
sidebar: mydoc_sidebar
# tags: [special_layouts]
keywords: committee, thesis, proposal, advisor
# summary: "You can use an accordion-layout that takes advantage of Bootstrap styling. This is useful for an FAQ page."
toc: false
folder: mydoc
---

<div class="panel-group" id="accordion">
    <div class="panel panel-default">
        <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#disagreements-about-committee" aria-expanded="false">
            <div class="panel-heading" style="background-color:#f5f5f5;">
                <h4 class="panel-title">
                    Disagreements about thesis committee members
                </h4>
            </div>
        </a>
        <div id="disagreements-about-committee" class="panel-collapse collapse noCrossRef">
            <div class="panel-body">
		<p>You and your advisor disagree on who should and should not be on your thesis committee.</p>
                <p><b>Chain of Command for Conflict Resolution</b></p>
                   <p class="answer">For almost all conflicts that you may encounter, there is no single correct point person to address your issue. You may enter the conflict-resolution process by taking your conflict to most levels of academic administration (up to the Dean's or Provost's office); however, the university "rule of thumb" is to handle conflicts at the lowest level of administration possible. The recommended path is as follows:</p>
                    <ol type="1">
                             <li><a href="associate_chair.html">Department Associate Chair for Graduate Studies</a></li>
                             <li><a href="department_chair.html">Department Chair</a></li>
                             <li><a href="ombudsmen.html">Ombudsmen</a></li>
                    </ol>
                <p><b>Relevant Policies</b></p>
                    <p class="answer">There are many different sources of laws, policies, and codes of conduct that might apply to you as a graduate student (half employee/half student). Unfortunately GT does not have a centralized location for all their policies making them particularly hard to find. Furthermore, the university administration in place to help you resolve your conflict are not necessarily aware of relevant university or USG policies that might apply to your conflict and are almost certainly not trained in policy interpretation. Therefore, it can be important for you to know your rights and the policies in place to protect you prior to seeking administrative support resolving a conflict. The following policies have been identified as relevant to your case:</p>
                    <ul>
                             <li><a href="https://studentlife.gatech.edu/node/49">GT Graduate Student Handbook</a></li>
                    </ul>
            </div>
        </div>
    </div>
    <!-- /.panel -->
    <div class="panel panel-default">
        <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#disagreements-about-proposal" aria-expanded="false">
            <div class="panel-heading" style="background-color:#f5f5f5;">
                <h4 class="panel-title">
                    Disagreements about proposal (timeline, content, etc.)
                </h4>
            </div>
        </a>
        <div id="disagreements-about-proposal" class="panel-collapse collapse noCrossRef">
            <div class="panel-body">
		<p>You and your committee member(s) disagree on the proposed timeline and research deliverables.</p>
                <p><b>Chain of Command for Conflict Resolution</b></p>
                   <p class="answer">For almost all conflicts that you may encounter, there is no single correct point person to address your issue. You may enter the conflict-resolution process by taking your conflict to most levels of academic administration (up to the Dean's or Provost's office); however, the university "rule of thumb" is to handle conflicts at the lowest level of administration possible. The recommended path is as follows:</p>
                    <ol type="1">
                             <li><a href="thesis_committee.html">Thesis Committee</a></li>
                             <li><a href="associate_chair.html">Department Associate Chair for Graduate Studies</a></li>
                             <li><a href="department_chair.html">Department Chair</a></li>
                             <li><a href="ombudsmen.html">Ombudsmen</a></li>
                    </ol>
                <p><b>Relevant Policies</b></p>
                    <p class="answer">There are many different sources of laws, policies, and codes of conduct that might apply to you as a graduate student (half employee/half student). Unfortunately GT does not have a centralized location for all their policies making them particularly hard to find. Furthermore, the university administration in place to help you resolve your conflict are not necessarily aware of relevant university or USG policies that might apply to your conflict and are almost certainly not trained in policy interpretation. Therefore, it can be important for you to know your rights and the policies in place to protect you prior to seeking administrative support resolving a conflict. The following policies have been identified as relevant to your case:</p>
                    <ul>
                             <li><a href="https://policylibrary.gatech.edu/student-life/satisfactory-academic-progress">GT Satisfactory Academic Progress</a></li>
                    </ul>
            </div>
        </div>
    </div>
    <!-- /.panel -->
    <div class="panel panel-default">
        <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#disagreements-about-dissertation" aria-expanded="false">
            <div class="panel-heading" style="background-color:#f5f5f5;">
                <h4 class="panel-title">
                    Disagreements about what is required for dissertation
                </h4>
            </div>
        </a>
        <div id="disagreements-about-dissertation" class="panel-collapse collapse noCrossRef">
            <div class="panel-body">
		<p>You and your committee member(s) have different opinions about what amount of work is adequate for your dissertation.</p>
                <p><b>Chain of Command for Conflict Resolution</b></p>
                   <p class="answer">For almost all conflicts that you may encounter, there is no single correct point person to address your issue. You may enter the conflict-resolution process by taking your conflict to most levels of academic administration (up to the Dean's or Provost's office); however, the university "rule of thumb" is to handle conflicts at the lowest level of administration possible. The recommended path is as follows:</p>
                    <ol type="1">
                             <li><a href="thesis_committee.html">Thesis Committee</a></li>
                             <li><a href="associate_chair.html">Department Associate Chair for Graduate Studies</a></li>
                             <li><a href="department_chair.html">Department Chair</a></li>
                             <li><a href="ombudsmen.html">Ombudsmen</a></li>
                    </ol>
                <p><b>Relevant Policies</b></p>
                    <p class="answer">There are many different sources of laws, policies, and codes of conduct that might apply to you as a graduate student (half employee/half student). Unfortunately GT does not have a centralized location for all their policies making them particularly hard to find. Furthermore, the university administration in place to help you resolve your conflict are not necessarily aware of relevant university or USG policies that might apply to your conflict and are almost certainly not trained in policy interpretation. Therefore, it can be important for you to know your rights and the policies in place to protect you prior to seeking administrative support resolving a conflict. The following policies have been identified as relevant to your case:</p>
                    <ul>
                             <li><a href="https://studentlife.gatech.edu/node/49">GT Graduate Student Handbook</a></li>
                    </ul>
            </div>
        </div>
    </div>
</div>

<script>
    if(location.hash !== null && location.hash !== "")
    {
        var url = location.hash.endsWith("-1") ? location.hash.substring(0, location.hash.length-2) : location.hash;
        $(url + ".collapse").collapse("show");
        var doc = document.getElementById(url.replace("#", "")).parentElement.parentElement;
        let position = doc.getBoundingClientRect();
        setTimeout(function () {
            window.scrollTo(position.left, position.top + window.scrollY - 400);
            },
        100);
    }

    $(window).on("click", function(e) {
        if(e.target.className.trim() == 'panel-title')
        {
            navigator.clipboard.writeText(e.target.childNodes[1].href);
            if(e.target.parentElement.parentElement.nextElementSibling.classList.contains("collapsed"))
                e.target.parentElement.parentElement.nextElementSibling.click();
        }

        else if(e.target.className.trim() == 'anchorjs-link')
        {
            console.log(e);
            navigator.clipboard.writeText(e.target.href);
            if(e.target.parentElement.parentElement.parentElement.nextElementSibling.classList.contains("collapsed"))
                e.target.parentElement.parentElement.parentElement.nextElementSibling.click();
        }
    });
</script>
