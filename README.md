# how I built my jekyll website

## it was not my first, I screwed up the first 5... 6

## what I wanted my website/blog to have

  * [X] 100% compatible with GitHub

  * [ ] Work on the gh-pages branch
  
  * [ ] Search bar *in the future

  * [X] Post Sharing

  * [X] Categories

  * [X] Responsiveness

  * [ ] Disqus comments

  * [ ] Mailchimp integration

  * [X] Bootstrap 4

  * [X] FontAwesome

  * [X] SASS Support

  * [ ] Google Analytics

  * [X] SEO Optimized
    - SEO Check up tool
      https://toolbox.seositecheckup.com/users

  ## todo's before I started

  1. [ ] Create Disqus account

  2. [ ] Create Mailchimp

  3. [ ] Get Google Analytics account

  4. [X] Create a logo

  ## tools

  * Dell Latitude 3340 with Ubuntu 18.04.3 LTS

  * Visual Studio Code

  * Google Chrome

  ## technologies I know a bit about

  * HTML5

  * CSS 3

  * Bootstrap 4

  * JavaScript

  * Markdown

  * git & GitHub

  ## technologies I knew NOTHING about and resources to learn

  * SASS

  * YML

  * Jekyll

  * SEO
    - https://blog.webjeda.com/optimize-jekyll-seo/

  * Mailchimp

  * Disqus

  * Open Graph
   - https://ogp.me/

  * Twitter Cards
   - https://developer.twitter.com/en/docs/tweets/optimize-with-cards/guides/getting-started

  ## Gmail account
  jekyllBlog@outlook.com
  cura17CR04$

  ## GitHub Accout
  JekyllGithubs
  cura17CR04$

  ## Step by Step

  1. Open the terminal and navigate to where I store my projects.
      $ cd Documents/

  2. Create a new jekyll site
      $ jekyll new blogName
      $ cd blogName
      ~/blogName $ bundle exec jekyll serve

      *ensure the blogName and the GitHub username are the same ????
  
  3. Browse to http://localhost:4000 and verify site is working

  4. Ctrl + C at the terminal to shut the server down

  5. Open the blogName folder in Visual Studio Code

  6. Open the _config.yml file and update/add the following:
      
    **site settings**

      * title: the name of the website
      * email: where I want to be contacted at
      * description: why did I make this
      * author: me
      * baseurl: comment out using #
      * url: this is the github URL (https://blogName.github.io)
      * social media usernames: me and more me
      * logo: the URL path to the file the contains the logo
      * lang: what language are you going to write

    **build settings**

      * markdown: kramdown
      * highlighter: rouge
      * permalink: /blog/:year/:month/:day/:title
      * paginate: (select a number)
      * sass:
          sass_dir: _sass
          style: compressed
      * comment out theme: minima
      * plugins: [jekyll-paginate, jekyll-sitemap, jekyll-feed, jekyll-seo-tag]

  7. Open the Gemfile and update the following:

    * comment out gem "minima", "~> 4.0.0"
    * update the jekyll_plugins with the following:
      - "jekyll-sitemap"
      - "jekyll-seo-tag"
      - "jekyll-paginate"

  8. Create a _data folder in the project's root folder

  9. Create a settings.yml inside the _data folder

  10. Create a _includes folder, it will contain HTML snippets of code like the navbar and the head of the HTML document.

  11. Create a _layout folder, contains HTML layout that will be applied to the pages and the posts when the site is created.

  12. Create a _sass folder, and inside create a main.scss file

  13. Create a assets folder, it will contain an images and a css folders

  14. Navigate to the css folder and create a styles.scss file

  15. Create a pages folder and inside create the following files:
    - about.md
    - blog.html
    - contact.html
    - feed.xml
    - resume.html
  
  16. Start adding content and style to the website.

  17. Push changes to GitHub and live site.

  * Muse site: http://demo.lion-coders.com/html/alpha/index-gradient.html

  