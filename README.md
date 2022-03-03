# artifact-directory-template

This repository is a template for turning in links/locations to your
project artifacts. Instructions:

1. Fork this repository
   * You will be changing the file contents in this repository, but
     *do not change the file names!*.
2. Replace the blank `report.pdf` with your project report (you may
   update this with newer versions as the week goes on).
3. Edit `title-abstract.txt` and replace the sample title/abstract
   with the title/abstract of your project.
   * Be sure to leave the formatting of the file intact (with the
     `title:` and `abstract:` lines untouched).
4. Edit the `artifacts.json` file with links to your project
   artifacts. Do NOT change the keys of the json file, only the
   values.
   * `this-repository` contains the `github` url to your forked
     `artifact-directory-template` repository (this will allow us to
     get the newest version of your report and title/abstract).
   * `project-repository` contains the `github` url to your project
     repository (code artifact).
   * `dockerhub-repository` contains the docker username, docker
     repository name, and tag for reproducing your project.
   * `project-website-url` contains the _url_ to your project website.
   * `project-website-code` contains the github url to your project
     website's source code (if it's the same as your code repository,
     then re-list that url here).
5. Turn in the forked repository to Gradescope.
