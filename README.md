# NOAA simple 

This is a template for [a simple Quarto website](https://nmfs-opensci.github.io/NOAA-quarto-simple/) that looks like a "book". This is a common format for documentation. It includes a GitHub Action that will build the website automatically when you make changes to the files.

`gh-pages` branch. Serving the website files from this branch is a common what to keep all the website files from cluttering your main branch. 

## GitHub Set-up

* Click the green "Use This Template" button to make a repository with this content.
* Turn on GitHub Pages under Settings > Pages . You will set pages to be made from the gh-pages branch and root directory.
<img width="540" alt="image" src="https://user-images.githubusercontent.com/2545978/196808262-3d2262be-b9b5-4897-bba5-fc2f056dd335.png">

* Turn on GitHub Actions under Settings > Actions > General
<img width="719" alt="image" src="https://user-images.githubusercontent.com/2545978/196808404-0c075fcf-db03-4516-88dd-3143b9fca475.png">

* Edit the repo description and Readme to add a link to the webpage. When you edit the description, you will see the link url in the url box or you can click on the Actions tab or the  Settings > Pages page to find the url.
Quarto website

## Customize

* Edit the qmd or md files in the `content` folder. qmd files can include code (R, Python, Julia) and lots of Quarto markdown bells and whistles (like call-outs, cross-references, auto-citations and much more).
* Add the files to `_quarto.yml`

