---
layout: default
---

<div class="content-section">
<div class="inline-wrapper">
<h2 id="workshop-details">Workshop Details</h2>

Welcome to the <b>ICRA 2025</b> Workshop on Active Perception and Robotic Information Gathering!

The ability to actively gather and perceive relevant information is a key requirement for autonomous robots.
Unlike traditional approaches that rely on passive data collection, active perception empowers robots to 
strategically direct their sensors and resources towards the most informative aspects of the environment. 
This shift is crucial for operating in complex, dynamic environments requiring adaptability and efficiency,
e.g. in exploration, search and rescue, and inspection applications. 

This workshop will bring together researchers and practitioners to explore developments in active perception
and robotic information gathering techniques. It will explore how robotic systems can evaluate and determine
the best ways to collect and use data, focusing on topics such as efficient and informative path planning,
sensor fusion, environmental modeling, coordinated information gathering, real-time uncertainty estimation,
behavioral reasoning and information theory. Thus advancing maximal critical data acquisition, efficient
and informative active perception, effective and synergistic robot teaming, theoretical foundations of 
behavioral reasoning and information theory. Discussions will also highlight the role of advanced deep 
learning methods to enable continuous learning and adaptation over time. Participants from diverse 
backgrounds are invited to attend to highlight the core synergies in the information gathering 
problem across application domains.
</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="call-for-papers">Call for Papers</h2>

<h3>Topics</h3>

<ul id="topic-list">
    <li>Active Perception</li>
    <li>Planning</li>
    <li>Information gathering</li>
    <li>Exploration</li>
    <li>...</li>
</ul>

<h3>Submission</h3>

TODO

<h3>Awards</h3>

TODO

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
                <a href="{{ speaker.url | relative_url }}">{{ speaker.name }}</a>
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
Contact us at: some email address
</span>

</div>
</div>

<div class="content-section">
<div class="inline-wrapper">
<h2 id="workshop-program">Workshop Program</h2>

<table>
    <tr>
        <th>Time</th>
        <th>Title</th>
        <th>Speaker</th>
    </tr>
    <tr>
        <td>08:45 - 09:00 AM</td>
        <td>Welcome message and overview of the workshop</td>
        <td>Organizers</td>
    </tr>
    <tr>
        <td>09:00 - 09:25 AM</td>
        <td>Talk (Sensing)</td>
        <td>TBD</td>
    </tr>
    <tr>
        <td>09:25 - 09:50 AM</td>
        <td>Talk (Sensing)</td>
        <td>TBD</td>
    </tr>
    <tr>
        <td>09:50 - 10:00 AM</td>
        <td>Spotlight Talks</td>
        <td></td>
    </tr>
    <tr>
        <td>10:00 - 10:30 AM</td>
        <td>Coffee Break and Posters</td>
        <td></td>
    </tr>
    <tr>
        <td>10:30 - 10:55 AM</td>
        <td>Talk (Theory)</td>
        <td>TBD</td>
    </tr>
    <tr>
        <td>10:55 - 11:20 AM</td>
        <td>Talk (Planning)</td>
        <td>TBD</td>
    </tr>
    <tr>
        <td>11:20 - 11:45 AM</td>
        <td>Talk (Planning)</td>
        <td>TBD</td>
    </tr>
    <tr>
        <td>11:45 - 12:10 AM</td>
        <td>Talk (Planning)</td>
        <td>TBD</td>
    </tr>
    <tr>
        <td>12:10 - 01:15 PM</td>
        <td>Lunch</td>
        <td></td>
    </tr>
    <tr>
        <td>01:15 - 01:40 PM</td>
        <td>Talk (Mapping)</td>
        <td>TBD</td>
    </tr>
    <tr>
        <td>01:40 - 02:05 PM</td>
        <td>Talk (Mapping)</td>
        <td>TBD</td>
    </tr>
    <tr>
        <td>02:05 - 02:15 PM</td>
        <td>Spotlight Talks</td>
        <td></td>
    </tr>
    <tr>
        <td>02:15 - 02:45 PM</td>
        <td>Coffee Break and Posters</td>
        <td></td>
    </tr>
    <tr>
        <td>02:45 - 03:10 PM</td>
        <td>Talk (Industry)</td>
        <td>TBD</td>
    </tr>
    <tr>
        <td>03:10 - 03:35 PM</td>
        <td>Talk (Industry)</td>
        <td>TBD</td>
    </tr>
    <tr>
        <td>03:35 - 03:45 PM</td>
        <td>Break</td>
        <td></td>
    </tr>
    <tr>
        <td>03:45 - 04:45 PM</td>
        <td>Panel Discussion</td>
        <td></td>
    </tr>
    <tr>
        <td>04:45 - 05:00 PM</td>
        <td>Closing Remarks</td>
        <td></td>
    </tr>
</table>
</div>
</div>
