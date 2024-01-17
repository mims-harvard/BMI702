---
layout: page
title: Home
nav_order: 1
description: BMI 702 - Biomedical Artificial Intelligence

---

# [BMI 702](https://dbmi.hms.harvard.edu/education/courses/bmi-702) | Biomedical Artificial Intelligence

{: .mb-2 }
Harvard - Foundations of Biomedical Informatics II, Spring 2024
{: .mb-0 .fs-6 .text-grey-dk-000 }

<div>
	<p>
		Artificial intelligence is poised to enable breakthroughs in science and reshape medicine. This course provides a survey of artificial intelligence for biomedical informatics, covering methods for key data modalities: clinical data, networks, language, and images. It introduces machine learning problems from a practical perspective, focusing on tasks that drive the adoption of machine learning in biology and medicine. 
	</p>
	<p>
		The curriculum delves into foundational algorithms and highlights the nuances of handling biomedical data. It places a strong emphasis on strategies for evaluating and seamlessly integrating machine learning methods into biomedical research and clinical practice. A key aspect of this course is its focus on the broader implications of artificial intelligence. This includes critical discussions on topics such as trustworthiness, interpretability, evaluation, and the ethical and legal challenges associated with the implementation of artificial intelligence in healthcare.
	</p>
</div>

<div>

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}

</div>

<!-- <ul> -->
<!-- <li><b>THIS PAGE IS UNDER CONSTRUCTION. Please don’t interpret anything on this website as truth until this warning is removed. </b></li>
<li>Please read our <a href="http://www.ds100.org/su21faq">course FAQ</a> before contacting staff with questions that might be answered there.</li>
<li>The <a href="{{ site.baseurl }}/syllabus">Syllabus</a> contains a detailed explanation of how each course component will work this summer, given that the course is being taught entirely online.</li>
<li>The scheduling of all weekly events is in the <a href="{{ site.baseurl }}/calendar">Calendar</a>.</li>
<li>The Zoom links for all live events are in <a href="https://piazza.com/class/kpcl6edmxuk3fg?cid=6">@6 on Piazza</a>.</li>
<li><strong>Note:</strong>The schedule of lectures and assignments is subject to change.</li>
</ul> -->

<br>

{% for module in site.modules %}
{{ module }}
{% endfor %}