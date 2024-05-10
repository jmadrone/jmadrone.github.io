---
layout            : splash
permalink         : /
hidden            : true
header            :
  overlay_color   : "#5e616c"
  overlay_image   : /assets/images/background-header.jpg
  actions         :
    - label       : "<i class='fas fa-download'></i> Download my CV now"
      url         : "/cv/"
excerpt           : "Innovating and solving problems in IT for over 20 years"
intro             : 
  - excerpt       : "From a young age, while my peers were shooting hoops, I was immersed in the world of technology, coding away. Computers have always been my passion, driving me to develop strong analytical skills and a deep understanding of network protocols and technologies. My ability to swiftly acquire new skills on the fly empowers me to troubleshoot, isolate, and resolve issues with efficiency and precision.<br/><small>-Josh Madrone</small>"
feature_row       :
  - image_path    : /assets/images/resume.png
    alt           : "resume"
    title         : "My Resume"
    excerpt       : "View my resume and download a PDV version."
    url           : "/cv/"
    btn_class     : "btn--primary"
    btn_label     : "Download CV"
  - image_path    : /assets/images/josh-crater-lake-square-300px.jpg
    alt           : "Josh at Crater Lake, OR"
    title         : "About Me"
    excerpt       : "I have been designing, implementing, and managing complex routed networks for over 15 years..."
    url           : "/about/"
    btn_class     : "btn--primary"
    btn_label     : "Learn more"
  - image_path    : /assets/images/my-work.png
    alt           : "my work image"
    title         : "Some of My Work"
    excerpt       : "A collection of some of the work that I've done in my career."
    url           : "/portfolio/"
    btn_class     : "btn--primary"
    btn_label     : "View more"  
feature_row2      :
  - image_path    : /assets/images/citation-compliance-logo-small.png
    alt           : "Learn more about the Citation Manage platform"
    title         : "Director of Infrastructure<br />Citation Compliance Inc."
    excerpt       : "In this dynamic position, I am responsible for designing, implementing, and maintaining the robust infrastructure that supports our clients' compliance initiatives."
    url           : "/portfolio/citation-compliance/"
    btn_label     : "Read More"
    btn_class     : "btn--primary"
feature_row3      :
  - image_path    : /assets/images/msg-logo.png
    alt           : "Mattole Salmon Group logo"
    title         : "IT Administrator & Project Coordinator<br />Mattole Salmon Group"
    excerpt       : >
      As the IT Administrator at the Mattole Salmon Group, a revered non-profit organization based in Petrolia, CA, I play a pivotal role in ensuring the seamless operation and optimization of our technological infrastructure. In this dynamic position, I spearheaded a transformative project that underscores our commitment to innovation and efficiency, the migration from an on-premises an all-cloud solution, leveraging the power of Amazon Web Services (AWS) and Microsoft Azure.
#      <small><a href="https://github.com/mmistakes/minimal-mistakes/releases/tag/4.26.1">Latest release v4.26.1</a></small>
    url           : "/portfolio/mattole-salmon-group/"
    btn_label     : "Read More"
    btn_class     : "btn--primary"
feature_row4      :
  - image_path    : /assets/images/emsec-logo-mixed-mode.png
    alt           : "Emerald Security logo"
    title         : "Network Engineer & President<br/>Emerald Security LLC"
    excerpt       : >
      As the Network Engineer and Founder of Emerald Security, a leading Managed Services Provider (MSP) nestled in the picturesque town of Trinidad, California, my role integrates technical expertise, strategic vision, and entrepreneurial spirit. Charged with delivering state-of-the-art IT solutions and safeguarding the digital assets of our clients, I am at the forefront of innovation and excellence in the  rapidly evolving field of cybersecurity and network infrastructure.
    url           : "/portfolio/emerald-security/"
    btn_label     : "Read More"
    btn_class     : "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="left" %}
