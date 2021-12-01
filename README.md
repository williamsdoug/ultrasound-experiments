# ultrasound-experiments

Repo containing exploratory code for analyzing medical ultrasound images.  This is currently in early development phases and may not work.

Note:  This repo organized using nbdev.  Command ```nbdev_build_docs``` currently produces error



##  Folder Organization
- experimental_nbs:  Discovery and model training code
- models: Directory for all models.  Contents not saved to GitHub
- nb_dev related folders
  - ultrasound: Supporting library
  - nbs: Development notebooks for supporting library
  - tutorial_nbs:  Usage examples for supporting library


## Previewing Documents Locally 

It is often desirable to preview nbdev generated documentation locally before having it built and rendered by GitHub Pages.  This requires you to run Jekyll locally, which requires installing Ruby and Jekyll. Instructions on how to install Jekyll are provided [on Jekyll's site](https://jekyllrb.com/). You can run the command `make docs_serve` from the root of your repo to serve the documentation locally after calling `nbdev_build_docs` to generate the docs. 

In order to allow you to run Jekyll locally this project contains manifest files, called Gem files, that specify all Ruby dependencies for Jekyll & nbdev. **If you do not plan to preview documentation locally**, you can choose to delete `docs/Gemfile` and `docs/Gemfile.lock` from your nbdev project (for example, after creating a new repo from this template). 
