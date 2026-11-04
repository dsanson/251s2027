---
title: '{{< meta course.title >}}'
subtitle: "PHI {{< meta course.number >}} ({{< meta course.term >}} {{< meta course.year >}})"
image: media/minujin-marta-la-invasion-de-la-mente-1984.jpg
image-alt: "A scupltural bust coming apart into vertical slices"
image-title: "Marta Minujín, La Invasión de la Mente (1984)"
image-url: https://artsandculture.google.com/asset/la-invasión-de-la-mente-marta-minujín/8wFkVEjRsyrknA
format:
  html:
    toc: false
    template-partials:
      - templates/empty/title-block.html
      - templates/empty/title-metadata.html
    format-links:
      - html
    include-in-header: 
      - text: |
          <style>
            h2.index-title {
              border-bottom: 0;
              padding-bottom: 0;
              margin-bottom: .2em;
              margin-top: 0;
            }
            h3.index-subtitle {
              margin-top: 0;
              margin-bottom: 1em;
              font-size: 1.2rem;
            }
          </style>
---

:::: {layout="[ 70, 30 ]"}

::: {#first-column}

## {{< meta title >}} {.index-title}

### {{< meta subtitle >}} {.index-subtitle}

I will not use Canvas, so this is our course webpage.
To stay on top of readings and assignments, you need to
check the [schedule](schedule.md), come to class, and pay attention to in-class announcements. 

There is no online grade book, so if you want to know 
your grade, either you can calculate it yourself or you can ask me!

See the [syllabus](syllabus.md) for more details about the course topic and course assignments.

I am teaching two sections of this course. Attend the section for which you are enrolled.

Class Meetings
:  {{< meta course.meeting.1.time >}}, {{< meta course.meeting.1.place >}}.
:  {{< meta course.meeting.2.time >}}, {{< meta course.meeting.2.place >}}.

Office Hours
:   {{< meta course.office-hours.time >}}, {{< meta course.office-hours.place >}}

:::

::: {#second-column} 

![[{{< meta image-title >}}]({{< meta image-url >}}){style="color: hsl(0,0%,40%); font-size: .9rem; text-align: center;"}]({{< meta image >}}){alt="{{< meta image-alt >}}" .lightbox }

:::

::::

