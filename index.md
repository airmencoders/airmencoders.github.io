---
layout: splash
feature_row:
  - title: "Projects"
    excerpt: "Learn more about our projects."
    url: "/projects/"
    btn_label: "Go to Projects"
    btn_class: "btn--inverse"
  - title: "Learn to Code"
    excerpt: "Learn more about coding, DevSecOps, and enjoy our list of free courses."
    url: "/learn/"
    btn_label: "Start Learning"
    btn_class: "btn--inverse"
  - title: "AF Software"
    excerpt: "Learn more about the Air Force's software goals and enabling platforms on the Chief Software Officer's website."
    url: "https://software.af.mil"
    btn_label: "CSO Website"
    btn_class: "btn--inverse"
---
  
<br /><br />
![Airmen Coders logo with #BuiltByAirmen](/assets/images/AirmenCodersFull500x276.png){: .align-center}  

<p align="center">We are a group of U.S. Air Force Airmen who use code to improve the lives of our fellow Airmen.</p>
<br /><br />
{% include feature_row %}
  
<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}

## Team Guidelines
* We build code to help Airmen, they are our customers not our OPRs/EPRs!
* We open source as much as possible [cio.gov](https://sourcecode.cio.gov/OSS/) [code.mil](https://code.mil)
* We are responsible users of existing open source code
* We help each other


## Have questions or want to join us?
Send an email to AirmenCoders [at] us.af.mil, we would love to hear from you!

<script type="text/javascript" src="https://jira.il2.dsop.io/s/d41d8cd98f00b204e9800998ecf8427e-CDN/-cd1e9/810001/6411e0087192541a09d88223fb51a6a0/2.2.4.7/_/download/batch/com.atlassian.plugins.jquery:jquery/com.atlassian.plugins.jquery:jquery.js?collectorId=92403d4d"></script><script type="text/javascript" src="https://jira.il2.dsop.io/s/c717ea36400ed7a84303a68988bb7b64-T/-cd1e9/810001/6411e0087192541a09d88223fb51a6a0/4.0.1/_/download/batch/com.atlassian.jira.collector.plugin.jira-issue-collector-plugin:issuecollector/com.atlassian.jira.collector.plugin.jira-issue-collector-plugin:issuecollector.js?locale=en-US&collectorId=92403d4d"></script>


