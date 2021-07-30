# 8igMac's website

This website is built using [Zola](https://www.getzola.org/), a static site generator written in Rust.

## Useful command (ran under project dir)
Build the whole site in the public directory.
```
$ zola build
```

Start a developing server.
```
$ zola serve
```

Perform checking by building all page without writing 
to disk. Also check all the external links in Markdown files by trying to fetch them.
```
$ zola check
```
