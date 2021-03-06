# gfm-toc

Ruby utility to generate a markdown formatted table of contents from GitHub flavored markdown files.

# Usage

The utility is all contained in a single file, so you can just grab the file with `curl`:

```shell
# download the utility
curl -O https://raw.githubusercontent.com/atheiman/gfm-toc/master/gfm-toc
# make it executable
chmod 764 gfm-toc
# show the help
./gfm-toc -h
# update your markdown file with a %TOC% where you want the TOC generated
./gfm-toc README.md
```

Place `%TOC%` in your markdown file whereever makes sense to you. Any headers identified with a `#` below the `%TOC%` are added into the generated table of contents.

See [INPUT.md](https://raw.githubusercontent.com/atheiman/gfm-toc/master/INPUT.md) and [OUTPUT.md](./OUTPUT.md) for a thorough example.

Run the utility with the `-h`,`--help` option to see the full option list.

[It should work with any crazy header you can come up with.](./.crazy-headers.md)
