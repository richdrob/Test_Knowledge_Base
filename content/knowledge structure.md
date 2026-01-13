---
title: Knowledge Structure
draft: false
tags:
  -
---
# Core Concept

We've taking a good amount of time to think of the best way to organize our knowledge.  A problem that has occurred with our previous knowledge is making sure we have a way to ensure our documentation is reviewed and kept up to date.  At the same time, If we organize our knowledge too much, it becomes compartmentalize and hard to use the knowledge on a daily basis.  With what we believe the core issues with our current system identified, we set the following goals for organizing our knowledge.

- Our knowledge should be organized in the way that makes completing yearly audits of our knowledge easiest
- Our knowledge needs to be written in a way that makes it easily searchable.
- All parameters and properties of a knowledge article/document needs to be easily and consistently replicated for all team members.

We plan on on achieving these goals using a combination of a comprehensive folder structure, [[tags]] and [[properties]] to ensure our documents remain organized 
### File and Folder Structure

We've taking a good amount of time to think of the best way to organize our knowledge.  A problem that has occurred with our previous knowledge is making sure we have a way to ensure our documentation is reviewed and kept up to date.  to make the process of reviewing documentation and knowledge easier, we will be using folders to organize the top of the structure by `service owner`.  In this folder, we will include an index page for the service owner that covers their services, contact information, and our specific contact for reviewing documentation (which will have a review data in the [[properties]]).  We will then create individual folders for separate `services`, `sub-services`, and any additional delineation that is needed.

>[!example]-
>Here is a static version of what a file structure may look like starting left to right:
>` UMnet > Umnet.md, WiFi, Network, NSO, Firewall> subfolders of services`

We've gone with this approach to make review of our documents as easy as possible.  We can work with each individual service owner to find the best strategy for both teams to review that our information is up to date.
### Tagging to reduce rigidity

We will then use [[tags]] to create groups of documents based of several different.  We have talked about this extensively in it's own document so we recommend reviewing it!  

The use of tagging will allow us to finely hone our searching capability, making finding our documents easier.  Induvial staff members could even use tags as way to make their own "bookmarks" to assist with searching.

> [!example]-
> Joshua and Rich work weekly on network availability metrics, they create the tag #jtfav and #rdfav and apply this tag to the `jasper network metrics` markdown file.  This allows them to add this tag to their search bar and it will identify this article and any others with the tag.

### Creating standardized properties

It is possible to use [[properties]] to create a text property with any alias.  If we standardize this information across all of our articles with can make reviewing and updating our articles easier.  Some example properties include:

```
Date Created:  <mm;dd;yyyy>
Date Reviewed: <mm;dd;yyyy>
Service Owner: [[Service Name]]
Service Owner Contact:  [[contact name]]

```

By adding this information to each file, it will enable us to create programs using this information.  We could create a script to automatically create a spreadsheet of every document for a specific service that can be sent to a service owner for review.  We can create a RSS feed that sends a message or email anytime an article's `Date Reviewed` is older than 1 year.  this can then be stored and run within our [Github Organization](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/about-organizations), keeping them safe and secure.  
### Integrating Teamdynamix

In any circumstance where we have an existing Teamdynamix article we use, we will continue to use this.  We will create an individual markdown file that will externally link to the relevant article.  Additionally, we will create a template to create a new TDx article for any article that cannot be added to Teamdynamix for security or technical reasons (an example of this would be the `spectrum alarm operator response` spreadsheet which is too big and contains too much sensitive information to add to the TDx KB).

---

We have included a [canvas](https://obsidian.md/canvas) in the `content` folder of this site which can be viewed using [obsidian](https://obsidian.md/) (we are working on a way to integrate canvas' soon!).  This shows a more visual view of how the file structure will work.
# Feedback needed

This is by no means the final form of this system.  We want to hear from you on how this system could work better for everyone, or specific things from the previous website that would need to be included in our new site.


