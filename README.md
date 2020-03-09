# Rajesh's logs

This is a small site where the author wanted to log all the things
learnt; Mostly related to computers and programming.

### This is a slate docs

To develop and run locally

```
$ bundle install
$ bundle exec middleman server
```
Check the page [http://localhost:4567/](http://localhost:4567/)

## Source
The main file is index.html.md inside `source` folder.
In index file one can include other `.md` files directly.
The file must be placed inside `source/includes` using

```
includes:
  - file1
  - file2
```

## Workflow

- Edit/Add/Remove file from source and includes folders.
- Run `bundle exec middleman server`
- Visualize the changes on the browser [http://localhost:4567/](http://localhost:4567/)
- Git commit with messages
- Git Push to remote server
- Run `./deploy.sh` // which basically creates html files from md files
- Those html files are kept separate on `gh-pages` branch and pushes it.
- This get automatically pubished to github pages
- In our case it is [site/rajzdocs](https://mrprajesh.github.io/rajzdocs/)

### Author
[Rajesh Pandian M](https://mrprajesh.github.io)
