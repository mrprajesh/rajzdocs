# This is a slate docs

To develop and run locally

```
$ bundle install
$ bundle exec middleman server
```
Check the page http://localhost:4567/

## Source
The main file is index.html.md inside `source` folder
In index.html.md file one can include other html.md file using
```
includes:
  - file1
```

These files must be place inside `source/include`



