# gh0st Hugo Theme

![gh0st's landing page](https://raw.githubusercontent.com/dipeshsingh253/saral/main/images/screenshot.png)


## Getting Started

**Installation:**

Install the Hugo program:<br/>

`winget install Hugo.Hugo.Extended`<br/>

Create your site locally - requires Git to be installed<br/>

[Hugo Installation Instructions](https://gohugo.io/getting-started/quick-start/#explanation-of-commands)<br/><br/>

After creating your Hugo site, clone the gh0st theme into the themes directory, adding it to your project as a Git submodule.<br/>
`git submodule add https://github.com/vogonairlock/gh0st.git themes/gh0st`

Append a line to the site configuration file, indicating the current theme.<br/>
`echo "theme = 'gh0st'" >> hugo.toml`

Start Hugo’s development server to view the site.<br/>
`hugo server`


**Content:**
   - Start adding your content in the `content` directory.

**Development:**
   - Run `hugo server -D` to preview your site locally.


## Special Thanks 😊
  - [Saral](https://github.com/dipeshsingh253/saral): gh0st is based off of the Saral theme

