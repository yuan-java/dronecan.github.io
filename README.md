## DroneCAN GitHub Pages

You can use the [editor on GitHub](https://github.com/dronecan/dronecan.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dronecan/dronecan.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Example of header links
1. create a folder named 'examples' under root directory
2. open `_includes/navbar.html`, add the folder name to href tag:
`<li><a href="../examples">Examples</a></li>`
3. create index.md file in that folder
4. add the layout code to the top of the md file:
`---`
`layout: default`
`---`

More information of develop website with Jekyll can be found here:
https://jekyllrb.com/docs/


### Development
Due to the 10 builds per hour [Usage limits](https://jekyllrb.com/docs/pages/) of GitHub Pages, you may need to build and test the project locally: 

[Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)