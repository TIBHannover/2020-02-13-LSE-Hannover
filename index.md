---
carpentry: "dc"
venue: "Leibniz School of Education"
address: "Am Kleinen Felde 30, 30167 Hannover > Raum 332 (Gebäude 2705)"
country: "Germany"
language: "de"
latitude: "52.38600"
longitude: "9.72255"
humandate: "13. - 14. Feb. 2020"
humantime: "Zeitplan siehe unten"
startdate: 2020-02-13
enddate: 2020-02-14
instructor: ["Dr. Katrin Leinweber", "You?"]
helper: ["You?"]
email: ["carpentries@tib.eu"]
collaborative_notes: https://hackmd.io/rwJ5Mgo8SPidtWDcORdNZQ?edit
---

## General Information

{% include dc/who.html %}

<p id="where">
  <strong>Where:</strong>
  {{page.address}}.
  Get directions with
  <a href="//www.openstreetmap.org/?mlat={{page.latitude}}&mlon={{page.longitude}}&zoom=16">OpenStreetMap</a>
  or
  <a href="//maps.google.com/maps?q={{page.latitude}},{{page.longitude}}">Google Maps</a>.
</p>

<p id="when">
  <strong>When:</strong>
  {{page.humandate}}.
  {% include workshop_calendar.html %}
</p>

<p id="requirements">
  <strong>Requirements:</strong> Participants must bring a laptop with a
  Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) that they have administrative privileges on. They should have a few specific software packages installed (listed <a href="#setup">below</a>).
</p>

<p id="accessibility">
  <strong>Accessibility:</strong> We are committed to making this workshop
  accessible to everybody.
  The workshop organizers have checked that:
</p>
<ul>
  <li>The room is wheelchair / scooter accessible.</li>
  <li>Accessible restrooms are available.</li>
</ul>
<p>
  Materials will be provided in advance of the workshop and
  large-print handouts are available if needed by notifying the
  organizers in advance.  If we can help making learning easier for
  you (e.g. sign-language interpreters, lactation facilities) please
  get in touch (using contact details below) and we will
  attempt to provide them.
</p>

<p id="contact">
  <strong>Contact</strong>:
  Please <a href="https://studip.uni-hannover.de/dispatch.php/course/details?cid=571aecad2695554c97406afc7411a632">register yourself via Stud.IP</a> if possible. If not, please email
  <a href='mailto:{{page.email}}'>{{page.email}}</a>
  and briefly explain your motivation to attend the workshop. We have about 5 seats for non-LSE attendees and will inform you about our selection on Jan. 17th.
</p>

---

<h2 id="schedule">Zeitplan</h2>

{% include dc/schedule.html %}

---

## Collaborative Notes

We will use this <a href="{{page.collaborative_notes}}">collaborative document</a> for chatting, taking notes, and sharing URLs and bits of code.

---

## Code of Conduct

Everyone who participates in Carpentries activities is required to conform to the <a href="https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html">Code of Conduct</a>.This document also outlines how to report an incident if needed.

---

## Setup

Please find those details on [DataCarpentry.org/python-ecology-lesson/setup](https://datacarpentry.org/python-ecology-lesson/setup.html).
In addition, you will need an up-to-date web browser.
