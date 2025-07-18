---
layout: page
title: About
permalink: /about/
weight: 3
---


# **About Me** <span><a href="/assets/cv.pdf" class="btn btn-info" id="cv-button">CV</a></span> <span><a href="/assets/resume.pdf" class="btn btn-info" id="cv-button">Resume</a></span>
:wave: Hi there!

:pushpin: I'm {{ site.author.name }}, a Software Engineer based in Bari (Italy), currently working at Accenture. I’m passionate about coding and video games, and I enjoy building clean and efficient software systems.

:video_game: My interests revolve around cloud technologies, AI applied to code generation and automation, software architectures, game development, and personal finance. I constantly explore how these areas intersect and evolve.

:mortar_board: I hold a degree in Software Development, which gave me a strong foundation in designing and building applications—from backend systems to interactive interfaces.

:rocket: I’m always eager to learn new tools and frameworks, tackle complex problems, and take on new challenges that push me to grow as a developer.

<div class="row skills-row">
{% include about/skills.html title="Programming" source=site.data.programming-skills %}
{% include about/skills.html title="Frameworks/Libraries" source=site.data.frameworks-skills %}
</div>
<div class="row skills-row">
{% include about/skills.html title="Tools" source=site.data.tools-skills %}
{% include about/skills.html title="Web" source=site.data.web-skills %}
</div>