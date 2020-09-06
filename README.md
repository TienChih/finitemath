# TienChih.github.io

While in this folder, use the following command to rebuild your document to HTML:

```
pretext build
```

Add the `--diagrams` option if e.g. TikZ images need to be rebuilt as well
(and `-v` to display updates on the long build process).

```
pretext -v build --diagrams
```

To preview your current work:

```
pretext view
```

By default your current build is not published publicly. Use
this and follow instructions to publish to GitHub Pages:

```
pretext publish
```