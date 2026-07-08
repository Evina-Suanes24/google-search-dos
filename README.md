# Google Search Clone

Live Demo: [Insert GitHub Pages URL Here]

## Project Overview

This project is a functional front-end clone of Google Search, Google Image Search, and Google Advanced Search. It demonstrates the ability to map HTML forms to external server endpoints using HTTP GET parameters, all styled with CSS to match Google's core aesthetics.

## Team Members & Responsibilities

This project was developed collaboratively using a strict Git Feature Branch Workflow.

- [Evina Suanes]&#58; Standard Google Search Page & "I'm Feeling Lucky" Button

- [Gilbert Aquino]&#58; Google Image Search Page & Navigation

- [Mark Edzon Araojo] &#58; Google Advanced Search Page & CSS Styling


## Technical Architecture (URL Parameters)

This application successfully routes search queries to Google's servers by passing the following GET parameters through HTML forms:

- **q**: The primary search query input.

- **btnI**: Triggers the "I'm Feeling Lucky" redirect bypass.

- **tbm=isch**: Hidden parameter used to route directly to Google Images.

- **as_q**: Advanced Search - "all these words".

- **as_epq**: Advanced Search - "this exact word or phrase".

- **as_oq**: Advanced Search - "any of these words".

- **as_eq**: Advanced Search - "none of these words".


## Collaboration Workflow

Our team managed the codebase using Git Feature Branch Workflow. Each member created their own feature branch, worked on their assigned feature, committed changes, and submitted pull requests for review before merging into the main branch.

We encountered minor merge conflicts while combining updates from different branches. We resolved them by pulling the latest changes from the main branch, manually fixing conflicts, and testing the website before completing the merge.