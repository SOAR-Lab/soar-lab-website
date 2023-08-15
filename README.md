## Update Papers and Members
- Put the PDF file inside the *papers* folder.
- Create a new item in the *ref.bib* file under the *assets* folder and add the relevant information to the item.

The paper will be added to the list of papers in the publications page.

To update the information about the team members or collaborators, simply edit the corresponding files under the *data* folder.

## Build

* Install [Jekyll](https://jekyllrb.com/docs/installation/)  (version less than 4.0 required) on your local computer
    * On MacOS, you will need to upgrade your Ruby version from the depricated v2.3 that is shipped. Follow the above Jekyll instructions closely.
* Run `$ bundle exec jekyll serve` in the repository root directory
* Your site is now hosted locally at `localhost:4000`, which you can access with your web browser.
   * It will be automatically re-built as you save changes to the files it contains.
   Refreshing your web browser reveals these changes.

Note:
* This webpage uses Jekyll plugins like Jekyll Scholar to automatically build your bibliography. 
  If you are using Github pages then you will have to build the site with the `Rakefile` in the root directory of the source branch.
  You can do so by first modifying the file as appropriate and then, after pushing your changes, execute `rake publish`.

## Customization

* Modify `_config.yml` as appropriate
* Modify YAML database files, located in `_data/*.yml`, as appropriate
* Modify individual pages, located in `_pages/*.md`, as appropriate

### Navbar

The pages listed in the top navbar are located in `_config.yml` file.
The typical options are already included or commented, though additional pages can be created and listed here.

### Creating or editing pages

All pages are located in the `_pages` directory.
Pages generally load information from YAML databases located as `_data/*.yml`.
Creating new pages can be done by using existing pages as a template.

#### Page header information

All pages require header information.
Example header data for the 'Talks' page is below.
```
---
title: "Talks"
layout: gridlay
sitemap: false
permalink: /talks/
---
```
The `layout` variable corresponds to HTML layouts in the `_layouts` directory.
The differences between most layouts is subtle and `gridlay` can generally be used.
The permalink must be unique for each page, and corresponds to the directory that will store the page in the compiled HTML.
Refer to your pages in `_config.yml` via the `title` variable.

#### Markdown

All pages are written in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) as `*.md`.
HTML commands and CSS styles can be directly used in a markdown files.

#### Publication page and database

The publications and talks are now listed via Jekyll Scholar.
The bibliography file `ref.bib` is located in the `cv/` directory.
Modify according to your needs.

## Hosting

Once your site has been modified to fit your needs, you should host it somewhere so others can access it.

### Github pages

A simple way to host your site for free is via [Github Pages](https://pages.github.com/).
This will provide you a free domain name at your_github_username.github.io.
Instructions on how to do this are available on their page.
They generally involve creating a repository on your Github titled `your_github_username.github.io` and uploading your files there (everything excepted the `_site/` directory, which the Github Pages service will generate using its own version of Jekyll).
Then, Github will automatically rebuild your site every time you push a commit to the repository (no bundle/jekyll commands required).


## License

Copyright 2021, Spencer H. Bryngelson and controlled via the MIT license.
You can copy and mess with this template.
