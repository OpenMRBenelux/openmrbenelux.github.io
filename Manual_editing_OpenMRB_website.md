# Manual to edit the OpenMRB website 

**Content**:

- [Manual to edit the OpenMRB website](#manual-to-edit-the-openmrb-website)
  - [Step 1: Install Ruby, RubyGems and Jekyll](#step-1-install-ruby-rubygems-and-jekyll)
  - [Step 2: Get the OpenMRB website repository ready](#step-2-get-the-openmrb-website-repository-ready)
  - [Step 3: Editing the website](#step-3-editing-the-website)
    - [Editing and updating separate pages](#editing-and-updating-separate-pages)
    - [Changing the structure of the website](#changing-the-structure-of-the-website)
    - [Adding team members & speakers](#adding-team-members--speakers)
    - [Running the website locally to see your changes](#running-the-website-locally-to-see-your-changes)
    - [Changing formatting](#changing-formatting)
    - [Current repository structure](#current-repository-structure)
  - [Jekyll-specific files and information](#jekyll-specific-files-and-information)



## Step 1: Install Ruby, RubyGems and Jekyll

Before working with Jekyll as a static website generator, we need to perform some installation steps. For Windows, follow [this instruction video](<https://www.youtube.com/watch?v=LfP7Y9Ja6Qc&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=3>). If you are using Windows, consider downloading the Ubuntu app from the Windows Store (using the Linux Subsystem for Windows). We need to install:

1. **Ruby**, a programming language that can run Jekyll
- Check your version: `ruby -v` (2.1 or higher needed)
   
- [Download for Windows](<https://rubyinstaller.org/downloads/>) (Mac already has it installed)
   
2. **RubyGems**, a package manager for Ruby that can install, update and maintain Ruby programs. We later use it to install Jekyll
- Check your version: `gem -v`
   
3. Install **Jekyll** using RubyGems:

   - `gem install jekyll bundler`

   - Check your version: `jekyll -v`



## Step 2: Get the OpenMRB website repository ready

This step assumes that you have [git installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) on your PC and already have a [Github account](https://github.com/join).  

1. [Fork](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) the [OpenMRB website repository](https://github.com/OpenMRBenelux/openmrbenelux.github.io) to your own account

2. Clone your forked repository to your Ubuntu/Linux environment (the environment that can run Jekyll). For example, make a directory “git” (`mkdir git`) to clone the current and future repositories in.

   - `cd git`

   - `git clone https://github.com/DorienHuijser/openmrbenelux.github.io.git`

3. Go into your now created repository folder: `cd openmrbenelux.github.io`

4. Set up the [OpenMRB website repository](https://github.com/OpenMRBenelux/openmrbenelux.github.io) as the upstream repository so you can push and pull to and from it directly:
   - Check your remotes: `git remote -v`. There should already be an `origin` (i.e., the link from which you cloned). 
   - Now also add the upstream repository: `git remote add upstream https://github.com/OpenMRBenelux/openmrbenelux.github.io.git`
   - If you check your remotes again with `git remote -v`, you will find both the `origin` and the `upstream` repositories.

5. Now you can update your own local copy of the repository with the changes made in the upstream (main) repository with
   - `git pull upstream master` (when updating your master branch with the upstream master branch)
   - or: `git checkout [other branch]` followed by `git pull upstream [other branch]` (when updating another branch with the upstream's branch)



## Step 3: Editing the website

Watch this [youtube playlist](https://www.youtube.com/watch?v=T1itpPvFWHI&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB ) to learn more about the Jekyll static website generator.



### Editing and updating separate pages

1. Move into the folder of the repository: `cd openmrbenelux.github.io` (or a longer path, e.g., `cd /mnt/c/Users/username/Documents/openmrbenelux.github.io`)
2. Make sure you are working on the correct branch: `git checkout [branchname]`
3. Edit the markdown (.md) files of the pages you want to edit. For example, use Atom or Typora or any other markdown editor [would recommend Typora because it also reads and allows editing html]. Save the changes.
4. To see your changes locally, run `bundle exec jekyll serve` (see below)
5. If you are happy with your change, stage the change: `git add [filename]` or `git all -A .` (if you want to stage ALL changes made)
6. Commit your staged files: `git commit -m "Edit x"`
7. Push your changes to your fork (online copy): `git push origin [branch name]`
8. On Github, open a Pull Request to merge your changes with the openmrbenelux repository



### Changing the structure of the website

There are currently 2 files with navigation menus which can be found in the `_data` folder of the repository:

- `navigation.yml`: This yml file (which can also be edited with a text editor) contains the menu as displayed at the top of the main page. It can unfortunately only contain 1 dropdown level!
- `past-events.yml` is a menu that is only displayed on the pages of previous events via the front matter on those pages (`menubar: past_events`).



If you want to move pages around:

1. Edit the relevant .yml file. Make sure the file links to the correct markdown files (in the correct repository folder) and file is correctly formatted (.yml files are very sensitive to wrong tabs and dashes)
2. Serve the website locally to make sure that your changes still result in a working website
3. Save, stage and commit your changes
4. Do a pull request



You can also create new menu bars in the same way as the existing ones: just create a new .yml file and on the relevant pages, include `menubar: name_of_menufile.yml` in the frontmatter of the page.



### Adding team members & speakers

Adding team members, advisors or speakers can be done by adding them to the relevant `.yml` files in the `_data` folder. The `page-team` and `page-speakers` pages have been set up to read the content directly from there and generate the HTML code automatically.

The CSS for those pages is being transferred or kept in the relevant files in the `_sass` folder.



### Running the website locally to see your changes

1. Move into the correct folder:`cd openmrbenelux.github.io`

2. Change to the correct branch: `git checkout [branchname]`

3. Serve the website locally: `bundle exec jekyll serve`

4. A text such as this will appear in your command window: 

   `Auto-regeneration: enabled for '/home/dorienhuijser/git/openmrbenelux.github.io'`

   `LiveReload address: http://127.0.0.1:35729`

   `Server address: http://127.0.0.1:4000/`

   `Server running... press ctrl-c to stop.`

   `LiveReload: Browser connected`

5. Copy the server address to your browser and check out the website locally in your browser!
6. If you want to stop serving (e.g., because you want to commit changes), press `CNTRL + C`



### Changing formatting

...

***Include info about formatting on the entire website vs. on separate pages***



### Current repository structure 

- `2019`, `2020` and `2021` folders contain the .md files which will be converted to html on the website
- `_data`: contains menus (footer_menu, navigation and past_events) and information about the team and speakers which will be automatically rendered on the website
- `_includes`: files that are referred to by `_layouts` html files
- `_layouts`: layouts, defined by the theme
- `_products`: files with the content that are referred to in `_layouts/content.html`. The content page itself just contains the text: `layout: content`.
- `_sass`: layout specifications
- `assets`: mainly images (in ext_images folder) 
- `img`: some more images
- `node_modules`: stuff for the Bulma theme
- Individual files:
  - README.md: handy info about the Bulma theme
  - _config.yml: see below
  - index.md and other .md files: homepage and other pages that are not assigned to a specific year



## Jekyll-specific files and information

- `_config.yml`: website settings. Allows defining default front matter:

  `defaults:`

  ​	`-`

  ​		`scope:`

  ​			`path: ""` # which files to apply the formatting to, e.g., "projects" > only in projects folder

  ​			`type: page`

  ​		`values:`

  ​			`layout: "page"`

  ​			`author: "authorname"`

- `Gemfile`: stores all Ruby dependencies for the website (e.g. Jekyll, theme, plugins)

- `index.md`: homepage, can be modified

- `_layouts` folder: which layouts does the theme you are using have? `layout: page` (front matter) refers to `page.html` in this _layouts folder. You can also create a layout yourself (in html). This will override the layouts from the theme.

  - `{{ content }}` > placeholder variable that refers to all content created that uses that layout
  - `{{ layout.variablename }}` to access front matter variables in the layout
  - `{{ page.variablename }}` to access front matter variable from a page
  - `{{ site.variablename }}` to access site-level variables from the `_config.yml` file
  - See all variables to refer to [HERE](https://jekyllrb.com/docs/variables/)
  - Layouts can contain different layouts within them as well (defined as front matter, e.g., `layout: "wrapperlayout"`). This way you only need to define the "main" layout once.

- `_includes`: defines specific formatting pieces that you can refer to in `_layouts`

  - e.g. `header.html` in `_includes` folder: `{% include header.html %}` in a layout
  - Include style information:
    -  `{% include header.html color="blue" %}` in a layout
    -  ` <h1 style="color: {{ include.color }}">{{ site.title }}</h1><hr><br> ` in `header.html`

- `_data`: yml, json or csv files. Can be accessed via a layout with `{{ site.data.nameofdatafile }}`

  - or loop through the file: `{% for item in site.data.nameofdatafile %} #do something {% endfor %}`



**Front matter**

- Information *about* the pages (e.g., title, date, layout, author), written in either YML or JSON
- Custom front matter variables are also possible
- Affect the URL of the page. Use a permalink variable, so that the URL will not break if the front matter changes
  - `permalink: "/my-permanent-url/"`
  - `permalink: /:categories/:title` > takes the categories and title for the URL



**Change the theme of the website**: 

- Go to rubygems.org and search for a new jekyll-theme that you like
- In the readme.md of the theme, there are usually instructions what to call the theme
- In the `Gemfile`: add `gem "jekyll-new-theme-you-want-to-use"`
- In the terminal: run `bundle install` to install all Gems in the Gemfile
- In the `_config.yml` file, update the `theme` variable
- Also check your pages/posts: do they use layouts that are included in the new theme? (see `_layouts` folder)



Page names: hyphen (-) will become a space

Drafts: put in `_drafts` folder, run `jekyll serve --draft` to include in website build



**Looping through pages (for loops in layouts)**

```
{% for page in site.pages %}

​<li><a href="{{ page.url }}">{{page.title}}</a></li> # create a navigation list

{% endfor %}
```


**Conditionals (if-else loops in layouts)**

```
{% if page.title == "My First Post" and condition %} # and, or both possible

​This is the first post

{% elsif page.title == "My Second Post"%}
​This is the second post

{% else %}
This is another post

{% endif %}
```



**Style navigation list**

```
{% for page in site.pages %}

<li><a style="{% if page.url == page.url %}color:red{% endif %}" href="{{ page.url }}">{{page.title}}</a></li>

{% endfor%}
```



**Static files**

- Don't have front matter, e.g., jpeg, pdf, etc. files. Are automatically recognized by Jekyll, directory does not matter much. E.g., in a layout: 

```
{% for file in site.static_files %}

​	{{ file.path }} {{ file.name }} <br>

{% endfor %}
```

- Give them front matter: in `_config.yml` file:

  `defaults:`

  ​	`- scope:`	

  ​		`path: "assests/img"`

  ​	`values:`

  ​		`image: true`

- In layout, this front matter can now be accessed:

```
   {% for file in site.static_files %}

   {% if file.image %}
  ​ <img scr="{{file.path}}" alt="{file.name}"> # if the file is an img, show it
  ​	{% endif %}

  {% endfor %}
```

