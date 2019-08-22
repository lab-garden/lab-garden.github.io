# Lab.Garden

[lab.garden](https://lab.garden/)

## Development

### Requirements

* Ruby

### Installation

    gem install bundler
    git clone https://github.com/lab-garden/lab-garden.github.io.git
    cd lab-garden.github.io
    bundle install

### Run the site in development mode

    bundle exec jekyll serve --watch

The site will compile and run at http://localhost:4000

### Adding posts

To add a news article, create a file in the `_posts` directory, and name the file using this pattern:

    _posts/YYYY-MM-DD-article-slug.html

At the top of the file, add the frontmatter, following this template:

    ---
    layout: post
    title:  "Mobile Garden 移動花園 工作坊"
    author: admin
    categories: [ events ]
    image: assets/images/IMG_5935.JPG
    featured: true
    hidden: true
    ---

### Adding authors

Update the `# Authors` section of the `_config.yml` file.

### License

Mediumish theme Copyright (c) 2019 WowThemes.net
License: MIT
