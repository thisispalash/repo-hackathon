# template-repo
> fork me !

## Github Pages

## Pull Requests

## Branches

`dev` :: branch where actual development happens, parallel is better (eg, uiux, web3, docs, serv, etc.)

`master` :: branch where [prallel] development is merged for new version, private beta if you will

`stage` :: branch where a landing page is created for above version, public beta if you will

`release` :: branch that browsers _land_ on, no changes must occur on this branch, except for merges from the `stage` branch

# Folder Structure

```
|- /demo
|-- /dat
|--- README.md
|-- /env
|--- README.md
|- /docs
|-- design.md
|-- externals.md
|-- howitworks.md
|-- improvements.md
|-- README.md
|- /src
|-- README.md
|- /static
|-- /css
|--- index.css
|--- ...
|-- /img
|--- logo.png
|--- cover.png
|--- ...
|-- /js
|--- index.js
|--- ...
|-- /tmp
|--- header.html
|--- footer.html
|--- ...
|- .gitignore
|- CNAME
|- index.html
|- README.md
|- LICENSE
```