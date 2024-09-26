---
title: Best practices and tips in markdown
description: It covers best tips and practices to help you create clear and easy to read markdown files. This guide also contains tips and workarounds on how to add complicated syntaxes or features in markdown. These tips will help you create high quality markdown documents.
summary: This detailed guide covers how to write quality markdown documents easier and faster. You will also find the top markdown tools to create markdown files seamlessly.
date: 2024-06-25T15:50:00+01:00
lastmod: 2024-08-27T15:15:00+01:00
draft: false
menu:
  docs:
    parent: ""
    identifier: "best-practices-3f4a9b7c8d2e57129c8a7f63e0b1d0e4"
weight: 2
toc: true
seo:
  title: "Best practices and tips in markdown" # custom title (optional)
  description: Learn essential best practices and tips for writing Markdown, along with a comprehensive guide to the top Markdown tools, their features, and pricing options. # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-5378239849378753"
     crossorigin="anonymous"></script>

<ins class="adsbygoogle"
     style="display:block; text-align:center;"
     data-ad-layout="in-article"
     data-ad-format="fluid"
     data-ad-client="ca-pub-5378239849378753"
     data-ad-slot="8846640451"></ins>

<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>

In this lesson, you will be learning:

- Best tips and practices in markdown.
- Markdown style guides.
- Markdown tools (both web and desktop).

Let's get started!

# Introduction.

Markdown like any other type of writing has rules and laws that guides its use. Writing practises against these rules can lead to an erroneous or disorganized documentation. Below are the best practises and tips to apply when working with markdown:

1. **Use headings and subheadings:**

Headings provide a way to arrange your content. It divides your document into digestible chunks that readers can easily read and understand. Using headings in markdown can help anyone reading the document navigate between sections and topics of choice.

Well written headings provide an insight into what the next set of paragraphs talk about. Sub-headings on the other hand are used to narrow-down each heading to its other component parts.

For example, a documentation/article on a video editing software named **VidEdit** will have headings and sub-headings as seen below:

```
## 1. What is VidEdit?

## 2. Features of VidEdit
    ### a. Download images with VidEdit
        #### i. Download images via URL.
    ### b. Extract audio from video
    ### c. Add audio to videos

## 3. VidEdit Integrations
    ### a. Integrate VidEdit with Youtube
    ### b. Integrate VidEdit with Tiktok
```

You can also preview it below:
{{< details "Preview" >}}

## 1. What is VidEdit?

## 2. Features of VidEdit

### a. Download images with VidEdit

#### i. Download images via URL.

### b. Extract audio from video

### c. Add audio to videos

## 3. VidEdit Integrations

### a. Integrate VidEdit with Youtube

### b. Integrate VidEdit with Tiktok

{{< /details >}}

From the headers above, readers can easily navigate between the sections that matter to them. The headings are written first, followed by the sub-headings. Each sub-heading has an extra hash (#) added to it. This helps to maintain a proper hierarchy of the content.

2. **Use whitespaces and line breaks:**

Whitespaces refer to the spaces between the words and paragraphs of your content. They help to separate words and paragraphs for easy comprehension and readability. However, whitespaces needs to be used carefully so your work doesn’t look vacant or over-spaced. Below is an example of a document with whitespaces defect like over-spacing and under-spacing:

```
Python is a high-level, interpretedprogramming language known for its simplicity andreadability.

It is widely used in various fields,  including webdevelopment, data science, artificial intelligence, and  more. Python's syntax allows programmers to write clear and  logical code for small and large-scale projects.
```

After writing, it is important to cross-check your document to spot and correct whitespace errors. Below is a correction of the document above:

```
Python is a high-level, interpreted programming language known for its simplicity and readability.

It is widely used in various fields, including web development, data science, artificial intelligence, and more. Python's syntax allows programmers to write clear and logical code for small and large-scale projects.
```

3. **Use descriptive texts for links and images:**

One of the ways to create a versatile and readable markdown file is by adding descriptive texts to links and images. These texts provide extra information about the link and image displayed. They are also used by search engines in indexing which can boost your content's search engine rankings (SEO).

Check the examples below:

```
# Bad link text
Facebook is a very popular messaging app. [click here](https://web.facebook.com/) to sign up.

# Descriptive link text
[Facebook](https://web.facebook.com/) is a very popular messaging app. You can create an account within 10 seconds.

# Bad image text
!\[Image\](image_link)

# Descriptive image text
!\[An image of a man carrying a dog\](image_link)
```

Check the preview below:

{{< details "Preview" >}}

#### Bad link text

Facebook is a very popular messaging app. [click here](https://web.facebook.com/) to sign up.

#### Descriptive link text

[Facebook](https://web.facebook.com/) is a very popular messaging app. You can create an account within 10 seconds.
{{< /details >}}

4. **Escape special characters with backslash:**

In some cases, you may want to include special characters like asterisks (\*), hash(#), etc. in your markdown document. This can prove difficult since these special characters are also commands used in writing markdown. One way to solve this is by using a backslash (\). Below is an example:

```
# The text below will be italicized
*me and you*

# The backslash prevents the text from being italicized
\*me and you\*
```

Check the preview below:
{{< details "Preview" >}}

#### The text below will be italicized

_me and you_

#### The backlash prevents the text from being italicized

\*me and you\*
{{< /details >}}

5. **Use lists appropriately and consistently:**

Use the normal counting numbers (1, 2, 3, …) to create ordered lists, such as a step-by-step process. Use asterisks (\*) or dash (-) to create unordered lists. If you use asterisks (\*) to create a list in your first paragraph, consider using it throughout your document for consistency. The same thing applies to when you use a dash (-). Here is an example below:

```
At the musical fest, we ate and drank the following:

- fish
- meat
- wine
- youghurts.

There were also fun events like,

- games
- musical challenge
- dance battle, etc.
```

6. **Edit tables for readability:**

Creating tables in markdown can be tricky, especially when each row and cells have words and characters of unequal length. To ensure readability of your markdown files, apply enough spaces to align each column with their respective data. Below is a comparison between a wrong table format and a readable one:

```
# Wrong table format
| Name | Email |
|---|---|
| Edun Rilwan | edun...@gmail.com |
| Oladapo Alex| alex...@gmail.com |

# Readable table format
| Name              | Email             |
| ---               | ---               |
| Edun Rilwan       | edun...@gmail.com |
| Oladapo Alexandra | alex...@gmail.com |
```

Check the preview below:

{{< details "Preview" >}}

#### Markdown table

| Name              | Email             |
| ----------------- | ----------------- |
| Edun Rilwan       | edun...@gmail.com |
| Oladapo Alexandra | alex...@gmail.com |

_NOTE: Both format will render your table correctly. However, it is useful when editing your markdown file and sharing it with others.
Editors can quickly find out which column each row data belongs to._
{{< /details >}}

7. **Using backticks for writing code:**

Markdown allows you to create code snippets using backticks (`). It’s usage can differ based on what you want to achieve. Below is a breakdown on how to use backticks in different scenarios:

````
# For a simple code or inline code
``your code goes here``

# For a code block or long code snippet

```
your code goes here
```

# Specify the programming lanaguage (1)
```python
numbers = [1, 2, 3]
for n in numbers:
    print(n)
```

# Specify the programming lanaguage (2)
```javascript
const name = "Rilwan";
console.log(name);
```
````

Check the preview below:
{{< details "Preview" >}}

#### For a simple code or inline code

`your code goes here`

#### For a code block or long code snippet

```
your code goes here
```

#### Specify the programming lanaguage (1)

```python

# Python

numbers = [1, 2, 3]
for n in numbers:
    print(n)
```

#### Specify the programming lanaguage (2)

```javascript
// Javascript

const name = "Rilwan";
console.log(name);
```

{{< /details >}}

8. **Add metadata to your markdown file:**

When creating a markdown file for a blog post or documentation site, it is important to include a metadata that contains vital information about the file and its content. This piece of information is useful as it gives documentation sites, blogs, and markdown editors a summary of your file.

Metadata are included in a section of the markdown file called **Front matter.** It is always in the beginning of the markdown file and are enclosed by triple dashes (---). Below is an example of a metadata for a markdown file on **Introduction to Python**:

```
---
title: "Introduction to Python"
author: "Edun Rilwan"
date: "2024-08-03"
description: "An introductory guide to Python programming language, covering basic concepts and syntax."
tags: ["python", "programming", "beginner", "tutorial"] category: "Programming Tutorials"
---
```

9. **Using image as link text:**

This tip allows you to create a clickable image in markdown. This image is wrapped around a link which directs users to a new web page when it is clicked. Here is an example of how to implement it below:

```
# Format
[![Alt text](image_link)](link_url)

# Sample Usage
[![Django framework logo](https://cdn-icons-png.flaticon.com/512/9307/9307630.png)](https://docs.djangoproject.com/en/5.1/)
```

##### Check the preview below:

{{< details "Preview" >}}
[![Django framework icon](https://cdn-icons-png.flaticon.com/512/9307/9307630.png)](https://docs.djangoproject.com/en/5.1/)

When you click on the image above, you will be redirected to django's official documentation.
{{< /details >}}

## Consistent formatting and styles in markdown

There are different style guides for creating consistent styles in markdown. Each documentation provides detailed guide on how to ensure consistency in markdown. Here is a list of some of these guide:

1. [Markdown style guide](https://google.github.io/styleguide/docguide/style.html) by Google.
2. [Formatting standards for readable & consistent Markdown](https://github.com/carwin/markdown-styleguide) by Carwin on GitHub.
3. [Markdown style guide](https://docs.gruntwork.io/guides/style/markdown-style-guide/) by Gruntwork docs.

## Tools for markdown editing

There are various tools used for writing and editing markdown files. Below is a list of the top 5 markdown editing tools:

1. **Dillinger:**
   ![A screenshot of Dillinger markdown editor](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/qf6mso4f97kxny8o7wmg.png)

[Dillinger](https://dillinger.io/) is the first on the list as a user-friendly markdown editor that allow users to create markdown files and also see the live preview of the markdown content on the right side of the screen.

**Features**

- Dillinger allows you to export your markdown file as a styled HTML file, pure HTML file, and PDF.
- Dillinger is integrated with cloud storages like Dropbox, Google Drive, OneDrive to allow seamless file import and export.
- You can also save your markdown files to Medium, Github and Bitbuket directly from Dillinger.
- Files stored on the cloud storages listed above can also be imported to Dillinger.

**Pricing**:
Dillinger is a free web based markdown editor.

2. **Typora:**
   ![A screenshot of Typora features section](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/yzug47rewgvs2g79ngyy.png)

[Typora](https://typora.io/) is a markdown editor for windows, MacOS and Linux systems. It is created to enable users to focus on writing and eliminate any distractions. There is no preview window, mode switcher, etc. Your markdown content is immediately converted to plain text as you type along. This allows you to focus mainly on the content itself.

**Features**

- With Typora, you can add diagrams, mathematical formulas or equations to your markdown file.
- Typora has an autocomplete feature to quickly write out common markdown syntaxes.
- Markdown files can be exported as a PDF, Epub, HTML, and other document types with Typora.
- Typora allows you to chose different themes for your markdown editor interface.

**Pricing**:
Typora is not free to use. Users have access to a free 15 days trial after which they will have to pay a one time fee of $14.99 for a lifetime access.

3. **StackEdit:**
   ![A screenshot of StackEdit home page](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lauayhrrl3lga9jjn52k.png)

[StackEdit](https://stackedit.io/) is an inbrowser Markdown editor. It allows you to visualize and preview the final rendering of your files as you write.

**Features**

- StackEdit has a **WYSIWYG** editor.
- StackEdit can sync your files with cloud storages like Google Drive, Dropbox, and Github.
- Your markdown files can also be published directly to CMS sites such as, blogger, wordpress, zendesk.
- StackEdit can be used to edit markdown files both online and offline.
- You can add emojis and musical notes to your markdown files with StackEdit.

**Pricing**:
StackEdit is free to use.

4. **Ghostwriter:**
   ![A screenshot of Ghostwriter markdown editor](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/d088egqjl93c32j2so84.png)

[Ghostwriter](https://ghostwriter.kde.org/) is a markdown editor for both Windows and Linux systems. It allows you to create markdown files without distractions. You can choose to see the live preview as you write along or focus mainly on the writing canvas.

**Pricing**:
Ghostwriter is free and open source.

5. **Mou:**
   ![A screenshot of how to download Mou markdown editor.](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/v9zy5zjr95r8w8iwiong.png)

[Mou](https://apps.apple.com/na/app/mou-markdown-editor/id1308265497?mt=12) is a markdown editor for MacOS operating systems. It has a live preview feature and allow users to choose custom themes for their editors.

**Pricing**:
Mou is a free markdown editor for MacOS systems.