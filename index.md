---
layout: workshop      # DON'T CHANGE THIS.
root: .               # DON'T CHANGE THIS EITHER.  (THANK YOU.)
carpentry: "swc"    # what kind of Carpentry (must be either "dc" or "swc")
venue: "Carpentry Instructor Training supported by ELIXIR Sweden, Stockholm, Sweden"        # brief name of host site without address (e.g., "Euphoric State University")
address: "Science for Life Laboratory, Tomtebodavägen 23A, 17165 Solna, Sweden. Auditorium Air"      # full street address of workshop (e.g., "Room A, 123 Forth Street, Blimingen, Euphoria")
country: "Sw"      # lowercase two-letter ISO country code such as "fr" (see https://en.wikipedia.org/wiki/ISO_3166-1)
language: "En"     # lowercase two-letter ISO language code such as "fr" (see https://en.wikipedia.org/wiki/ISO_639-1)
latlng: "FIXME"       # decimal latitude and longitude of workshop venue (e.g., "41.7901128,-87.6007318" - use http://www.latlong.net/)
humandate: "April 03-04, 2019"    # human-readable dates for the workshop (e.g., "Feb 17-18, 2020")
humantime: "9:30 am - 5:30 pm"    # human-readable times for the workshop (e.g., "9:00 am - 4:30 pm")
startdate: 2018-12-03      # machine-readable start date for the workshop in YYYY-MM-DD format like 2015-01-01
enddate: 2018-12-03        # machine-readable end date for the workshop in YYYY-MM-DD format like 2015-01-02
instructor: ["Allegra Via", "Malvika Sharan"] # boxed, comma-separated list of instructors' names as strings, like ["Kay McNulty", "Betty Jennings", "Betty Snyder"]
helper: ["Jessica M. Lindvall", "Pascal Kahlem"]     # boxed, comma-separated list of helpers' names, like ["Marlyn Wescoff", "Fran Bilas", "Ruth Lichterman"]
contact: ["jessica.lindvall@nbis.se"]    # boxed, comma-separated list of contact email addresses for the host, lead instructor, or whoever else is handling questions, like ["marlyn.wescoff@example.org", "fran.bilas@example.org", "ruth.lichterman@example.org"]
etherpad: https://pad.carpentries.org/2019-04-03-ttt-stockholm         # optional: URL for the workshop Etherpad if there is one
eventbrite:           # optional: alphanumeric key for Eventbrite registration, e.g., "1234567890AB" (if Eventbrite is being used)
---

<!-- See instructions in the comments below for how to edit specific sections of this workshop template. -->

<!--
  HEADER

  Edit the values in the block above to be appropriate for your workshop.
  If the value is not 'true', 'false', 'null', or a number, please use
  double quotation marks around the value, unless specified otherwise.
  And run 'tools/check' *before* committing to make sure that changes are good.
-->

<!--
  EVENTBRITE

  This block includes the Eventbrite registration widget if
  'eventbrite' has been set in the header.  You can delete it if you
  are not using Eventbrite, or leave it in, since it will not be
  displayed if the 'eventbrite' field in the header is not set.
-->
{% if page.eventbrite %}
<iframe
  src="https://www.eventbrite.com/tickets-external?eid={{page.eventbrite}}&ref=etckt"
  frameborder="0"
  width="100%"
  height="248px"
  scrolling="auto">
</iframe>
{% endif %}

<h2 id="general">General Information</h2>

<!--
  INTRODUCTION

  Edit the general explanatory paragraph below if you want to change
  the pitch.
-->

<p>
  The course is aimed at everyone who is
  interested in becoming a better teacher. In particular, this training
  is aimed at those who want to become <a href="{{ site.swc_site }}">Software Carpentry</a>
  and <a href="{{ site.dc_site }}">Data Carpentry</a>
  instructors, run workshops and contribute to the Carpentry training
  materials. You don't currently have to be an instructor or a
  teacher to attend this workshop, but you do need to be willing and
  committed to becoming one and to improving your teaching techniques.
</p>

<p>
  <a href="{{ site.swc_site }}">Software Carpentry</a>
  and <a href="{{ site.dc_site }}">Data Carpentry</a>'s mission is to
  help scientists and engineers get more research done in less time
  and with less pain by teaching them basic lab skills for scientific
  computing.  This hands-on two-day workshop covers the basics of
  educational psychology and instructional design, and looks at how to
  use these ideas in both intensive workshops and regular classes.
</p>
<p>
  The workshop is a mix of lectures and hands-on lessons where you
  practice giving a short lesson using approaches learned and
  implement some of the teaching techniques which we will discuss.
  This is training for teaching, not technical training; you do not
  need any particular technical background, and we will not be
  teaching that. This workshop is based on the constantly revised and
  updated
 <a href="{{ site.training_site }}">curriculum</a>.
</p>

<!--
  LOCATION

  This block displays the address and links to maps showing directions
  if the latitude and longitude of the workshop have been set.  You
  can use http://itouchmap.com/latlong.html to find the lat/long of an
  address.
-->
{% if page.latlng %}
<p id="where">
  <strong>Where:</strong>
  {{page.address}}.
  Get directions with
  <a href="https://goo.gl/maps/2HH4kPKZkQk">Google Maps</a>.
</p>
{% endif %}

<p>
  <strong>Requirements:</strong> When possible, participants should bring 
  a laptop that can be connected to Internet 
  to follow teaching materials and developing shared note. 
  </br>
  A device for recording audio and video (mobile phones and
  laptops are OK) will also be useful as throughout the two days, we are going
  to record one another teaching in pairs or threes.  It does not have
  to be high-quality, but it should be good enough that you can
  understand what someone is saying.
</p> 
<p>
  Please note that after this course is over, you will be asked to do
  three short follow-up exercises online in order to finish qualifying
  as an instructor: the details are available at
  <a href="{{ site.training_site }}/checkout/">{{ site.training_site }}/checkout/</a>.
  If you have any questions about the workshop, the reading material,
  or anything else, please get in touch.
</p>
<p align="center">
  <em>
    All participants are required to abide by The Carpentries'
    <a href="https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html">Code of Conduct</a>.
  </em>
</p>

<p id="accessibility">
  <strong>Accessibility:</strong> We are committed to making this workshop
  accessible to everybody. Please contact the workshop organisers to let them know
  if need any assistance to make your participation at the workshop more comfortable.
</p>
<p>
  Materials will be provided in advance of the workshop and
  large-print handouts are available if needed by notifying the
  organizers in advance.  If we can help making learning easier for
  you (e.g. requirements related to mobility, dietary etc.) please
  please get in touch (using contact details below) and we will
  attempt to provide them.
</p>
<p>
<h3>Registration:</h3>
<a href="https://goo.gl/forms/ty3D8267DefQLR3t2">Registration link</a>
</p>
<p id="contact">
  <strong>Contact</strong>:
  Please email
  {% if page.contact %}
    {% for contact in page.contact %}
      {% if forloop.last and page.contact.size > 1 %}
        or
      {% else %}
        {% unless forloop.first %}
        ,
        {% endunless %}
      {% endif %}
      <a href='mailto:{{contact}}'>{{contact}}</a>
    {% endfor %}
  {% else %}
    to-be-announced
  {% endif %}
  for more information.
</p>

<hr/>

<h2 id="preparation" name="preparation">Preparation</h2>

<p>
  Please read the following before the workshop begins:
</p>
<ol>
  <li><a href="{{ site.training_site }}/papers/science-of-learning-2015.pdf">The Science of Learning</a></li>
</ol>
<p>
  Please also read through <em>one</em> of the episodes below
  carefully, so that you can do some exercises based on it on the
  first day of the class.
</p>
<div class="row">
  <div class="col-md-6">
    <p><strong>Data Carpentry</strong></p>
    <ul>
      <li><a href="{{ site.dc_site }}/OpenRefine-ecology-lesson/01-working-with-openrefine">Faceting and Clustering in OpenRefine</a></li>
      <li><a href="{{ site.dc_site }}/sql-ecology-lesson/01-sql-basic-queries">Basic Queries in SQL</a></li>
      <li><a href="{{ site.dc_site }}/R-ecology-lesson/02-starting-with-data.html">Starting with Data in R</a></li>
      <li><a href="{{ site.dc_site }}/python-ecology-lesson/02-starting-with-data">Starting with Data in Python</a></li>
    </ul>
  </div>
  <div class="col-md-6">
    <p><strong>Software Carpentry</strong></p>
    <ul>
      <li><a href="{{ site.swc_pages }}/shell-novice/03-create/">Working with Files and Directories in the Unix Shell</a></li>
      <li><a href="{{ site.swc_pages }}/git-novice/04-changes/">Tracking Changes in Git</a></li>
      <li><a href="{{ site.swc_pages }}/sql-novice-survey/01-select/">Selecting Data in SQL</a></li>
      <li><a href="{{ site.swc_pages }}/python-novice-inflammation/02-loop/">Repeating Actions with Loops in Python</a></li>
      <li><a href="{{ site.swc_pages }}/r-novice-gapminder/05-data-structures-part2/">Exploring Data Frames in R</a></li>
    </ul>
  </div>
  <div class="col-md-6">
    <p><strong>Spanish versions of some of the lessons</strong></p>
    <ul>
      <li><a href="https://swcarpentry.github.io/shell-novice-es/03-create/">Trabajando con archivos y directorios (Unix)</a></li>
<li><a href="https://swcarpentry.github.io/r-novice-gapminder-es/05-data-structures-part2/">Explorando data frames (R)</a></li> 
<li><a href="https://carpentries-es.github.io/python-ecology-lesson-es/02-starting-with-data/index.html">Comenzando con datos (Python)</a></li> 
 <li><a href="https://swcarpentry.github.io/git-novice-es/04-changes/">Rastreando Cambios</a></li>
</div>
</div>

<hr/>

<h2 id="surveys">Surveys</h2>

<h3 id="pre_workshop_survey">Pre-training survey</h3>

<p>
  Before attending the workshop, please fill out <a href="{{ site.instructor_pre_survey }}{{ site.github.project_title }}">our pre-training survey</a>.
</p>

<h3 id ="post_workshop_survey">Post-training survey</h3>

<p>
  After attending the workshop, please fill out <a href="{{ site.instructor_post_survey }}{{ site.github.project_title }}"> our post-training survey</a>
</p>


<h2 id="materials" name="materials">Training Materials and Schedule</h2>

<p>
  Please see <a href="{{ site.training_site }}">this site</a> for course material and tentative schedule.
</p>


<hr/>



<div class="row">
  <div class="col-md-6">
    <h3>Day 1</h3>
    <table class="table table-striped">
      <tr> <td>09:30</td> <td>Welcome </td> </tr>
      <tr> <td>09:45</td> <td>Building Skill With Practice	</td> </tr>
      <tr> <td>10:50</td> <td>Expertise and Instruction </td> </tr>
      <tr> <td>11:40</td> <td>Morning Break </td> </tr>
      <tr> <td>11:55</td> <td>Memory and Cognitive Load </td> </tr>
      <tr> <td>12:40</td> <td>Building Skill With Feedback </td> </tr>
      <tr> <td>13:00</td> <td>Lunch </td> </tr>
      <tr> <td>14:00</td> <td>Motivation and Demotivation </td> </tr>
      <tr> <td>15:05</td> <td>Mindset</td> </tr>
      <tr> <td>15:45</td> <td>Afternoon Break </td> </tr>
      <tr> <td>16:00</td> <td>Teaching is a Skill </td> </tr>
      <tr> <td>17:10</td> <td>Wrap-Up and Homework for Tomorrow </td> </tr>
      <tr> <td>17:30</td> <td>Finish </td> </tr>
    </table>
  </div>
  <div class="col-md-6">
    <h3>Day 2</h3>
    <table class="table table-striped">
      <tr> <td>09:30</td> <td>Welcome Back </td> </tr>
      <tr> <td>09:40</td> <td>Live Coding is a Skill </td> </tr>
      <tr> <td>10:50</td> <td>Preparing to Teach </td> </tr>
      <tr> <td>11:40</td> <td>Morning Coffee </td> </tr>
      <tr> <td>11:55</td> <td>More Practice Live Coding </td> </tr>
      <tr> <td>12:40</td> <td>Managing a Diverse Classroom </td> </tr>
      <tr> <td>13:00</td> <td>Lunch </td> </tr>
      <tr> <td>14:00</td> <td>Checkout Process </td> </tr>
      <tr> <td>14:15</td> <td>The Carpentries: How We Operate </td> </tr>
      <tr> <td>15:30</td> <td>Afternoon Break </td> </tr>
      <tr> <td>15:45</td> <td>Workshop Introductions </td> </tr>
      <tr> <td>16:25</td> <td>Putting It Together </td> </tr>
      <tr> <td>16:45</td> <td>Wrapping Up </td> </tr>
      <tr> <td>17:00</td> <td>Argentina Instructor Introductions </td> </tr>
      <tr> <td>17:30</td> <td>Finish </td> </tr>
    </table>
  </div>
</div>
<hr/>


<!--
  ETHERPAD

  At `_misc/etherpad.txt` you will find a template for the etherpad.

  Display the Etherpad for the workshop.  You can set this up in
  advance or on the first day; either way, make sure you push changes
  to GitHub after you have its URL.  To create an Etherpad, go to

      http://pad.software-carpentry.org/YYYY-MM-DD-site

  where 'YYYY-MM-DD-site' is the identifier for your workshop,
  e.g., '2015-06-10-esu'.
-->
{% if page.etherpad %}


<p id="etherpad">
  <strong>Etherpad:</strong> <a href="{{page.etherpad}}">{{page.etherpad}}</a>.
  <br/>
  We will use this Etherpad for chatting, taking notes, and sharing URLs and bits of code.
</p>

<p><strong>Sponsors and supporters:</strong></p>
<p>This course is organized by the ELIXIR-EXCELERATE, in collaboration with ELIXIR Sweden and ELIXIR-IIB. 
  
 This course is also supported by <a href="https://www.denbi.de/">de.NBI</a> - ELIXIR, Germany.</p>
<p><img src="https://www.elixir-europe.org/system/files/elixir_sweden_white_background.png" height="60"/>      <img src="http://elixir-italy.org/wp-content/themes/iib/images/logo.png" height="60"/>     <img src="https://www.denbi.de/templates/nbimaster/img/denbi-logo-color.svg" height="60"/></p>
<p> </p>
{% endif %}
