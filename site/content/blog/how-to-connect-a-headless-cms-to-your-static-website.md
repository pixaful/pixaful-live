+++
date = ""
description = "A headless CMS will help you to manage your website when you do not have access to your files"
featured_image = "/v1566200296/forestry_k1xdit.jpg"
ogdescription = "A headless CMS will help you to manage your website when you do not have access to your files"
ogtitle = "Forestry: A headless CMS that commits"
summary = "As long as you have your static website connected it to git then you can connect Forestry to it and it will make commits for you."
title = "How to connect a headless CMS to your static website"
twitterdescription = "A headless CMS will help you to manage your website when you do not have access to your files"
twittertitle = "How to connect a headless CMS to your static website"
webp_version = "/v1566200296/forestry_k1xdit.jpg"

+++
**Forestry is a headless CMS that commits.** This means that you can connect a content management system to your static website. As long as you have connected it to git then you can connect Forestry to it and it will make commits for you.

The setup is minimal, you have to make a few adjustments to some settings to ensure that pages and menus can be modified and you are good to go.

Personally I find working on my pages in Visual code Studio to be much quicker and I have more control over the output, especially when I am mixing HTML with markdown.

Forestry however can be connected to Cloudinary so you can upload your images to the cloud and it won't bog down your repository. 

If this all sounds very complicated to you, don't worry as I will be releasing a video in teh next few days which will hopefully explain my method.

I built this site using a starter theme called [Victor Hugo](https://github.com/netlify-templates/victor-hugo), which is Netflify's own offering of a hugo template. It comes with Webpack and some other stuff I don't really understand just yet.

I connected it to my Netlify account using the deploy to Netlify button. Then I created a Forestry account and connected that repository to it. 

At this point you don't get much as you have not created any pages or posts and you do need to configure a menu. 

Hugo among other static site generators uses something called Front Matter.

Front matter is small snippets of code and data that you can include on your pages which then gets outputted into code, for example Open Graph and Twitter cards, featured image information, dates, titles and descriptions. 

You can create front matter templates in Forestry. They get committed in git and once done you can use that data to create your layout templates.

Bad explanation and I will probably rewrite this post very soon, so hang on for the video!