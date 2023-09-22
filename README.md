# esm-tools.github.io

A very good tutorial on how to set up a Github page I found here:

https://www.aleksandrhovhannisyan.com/blog/getting-started-with-jekyll-and-github-pages/#where-do-i-put-my-pages-in-jekyll

# How to add a new blog post
- Create a new file in the `_posts` folder with the following filename format: `YYYY-MM-DD-blog-post-title.md`

Example: `2023-09-15-welcome-to-esm-tools.md`

# How to test this page locally (wip)
In order to test this Github page locally, please do the following steps:
- Install the following software: Ruby, Bundler and Jekyll
```
sudo apt-get install ruby-full
gem install bundler jekyll
```

- Clone the repository
```
git clone https://github.com/esm-tools/esm-tools.github.io.git
```

- Change to the local repository and checkout or create a branch
```
cd esm-tools.github.io
git checkout <test_branch>
```
- Run
```
bundle install
```
```
bundle exec jekyll serve --livereload
```
- open the following address in your webbrowser
`http://127.0.0.1:4000/`
