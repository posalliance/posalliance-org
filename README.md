# posalliance.org website

This repo contains the code to produce posalliance.org

## Contributing

This site is generated with [Hugo](https://gohugo.io/>). See [Hugo docs](https://gohugo.io/documentation/) for more information

### Updating a page
 - Fork repo
 - Edit the page under `content/<page>/_index.md`
 - Submit PR

### Creating a page
 - Fork repo
 - Create page under `content/<pagename>` as `_index.md`
 - Include the `frontmatter` e.g.
    ```
    ---
    title: My page title
    menu: "main"
    ---
    ***Markdown goes here**
    ```
 - Create the page using [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### Previewing changes locally
Optionally you can preview the changes by [Installing Hugo](https://gohugo.io/getting-started/installing)

**MacOS**: `brew install hugo`

**Windows**: `choco install hugo -confirm` or check [Installing Hugo](https://gohugo.io/getting-started/installing)

**Linux**: `sudo apt-get install hugo` or `snap install hugo`

To run, simply run `hugo serve` in your local git repo.

### Editing theme / design
This website uses the [hugo learn theme](https://themes.gohugo.io/hugo-theme-learn/)
 - Clone repo
 - Install hugo
 - Follow the [offical learn theme docs](https://learn.netlify.com/en/)
 - Submit PR

 ## Licence
 All content and code is released under MIT licence. Do whatever you want.


