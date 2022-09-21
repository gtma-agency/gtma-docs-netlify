---
title: "Real Estate Site - Gantt Chart"
date: 2022-09-21T01:03:40-08:00
lastmod: 2022-09-21T01:03:40-08:00
weight: ""
---

<div class="mermaid">
    gantt
        dateFormat  YYYY-MM-DD
        todayMarker stroke-width:5px,stroke:#0f0,opacity:0.5
        section Strategy
        Kickoff             :kickoff, 2022-09-01, 3d
        Send Survey         :survey, after kickoff, 3d
        Discovery Call      :crit, discovery, after survey, 3d
        Review Wireframes   :wireframes, after discovery, 1d
        Present ST & SM     :crit, styletile, after discovery, 3d
        section Design
        Homepage design     :home, after styletile, 5d
        HP review    :crit, hpreview, after home, 3d
        Inner Page Design   :innerpage, after hpreview, 5d
        IP Review   :crit, ipreview, after innerpage, 3d
        section SEO
        Keyword research    :keyword, after survey, 7d
        Review Wireframes   :wireframes, after discovery, 1d
        section Development
        Spin up site        :spin, after hpreview, 1d
        Build Home Page     :buildhp, after spin, 3d
        Present Home Page   :crit, presenthp, after buildhp, 3d
        Build inner pages   :buildip, after ipreview, 5d
        Internal QA         :internalqa, after buildip, 3d
        Present Site        :crit, present, after internalqa, 3d

  </div>
