# Cornerstone

<img align="right" width="250" src="http://632963c32a968e946ade-6a1f0be81bdf28a63f5fcf21842b6ecd.r29.cf1.rackcdn.com/cornerstone-logo.png">
## Installation

### Installing Required Packages

1. [Install Ruby](https://www.ruby-lang.org/en/installation/) if not present on the system.
2. [Install Gem](http://rubygems.org/pages/download) if not present on the system.
3. Install Rake if not present on the system - `sudo gem install rake`
4. [Install Git](http://git-scm.com/downloads) if not present on the system.

### Setup Project for Editing

1. Clone the vermeer branch of this repo - `git clone https://github.com/troyswanson/cornerstone --branch vermeer`
2. Move to the directory - `cd cornerstone`
3. Install dependencies using rake - `sudo rake install`
4. Run rake sass:build task to convert sass files to css - `rake sass:build`
5. Run rake jekyll:serve task to run the project - `rake jekyll:serve`

## Updating Content

All content is contained in the /site/docs directory in a $section.md file. 

Content is written in markdown. A helpful hint sheet for markdown syntax can be found [here](http://daringfireball.net/projects/markdown/syntax).

Primary Actions that will take place when modifying the project revolve around three primary actions: 

+ Adding a Category to the Side Nav.
+ Adding an Element to a Category.
+ Modifying an Element in a Category.

### Adding a Category to the Side Nav

1. Open the `/site/_data/nav.yaml` file
2. Find the section [Brand / Content / Patterns / Visual] of the site to which you want to add a category.
3. Insert the title of the category being creating under the Docs heading.
4. Create a markdown file in the `/site/docs` folder corresponding to the name inserted in step 3. Ex: mycategory.md
5. Populate the file with the desired elements.

### Adding an Element to a Category

1. Find the `/site/docs` folder and open the .md file corresponding to the Category name which will house the element. Ex: mycategory.md
2. Insert the element in markdown under an independent h2 tag. 
3. When adding an element ensure the required information is present. [Title / Use Case / How to Use / When to Use / Design Rationale / Code Snippits / Contextual Examples / Size & View-ports ]

### Modifying an Element in a Category

1. Find the `/site/docs` folder and open the .md file corresponding to the Category name.
2. Find the element in the .md file and edit the fields requiring modification.

