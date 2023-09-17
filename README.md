# Jekyll Theme - Mundana by WowThemes.net

[Live Demo](https://wowthemesnet.github.io/mundana-theme-jekyll/) &nbsp; | &nbsp;
[Download](https://github.com/wowthemesnet/mundana-theme-jekyll/archive/master.zip) &nbsp; | &nbsp;
[Buy me a coffe](https://www.wowthemes.net/donate/) &nbsp; |
&nbsp; [Documentation](https://bootstrapstarter.com/mundana-theme-jekyll/) &nbsp; | &nbsp;
[WordPress version](https://www.wowthemes.net/themes/mundana-wordpress/)

![mundana jekyll theme screenshot](assets/images/screenshot.jpg)

## Journalism instructions

### Terminology

categories

: topic

tags

: administrative tags

: formatting (`featured`, `sticky`)

### Upon new author

1. Add author to `authors` in [_config.yml](_config.yml)
   i. Will need to upload avatar to `/assets/images/`
2. Add page `_pages/author-<name>.html`, for example [_pages/author-medha.html](_pages/author-medha.html)
   i. Contents should be identically [_pages/author-medha.html](_pages/author-medha.html),
   but find-and-replace (match case) `medha` with `<name>`

### To post

#### From md

- put the markdown file in `_posts/`
- add frontmatter to match other posts
- change filename to `YYYY-MM-DD-whatever.md`
- note that header image is not resized on the posts page,
  and not necessarily resized on home/other pages
- make sure all relative urls not in the front matter are of the form
  `{{ site.baseurl }}/assets/images/greenline.png`
  (not sure this is actually necessary but do it anyways)

#### From docx

- import docx into md using `Markdown Converter`
- fix anything wrong with it
- follow [from md steps](#from-md)

-----

### Documentation

[How to install & use](https://bootstrapstarter.com/bootstrap-templates/mundana-theme-jekyll/)

### Contribute to Mundana repository

1. In the top-right corner of this page, click **Fork**.

2. Clone a copy of your fork on your local, replacing *YOUR-USERNAME* with your Github username.

   `git clone https://github.com/YOUR-USERNAME/mundana-theme-jekyll.git`

3. **Create a branch**:

   `git checkout -b <my-new-feature-or-fix>`

4. **Make necessary changes and commit those changes**:

   `git add .`

   `git commit -m "new feature or fix"`

5. **Push changes**, replacing `<add-your-branch-name>` with the name of the branch you created earlier at step #3. :

   `git push origin <add-your-branch-name>`

6. Submit your changes for review. Go to your repository on GitHub, you'll see a **Compare & pull request** button.
   Click on that button. Now submit the pull request.

That's it! Soon I'll be merging your changes into the master branch of this project. You will get a notification email
once the changes have been merged. Thank you for your contribution.

### Copyright

Copyright (C) 2019 WowThemes.net.

Theme designed and developed by [Sal](https://www.wowthemes.net), *free* under MIT license.

<a href="https://www.wowthemes.net/donate/" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

### Live Demo

[Live Demo](https://wowthemesnet.github.io/mundana-theme-jekyll/)
