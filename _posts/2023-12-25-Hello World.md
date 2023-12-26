---
layout: post
title: Hello World 
subtitle: Remote theme allows you to use a theme on any GitHub repository
cover-img: https://iruelas.files.wordpress.com/2022/05/20220430_2047542735328794992005314.jpg
thumbnail-img: /img/avatar-icon.png
share-img: /assets/img/path.jpg
tags: [GitHub, Jekyll]
author: marlucjo
---


Beautiful Jekyll was initially developed as a GitHub Pages theme that was meant to be used via *forking*, but several years later GitHub released the *remote themes* feature that allows you to use a theme on any GitHub repository. For full details, you should read GitHub’s documentation on remote themes, but here is a summary of the steps required:

### [GitHub repository with remote_theme](https://beautifuljekyll.com/getstarted/#install-steps-hard)

1. Create a new GitHub repository (or go to an existing repository).
2. Add **remote_theme**: ``daattali/beautiful-jekyll@6.0.1`` to your ``_config.yml`` file (remove any previous ``theme`` or ``remote_theme`` parameters that may have been there before).
3. Go to **Settings**, click on the **Pages** tab on the left side, select “master” (or “main”) in the Branch section, and click **Save**.
4. Your website will be at ``https://YOURUSERNAME.github.io/REPOSITORY``
5. Go through Beautiful Jekyll’s ``_config.yml`` file and copy any settings you want to use into your project’s config file.
6. Some config features will not work immediately because of missing files that you’ll need to copy from Beautiful Jekyll into your project:
    - To enable the **tags index page**, you need to copy ``tags.html``.
    - To enable the **RSS feed**, copy ``feed.xml``.
    - If you use **staticman comments**, copy ``staticman.yml`` and ``_data/ui-text.yml``.
7. If you want the **home page** to include a feed of all blog posts, create an ``index.html`` file and use ``layout: home`` in its YAML.

If at any point in the future you want to update to a [newer version](https://beautifuljekyll.com/updates/) of Beautiful Jekyll, you can simply update the remote_theme or gem fields accordingly.
