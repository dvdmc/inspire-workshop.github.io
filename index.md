---
layout: default
---

<div class="content-section">
<div class="inline-wrapper">
<h2 id="workshop-details">Workshop Details</h2>

<p>
Welcome to the <b>ICRA 2025</b> Workshop on <b>In</b>formative <b>S</b>ensing and <b>P</b>lanning for <b>I</b>ntelligent <b>R</b>obotic <b>E</b>xploration!
</p>

<p>
The ability to actively gather and perceive relevant information is a key requirement for autonomous robots.
Unlike traditional approaches that rely on passive data collection, active perception empowers robots to strategically direct their sensors and resources towards the most informative aspects of the environment.
This shift is crucial for operating in complex, dynamic environments requiring adaptability and efficiency, e.g., in exploration, search and rescue, and inspection applications. 
</p>

<p>
This workshop will bring together researchers and practitioners to explore developments in active perception and robotic information gathering techniques.
It will explore how robotic systems can evaluate and determine the best ways to collect and use data, focusing on topics such as efficient and informative path planning, sensor fusion, environmental modeling, coordinated information gathering, real-time uncertainty estimation, behavioral reasoning and information theory. 
Thus advancing maximal critical data acquisition, efficient and informative active perception, effective and synergistic robot teaming, theoretical foundations of behavioral reasoning and information theory. 
Discussions will also highlight the role of advanced deep learning methods in enabling continuous learning and adaptation over time. 
Participants from diverse backgrounds are invited to attend to highlight the core synergies in the information gathering problem across application domains.
</p>

</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="call-for-papers">Call for Papers</h2>

<h3>Topics</h3>

<ul class="default-list">
{% for topic in site.call.topics %}
    <li>{{ topic }}</li>
{% endfor %}
</ul>

<h3 id="submissions">Submission</h3>

<p>
Researchers in robotic information gathering and exploration are 
encouraged to contribute to the workshop by submitting a <b>two-page paper</b> 
(excluding references) in PDF format. We encourage the submission of new 
ideas and will only consider non-archival abstracts based on a prior 
publication if the submission is not based on new content.
</p>

<p>
Submission link: <a href="{{ site.call.submissions.url }}">{{ site.call.submissions.link_name }}</a>
</p>

<p>
In particular, submitted papers must be formatted according to the 
guideline of ICRA 2025. The program committee will review each 
contribution, and the authors will be notified of the result.
</p>

</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="important-dates">Important Dates</h2>

<ul class="default-list">
    {% for event in site.events %}
    <li><b>{{ event.date }}</b>: {{ event.name }}</li>
{% endfor %}
</ul>

</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="invited-speakers">Invited Speakers</h2>

<div class="people-list">
{% for speaker in site.speakers %}
    <div class="single-person">
        <ul>
            <li>
                <img alt="{{ speaker.name }}" src="{{ speaker.photo_url }}">
            </li>
            <li>
                <a href="{{ speaker.url | relative_url }}" target="_blank">{{ speaker.name }}</a>
            </li>
            <li>{{ speaker.role }}</li> 
            <li>{{ speaker.organization }}</li> 
            <li>{{ speaker.country }}</li>
        </ul>
    </div>
{% endfor %}
</div>
</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="invited-panelist">Invited Panelist</h2>

<div class="people-list">
{% for panelist in site.panelists %}
    <div class="single-person">
        <ul>
            <li>
                <img alt="{{ panelist.name }}" src="{{ panelist.photo_url }}">
            </li>
            <li>
                <a href="{{ panelist.url | relative_url }}">{{ panelist.name }}</a>
            </li>
            <li>{{ panelist.role }}</li> 
            <li>{{ panelist.organization }}</li> 
            <li>{{ panelist.country }}</li>
        </ul>
    </div>
{% endfor %}
</div>
</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="workshop-organizers">Workshop Organizers</h2>

<div class="people-list">
{% for organizer in site.organizers %}
    <div class="single-person">
        <ul>
            <li>
                <img alt="{{ organizer.name }}" src="{{ organizer.photo_url }}">
            </li>
            <li>
                <a href="{{ organizer.url | relative_url }}">{{ organizer.name }}</a>
            </li>
            <li>{{ organizer.role }}</li> 
            <li>{{ organizer.organization }}</li> 
            <li>{{ organizer.country }}</li>
        </ul>
    </div>
{% endfor %}
</div>

<span style="font-weight: bold; text-align: center; display: block; margin-top: 20px;">
Contact us at: m.popovic@tudelft.nl
</span>

</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="involved-institutions">Involved Institutions</h2>

<div id="institution-logos">
    {% for institution in site.institutions %}
        <div class="institution-logo">
            <a href="{{ institution.url }}">
                <img alt="{{ institution.name}}" src="{{ institution.logo_url}}">
            </a>
        </div>
    {% endfor %}
</div>
</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="workshop-program">Workshop Program</h2>

<div id="program-table">
    <div class="program-row">
        <div>08:45 AM</div>
        <div>Welcome message and overview of the workshop</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>09:00 AM</div>
        <div>TBD</div>
        <div>Martin Saska</div>
    </div>
    <div class="program-row">
        <div>09:25 AM</div>
        <div>Intelligent Data-Centric Approaches to UAV Sensing</div>
        <div>Antonella Barišić Kulaš</div>
    </div>
    <div class="program-row">
        <div>09:50 AM</div>
        <div>Spotlight Talks</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>10:00 AM</div>
        <div>Coffee Break and Posters</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>10:30 AM</div>
        <div>TBD</div>
        <div>Tara Javidi</div>
    </div>
    <div class="program-row">
        <div>10:55 AM</div>
        <div>Multi-scale and multi-objective informative planning</div>
        <div>Jen Jen Chung</div>
    </div>
    <div class="program-row">
        <div>11:20 AM</div>
        <div>Autonomous gas source search using information-theoretic and reinforcement learning approaches in uncertain environments</div>
        <div>Hyondong Oh</div>    
    </div>
    <div class="program-row">
        <div>11:45 AM</div>
        <div>TBD</div>
        <div>Nare Karapetyan</div>
    </div>
    <div class="program-row">
        <div>12:10 PM</div>
        <div>Lunch</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>01:15 PM</div>
        <div>Learning for Active Perception and Active Perception for Robot Learning</div>
        <div>Lukas Schmid</div>    
    </div>
    <div class="program-row">
        <div>01:40 PM</div>
        <div>Talk  (Mapping)</div>
        <div>TBD</div>
    </div>
    <div class="program-row">
        <div>02:05 PM</div>
        <div>Spotlight Talks</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>02:15 PM</div>
        <div>Coffee Break and Posters</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>02:45 PM</div>
        <div>Learning and control-based active perception over continuous SE(3) trajectories</div>
        <div>Shumon Koga</div>
    </div>
    <div class="program-row">
        <div>03:10 PM</div>
        <div>TBD</div>
        <div>Ali-akbar Agha-mohammadi</div>
    </div>
    <div class="program-row">
        <div>03:35 PM</div>
        <div>Break</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>03:45 PM</div>
        <div>Panel Discussion</div>
        <div></div>
    </div>
    <div class="program-row">
        <div>04:45 PM</div>
        <div>Closing Remarks</div>
        <div></div>
    </div>
</div>
</div>
</div>
