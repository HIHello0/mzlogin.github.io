code log
My personal blog: https://mazhuang.org, welcome Star and Fork.

overview
Effect preview
Fork Guide
Documentation
experience and thinking
contact me
thank you
Effect preview
Online preview →

screenshot home

Fork Guide
After Fork this project, there are still some things that need to be done to make your page run "correctly".

Set the project name and branch correctly.

According to GitHub Pages, the master branch of a project named username.github.io, or the gh-pages branch of a project with another name can automatically generate GitHub Pages pages.

Modify the domain name.

If you need to bind your own domain name, then modify the content of the CNAME file, and configure it by referring to Configuring a custom domain for GitHub Pages site; if you do not need to bind your own domain name, then delete the CNAME file.

Change setting.

The configuration of the website is basically concentrated in the _config.yml file, and replace the parts related to personal information with your own, such as the url, title, subtitle and third-party comment module configuration of the website.

Comment module: currently supports disqus, gitment, gitalk, utterances, beaudar and giscus, you can choose one of them, and giscus is recommended. Their respective official configuration guide links are posted in the Comments section of the _config.yml file, please refer to the official guide configuration.

Note: If you use disqus, please change disqus.username to your own, otherwise please leave this field blank, because disqus has flaws in its policy of whitelisting usernames and domains. See Issues#2 for my documentation of the bug.

Delete my articles and pictures.

Except for the template.md file in the following folders, all can be deleted, and then add your own content.

Inside the _posts folder are my published blog posts.
Inside the _drafts folder are my unpublished blog posts.
Inside the _wiki folder are my published wiki pages.
Inside the _fragments folder are my published short article fragments.
The images folder contains the images used in my articles and pages.
Modify the "About" page.

The content of the pages/about.md file corresponds to the "About" page of the website. The content in it is mostly personal. Replace them with your own information, including the data in the skills.yml and social.yml files in the _data directory.

For the meaning of the content in skills.yml and social.yml, please refer to: the meaning of the content of the yml file in the _data directory.

Documentation
This blog template FAQ Q & A.

To preview blog effects locally, please refer to Setting up your Pages site locally with Jekyll.

experience and thinking
It is recommended to follow certain standards for typesetting, and we recommend Chinese copywriting typesetting guide (simplified Chinese version).

Simple, try not to display redundant content on each page.

Sometimes a picture is worth a thousand words, other times it might just slow down the page load.

Say something, don't make painless groans.

If you write a technical article, you should first clarify the technical principles before you start writing. It is inefficient to organize the article while exploring the technology.

Put an end to long sentences that are difficult to break and understand. If you can't split them into several short sentences, it means that your understanding in your mind is not clear.

You can learn from those high-quality bloggers, their writing, content organization, and what is worth learning.

contact me
If you have any suggestions on the template or content of this blog, you can contact me through Issues or the WeChat public account "Mensao Programmer".



thank you
The appearance of this blog is modified based on DONGChuan, thanks!
