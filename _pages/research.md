---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Float four columns side by side */
.column {
  float: left;
  width: 25%;
  padding: 0 10px;
  height: 100%;
}

/* Remove extra left and right margins, due to padding */
.row {margin: 0 -5px;}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive columns */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}

/* Style the counter cards */
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  padding: 16px;
  text-align: center;
  background-color: #f1f1f1;
  margin-top: 4px;
  margin-bottom: 4px

}
</style>

## Research

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>**Mining Emotions from Software Engineering Communication**</h4>
Emotions can strongly impact activities that are collaborative in nature and require creativity and problem-solving skills, such as software development. Research has shown that positive emotions (e.g., Joy) are associated with increased productivity and job satisfaction in software engineering teams. On the other hand, negative emotions (e.g., Frustration) can cause developers to lose motivation and exhibit lower participation, ultimately leading to team attrition. In this project, we aim to mine emotions and affect in software related text towards improving collaboration and productivity in software projects.
<br>
<a href="{{ site.url }}{{ site.baseurl }}/papers/shedding_light.pdf" target="_blank"><button style="margin:1px" class="btn btn-success btm-sm">ICSE24#1</button></a><a href="{{ site.url }}{{ site.baseurl }}/papers/ICSE_24_Emotion_Cause.pdf" target="_blank"><button style="margin:1px" class="btn btn-success btm-sm">ICSE24#2</button></a><a href="{{ site.url }}{{ site.baseurl }}/papers/exploring_toxicity.pdf" target="_blank"><button style="margin:1px" class="btn btn-success btm-sm">ICSE NIER24</button></a> <a href="{{ site.url }}{{ site.baseurl }}/papers/incivility.pdf" target="_blank"><button style="margin:1px" class="btn btn-success btm-sm">MSR24</button></a> <a href="{{ site.url }}{{ site.baseurl }}/papers/toxicity.pdf" target="_blank"><button style="margin:1px" class="btn btn-success btm-sm">FSE23#1</button></a>
<!-- <br> -->
<a href="{{ site.url }}{{ site.baseurl }}/papers/emotions.pdf" target="_blank"><button style="margin:1px" class="btn btn-success btm-sm">FSE23#2</button></a> <a href="{{ site.url }}{{ site.baseurl }}/papers/trust.pdf" target="_blank"><button style="margin:1px" class="btn btn-success btm-sm">ICSE23</button></a> <a href="{{ site.url }}{{ site.baseurl }}/papers/Data Augmentation.pdf" target="_blank"><button style="margin:1px" class="btn btn-success btm-sm">ASE22</button></a>
<br><br>

<h4>**Mining Information from Developer Chat Conversations Towards Building Software Maintenance Tools**</h4>
Popular chat platforms such as Slack host public chat communities that focus on specific software development topics such as Python or Ruby-on-Rails. Many of those chat communications contain valuable information, such as description of code snippets and APIs, opinions on good programming practices, and causes of common errors/exceptions. This project aims to develop analyses for automatically identifying and extracting information in developers’ chat communications towards improving and building new tools to support software engineers.
<br>
<a href="{{ site.url }}{{ site.baseurl }}/papers/DISCO.pdf" target="_blank"><button class="btn btn-success btm-sm">MSR22</button></a> <a href="{{ site.url }}{{ site.baseurl }}/papers/Automatic Extraction.pdf" target="_blank"><button class="btn btn-success btm-sm">ICSE21</button></a> <a href="{{ site.url }}{{ site.baseurl }}/papers/Automatically Identifying the Q.pdf" target="_blank"><button class="btn btn-success btm-sm">TOSEM21</button></a> <a href="{{ site.url }}{{ site.baseurl }}/papers/Software-related Slack.pdf" target="_blank"><button class="btn btn-success btm-sm">MSR20</button></a> <a href="{{ site.url }}{{ site.baseurl }}/papers/Exploratory Study of Slack Q.pdf" target="_blank"><button class="btn btn-success btm-sm">MSR19</button></a>        
<br><br>

<h4>**Studying Developer Focus on Question and Answer (Q&A) Forums**</h4>
Although popular Q&A forums such as Stack Overflow serve as a good knowledge resource, the abundance of information can cause developers to spend considerable time in identifying relevant answers and suitable fixes. This project aims to help developers identify informative code and text from Q&A forums, once they have narrowed down their search to a post relevant to their task.
<br>
<a href="{{ site.url }}{{ site.baseurl }}/papers/Finding Help with Programming.pdf" target="_blank"><button class="btn btn-success btm-sm">JSS19</button></a> <a href="{{ site.url }}{{ site.baseurl }}/papers/Automatic Identification of Informative.pdf" target="_blank"><button class="btn btn-success btm-sm">NLBSE22</button></a>    
<br><br>

<h4>**Learning about Code Snippet Characteristics in Software Artifacts**</h4>
Large corpora of software-related artifacts (e.g., blogs, bug reports, emails) offer the unique opportunity to learn from developers’ discussion about code snippets. The goal of this project is to gain insight into the potential value and difficulty of mining the natural language text associated with the code snippets found in a variety of software-related documents, including blog posts, API documentation, code reviews, and public chats.
<br>
<a href="{{ site.url }}{{ site.baseurl }}/papers/What Information.pdf" target="_blank"><button class="btn btn-success btm-sm">SANER17</button></a>
<br><br>

<h4>**Mining Source Code Descriptions from Research Articles**</h4>
Digital libraries of computer science research articles can be a rich source for code examples that are used to motivate or explain particular concepts or issues. In this project, we designed a technique to automatically identify natural language descriptions of code segments embedded within articles. Extracting these natural language descriptions alongside code could enable new advances in areas including code-based search, automatic code comment generation, and documentation generation.
<br>
<a href="{{ site.url }}{{ site.baseurl }}/papers/Extracting Code Segments.pdf" target="_blank"><button class="btn btn-success btm-sm">MSR17</button></a>
</div>
</div>

## Past and Present Collaborators

<div class="row">
{% for member in site.data.collaborators %}
<div class="column">
<div class="card">
<img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" style="width:auto; max-height:120px"/>
<h5><a href="{{ member.website }}" target="_blank">{{ member.name }}</a></h5>
</div>
</div>
{% endfor %}
</div>

## Research Funding

<div class="row">
{% for member in site.data.funding %}
<div class="column">
<div class="card">
<img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" style="width:auto; max-height:120px"/>
<h5><a href="{{ member.website }}" target="_blank">{{ member.name }}</a></h5>
<h5>Total Award Amount: $7,000</h5>
</div>
</div>
{% endfor %}
</div>
