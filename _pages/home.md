---
layout: splash
permalink: /
#hidden: true
author_profile: false
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/background-header.jpg
  actions:
    - label: "<i class='fas fa-download'></i> Download my CV now"
      url: "/cv/"
excerpt: >
  Innovating and solving problems in IT for over 20 years
#intro: 
#  - excerpt: 'From a young age, while my peers were shooting hoops, I was immersed in the world of technology, coding away. Computers have always been my passion, driving me to develop strong analytical skills and a deep understanding of network protocols and technologies. My ability to swiftly acquire new skills on the fly empowers me to troubleshoot, isolate, and resolve issues with efficiency and precision.'
feature_row:
  - image_path: /assets/images/resume.png
    alt: "resume"
    title: "My Resume"
    excerpt: "View my resume and download a PDV version."
    url: "/cv/"
    btn_class: "btn--primary"
    btn_label: "Download CV"
  - image_path: /assets/images/josh-crater-lake-square-300px.jpg
    alt: "Josh at Crater Lake, OR"
    title: "About Me"
    excerpt: "I have been designing, implementing, and managing complex routed networks for over 15 years..."
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/my-work.png
    alt: "my work image"
    title: "Some of My Work"
    excerpt: "A collection of some of the work that I've done in my career."
    url: "/portfolio-archive/"
    btn_class: "btn--primary"
    btn_label: "View more"  
  feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

# {% include feature_row id="intro" type="center" %}

{% include feature_row %}

# {% include feature_row id="feature_row2" type="left" %}

# {% include feature_row id="feature_row3" type="right" %}

# {% include feature_row id="feature_row4" type="center" %}
