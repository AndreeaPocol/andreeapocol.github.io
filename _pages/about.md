---
layout: single
title: "Andreea Pocol"
excerpt: "Academic Portfolio"
permalink: /
author_profile: true
---

# Welcome

I am a Ph.D. Candidate at the **University of Waterloo**, specializing in the intersection of Digital Image Processing and Human-Computer Interaction (HCI). My doctoral research explores the cinematic language of colour, bridging the gap between computational scale and human perception. I leverage Big Data to identify long-term aesthetic trends across thousands of films, applying digital image processing to extract and quantify pixel-level colour data. Ultimately, my work integrates Human-Computer Interaction (HCI) principles to investigate the psycho-physical impact of colour grading, decoding how these techniques are engineered to evoke specific emotional responses.



### Research Interests
My thesis research aims to analyze the use of colour in film. I am particularly interested in:
* **Big Data:** Mining large-scale datasets to reveal longitudinal patterns in visual storytelling.
* **Digital image processing:** Developing custom pipelines for frame-by-frame, pixel-based analysis of movie frames for cinematographic colour palettes.
* **Human-computer interaction:** Analyzing the intersection of colour theory and human psychology to understand how specific grading choices modulate viewer affect.


---

### Recent Publications
{% assign all_recent_pubs = site.publications | sort: "date" | reverse %}
{% for post in all_recent_pubs limit:3 %}
  * **[{{ post.title }}]({{ post.url }})** *{{ post.venue }}*, {{ post.date | date: "%B %Y" }}
{% endfor %}

---

### Resume
<div style="text-align: center; margin-top: 20px;">
  <iframe src="{{ site.baseurl }}/files/ANDREEA_POCOL_RESUME.pdf" 
          width="100%" 
          height="800px" 
          style="border: none;">
    This browser does not support PDFs. Please <a href="{{ site.baseurl }}/assets/files/ANDREEA_POCOL_RESUME.pdf">download the PDF</a> to view it.
  </iframe>
</div>
