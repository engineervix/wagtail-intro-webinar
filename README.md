# Webinar - Introduction to Wagtail

These are the slides I curated for a Webinar I hosted on 2024-05-30.

Slides powered by [Slidev](https://github.com/slidevjs/slidev)!

To start the slide show:

- `npm install`
- `npm run dev`
- visit http://localhost:3030

Edit the [slides.md](./slides.md) to see the changes.

Learn more about Slidev at [sli.dev](https://sli.dev/).

## Webinar Outline

> The idea is to be more engaged with participants - shouldn't be a one-man show

0. Provision for late joiners (3min)
1. Quick introductions (5min)
   - who you are
   - what you do
   - any other fun stuff
2. Possibly do a quick poll (show of hands) to determine (2min)
   - people who are not devs
   - people who know Python
   - people who know Django
3. Present (15min)
4. Q and A (10min)
5. Demo / Q & A (25min)
6. Feedback (provide link)

## Presentation Outline and Notes

0. Opening Slide     <!--show at webinar.start() -->
1. `whoami`            <!--for item 1 of the webinar -->
2. TOC
3. Wagtail
    - Name (and logo)
    - since 2014 (v0.1 on Feb 9, 2014, v1.0 on Jul 16, 2015) [Wordpress came out May 2003, Django came out in Jul 2005, Laravel in June 2011]
    - show github stars history
    - A content management system
        - A content management system (CMS) is a software application that is used to manage digital content (such as web pages, blog posts, etc.), 
        - allowing multiple contributors to create, edit and publish.
        - Workflows assigns permissions for managing content based on roles such as authors, editors and admins
        - focus on **content** - lifecycle, diversity, workflows
4. Wagtail is not
    - a one-size-fits-all solution
    - a blog engine
    - a WYSIWYG website builder for beginners
    - limited to specific front-end frameworks
        - With the Wagtail templating system, your designers and frontend developers have complete frontend freedom. Wagtail can be integrated with the frontend technology of your choice, and you can even choose to operate Wagtail as a headless CMS with multiple frontends.
5. Key Features
    - Open Source 
        - license
        - great community [GitHub, Slack, StackOverflow, etc.]
        - public roadmap and regular releases
        - well documented
    - Tech
        - Python: Wagtail is built in Python, one of the most popular global programming languages, used widely in machine learning and big data.
        - Django
    - highly scalable, extensible and flexible
        - Wagtail can be scaled up to handle traffic from millions of visitors every month as well as be extended to include data tools and rich data visualizations. It meets Google’s strict security standards and multiple Wagtail sites run on the google.com domain.
    - control over content display and organisation
        - Editors love it because they have the freedom to build pages the way they want to without coding. Developers love it because StreamField gives them precise control over how content is displayed and how data is organised.
    - reusable content
        - With snippets, there’s no need to waste time recreating components. Snippets offer developers a quick way to add reusable components to the intuitive Wagtail administrative panel so editors can use them over and over again.
    - image / document management 
        - With the image focal point and custom cropping tools in Wagtail, you have more control over how images are cropped and displayed. The multiple image upload and image deduplication features also help you keep your image library organised and under control
    - form builder
        - Empower your content creators to interact with readers with the Wagtail custom form builder. After some simple configuration on the backend, editors can use the easy configuration of Wagtail forms to create contact forms, surveys, and more.
    - custom publishing workflows
    <!-- numeronym. Numeronyms are a type of abbreviation where numbers are used to represent the number of letters omitted between the first and last letters of a word. -->
    - i118n & localisation
        - Internationalization is the process of designing a software application so that it can be adapted to various languages and regions without engineering changes
        - localisation = adapting a product's translation to a specific country or region. It is the second phase of a larger process of product translation and cultural adaptation (for specific countries, regions, cultures or groups) to account for differences in distinct markets, a process known as internationalisation and localisation.
    - a11y
        - The Wagtail team aims for compliance with Section 508, WCAG 2.1 (AA level) and ATAG 2.0 (AA level). Wagtail comes with several built-in features to support users with accessibility needs and an accessibility checker to encourage accessible content creation. We are also proud Wagtail CMS is a trusted tool used by the Royal National Institute of Blind People.
    - focus on sustainability
        - Committed to reducing the climate impact of Wagtail CMS, our software includes green features that encourage sustainable web practices. The Wagtail team has also committed to measuring the impact of Wagtail and has put together a sustainability roadmap to track our progress.
<!-- // 6. Wagtail is for you if...[add these to No. 5, as required]
    - You need a highly customizable CMS
    - You want a CMS that scales
    - You value developer experience
    - You prioritize content editing experience
    - You want a CMS with a strong community
    - You want a CMS that integrates with other tools -->
6. Q & A, then Demo
    - setup a new project
    - create some models
    - add templates
    - add content
7. Questions, then end

## Feedback -- menti.com

**General Feedback:**

-   Overall, how would you rate this webinar? (Scale of 1-5 or 1-10)
-   Did the webinar meet your expectations? Why or why not?
-   What was your biggest takeaway from the webinar?
-   What was the most helpful part of the webinar?
-   What was the least helpful part of the webinar?
-   Would you recommend this webinar to others? Why or why not?
-   How likely are you to attend future webinars on Wagtail or related topics?

**Wagtail-Specific Feedback:**

-   Before this webinar, had you heard of Wagtail?
-   After this webinar, are you more or less interested in using Wagtail for your website?
-   What specific features of Wagtail are most appealing to you?
-   What concerns or questions do you still have about Wagtail?
-   How would you compare Wagtail to other CMS platforms you've used?
-   Do you have any specific use cases or projects in mind where you think Wagtail would be a good fit?

**Content and Presentation Feedback:**

-   Was the content relevant and informative?
-   Was the presentation engaging and easy to follow?
-   Were the visuals (slides, demos, etc.) helpful in explaining the concepts?
-   Did the speaker(s) answer your questions clearly and thoroughly?
-   Was the pace of the webinar too fast, too slow, or just right?
-   How would you rate the speaker's knowledge and expertise on Wagtail?
