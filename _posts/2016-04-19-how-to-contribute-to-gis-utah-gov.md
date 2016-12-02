---
layout: post
status: publish
published: true
title: 'How to Contribute to gis.utah.gov'
author:
  display_name: Steve Gourley
  email: sgourley@utah.gov
date: 2016-04-19 16:11:21
categories: Featured
tags: how-to
---

The Utah GIS community accomplishes great things when working together. The [UGIC Conference](), the many [GIS User Groups](), and datasets like Statewide [Address Points]() are some examples of the community working together to create meaningful products. This website is no different; Contributions to gis.utah.gov are welcome and encouraged!

#### Creating New Content

When you, your group, or your employer have content that would benefit the audience of gis.utah.gov, please consider publishing it here. The ease of contributing stems from the website being hosted on [GitHub.com](https://github.com/home). Once you have gone through the process once, you will be an expert.

> GitHub fosters a fast, flexible, and collaborative development process that lets you work on your own or with others.

#### A Post or a Page

The first decision an author needs to make is whether to create a `Post` or a `Page`. Differentiating between the two is done by the type of content being created. If your content is newsy or time sensitive, then it would be considered a `Post`. If the content has permanent value and fits into the organizational structure of the website, then it would considered a `Page`. If you are having trouble deciding, _always_ choose a `Post`.

#### The Starting Point

![templater screenshot]({{ "/images/contributing/content-templater.png" | prepend: site.baseurl }})
{:.inline-text-right}
The ever resourceful [Scott Davis](https://twitter.com/@SThomasDavis) created a great tool, the [Templator](http://gis.utah.gov/templater), to create a starting point for authoring new content. This is _the_ entry point for all authors creating new content.

**Start** by creating a title. This will be used to create the url on the website and also the heading for the article. **Next** choose your content type based on the decision above. Fill out the Author information - This will be displayed above the title on the post. Please use your **full name**. Once you **click** `Generate`, the templater will present you with a `File Path` and `Contents`.

#### GitHub

You will need a GitHub account to participate, so [create a free GitHub account](https://github.com/join) if you do not already have one. Navigate to the [agrc organization](https://github.com/agrc/) on GitHub and find the [website source code](https://github.com/agrc/agrc.github.io). [Fork](https://help.github.com/articles/github-glossary/#fork) the [repository](https://help.github.com/articles/github-glossary/#repository) to create a personal copy of gis.utah.gov website.

#### Creating and Naming New Content

The gis.utah.gov website is generated using [Jekyll](http://jekyllrb.com/). Jekyll is a tool that aids in the creation of the websites content as well as the look and feel. Jekyll dictates how the website directory structure is organized.

New `Posts` should be placed in the [`_posts`](https://github.com/agrc/agrc.github.io/tree/master/_posts) folder of your fork (*https://github.com/YOUR USER NAME/agrc.github.io/tree/master/_posts*). This can be accomplished by first navigating to the `_posts` folder and clicking the `New File` button. Copy and paste the content generated in the `File Path` input that the templater created.

`Posts` can go anywhere in the website structure. To achieve the extensionless urls, an `index.md` or `index.html` file is created inside of a folder. The folder name will be the url to the content. eg: `gis.utah.gov/folder-name`. Folders can be nested within folders as can be seen in the [existing structure](https://github.com/agrc/agrc.github.io/tree/master/data). The templater will take care of the naming, therefore clicking the `New File` button and pasting the content generated in the `File Path` input should give the desired result.

By default, the templater has given the new file a `.md` markdown extension.

> Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML).

There are many implementations of markdown, but all Jekyll websites use [kramdown](http://kramdown.gettalong.org/syntax.html). You have the choice to write your post in html or markdown. Please update the extension to match your choice.

#### Authoring New Content

The templator has created the [YAML Front Matter](https://jekyllrb.com/docs/frontmatter/) required to display your new content correctly. You can ignore that. Copy and paste the `Contents` text from the templater into the `Edit new file` location of GitHub. You can continue to author your content in GitHub or use your favorite text editor. Once you are finished, write a [commit message](https://help.github.com/articles/github-glossary/#commit) and commit the new file.

#### Adding Images and Assets

By convention, the gis.utah.gov website places all of it's images in the [`images`](https://github.com/agrc/agrc.github.io/tree/master/images) folder and all other assets (PDF's, text files, etc) in the [`downloads`](https://github.com/agrc/agrc.github.io/tree/master/downloads) folder. From the `images` or `downloads` directory in your browser, drag the assets you would like to reference in your post on to the browser window[^1]. GitHub will recognize this and upload the assets. Finally, add a commit message and commit the changes.

#### The Pull Request

To close the contribution loop, a [pull request](https://help.github.com/articles/github-glossary/#pull-request) must be created asking AGRC to pull in your commits to be incorporated into the website. In your fork of the website, there will be a `Pull request` button. Clicking this button and following through the steps to completion will summarize the changes made and send a notification to AGRC of the request. The pull request creates a link between your [branch](https://help.github.com/articles/github-glossary/#branch) and the AGRC repository. Any subsequent commits will show up in the pull request. It is a living connection while the pull request is open. This gives AGRC and the contributor a chance to have a discussion and fix any errors.

Once the pull request is accepted and merged, the website will automatically regenerate and deploy to production. The edits will be live, [@MapUtah](https://twitter.com/@MapUtah) will tweet about the new content as well as a link will be posted to [facebook](https://facebook.com/utahagrc).

[^1]: There may be browser limitations with this functionality.
