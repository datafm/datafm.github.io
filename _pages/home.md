---
layout: default
urltitle: "DATA-FM Workshop @ ICLR 2025"
title: "2nd ICLR Workshop on Navigating and Addressing Data Problems for Foundation Models (DATA-FM @ ICLR 2025)"
categories: workshop, iclr, data, 2025, data attribution, data valuation, data selection
permalink: /
bibtex: true
paper: true
acknowledgements: ""
---


<div class="row reverse pt-16">
  <div class="col-xs-12 col-md-7" style="padding-top: 40px;">
    <h1>2nd Workshop on Navigating and Addressing Data Problems for Foundation Models <br> (DATA-FM @ ICLR 2025)</h1>
    <br>
    <p>
      Foundation models (FMs) have become central to modern machine learning, with data playing a crucial role in their development and sparking increased attention to data-related challenges such as curation and attribution. Adapting traditional data-centric methods to FMs is challenging due to the scale of both data and model architectures, necessitating interdisciplinary collaboration and community efforts. Building on the success of the first Data Problems in Foundation Models (DATA-FM) workshop at ICLR 2024, the second DATA-FM workshop will address persistent and emerging data-related challenges in FM deployment. While longstanding issues in data collection, curation, and synthesis remain relevant, new challenges have arisen as FMs are integrated into a growing number of applications and become increasingly multi-modal. Concurrently, the societal impact of AI has intensified, highlighting concerns such as data copyright. These evolving challenges emphasize the need for continued, focused discussions on data-related issues in FM development. Our goals include fostering a comprehensive understanding of these challenges across the entire FM pipeline and creating a platform for interdisciplinary researchers to connect, collaborate, and drive progress. We hope this workshop will serve as a catalyst for innovative solutions to critical data challenges, shaping the future of FMs and their wide-ranging applications.
    </p>
    <p>
      In case of any issues or questions, feel free to email the organizers at <a href="mailto:tianhaowang@princeton.edu" class="red">tianhaowang@princeton.edu</a>.
    </p>
  </div>
  <div class="col-md-1 hidden-xs">
  </div>
  <div class="col-xs-12 col-md-4">
    <br>
    <img class="cover" src="{{ "/static/img/cover_sg.jpg" | prepend:site.baseurl }}">
  </div>
</div>



<br/>

<div class="row" id="dates">
  <div class="col-xs-12">
    <h2>Important Dates</h2>
    <br />
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <table class="table table-striped">
      <tbody>
        <tr>
          <td><b>Submission Deadline</b></td>
          <td><s>Feb 7th, 2025, 11:59pm Anywhere on Earth (AoE)</s></td>
        </tr>
        <tr>
          <td><b>Decision Notification</b></td>
          <td><s>March 5th, 2025</s></td>
        </tr>
        <tr>
        </tr>
        <tr>
          <td><b>Camera-ready Deadline</b></td>
          <td><s>April 23rd, 2025</s></td>
        </tr>
        <!-- Need to determine if ICLR supports videos for workshops.
        <tr>
          <td>Paper Video Submission Deadline</td>
          <td>April 20, 2025</td>
        </tr>
        -->
        <tr>
          <td><b>Workshop Date</b></td>
          <td>April 28th, 2025 @ Singapore EXPO Hall 4 #4, Singapore</td>
        </tr>
        <tr>
          <td><b>Workshop Virtual Link</b></td>
          <td><a href="https://iclr.cc/virtual/2025/workshop/23969" target="_blank">https://iclr.cc/virtual/2025/workshop/23969</a></td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<br />
<hr />

<div class="row" id="cfp">
  <div class="col-xs-12">
    <h2>Call for Papers</h2>
    <br />
  </div>
</div>


<div class="row">
  <div class="col-xs-12">
    <p>
      We invite submissions to the 2nd DATA-FM workshop, focusing on data-centric techniques and foundation model (FM) development. We encourage submissions across a wide range of topics, including but not limited to:
    </p>
    <p>Data Collection and Curation for Foundation Models</p>
    <ul>
      <li>Practical strategies for curating data (e.g., filtering, mixing, repairing) tailored to FM training stages.</li>
      <li>Extending data curation techniques to Retrieval-Augmented Generation (RAG), multimodal settings, and LLM agents.</li>
      <li>Theoretical frameworks for guiding data selection and scaling laws for foundation models.</li>
    </ul>
    <p>Data Attribution, Interpretability, and Data Marketplaces</p>
    <ul>
      <li>Efficient techniques for attributing model outputs to specific training data.</li>
      <li>Evaluating and comparing data attribution methods.</li>
      <li>Economic models for data pricing and the design of data marketplaces that ensure fair compensation.</li>
    </ul>
    <p>Legal and Technical Solutions for Data Copyright Protection</p>
    <ul>
      <li>Mitigation strategies and mathematical frameworks for addressing copyright issues in FM training data.</li>
      <li>Connections between copyright, privacy, and fairness, including adaptations of techniques like machine unlearning.</li>
    </ul>
    <p>Synthetic Data and Model Collapse</p>
    <ul>
      <li>High-quality synthetic data generation and its impact on FM performance, robustness, and safety.</li>
      <li>Understanding and mitigating model collapse through theoretical and empirical investigations.</li>
    </ul>
    <p>Data and Society (Safety, Privacy, Fairness, and Other Social Impacts)</p>
    <ul>
      <li>Improving AI safety, privacy, and fairness through data-centric approaches.</li>
      <li>Addressing the side effects of data curation on fairness and ethics in FMs.</li>
    </ul>
    <p>Benchmarks and Evaluations</p>
    <ul>
      <li>Designing evaluation metrics for data-centric techniques and creating reliable dataset benchmarks for FMs.</li>
      <li>Identifying and addressing pitfalls in existing dataset benchmarks, such as test data contamination.</li>
    </ul>
    <br />
    <h5>Submission Guidelines</h5>
    <br />
    <p>We welcome submissions to two paper tracks for the workshop:</p>
    <ol>
      <li><strong>Research/Position Papers Track</strong>: Submissions may be up to 10 pages, excluding references and appendices. All papers must be formatted using the DATA-FM template (see below). </li>
      <li><strong>Tiny Papers Track</strong>: This track encourages submissions describe early-stage research, including modest theoretical results, novel observations from preliminary experiments, or new perspectives on existing problems. Submissions are required to be 3-5 pages using the official ICLR template.</li>
    </ol>
    <p>
    Paper templates and style files (adapted from the ICLR template) can be found in <a class="red" href="https://www.overleaf.com/read/nwjhqwpftgnw#26a403">this Overleaf template</a>. Submissions must follow the template and style, and be properly <b>anonymized (for double-blind review)</b>, and not exceed the page limits for the specified track (excluding references and appendices). Accepted papers will be shared on OpenReview, but the workshop will remain <strong>non-archival</strong>. 
    </p>
    <p> Submissions should be uploaded via the <a class="red" href="https://openreview.net/group?id=ICLR.cc/2025/Workshop/Data_Problems">ICLR 2025 DATA-FM Workshop Submission</a> portal on OpenReview (<b>CLOSED</b>).
    </p>
    <br />

    <h5>Author-Reviewer Policy</h5>
    <br />
    <p> The workshop program committee plays an important role in identifying and giving feedback on up-and-coming work that would most benefit from discussion and visibility at the workshop. To sustain our review and program selection processes, we expect <b>at least one author of each submitted paper to volunteer to participate as a reviewer</b> for the DATA-FM 2025 workshop.
    </p>



    <br />
    <h5>Regarding Tiny Papers Track</h5>
    <p>
    This year, ICLR is discontinuing the separate “Tiny Papers” track, and is instead requiring each workshop to accept short (3–5 pages in ICLR format, exact page length to be determined by each workshop) paper submissions, with an eye towards inclusion; see <a class="red" href="https://iclr.cc/Conferences/2025/CallForTinyPapers">ICLR 2025 Tiny Papers Track</a> for more details. Authors of these papers will be earmarked for potential funding from ICLR, but need to submit a separate application for Financial Assistance that evaluates their eligibility. This application for Financial Assistance to attend ICLR 2025 will become available on <a class="red" href="https://iclr.cc/Conferences/2025/">ICLR 2025 Website</a> at the beginning of February and close on March 2nd.

    </p>


    <br />
    <h5>Poster Guidelines</h5>
  
    <ol>
      <li> 
      <strong>Workshop Poster size:</strong>  Maximum size allowed for printing: 61cm x 91cm (24in x 36in) width/height.
      </li>
      <li>
      Due to limited wall space workshop posters need to be in <strong>Portrait format</strong>.
      </li>
      <li>
        <strong>Poster Printing:</strong>
        You can print your poster using any service you want.
        ICLR offers an optional poster printing service with delivery to the convention center and can be ordered <a href="https://docs.google.com/forms/d/e/1FAIpQLSeymkgqJXjwrcI2OBt6KpB8D9XHFVhL2YScg7BGr1Fd_3aWpQ/viewform?usp=header" target="_blank">here.</a> 
      </li>
    </ol>
  </div>
</div>




<!-- 
<br>
<br>


<div class="row">
  <div class="col-xs-12">
        <p>
            We invite submissions to the ICL 2024 workshop, focusing on the development of new architectures, algorithms, theoretical analysis, empirical studies, and applications of In-Context Learning (ICL). Submissions must present original research that has not been previously published. 
        </p>
        <p>Specific topics of interest include, but are not limited to:</p>
        <ul>
<li>architectures, training paradigms, and inductive biases that enable or improve ICL;</li>
<li>theoretical analyses and guarantees for ICL methods;</li>
<li>empirical evaluation of the performance of ICL on interpretability, controllability, and safety considerations for ICL systems;</li>
<li>similarities and differences between ICL in large-scale language modeling systems and learned algorithms in other domains;</li>
<li>the relationship between ICL and few-shot learning, meta-learning and automated machine learning (AutoML).</li>
        </ul>
        <p>Accepted papers will be presented as posters and a subset will be selected for oral presentation. The ICL 2024 workshop will be held in person at ICML 2024 with virtual participation options to be determined.</p>
        <h3>Submission Guidelines</h3>
        <br />
        <p>
        We welcome both <b>long</b> (up to 8 pages) and <b>short</b> papers (up to 4 pages); the track can be selected during submission.
        Submitted manuscripts should be composed of a page-limited main body followed by an unlimited number of pages for references and appendices, all in a single file.
        Submissions should be uploaded via the <a class="red" href="https://openreview.net/group?id=ICML.cc/2024/Workshop/ICL">ICML 2024 Workshop ICL Submission</a> portal on OpenReview.
        </p>
        <p>Paper templates and style files (adapted from the ICML template) can be found in <a class="red" href="https://www.overleaf.com/read/mcmwbswdxwgq#4ee6ba">this Overleaf template</a>. Submissions must follow the template and style, be properly <b>anonymized (for double-blind review)</b>, and not exceed the page limits for the specified track (excluding references and appendices). We will <b>have non-archival proceedings</b>, but will share accepted papers and their reviews on OpenReview. We encourage including code in papers, though we ask to anonymize the code along with the submission.</p>
        <h3>Dual Submission Policy</h3>
        <br />
        <p>We aim to host work-in-preparation that would most benefit from feedback, which informs our dual submission policy.  We accept submissions that are <b>currently under review</b> for publication in other venues. However, as per ICML guidelines, we do not accept works <b>accepted for publication</b> in another archival venue as of the date of the workshop deadline. A work accepted at ICML 2024 or KDD 2024 can thus <b>not</b> be submitted to the workshop, but a paper under review at NeurIPS 2024 would be eligible.</p>
        <h3>Review Process</h3>
        <br />
        <p>
We will ask each reviewer to evaluate 1–2 submissions starting the week of Tuesday, May 28th. All reviews will be due no later than Friday, June 7th, anywhere on earth, to enable us to notify authors on time. Our active review period is thus between <b>May 28th and June 7th</b>.
</p>
        <h3>Author-Reviewer Policy</h3>
        <br />
        <p>
The workshop program committee plays an important role in identifying and giving feedback on up-and-coming work that would most benefit from discussion and visibility at the workshop.
To sustain our review and program selection processes, we require <b>at least one author of each submitted paper to volunteer to participate as a reviewer (and to accept if selected by the Organizers)</b> for the ICL 2024 workshop (identified in the OpenReview submission form).
</p>
        <h3>Call for Reviewers</h3>
        <br />
        <p>If you are interested in reviewing papers for the workshop outside of the author-reviewer requirements, we invite you to nominate yourself and/or others to serve on the program committee by filling out the <a class="red" href="https://forms.gle/j8jSDxMEVmTHKqfr5">reviewer nomination form
</a>.</p>
  </div>
</div>

-->
<br />

<hr />



<div class="row">
    <div class="col-xs-8">
    </div>
</div>

<div class="row" id="schedule">
  <div class="col-xs-12">
    <h2>Schedule 28/04/2025 (Tentative)</h2>
    <br/>
    <p> All times listed below are in Singapore Time SGT (GMT+8).  </p>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <table class="table table-striped">
      <tbody>
        <tr>
          <td><b>MORNING SESSION 🌅🕘</b></td>
          <td></td>
        </tr>
        <tr>
          <td>9:00 - 9:05 AM</td>
          <td>
            Opening Remarks 📖
          </td>
        </tr>
        <tr>
          <td>9:05 - 9:35 AM</td>
          <td>
            Invited Talk: <a href="https://www.peterhenderson.co/" target="_blank" >Peter Henderson</a> 🤝🗣️
          </td>
        </tr>
        <tr>
          <td>9:35 - 10:05 AM</td>
          <td>
            Invited Talk: <a href="https://www.cs.princeton.edu/~danqic/" target="_blank" > Danqi Chen</a> 🤝🗣️
          </td>
        </tr>
        <tr>
          <td>10:05 - 10:20 AM</td>
          <td>
            Coffee Break ☕
          </td>
        </tr>
        <tr>
          <td>10:20 - 10:50 AM</td>
          <td>
            Spotlight Presentation: Xinran Gu 📊 <br>
            <a href="https://openreview.net/forum?id=ZKA4yiGdrA" target="_blank" > Data Mixing Can Induce Phase Transitions in Knowledge Acquisition</a>
            <br>
            Spotlight Presentation: Xiang Yue 📊 <br>
            <a href="https://openreview.net/forum?id=AgtQlhMQ0V" target="_blank" > Demystifying Long CoT Reasoning in LLMs </a>
          </td>
        </tr>
        <tr>
          <td>10:50 - 12:00 PM</td>
          <td>
            Poster Session I 🪧 
          </td>
        </tr>
        <tr>
          <td>12:00 - 1:30 PM</td>
          <td>
            Lunch Break 🍲
          </td>
        </tr>
        <tr>
          <td><b>AFTERNOON SESSION 🌇🕐</b></td>
          <td></td>
        </tr>
        <tr>
          <td>1:30 - 2:00 PM</td>
          <td>
            Invited Talk: <a href="https://people.csail.mit.edu/mirrokni/Welcome.html" target="_blank" >Vahab Mirrokni </a>🤝🗣️
          </td>
        </tr>
        <tr>
          <td>2:00 - 2:30 PM</td>
          <td>
            Invited Talk: <a href="https://kyleclo.com/" target="_blank" > Kyle Lo</a> 🤝🗣️ <br>
             <b>The OLMo Cookbook: Open Recipes for Language Model Data Curation </b>
          </td>
        </tr>
        <tr>
          <td>2:30 - 3:00 PM</td>
          <td>
            Spotlight Presentation: Zheng Xu 📊 <br>
            <a href="https://openreview.net/forum?id=CpXhMOJOQ6" target="_blank" > Synthesizing Privacy-Preserving Text Data via Finetuning without Finetuning Billion-Scale LLMs </a>
            <br>
            Spotlight Presentation: Brandon Trabucco  📊 <br>
            <a href="https://openreview.net/forum?id=UUEGIdyQI0" target="_blank" > Towards Internet-Scale Training For Agents </a>
          </td>
        </tr>
        <tr>
          <td>3:00 - 3:30 PM</td>
          <td>
            Coffee Break ☕
          </td>
        </tr>
        <tr>
          <td>3:30 - 4:00 PM</td>
          <td>
            Invited Talk: <a href="https://www.comp.nus.edu.sg/~lowkh/" target="_blank" > Bryan Low</a> 🤝🗣️ <br>
             <b>Data-centric AI Research @ GLOW.AI</b>
          </td>
        </tr>
        <!-- <tr>
          <td>3:30 - 4:10 PM</td>
          <td>
            Panel Discussion 👥💬
          </td>
        </tr> -->
        <tr>
          <td>4:00 - 4:05 PM</td>
          <td>
            Closing Remarks 📗
          </td>
        </tr>
        <tr>
          <td>4:05 - CLOSE</td>
          <td>
            Poster Session II 🪧
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</div>


<br />
<hr />

<div class="row" id="speakers">
  <div class="col-xs-12">
    <h2>Speakers (Tentative)</h2>
    <br />
  </div>
</div>



<!-- <div class="row">
  <div class="col-md-4 col-xs-6">1</div>
  <div class="col-md-4 col-xs-6">2</div>
  <div class="col-md-4 col-xs-6">3</div>
  <div class="col-md-4 col-xs-6">4</div>
  <div class="col-md-4 col-xs-6">5</div>
  <div class="col-md-4 col-xs-6">6</div>
  <div class="col-md-4 col-xs-6">7</div>
  <div class="col-md-4 col-xs-6">8</div>
</div> -->


<div class="row">
  <div class="col-lg-3 col-md-3  col-sm-6  col-xs-12">
    <a href="https://www.cs.princeton.edu/~danqic/">
      <img class="people-pic" src="static/img/people/danqi_chen.jpg">
    </a>
    <div class="people-name">
      <a href="https://www.cs.princeton.edu/~danqic/">Danqi Chen</a>
      <h6>Princeton University</h6>
    </div>
  </div>
  <div class="col-lg-3 col-md-3  col-sm-6  col-xs-12">
    <a href="https://www.peterhenderson.co/">
      <img class="people-pic" src="static/img/people/peter_henderson.jpg">
    </a>
    <div class="people-name">
      <a href="https://www.peterhenderson.co/">Peter Henderson</a>
      <h6>Princeton University</h6>
    </div>
  </div>
  <div class="col-lg-3 col-md-3  col-sm-6  col-xs-12">
    <a href="https://kyleclo.com/">
      <img class="people-pic" src="static/img/people/kyle_lo.jpg">
    </a>
    <div class="people-name">
      <a href="https://kyleclo.com/">Kyle Lo</a>
      <h6>Allen Institute for AI (Ai2)</h6>
    </div>
  </div>
  <div class="col-lg-3 col-md-3  col-sm-6  col-xs-12">
    <a href="https://www.comp.nus.edu.sg/~lowkh/">
      <img class="people-pic" src="static/img/people/bryan_low.jpg">
    </a>
    <div class="people-name">
      <a href="https://www.comp.nus.edu.sg/~lowkh/">Bryan Low</a>
      <h6>National University of Singapore (NUS)</h6>
    </div>
  </div>
  <div class="col-lg-3 col-md-3  col-sm-6  col-xs-12">
    <a href="https://people.csail.mit.edu/mirrokni/Welcome.html">
      <img class="people-pic" src="static/img/people/vahab_mirrokni.jpg">
    </a>
    <div class="people-name">
      <a href="https://people.csail.mit.edu/mirrokni/Welcome.html">Vahab Mirrokni</a>
      <h6>Google Research</h6>
    </div>
  </div>
<!--   <div class="col-lg-3 col-md-3  col-sm-6  col-xs-12">
    <a href="https://baharanm.github.io/">
      <img class="people-pic" src="static/img/people/baharan_mirzasoleiman.jpg">
    </a>
    <div class="people-name">
      <a href="https://baharanm.github.io/">Baharan Mirzasoleiman</a>
      <h6>University of California, Los Angeles (UCLA)</h6>
    </div>
  </div> -->
<!--   <div class="col-lg-3 col-md-3  col-sm-6  col-xs-12">
    <a href="https://www.arimorcos.com/">
      <img class="people-pic" src="static/img/people/ari_morcos.jpg">
    </a>
    <div class="people-name">
      <a href="https://www.arimorcos.com/">Ari Morcos</a>
      <h6>Datalogy AI</h6>
    </div>
  </div>   -->
</div>

<br/>



<br/>
<hr />
<div class="row" id="organizers">
  <div class="col-xs-12">
    <h2>Organizers</h2>
    <br />
  </div>
</div>

<div class="row">

  <div class="col-lg-3 col-md-4  col-sm-6  col-xs-12">
    <a href="https://ruoxijia.net/">
      <img class="people-pic" src="static/img/people/ruoxi_jia.jpg">
    </a>
    <div class="people-name">
      <a href="https://ruoxijia.net/">Ruoxi Jia</a>
      <h6>Virginia Tech</h6>
    </div>
  </div>

  <div class="col-lg-3 col-md-4  col-sm-6  col-xs-12">
    <a href="https://koh.pw/">
      <img class="people-pic" src="static/img/people/pang_wei_koh.jpg">
    </a>
    <div class="people-name">
      <a href="https://koh.pw/">Pang Wei Koh</a>
      <h6>University of Washington</h6>
    </div>
  </div>

  <div class="col-lg-3 col-md-4  col-sm-6  col-xs-12">
    <a href="https://dawnsong.io/">
      <img class="people-pic" src="static/img/people/dawn_song.jpg">
    </a>
    <div class="people-name">
      <a href="https://dawnsong.io/">Dawn Song</a>
      <h6> University of California, Berkeley</h6>
    </div>
  </div>

  <div class="col-lg-3 col-md-4  col-sm-6  col-xs-12">
    <a href="https://ai.sony/people/Jerone-Andrews/">
      <img class="people-pic" src="static/img/people/jerone_andrews.jpg">
    </a>
    <div class="people-name">
      <a href="https://ai.sony/people/Jerone-Andrews/">Jerone Andrews</a>
      <h6>Sony AI</h6>
    </div>
  </div>

  <div class="col-lg-3 col-md-4  col-sm-6  col-xs-12">
    <a href="https://www.linkedin.com/in/fykang/">
      <img class="people-pic" src="static/img/people/feiyang_kang.jpg">
    </a>
    <div class="people-name">
      <a href="https://www.linkedin.com/in/fykang/">Feiyang Kang</a>
      <h6>Virginia Tech</h6>
    </div>
  </div>

  <div class="col-lg-3 col-md-4  col-sm-6  col-xs-12">
    <a href="https://justhoanganh.com">
      <img class="people-pic" src="static/img/people/just_hoang_anh.jpg">
    </a>
    <div class="people-name">
      <a href="https://justhoanganh.com">Hoang Anh Just</a>
      <h6>Virginia Tech</h6>
    </div>
  </div>

  <div class="col-lg-3 col-md-4  col-sm-6  col-xs-12">
    <a href="https://tianhaowang.netlify.app/">
      <img class="people-pic" src="static/img/people/jiachen_tianhao_wang.jpeg">
    </a>
    <div class="people-name">
      <a href="https://tianhaowang.netlify.app/">Jiachen (Tianhao) Wang</a>
      <h6>Princeton University</h6>
    </div>
  </div>
</div>
<br/>
<br/>
<br/>
<br/>
<hr />




<div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0)">
    <h6>
        Website theme adapted from the <a href="https://iclworkshop.github.io/">ICL workshop @ ICML 2024</a>.
    </h6>
    <br>
</div>
