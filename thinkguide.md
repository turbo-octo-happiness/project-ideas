# ThinkGuide (Temporary Name)

## Premise

There are hundreds of resources for learning web development. However, finding and using these resources can be hit or miss. What if there was a place where people could create curated lists of resources, including the name, link, and a description of why the source is worth checking out. Visitors to the site could then expedite their research by using the resource guides. This service would provide experienced developers a way of giving back to the community by sharing their hard gained knowledge; while providing new developers access to great content without having to slog through poorly written or frankly incorrect information.

## Inspiration

A variety of different Library organization utilizes a CMS called LibGuide provided by [SpringShare](https://www.springshare.com/libguides/). The CMS allows librarians to collect and organize information on min-websites. The information could be an annotated bibliography, instructions for working with a tool, or a combination of the two. Each "LibGuide" contains one or more pages; each page is sub-divided into sections. As an example here is a LibGuide I created: <http://libraryschool.libguidescms.com/web_accessibility_for_visual_impairments>

## Similarities and Differences to previous projects

ThinkGuide does have a similar feel to Robby and my [Book-Kit](https://github.com/robbykim/book-kit) project. The biggest difference will be sharing information between users is an essential aspect of the ThinkGuide project. Also, visitors will not have to log in to view a guide.

## Basic Requirements

- A guide can have one or more pages
- Each page can have one or more sections
- Sections can contain text, images, and links
- Users can log-in to edit their guides
- Users can have zero or more guides
- All guides are public

## Why I think ThinkGuid Would Be a Cool Capstone Project

- Authentication will play a large part of the app. I don't know about everyone else, but I would like more practice with authentication. One possible solution to Authentication could be Auth0.
- Full featured CMS with editing tools. It would indefinitely be interesting to try and integrate a text-editor into the user dashboard so that they can create their guides.
- Storing images in a database, which requires they be uploading to the server.
