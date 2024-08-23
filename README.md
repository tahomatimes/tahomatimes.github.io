# Journalism instructions

## Terminology

categories

: topic

tags

: administrative tags

: formatting (`featured`, `sticky`)

## Upon new author

1. Add author to `authors` in [_config.yml](_config.yml)
   i. Will need to upload avatar to `/assets/images/`
2. Add page `_pages/author-<name>.html`, for example [_pages/author-medha.html](_pages/author-medha.html)
   i. Contents should be identically [_pages/author-medha.html](_pages/author-medha.html),
   but find-and-replace (match case) `medha` with `<name>`

## To post

### From md

- put the markdown file in `_posts/`
- add frontmatter to match other posts
- change filename to `YYYY-MM-DD-whatever.md`
- note that header image is not resized on the posts page,
  and not necessarily resized on home/other pages
- make sure all relative urls not in the front matter are of the form
  `{{ site.baseurl }}/assets/images/greenline.png`
  (not sure this is actually necessary but do it anyways)

### From docx

- import docx into md using `Markdown Converter`
    - If the formatting is bad, instead run
      ```shell
      pandoc --from docx --to gfm --standalone --no-highlight "Treaty of Versailles Resource Page.docx" > 2023-01-01-treaty.md
      ```
- fix anything wrong with it
- follow [from md steps](#from-md)

## To deploy to staging

* Continue to commit to local branch (e.g. `master`)
* Checkout `staging` branch and rebase onto `master`
* Push `staging` branch to `staging` remote
* Checkout `master` branch again for continued development
