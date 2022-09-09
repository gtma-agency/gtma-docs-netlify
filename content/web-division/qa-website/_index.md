---
title: "QA for a Website"
date: 2021-01-05T08:30:53-08:00
lastmod: 2021-01-05T08:30:53-08:00
weight: ""
---

## Know the Standard

In order to ensure that the deliverable is up to the quality that reflects GTMA well, and accomplished the task that we were hired to accomplish we need to know what the standard of excellence is. There are two things that will hold the standard, the design and the tech spec.

When it comes to a website, quality needs to be achieve across a number of disiplines including UX, UI, functionality, content, SEO, performance, securty, and accessibility.

### User Experience (UX)

The quality of the UX should already be integrated into the design. The sites UX will be agreed upon in the early strategy stages and so there shouldn't be any major discoveries of UX issues in the pre-launch or QA phase of the project. The only exception would be if we employed user testing before launch and found some gaps in our assumptions that needed to be addressed.

### Design (UI)

The bulk of the QA that will be documented will be in this category. Due to the dynamic nature of the web and the variables that can't be accounted for in current web design tools, there will be issues found at different screen widths. There will also be things that developers do not have a critical eye for that will need to be brought up explicitly in the QA tracker for them to fix.

### Functionality (Dev)

It's easy to make assumptions about some fucntionality based on a non-interactive design. Ideally these would all be defined in the tech spec, so that should be the standard for which this category of QA is judged against.

### Content

Content involves copy, and imagery. Where UI might be looking at the spacing around the imagery, or the styling of the text, content QA should be reviewing the copy for technical items like spelling and grammer. Content QA will also look at the content of the image and make sure it's appropriate for the section, and is supporting the copy. This QA feedback should go back to the person that developed the copy whether internal, or external. A good person to review at this level would be an account manager.

### SEO

Specifically technical SEO should be reviewed before the site launches to make sure that heading levels, alt tags and meta data are all in place.

### Performance

Every site should be tested with a Google Lighthouse audit, and score a minimum of 80 points for performance.
### Security

Because we're building in the WordPress ecosystem, secuiryt should be maintained by making sure WordPress core, and plugins are maintained and up-to-date. This will help make sure all security patches are added to the site, and leave as few vulnerabilities as possible.

In addition, we can make sure that security hardening and best practices are in place within the WordPress application (not using the admin user name, and requireing strong passwords), as well as hosting on the most robust and secure server possible
### Accessibility

We build each site with security in mind, but make sure that any site is compliant by including our A+C package with the maintenance agreement.

## Who should be doing QA

QA should be done by someone who is able to provide solutions to the issue. This requires that the reviewer is able to identify the problem, as well as the solution and describe it in such a way that the person assigned the task can complete. On a larger project, QA will need to be done by more than one person with expertise in different disciplines including dev, content, and design.

## How to us the QA Tracker

Because this is complex, we need a way to document the feedback in a way that is organized, actionable, and trackable. We use a QA tracker document set up in Google Sheets to acheive this.

The columns in the document are:

### Short Description

Briefly describe the issue

### Status

The possible options are:

* Pending - not started
* Resolved - completed as described
* Addressed - not completed, but not working on it.
* Discussion - needs more clarity

### Priority

The possible options are: 

* 0 - this is keeping other work from being done. Launch blocking
* 1 - this is important, potentially launch blocking
* 2 - not critical, could be completed post launch, but still needs to be done

### Reported by

The name of the person that identified the issue

### Assigned to

Who should be responsible for this. Can be left blank if the reporter doesn't know.

### Type

Possible options for this are:

1. Bug Fix - this doesn't match the defined design or tech spec
2. Change Order - this is a new feature that wasn't defined in the original design or tech spec
3. Issue - other issue that's not a Bug or Change

### Category

Possible options for this are:

1. Development
2. Content
3. Design

This will help determine who will fix this. On smaller projects this will be obvious, but may need to be specified in the "Assigned to" column if there are more people working on this.

### Location (URL)

Paste in the link to the page where this issue was discovered.

### Long Description

Describe in detial the solution to this issue.

## Important Instructions for leaving feedback

1. Only put one item in each line. This make is clean and simple to complete the task and move on to the next.
2. Feedback should be clear and actionable. Resist the urge to put niceties like "Please, do this... " or "Can you make this...". 
3. Use the most specific language possible. If you know from the design the number of pixels that need to be added, put that number in the task. Here are some good examples:

```
Add 16px of padding to the right side of the content area in the second section from the bottom.
Update the button color to #bada55 in the pre-footer CTA
```

Avoid vague statements that leave design decisions to the developer:

```
Can you move that button a little to the left to create more space?
Please make the background a little lighter. It feels a bit heavy for that spot.
```
