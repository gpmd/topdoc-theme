**Note: This is a slightly genericised version of the original [Topdoc demo theme](https://github.com/topcoat/topdoc-theme).**

Why did we genericise it? Well the original demo theme has a hard-coded header. We wanted to be able to pass in to `templateData` our own title, subtitle, url etc.

---

#Topdoc Demo Theme

A responsive [Topdoc](https://github.com/topcoat/topdoc) theme for the Topcoat Demos.


##Usage

If the topcoat repo is cloned locally as a sibling of this repo, running the following command:

```bash
topdoc -s release/css/ -d topdocs -t ../topdoc-theme/
```

Uses the template and generates the docs to a directory called `topdocs`.
