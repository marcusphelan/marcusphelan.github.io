---
layout: post
title: "Everyone's a Critic"
categories: misc
author: Marcus Phelan
meta: "markup"
tags: writing software
last_modified_at: 2020-08-25 23:36
---

### `A ∩ B`
If you write primarily for the web you are probably aware of markup languages that preclude the need to draft in HTML. This permits writers and editors to add emphasis to text without code tags which impair readability. In a Venn diagram of writers who track changes in documents and those that have a preference for plaintext markup solutions, the intersection is admittedly small. However, if you review documents in different formats you'll appreciate that flexibility is key to a frictionless workflow.

![AB](/assets/images/ab.png){: .center-image }
 *The needs of the few*

As a trainer I sometimes need to review documents of different file types. Using John Gruber's [Markdown](https://daringfireball.net/projects/markdown/) it is easy to work on text from different formats and styles. While there is no provision for tracking changes in Markdown, thankfully it has been incorporated in Fletcher Penney's [Multimarkdown](https://fletcherpenney.net/multimarkdown/), one of its variants.


I'm also a Microsoft Word user and there's no denying it's a powerful tool for collaboration and document review. However, it's not the best tool for all writing tasks. A woodworker's workshop holds an array of chisels and lathes and other tools I don't understand, all required for particular tasks. Working with words is really no different. 

When tracking changes or adding comments using Word it's necessary to keep one eye on the text and the other on the panel to the side of the 'page'. It's as if editors are like archers, shooting burning arrows of recrimination at superfluous adjectives from the refuge of their digital turret.

I don't like to edit from a distance.  I prefer to feel my hands on the words like a baker kneading a lump of dough into the desired shape- not always consistent or elegant, but at least honest and intentional.

Enter [CriticMarkup](http://criticmarkup.com), the ingenious markup syntax self-described by its creators Gabe Weatherhead and Erik Hess as _Plain Text Editing Markup for Humans_

> in early 2013 after they struggled to find a plain-text-friendly collaborative editing workflow. Realizing that such a thing didn’t exist, they foolishly set out to build it themselves.

This allows authors to make common changes to their writing using a simple syntax. The output can be viewed by any software that can render the syntax. Brett Terpstra's [Marked 2](https://marked2app.com), a power tool for writers, has this functionality.


|Operation|Syntax|
|:--|:--|
|highlight|`{==text==}`|
|delete|`{--text--}`|
|substitute|`{~~old text~>new text~~}`|
|comments|`{>>text<<}`|

This is rendered in Marked 2 as follows, enabling three views of the prose; with the markup applied, the original text or the edited version:

![CriticMArkup Syntax](/assets/images/critic.png){: .center-image }
*CriticMArkup syntax*

### There's an app for that
The output is rendered slightly differently depending on the app that it's written in. A longstanding favourite of mine is the remarkable outlining tool [FoldingText](https://www.foldingtext.com) which is still available but I'm not sure how actively it's being developed. It's a markdown editor that has a highly scriptable and customisable writing environment. The following passage was edited in FoldingText using CriticMarkup. I assigned key bindings to the syntax so that it could be applied to selected text with keyboard shortcuts.

![FoldingText](/assets/images/folding.png){: .center-image }
*FoldingText*

Another app that I've recently started using is [Drafts 5](https://getdrafts.com) which supports CriticMarkup by dint of its extensive action directory.  In fact it's possible to view the edits written in any app as long as you have a parser to view the output. The examples I'm providing are all macOS or iOS based but plaintext files are cross platform and can be read by programmes that work on other operating systems.

A common use case for me is grading assignments that are received in multiple document types such as`.docx`, `.odt`, `.pages`, `.rtf`, `.html` or `.pdf`. I extract the rich text and paste it as unformatted text into any editor, say a markdown `.md` file stored in DEVONthink. I can view the rendered CriticMarkup within [DEVONthink](https://www.devontechnologies.com/apps/devonthink), or use an external editor such as TextEdit and preview it in Marked 2, which can export the edited document to `.docx` for emailing to the student. DEVONthink's inclusion of MultiMarkdown means it now supports CriticMarkup.[^1]

[^1]: This fantastic research and document management system also has some great writing tools. I can't recommend it highly enough.

### Critical advantage

One of the greatest features of CriticMarkup is that you can use it in your favourite editor, as long as it supports the syntax. It permits fast and efficient markup without firing up a word processor at the risk of interrupting your editing flow. It's useful for collaboration and a great way to review text which can be outputted into common file formats, or web-ready content.

<a rel="me" href="https://mastodon.ie/@marcusphelan">Mastodon</a>
