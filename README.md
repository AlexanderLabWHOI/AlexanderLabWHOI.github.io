# Alexander Lab @ WHOI website

The code for the generation of this website are located here:  https://github.com/AlexanderLabWHOI/academic-kickstart

## Instructions for website modification:
  - Make changes to the md files in the content folder or the config file
  - Add, commit, and push changes to https://github.com/AlexanderLabWHOI/academic-kickstart
  - Run `deploy.sh` to (1) build with hugo, (2) add, commit, and push website changes to `AlexanderLabWHOI.github.io`
  - Update/populate publications with https://github.com/sourcethemes/academic-admin:
  ```
  academic import --bibtex static/pubs/featured-publications.bib --featured
  academic import --bibtex static/pubs/publications.bib
  ```
