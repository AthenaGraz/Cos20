---
title: "Static or dynamic web pages on the net: What the differences are and what advantages which system brings"
date: 2021-02-16T20:23:54+01:00
draft: true
image: "linzbichler-takashi--small_V2.png"
---
![Image coputer](/Cos20/business-1839876_1920.jpg)

In his lecture, Takashi Linzbichler shows the advantages of programmes like Hugo. Why you save time during development and for which group of people they are ideal.

## 1.1 Difference between static and dynamic websites?
A **static website** does not use an external database and is written in HTML and coded with CSS. Every website visitor will receive the same information. There is no other software needed to create a static website. It is a collection of texts, images and multimedia elements. It always shows the same information each time the website is visited. Static websites are easy and cheap to develop, but it requires web development skills to update.

**Dynamic websites** are database-driven sites and contain information that changes based on factors like the time zone of the visitor, the native language or the time of the day.
The content displayed on the website is, other than the static website, stored in a CMS or a database and also updated there.
Website pages on a dynamic website are generated in real time, based on the visitors data. This also happens with website cookies, that are stored on the visitor’s computer. A dynamic website also not just only uses HTML and CSS but many other coding languages.
It is easier to update and offers more functionality than a static website, but can be more expensive to host and have longer loading times.

## 1.2 What is a Content Management System (CMS)?
A CMS is software that is used to create and manage content - in text, image, video or other forms. CMS are mainly used for operating websites, but also for "offline platforms" (like in intranet networks). They can either be installed locally on a dedicated server (in the company) or run on a provider's server to which the user is given access. Well-known CMS are often open-source (e.g. Wordpress) and enable non-developers to build websites without coding skills.

**Some advantages of having a CMS are:**
+ Easy to use
+ multiple users can work in the back end at the same time
+ SEO Features
+ Plugins
+ Templates
+ simple updates

## 1.3 What is a Static Website Generator, how does it fit into the systemic view derived from questions 1.1 and 1.2?
A static website generator is a code framework that serves as the basis for static websites. Content is not stored in a database as with a CMS like mentioned before. The complete HTML code is stored on the developer's PC and is later uploaded to the server.

All files are stored in directories, and are separated in folders for content and design. Therefore, design changes can easily be made without changing the actual content.

Installation and operation are performed via the command line, like in HUGO.
Static site generators apply data and content to templates and generate websites that way.

Websites created through a static website generator differ from those mentioned in 1.1 and 1.2 because they are easier to use in terms of updating the website and the general development workflow. All data is located in one folder. This can be managed in a GitHub directory. This means that there is no need to update a CMS or to manage modules and data libraries.

## 1.4 How does it defer from a 'classical' CMS?\+ 1.5 Benefits vs. Drawbacks of Static Website Generators?
A **CMS** develops the web page dynamically in real time, as the client is requesting it and processes all the data from the database through an engine like Wordpress. Also, a CMS can integrate interactive features easily - this can be essential for building a website that requires forms or user accounts.

When a user requests a page on a **static site**, the request is being sent to the web server. The web server then finds the matching file there and sends it to the user. This makes a static website load very fast.

&#9989; good SEO rating because of  
&#9989; fast loading times   
&#9989; cheap hosting   
&#9989; high level of security   
&#9989; version control (git)   
&#9989; markdown support


&#10060; requires more knowledge than a CMS   
&#10060; requires more time to get started   
&#10060; there is no administration or user interface   
&#10060; no user-generated content

## 1.6 How does a typical Static Website Generator (e.g. Hugo) work?
Static Website Generators take content stored in files (not in databases) and apply that to templates and generate a structure of static HTML files. Therefore, SWG’s can be seen as publishing tools.

The content is written using Markdown and the template engine is based on the Go templates. Hugo is written in the Go programming language.

### 1.6.1 What type of input data is being used?
There is no database, so the input consists of only files and folders that run through a templating engine.

### 1.6.2 What type of output data is being generated?
The output is a static site (HTML) that is taken by the developer and deployed to the server.
When the website is requested by a user, the server matches those files and sends it back to the user.

![Image cms](/Cos20/cms-265127_1920.jpg)

## 1.7 Use cases for Static Website Generators?
Static site generators are ideal for developers who want a small website and build it themselves. Regarding Content Strategy students, static website generators could be used to create static, personalized portfolio or blog websites.

**Use cases:**
+ Blogs
+ Portfolios
+ Newsletter content
+ Forms

## 1.8 Where do you find/set the SEO- and accessibility-related stuff in a Hugo site/theme?

- **Config File:** Meta information like author name, Social Media, github link, etc. can be written in the config.toml file
- **Google Search Console:** You can also add your website into the Google Webmasters Console. Google needs to verify your ownership and the sitemap.xml has to be submitted for indexing.
- **Hugo Themes:** Review templates in order to find the most suitable templates that respond better, handle RSS better or make it easy to work with social media. There are some themes that are built for better SEO performance to find.
