# Personal Science Cookbook

This is a collection of useful "recipes" for personal science analysis.

Click [here](https://personalscience.github.io/cookbook/) to view the published book:

https://personalscience.github.io/cookbook/

------------------------------------------------------------------------

# How to Build This Book

This book uses the open source publishing system [Quarto](https://quarto.org/).

See [.\\\_quarto.yml](._quarto.yml%5D) for parameters

If you have a local repo, create a new `html` version using the Quarto command line:

```sh
quarto render
```

Final output is generated in `/docs`. 


Images and other assets are kept in `/assets`


## Github Pages

The published version at https://personalscience.github.io/cookbook/ is generated automatically. (See this repo's [settings/pages](./settings/pages)).

From the command line I type
```
quarto publish gh-pages
```

and it builds and deploys everything automatically.

