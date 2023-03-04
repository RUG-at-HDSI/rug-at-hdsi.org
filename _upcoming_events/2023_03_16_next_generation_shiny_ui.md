---
title: "Towards the Next Generation of Shiny UI"
event_date: "March 16th, 2023"
time: "5 PM - 6 PM ET"
layout: single
poster_png: ""
blurb: |
  Shiny, the R package for creating interactive web graphics, recently celebrated its 10th birthday. Since then, Shiny has grown tremendously in many areas (e.g., performance, functionality, extensions, etc); however, a "hello world" Shiny app still looks like it did 10 years ago. This is mostly because Shiny goes to great lengths to ensure backwards compatibility; and as a result, default Shiny UI will likely continue to be based on Bootstrap 3 (a CSS styling framework released in 2010). However, thanks to the new bslib R package, it is now easy to opt-into a modern Bootstrap 5 foundation that "just works" with Shiny, R Markdown, flexdashboard, pkgdown, bookdown, and more.  <br><br>

   In addition to upgrading Shiny's Bootstrap dependency, bslib also makes it much easier to do custom theming, leverage modern layout techniques, and create custom components (all from R without any CSS/HTML/JS required). At this point, bslib is still maturing, and does not yet provide what we'd consider a "complete UI toolkit", but it should eventually replace and/or improve upon all of Shiny UI. In this talk, I'll highlight bslib features that we're most excited about (e.g., expandable cards, accordions, (sidebar) layouts, input controls, etc.), discuss some best design practices for improving user experience with these tools, and present some real world examples of these tools in action.
registration_link: https://harvard.zoom.us/meeting/register/tJMtc-2tqj4iHdXy8u3Kd0f82viGy7W5MuEm 
---

#### Join us {{ page.event_date }} at 5pm Eastern Time!

<a href="{{ page.registration_link }}"><img src="{{ page.poster_png }}"></a>

<p>{{ page.blurb }}</p>

Registration Link: <br>
<a href="{{ page.registration_link }}">
{{ page.registration_link }}
</a>

## Bio 

Carson is a software engineer on the Shiny team at Posit. He joined Posit in 2018, and in recent years, has focused primarily on Shiny for Python and improving Shiny UI. The Shiny UI work has manifested in the creation and development of many R packages such as bslib, thematic, htmltools, htmlwidgets, sass, shiny, rmarkdown, flexdashboard, and more. Carson also has a PhD in statistics, is a recipient of the ASA's Chambers Statistical Software Award, has maintained the R package plotly since 2015, authored the book "Interactive data visualization with R, plotly, and shiny", and ran a successful freelance consulting service for numerous years.
