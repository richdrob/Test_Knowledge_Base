---
title: Welcome to the IOC Test Site
---
---
title: Welcome to the IOC Test Site
---

This is a proof of concept prototype of a potential replacement to the ITS Data Center Operations Google Site.  The website is built in [GitHub](https://github.com/) pages, using a markdown to html converter called [quartz 4](https://quartz.jzhao.xyz/).  We used a markdown editor called Obsidian to write and edit the individual pages on this site.  While this is the recommended way to work, it is possible to write articles using any text editor as long as they following the [syntax](https://www.markdownguide.org/basic-syntax/) used for markdown.

 We've included a few examples of different features, such as [[internal links]], [[tags]], and [[properties]].  We made sure to include some examples of critical functions of current google site, including a [[turnover]] page, and an [[example home page]].  We will also go over how we plan to organize the website using a [[knowledge structure]], allowing us to keep our information up to date and assist with #training new staff members.    Check out our list of pros and cons below and take some time to explore all this demo has to offer!

Current Progress for the Site Prototype:

- [x] Setup Obsidian for current site admins
- [x] Setup Visual Studio Code with [quartz 4](https://quartz.jzhao.xyz/) prerequisites
- [x] Configure GitHub Repository for SSH sync using NPM
- [x] Host site locally to confirm configuration
- [x] Sync site changes to the GitHub repo
- [x] Create Demo Documents for the site
- [ ] Receive feedback from IOC Manager and Staff
- [ ] Finalize configuration changes

## Pros

Here are some of the the features that we think are really cool!

#### Easy to Document and manage

Creating and adding files to the site is no harder than using [OneNote](https://onenote.cloud.microsoft/) or [Microsoft Word](https://word.cloud.microsoft/).  It would be very easy to train new employees on both how to write documents, and how to be a site administrator.

#### Version control and redundant knowledge protection

Using [Github](https://github.com/) pages means we receive the same option to clone, pull and run jobs on our website.  This will ensure that we always have a reliable backup of our site while working on changes for the next update.  We also will have all of our documents stored locally in the form of markdown files.  This ensures that even in the most catastrophic event of an entire site or service shutdown, we never have to worry about losing our knowledge.

This would also allow us to start storing other code related tasks in a [GitHub Organization](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/about-organizations).  We could then use this as a springboard to automate other processes (I'm looking at you [[Knowledge Review Process]]!!).

#### Follows all ITS Security rules regarding sensitive data

Once we create a [GitHub Organization](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/about-organizations), we will be able to limit access to this site to only the individuals we invite to the repository.  This adds the website behind the SSO barrier, which is the same as the [Teamdynamix Knowledge Base](https://teamdynamix.umich.edu/TDClient/30/Portal/Home/) and [Google Drive](https://drive.google.com/).  

#### Powerful features

Features like `in line code`, for easy copy and past strings.  The ability to update all [[internal links]] when you rename them, saving you from having to update every single article individually.  A find and replace plugin that can be used on every document on the site.  Any feature available in the markdown language, the version control of [GitHub], and the highly customizable nature of [Obsidian] gives us a vast array of tools to make organizing and updating our knowledge pain free.

## Cons

#### Site management will require site administrators

While editing individual documents to add to the site is easy, managing the overall website will require more in depth training.  This causes two main issues.  First, we need to create #training for specific staff members to become site administrators (preferably having one available during each shift).  Second, A [[Knowledge Submission Process]] (coming soon) will need to be created so that staff members who with to continue using their preferred tools can submit articles and knowledge to the website.

#### No concurrent editing allowed*

While there are ways to allow us to make changes to the site concurrently, they have not been implemented yet.  

> [!info] This is a problem with a potential solution, but further managerial input will be required
#### Not fully integrated with the TDx Environment

Due to restrictions in embedding articles from the [Teamdynamix Knowledge Base](https://teamdynamix.umich.edu/TDClient/30/Portal/Home/), we are not able to add and sync our knowledge.  We will need to rely on external linking, to articles within the KB on this site, which is the same system we used with the google site.

#### Cost

In order to create a [Github Organization](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/about-organizations), there is an associated fee.  Rich has more info on what those costs would be.


___
<script src="https://giscus.app/client.js"
        data-repo="richdrob/Test_Knowledge_Base"
        data-repo-id="R_kgDOQ1r6XQ"
        data-category-id="DIC_kwDOQ1r6Xc4C0tJf"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="bottom"
        data-theme="preferred_color_scheme"
        data-lang="en"
        crossorigin="anonymous"
        async>
</script>

