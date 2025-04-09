---
layout: "page"
urltitle: "Accepted Papers"
title: Accepted Papers
categories: accepted papers
permalink: /accepted/
---

<style>
  .abstract-toggle {
    cursor: pointer;
    color: #0056b3; /* Or your link color */
    text-decoration: none;
    font-size: 0.9em;
    margin-left: 15px;
    /* white-space: nowrap; /* Prevent breaking */ */
  }
  .abstract-toggle:hover {
    text-decoration: underline;
  }
  .abstract-content {
    display: none; /* Hide abstract by default */
    margin-top: 0.75em;
    padding: 0.8em 1em;
    background-color: #f7f7f7; /* Light background for abstract */
    border-left: 4px solid #ccc; /* Accent border */
    font-size: 0.95em;
    line-height: 1.6;
  }
  /* Optional: Style for the whole submission item block */
  .submission-block {
    margin-bottom: 2em;
    padding-bottom: 1em;
    border-bottom: 1px solid #eee;
  }
  .submission-block:last-child {
    border-bottom: none;
  }
</style>



<div class="row reverse pt-16">
  <div class="col-xs-12" style="padding-top: 40px;">

    <h2>
        We are grateful for the numerous submissions received for the 2nd Workshop on Navigating and Addressing Data Problems for Foundation Models (DATA-FM @ ICLR 2025). We thank all the authors who submited to our workshop. We are happy to announce this year's accepted papers.



      <br>
      <br>


    </h2>
  </div>

<h1>Oral</h1>
    <br>

   
    <div class="submission-block">
    {% for item in site.data.papers %}
        {% if item.decision == "Accept (Oral)" %}
            <h3>{{ item.title  }}<br>
            <a href="{{ item.link  }}" target="_blank"> OpenReview </a>
            <a class="abstract-toggle" onclick="toggleAbstract('{{ item.link  }}', this)">[Show Abstract]</a>

            <div id="{{ item.link  }}" class="abstract-content">
            {{ item.abstract | escape | markdownify }} 
            </div>

            </h3>
            <br>
        {% endif %}
    {% endfor %}
    </div>

<h1>Poster</h1>
    <br>

   
    <div class="submission-block">
    {% for item in site.data.papers %}
        {% if item.decision == "Accept (Poster)" %}
            <h3>{{ item.title  }}<br>
            <a href="{{ item.link  }}" target="_blank"> OpenReview </a>
            <a class="abstract-toggle" onclick="toggleAbstract('{{ item.link  }}', this)">[Show Abstract]</a>

            <div id="{{ item.link  }}" class="abstract-content">
            {{ item.abstract | escape | markdownify }} 
            </div>

            </h3>
            <br>
        {% endif %}
    {% endfor %}
    </div>
 </div>  



<script>
  function toggleAbstract(targetId, toggleElement) {
    var abstractDiv = document.getElementById(targetId);

    if (!abstractDiv) {
      console.error("Could not find abstract element with ID:", targetId);
      return; 
    }

    if (abstractDiv.style.display === 'none' || abstractDiv.style.display === '') {
      abstractDiv.style.display = 'block';
      if (toggleElement) {
        toggleElement.textContent = '[Hide Abstract]';
      }
    } else {
      abstractDiv.style.display = 'none';
      if (toggleElement) {
        toggleElement.textContent = '[Show Abstract]';
      }
    }
  }
</script>