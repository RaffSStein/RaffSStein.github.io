---
layout: page
title: About
permalink: /about/
weight: 3
---


# **About Me** <span><a href="/assets/cv.pdf" class="btn btn-info" id="cv-button">CV</a></span> 
Hi there!

I'm {{ site.author.name }}, a Software Engineer based in Italy, currently working at Accenture. I have 5+ years of experience designing and delivering high-scale, event-driven solutions in the finance and insurance markets, with deep expertise in Spring/Spring Boot and Quarkus, in both Java and Kotlin. I’ve led teams and mentored junior engineers, and I’m passionate about coding and video games, and about building clean and efficient software systems.

My interests revolve around cloud technologies, AI applied to code generation and automation, software architectures, game development, and personal finance. I constantly explore how these areas intersect and evolve.

I hold a degree in Software Development, which gave me a strong foundation in designing and building applications—from backend systems to interactive interfaces.

I’m always eager to learn new tools and frameworks, tackle complex problems, and take on new challenges that push me to grow as a developer.

<div class="row skills-row">
{% include about/skills.html title="Programming" source=site.data.programming-skills %}
{% include about/skills.html title="Frameworks/Libraries" source=site.data.frameworks-skills %}
</div>
<div class="row skills-row">
{% include about/skills.html title="Tools" source=site.data.tools-skills %}
{% include about/skills.html title="Web" source=site.data.web-skills %}
</div>
<div class="row skills-row">
{% include about/skills.html title="Languages" source=site.data.languages-skills %}
<div class="col-lg">
  <h2 class="mb-3">AI</h2>
  <p>I actively apply AI to day-to-day coding and build with it.</p>
  <p>
    {%- for tech in "Spring AI,Ollama,GPT-5,Hugging Face,LangChain,Agentic AI,GitHub Copilot" | split: "," -%}
    <span class="badge badge-pill text-primary border border-primary ml-1">{{ tech }}</span>
    {%- endfor -%}
  </p>
  <h2 class="mb-3 mt-4">More tech</h2>
  <p>
    {%- for tech in "TypeScript,Angular,Redis,Terraform,Elasticsearch,ELK,Splunk,Micrometer,JMeter,Spring Security,Hibernate,MongoDB,RabbitMQ" | split: "," -%}
    <span class="badge badge-pill text-primary border border-primary ml-1">{{ tech }}</span>
    {%- endfor -%}
  </p>
</div>
</div>