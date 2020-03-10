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

### Debug

You may use these below commands to debug when the `css` failed to load.

```
bundle exec middleman build --verbose
bundle exec middleman build
```
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

- Run `bundle exec middleman server`
- Edit/Add/Remove file from source and includes folders.
- Visualize the changes on the browser [http://localhost:4567/](http://localhost:4567/)
- Run `./deploy.sh` // which basically creates html files from md files
- Git commit i.e `git commit -am <msg>`  with messages (`git add .` if required)
- Git `push` to remote server
- Those html files are kept separate on `gh-pages` branch and pushes it.
- This get automatically pubished to github pages
- In our case it is [site/rajzdocs](https://mrprajesh.github.io/rajzdocs/)

### Author
[Rajesh Pandian M](https://mrprajesh.github.io)
