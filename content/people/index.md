---
title: "Home"
type: landing

design:
  spacing: "6rem"

  ---

## Why Hugo Blox?

- **Launch in Minutes, Not Months:** Pick a template, customize with drag-and-drop blocks, and deploy. Build anything from SaaS landing pages and online courses to academic resumés and lab sites.
- **Own Your Content & Brand:** You get static files with no vendor lock-in, leading to 100/100 Lighthouse scores. Your content, your rules.
- **Built for a Technical Workflow:** A modern stack with Hugo and Tailwind CSS. Write in Markdown, Jupyter, or BibTeX. Auto-sync publications.
- **Open & Extendable:** Start with a generous MIT-licensed core. Upgrade with premium templates and blocks or extend with React "islands" for custom interactivity.

<p align="center">
  <img src="./.github/media/templates.webp" alt="Template previews" width="900">
</p>

<p align="center">
  <a href="https://hugoblox.com/templates?utm_source=github&utm_medium=readme"><b>Browse Templates →</b></a>
</p>

---

sections:
  - block: hero
    content:
      title: Quiénes somos
      text: MetaDocencia es una organización sin fines de lucro fundada en 2020. Nuestra comunidad construye capacidades científicas locales para transformar la ciencia global. Hacemos crecer la ciencia en red, desde América Latina hacia el mundo.
    primary_action:
        text: Nuestra Gobernanza
        url: https://hugoblox.com/templates/](https://www.metadocencia.org/suscripcion/
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      background:
        image:
          filename: quienessomos.jpg
          filters:
            brightness: 0.3
        text_color_light: true
    
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Vamos por 5 años más
          text: Durante nuestros primeros 5 años tejimos lazos entre más de 2,000 profesionales de ciencia y técnica. Lo hicimos trabajando en equipo, de manera colectiva y colaborando con más de 40 comunidades. Gracias por estos primeros 5 años de aprendizaje, colaboración y crecimiento. ¡Vamos por 5 años más!
          # Upload image to `assets/media/` and reference the filename here
          image: quienesomos.jpg
          button:
            text: Conócenos
            url: https://hugoblox.com/templates/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
    
  - block: stats
    content:
      items:
        - statistic: "+1,000"
          description: |
            personas en Slack
        - statistic: "+40"
          description: |
            socios y patrocinadores
        - statistic: "88"
          description: |
            personas contribuyen a nuestro trabajo
        - statistic: "+6000"
          description: |
            personas conectadas en redes sociales
        - statistic: "+2600"
          description: |
            personas suscriptas a nuestro boletín
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, "1rem", 0, "1rem"]

  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Researchers
          - Grad Students
          - Administration
          - Visitors
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
---
