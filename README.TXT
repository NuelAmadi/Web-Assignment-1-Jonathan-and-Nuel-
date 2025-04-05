README - Task Assignment

Team Members:
- Jonathan
- Nuel

Task Distribution:


Part 1: Re-designing the Website

Content Review & Planning
- Review feedback from Assignment 1: Jonathan
- Decide on whether to reuse or create new content: Jonathan & Nuel

HTML Structure & Layout
- Rebuild page structure using semantic HTML5: Nuel
- Ensure consistency across pages (header, footer, main sections): Jonathan

CSS Design & Responsiveness
- Integrate normalize.css: Jonathan
- Define media queries for breakpoints (590px, 790px): Jonathan
- Style layout for:
  - Small devices (1-column format): Jonathan
  - Medium devices (2x2 grid layout): Nuel
  - Large devices (centered layout with fixed width): Jonathan

Images, Media & Assets
- Add images with alt tags: Jonathan
- Test all links and media: Jonathan & Nuel


Part 2: Accessibility Analysis & Improvements

Manual and Automated Accessibility Issues Identified:

Perceivable Issues:
- [Describe issues found related to perceivability, e.g., missing alt tags, low color contrast]

Operable Issues:
- [Describe issues found related to operability, e.g., inaccessible navigation, keyboard traps]

Understandable Issues:
- [Describe issues found related to understandability, e.g., confusing UI, inconsistent labels]

Robust Issues:
- [Describe issues found related to robustness, e.g., outdated ARIA attributes, HTML validation errors]

Generalized Changes Made:

Types of Issues Created:
- [Briefly summarize the types of accessibility problems that emerged during development]

Generalized Changes Implemented:
- [Summarize the types of changes made to address those issues, such as improving semantic HTML, adding ARIA roles, enhancing keyboard support, etc.]


Documentation, File Structure & Submission

- List of tasks and team roles: Jonathan
- Accessibility findings and changes made (perceivable, operable, understandable, robust): Jonathan & Nuel
- Organize files into correct folder structure: Jonathan
- Ensure correct naming conventions and zip folder: Nuel
- Submit to correct drive location: Nuel

Both members will be involved in the review and final testing of the website on multiple devices.


Automatic Accessibility Testing Summary:

We used the WAVE browser extension to test all three pages of our website: the homepage, about page, and contact page. The goal was to identify any accessibility issues that could affect users with visual or motor impairments, or those using assistive technologies like screen readers.

Homepage: The WAVE tool flagged a few alerts, including redundant title text on some images and heading structure issues. We resolved the redundant title text by removing repeated title attributes that matched the alt text. The heading structure was also reviewed to ensure it followed a logical order, with a single <h1> and appropriate use of <h2> and <h3> tags. After these changes, the homepage passed the accessibility check without further issues.

About Page: On the about page, WAVE identified redundant title text, table structure warnings, and a few contrast issues. We removed unnecessary title attributes from images to address the redundancy. For the table, we added a clear caption and added scope attributes to the column headers to improve screen reader support. The page now has a valid and accessible table structure. The contrast issues were not resolved at this stage.

Contact Page: The contact page had a couple of alerts related to form accessibility. These included orphaned form labels and missing fieldsets around related form elements. We fixed these by making sure every label was properly connected to its input using for and id, and we grouped related checkboxes and radio buttons inside <fieldset> tags with a <legend> to describe the group. We also removed one redundant image title attribute. After these updates, the page passed the WAVE tool's checks.

Overall, using WAVE helped us catch a number of issues that weren’t obvious at first. While not every issue was fully addressed (like contrast errors), we made meaningful changes that improved the accessibility and usability of the site for a wider range of users.
