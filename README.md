# gh0st Hugo Theme

![gh0st's landing page](https://raw.githubusercontent.com/dipeshsingh253/saral/main/images/screenshot.png)


## Getting Started

1. **Installation:**

a. Install the Hugo program:

`winget install Hugo.Hugo.Extended`

b. Create your site locally - requires Git to be installed

[Hugo Installation Instructions](https://gohugo.io/getting-started/quick-start/#explanation-of-commands)

c. After creating your Hugo site, clone the gh0st theme into the themes directory, adding it to your project as a Git submodule.
`git submodule add https://github.com/vogonairlock/gh0st.git themes/gh0st`

d. Append a line to the site configuration file, indicating the current theme.
`echo "theme = 'gh0st'" >> hugo.toml`

e. Start Hugo’s development server to view the site.
`hugo server`


2. **Content:**
   - Start adding your content in the `content` directory.

3. **Development:**
   - Run `hugo server -D` to preview your site locally.


## Special Thanks 😊
  - [Saral](https://github.com/dipeshsingh253/saral): gh0st is based off of the Saral theme

