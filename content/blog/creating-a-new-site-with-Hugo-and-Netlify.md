---
title: "Creating a new site with Hugo and Netlify, powered also by analytics, automated certs or custom domain config."
date: 2019-12-12T12:27:38+06:00
description : "Creating a new site with Hugo and Netlify, powered also by analytics, automated certs or custom domain config."
type: post
image: images/blog/hugo-netlify-post-3.png
author: Beatriz Martínez
mediumdevlink: https://dev.to/b3adev/creating-a-new-site-with-hugo-and-netlify-powered-also-by-analytics-automated-certs-or-custom-domain-config-2p48
tags: ["Web Development", "Hugo", "Netlify", "Tutorial", "Google Analytics"]
linktotweet: http://twitter.com/intent/tweet?text=Check%20out%20this%20post:%20“Creating%20a%20new%20site%20with%20Hugo%20and%20Netlify,%20powered%20also%20by%20analytics,%20automated%20certs%20or%20custom…”%20by%20%40beatrizmrg%20%23GoHugoIO%20%23Netlify%20%23googleanalytics%20%23DEVcommunity&url=https://dev.to/b3adev/creating-a-new-site-with-hugo-and-netlify-powered-also-by-analytics-automated-certs-or-custom-domain-config-2p48
---
I recently decided to create a new site to share my posts, exploring the currently available options and decided on Hugo and Netlify.

Hugo is nowadays one of the most popular open-source static site generators, very flexible, counts with shortcodes and plenty of themes. There is also a cli available, which burst the speed to have your site ready to be published.
Netlify then covers all the aspects from continuous deployment workflow with Git integration, supporting several branches and versions, automated certificates renewal or DNS if you choose to use a custom domain.

1. Install Hugo and create your first site
I am using macOS in the examples if you are using any other operating system, visit the official installation guides.