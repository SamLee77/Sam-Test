
# Overview of Express User Documentation

Welcome! 👋 This documentation will guide you through setting up a [**Node.js**](https://nodejs.org/) project for building small to medium-scale RESTful APIs using [**Express.js**](https://expressjs.com/).

The goal of this documentation is to provide you with enough information to build your first Express application. We will also focus on best practices and various ways to optimize workflow when working collaboratively.

These are the topics of this document

- Structuring project files
- Enforcing code standards
- Installing Express
- Writing routes
- Using middleware

## How We Collaborated Together

This user guide assignment occured while our classes were completely held online. Our main form of communication was over Discord instant messaging after we brainstormed our guide idea and instruction outline over Zoom.

We used Git and GitHub to collaborate on the documentation. With every new page, we would create a new branch to keep our work seperate until we were ready to merge to the master branch. 

## How We Created Our Guide

Our guide was created using our knowledge from setting up and using Express servers in COMP 2523 Object Oriented Programming 1. We referenced the official [Express documentation](https://expressjs.com/) to supplement our experiential knowledge. We reflected on the difficulties we had encountered while working with Express and in group projects to keep our instructions clear, complete, and concise.

### Using MkDocs

We chose to use MkDocs as our static site generator as we liked the appearance of the [Material for MkDocs](https://github.com/squidfunk/mkdocs-material) theme and the components provided by MkDocs. One of our team members had access to additional plugins which gave us the flexibility to customize the appearance of our documentation even further.

### Using Markdown

This was the first time writing extensively in markdown for two of our three group members. We learned how to style text using markdown from our COMM 2116 Business Communications 2 and developed our skills over the course of writing this documentation. 

### Using VS Code

All three members of the group used VS Code to write our markdown files. We previewed the markdown using VS Code's built-in markdown preview but we had to serve our guide with MkDocs to see the accurate rendering of our styles.

### Using a Style Guide

We loosely used the [Google Developer Documentation Style Guide](https://developers.google.com/style) to give our writing uniformity. We had previous used this style guide and its clear documentation made it an attractive style guide to reference.

### Learning Best Practices For Web Writing

In addition to user guides, developers also write documentation for their peers and company stakeholders. Most of this writing exists in a web format. As such it is important to construct documents that maximize readibility on the web.

#### Readability

People read technical writing to retrieve information and not for pleasure (typically). We streamlined our writing to be clear, concise, and complete to provide the necessary information as effectively as possible. Key words were bolded for scannability and we used figures and lists whenever possible.

We ensured that every procedure page had an overview that would give the reader a preview of the topic before going through the detailed steps. At the end, we included a conclusion to summarize what the reader would have accomplished from following the guide. 

We used MkDoc's admonitions to highlight any information we wanted to stand out to the reader. 

<figure>
  <figcaption>Specifies actions that may cause an error or will cause the application to crash.</figcaption>
  <img
  src="docs/pages/images/admonitions/danger.png"
  alt="The danger admonition.">
</figure>
<figure>
  <figcaption>Specifies actions that may lead to unexpected behaviour.</figcaption>
  <img
  src="docs/pages/images/admonitions/failure.png"
  alt="The failure admonition.">
</figure>
<figure>
  <figcaption>Specifies actions that may cause an error.</figcaption>
  <img
  src="docs/pages/images/admonitions/bug.png"
  alt="The bug admonition.">
</figure>
<figure>
  <figcaption>Specifies content that must be read before proceeding.</figcaption>
  <img
  src="docs/pages/images/admonitions/warning.png"
  alt="The warning admonition.">
</figure>
<figure>
  <figcaption>Indicates additional information or tips.</figcaption>
  <img
  src="docs/pages/images/admonitions/info.png"
  alt="The info admonition.">
</figure>
<figure>
  <figcaption>Indicates what success looks like.</figcaption>
  <img
  src="docs/pages/images/admonitions/success.png"
  alt="The success admonition.">
</figure>

#### Chunking
Due to the nature of our topic, we anticipated long informative pages. This can easily become difficult for a reader to follow. Knowing this, we focused on using sub-headings and figures to guide the reader.

We achose a navigation style (from MkDocs) that would show the subheadings for the current page as nested links. This allows our reader to gauge the relevancy of the material and to jump to a specific section if they desired.
  
#### Tone
This documentation is intended for the following users who are searching for a clear guide to setting up Express for a collaborative project:

- Beginner to intermediate developers who need to setup a backend for a personal project.
- Software development teams working on small or medium-sized web applications.

Therefore, we chose to write in a casual tone as if we were explaining to a peer. We kept the jargon to a minimal as we did not want to confuse any beginner coders. Any specialized terminology included a hyperlink to an external resource if the reader needed further explanation. 



  


## Conclusion
> write conclusion...

This document was built on: [Material for MkDocs](https://github.com/squidfunk/mkdocs-material)