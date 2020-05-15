---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<b>[Disentangled Image Generation Through Structured Noise Injection](https://arxiv.org/pdf/2004.12411.pdf)</b> <br> 
<b>Yazeed Alharbi</b>, Peter Wonka.
<i>Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition</i>. <b>CVPR 2020 (Selected for oral presentation)</b>.

<b>[Latent Filter Scaling For Multimodal Unsupervised Image-To-Image Translation](http://openaccess.thecvf.com/content_CVPR_2019/papers/Alharbi_Latent_Filter_Scaling_for_Multimodal_Unsupervised_Image-To-Image_Translation_CVPR_2019_paper.pdf)</b> <br> 
<b>Yazeed Alharbi</b>, Neil Smith, Peter Wonka.
<i>Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition</i>. <b>CVPR 2019</b>.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
