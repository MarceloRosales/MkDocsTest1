# MkDocs  

[MkDocs]( https://www.mkdocs.org/) is a **fast, simple and downright gorgeous** static site generator that's geared towards building project documentation.  
Documentation source files are written in Markdown, and configured with a single YAML configuration file.  
Start by reading the introductory tutorial, then check the User Guide for more information.  

**Mkdocs Python - How to Create & Publish Documentations For Your Packages**  
<iframe width="560" height="315" src="https://www.youtube.com/embed/NuNj75iE8KA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  

**Alexys Jacob - Create beautiful and localized documentations and websites using MkDocs + Github**  
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pYN6Z-t1-s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  

[MkDocs Materials](https://squidfunk.github.io/mkdocs-material/):  

Documentation that simply works. 
Write your documentation in Markdown and create a professional static site in minutes – searchable, customizable, for all devices.  

[MkDocs Themes]( https://github.com/mkdocs/mkdocs/wiki/MkDocs-Themes)   

[top](#)  
### MkDocs Install.  

[MkDocs official site]( https://www.mkdocs.org/)  
User Guide  
Building Documentation with MkDocs  
The MkDocs Developer Guide provides documentation for users of MkDocs. See Getting Started for an introductory tutorial. You can jump directly to a page listed below, or use the next and previous buttons in the navigation bar at the top of the page to move through the documentation in order.  
- [Installation](https://www.mkdocs.org/user-guide/installation/)  
- [Writing Your Docs](https://www.mkdocs.org/user-guide/writing-your-docs/)  
- [Choosing Your Theme](https://www.mkdocs.org/user-guide/choosing-your-theme/)  
- [Customizing Your Theme](https://www.mkdocs.org/user-guide/customizing-your-theme/)  
- [Configuration]( https://www.mkdocs.org/user-guide/configuration/)  
- [Deploying Your Docs]( https://www.mkdocs.org/user-guide/deploying-your-docs/)  

[HOW TO INSTALL MKDOCS ON MAC AND SETUP THE INTEGRATION TO GITHUB PAGES]( https://suedbroecker.net/2021/01/25/how-to-install-mkdocs-on-mac-and-setup-the-integration-to-github-pages/)  January 25, 2021  

Summary:  
LOCAL SETUP ON MAC OS  
- brew  `brew --version`;   
- Python 3  `python --version`; find&install `brew list <formula1> || brew  
- install <formula1>`; `brew install python3`; **`brew install python@3.10`**    
- Pip  : `pip --version`; `pip3 install --upgrade pip`    
- MkDocs  : `pip3 install mkdocs`  (I used this install as described in guide  
- option: `brew install mkdocs` (error)  
- MkDocs Material Extensions  : `pip3 install mkdocs-material`  
Other Plugins:  
- [i18n]( https://github.com/ultrabug/mkdocs-static-i18n):  ` pip install mkdocs-static-i18n`;  
- Theme Materials: ` pip install mkdocs-material`  


CONFIGURATION IN THE GITHUB PROJECT  
- GitHub CI  
- GitHub Pages  
- GitHub Branch  

MKDOCS INSTALLATION ON MAC  
STEP 1: VERIFY THE BREW INSTALLATION  
Check if intalled:  
`brew –version`  

STEP 2: CHANGE THE FOLDER PERMISSION TO INSTALL PYTHON, IF NEEDED  
sudo chown -R $(whoami) /usr/local/lib/pkgconfig  
chmod u+w /usr/local/lib/pkgconfig  

STEP 3: INSTALL PYTHON3  
To check if python and pip are installed use:  
`python --version`  (Python 3.8.2)  
`pip --version`  (pip 20.0.2 from /usr/local/lib/python3.8/site-packages/pip (python 3.8))  
Or 
`brew list <formula1> || brew install <formula1>`
If not installed use:  
`brew install python3`  
20220704: Already Installed version 3.8, 3.9 
I installed lates version:
` brew install python@3.10`  
```
Python has been installed as
  /usr/local/opt/python@3.10/bin/python3

Unversioned symlinks `python`, `python-config`, `pip` etc. pointing to
`python3`, `python3-config`, `pip3` etc., respectively, have been installed into
  /usr/local/opt/python@3.10/libexec/bin

You can install Python packages with
  /usr/local/opt/python@3.10/bin/pip3 install <package>
They will install into the site-package directory
  /usr/local/lib/python3.10/site-packages

tkinter is no longer included with this formula, but it is available separately:
  brew install python-tk@3.10

See: https://docs.brew.sh/Homebrew-and-Python

python@3.10 is keg-only, which means it was not symlinked into /usr/local,
because this is an alternate version of another formula.

If you need to have python@3.10 first in your PATH, run:
  echo 'export PATH="/usr/local/opt/python@3.10/bin:$PATH"' >> ~/.zshrc

For compilers to find python@3.10 you may need to set:
  export LDFLAGS="-L/usr/local/opt/python@3.10/lib"

For pkg-config to find python@3.10 you may need to set:
  export PKG_CONFIG_PATH="/usr/local/opt/python@3.10/lib/pkgconfig"

==> Summary
🍺  /usr/local/Cellar/python@3.10/3.10.5: 3,137 files, 56.8MB
==> Running `brew cleanup python@3.10`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
```

STEP 4: Install UPGRADE PIP  

`pip –version`  
`pip3 install --upgrade pip`  

STEP 5: INSTALL MKDOCS  
`pip3 install mkdocs`  (I used this install as described in guide).  

`brew install mkdocs` :  
```
Error: The `brew link` step did not complete successfully
The formula built, but is not symlinked into /usr/local
Could not symlink bin/mkdocs
Target /usr/local/bin/mkdocs
already exists. You may want to remove it:
  rm '/usr/local/bin/mkdocs'
```  

STEP 6: INSTALL MKDOCS-MATERIAL  
`pip3 install mkdocs-material`  

STEP 7: INSTALL MKDOCS-MATERIAL-EXTENSIONS  
pip3 install mkdocs-material-extensions  

VERIFY AND BUILD YOUR DOCUMENTATION  
STEP 1: ENSURE YOU HAVE THE MKDOCS.YML FILE IN PLACE  
Here is an example configuration for the mkdocs.yml file and here you find an example project, which is based on that configuration.  


---

[top](#)  
### Documentation
For full documentation visit [mkdocs.org](https://www.mkdocs.org).

### Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `Cnt+C` - to stop server. 
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.
* ` mkdocs gh-deploy` - deploy to github.  

Project layout

	mkdocs.yml  		# The configuration file.
	docs/
		index.md  	# The documentation homepage.
		...  			# Other markdown pages, images and other files.

[top](#)  
### To create a site:  


```
cd /Users/marcelorosales/Documents/GitHub/MkDocs/MkDocsTut220704
```  
```
mkdocs new Hello-siteTest  
```  

INFO     -  Creating project directory: Hello-siteTest  
INFO     -  Writing config file: Hello-siteTest/mkdocs.yml  
INFO     -  Writing initial docs: Hello-siteTest/docs/index.md  

```
Ls  
```  
Hello-siteTest  

```
cd Hello-siteTest  
```  

```
Tree  
```  
.  
├── docs  
│     └── **index.md**  
└── **mkdocs.yml**  

```
code .  
```

In editor softw Modify mkdocs.yml, the site_name, site_url, Nav, etc.   

```
site_name: Hello-siteTest
site_url: https://example.com_or_my.github
nav:
  - Home: Index.md
```
Save..  

[top](#)  
### Live Pre-view of the site (Local Server)  
In terminal.  
```
mkdocs serve  
```

INFO     -  Building documentation...  
INFO     -  Cleaning site directory  
INFO     -  Documentation built in 0.07 seconds  
INFO     -  [16:12:35] Watching paths for changes: 'docs', 'mkdocs.yml'  
INFO     -  [16:12:35] Serving on http://127.0.0.1:8000/  
INFO     -  [16:13:00] Browser connected: http://127.0.0.1:8000/  

[top](#)  
### To create more Nav Tabs

In editor: New File > language: .md > {# Name of the Tab or Section} > Save: {NewNavTabName} > Save
Eg.
NewNavTab1.md
NewNavTab2.md

Open mkdocs.yml > Add NavTabs file Names to Nav 

```
site_name: Hello-siteTest
site_url: https://example.com_or_my.github
nav:
  - Home: Index.md
  - New Nav Tab 1: NewNavTab1.md
  - New Nav Tab 2: NewNavTab2.md
```
[top](#)  
### MkDocs Themes  

In the **mkdocs.yml** file add a theme: Eg theme: readthedocs

```
site_name: Test site
site_url: https://example.com_or_my.github
nav:
  - Home: index.md
  - New Nav Tab 1: NewNavTab1.md
  - New Nav Tab 2: NewNavTab2.md

theme: readthedocs 
```
Other themes.  
```
theme: 
#  name: readthedocs 
  name: material

```
[top](#)  
### Add images/assets  

Stop server.  
Create assets/ in the docs/ .  
Insert images in the folder.  
In the Hom

![NiigataUicon](assets/NiigataUicon.png)  

[top](#)  
### Internationalization plugin.  

#### Pages
1. Create the pages in the desired languages.  

Index.md 	--> 	Index.en.md  
		| 	--> 	Index.jp.md  
		| 	--> 	Index.es.md  

2. Add plugins to .yaml file

```
plugins:
  - search # add search box.
  - i18n: # language plugin. 
      default_language: en
      languages:
        en: English
        jp: 日本語
        es: Español
```

Then deploy: mkdocs serve  


> May require Install plunging  
```
pip install mkdocs-static-i18n  
```
More info [here]( https://github.com/ultrabug/mkdocs-static-i18n)  


#### Images

1. Create the images in the desired languages and **`add the language as an extension`**.  

img.png 	--> 	img.en.png  
		| 	--> 	img.ja.png  
		| 	--> 	img.es.png  
> WARNING  -  Language jp is not supported by mkdocs-material==8.3.8, not setting the 'theme.language' option.  CORRECTION: is `ja` for Japanese, not jp.  

It works anyways‼!

2. In md files just use the name of the image, plug in will automatically assign the language extension to the corresponding language .md file.  Eg.  
```
![imgName](assets/img.png)   
```

[top](#)  
### To build site.  
Once site is finished, stop live preview **`Cnt+C`**  
In Terminal:   
```
mkdocs build
```
INFO     -  Cleaning site directory  
INFO     -  Building documentation to directory:  
            /Users/marcelorosales/Documents/GitHub/MkDocs/MkDocsTut220704/Hello-siteTest/site  
INFO     -  Documentation built in 0.11 seconds  

> Will create all the files and folders required for an HTML site.   

[top](#)  
### To deploy in Github.  

In terminal: (Make sure you are in the directory containing the site)  
```
mkdocs gh-deploy
```

**Revise this section**  

1. Open Github Desktop
1. Add > Add an existing repocitory > ..[].. > choose > path > add > ..[!∆!].. © `create a repository` > …[]…  
1. Name:{} > Description: {} > © Create Repository.  
1. Commit > Description > © Commit to main  
1. Go to my github.com > General > Danger zone > Change visibility > …[]… Make public > Please type … to confirm.  
1. Go to Pages > Branch: © gh-pages > © root > save  
1. ` Your site is published at Error! Hyperlink reference not valid.  

After committing to github.  
Try later.  

[top](#)  
### Automatic mkdocs gh-deploy and plugin extensions  

<iframe width="560" height="315" src=" https://www.youtube.com/embed/0pYN6Z-t1-s?start=1701 " title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  

Use **Github Actions** to run **`mkdocs gh-deploy`** automatically when `push` new commits.  

.github/workflows/gh-deploy.yml   

 [ ] Finish this section.  

Theme Materials  

Install  
```
pip install mkdocs-material
```

[top](#)  
### Material theme extension guide. 


[Navigation]( https://squidfunk.github.io/mkdocs-material/setup/setting-up-navigation/#navigation-expansion)  


### Mkdocs Install MAC OS   
brew --version  
python --version  
brew install python3   _# (not used)_    
brew install python@3.10  
pip --version  
pip3 install --upgrade pip  
pip3 install mkdocs  
brew install mkdocs   _# (not use)_  
pip3 install mkdocs-material  
**Other Plugins:**   
pip install mkdocs-static-i18n    _# (Internationalization plugin)_      
pip install mkdocs-material   


#### Comments in Markdown  

If you want a comment that is strictly for yourself (readers of the converted document should not be able to see it, even with "view source") you could (ab)use the link labels (for use with reference style links) that are available in the core Markdown specification:  
http://daringfireball.net/projects/markdown/syntax#link  
That is:  
```
[comment]: <> (This is a comment, it will not be included)
[comment]: <> (in  the output file unless you use it in)
[comment]: <> (a reference style link.)
```

Or you could go further:  
```
[//]: <> (This is also a comment.)
```
To improve platform compatibility (and to save one keystroke) it is also possible to use # (which is a legitimate hyperlink target) instead of <>:  
```
[//]: # (This may be the most platform independent comment)
```
For maximum portability it is important to insert a blank line before and after this type of comments, because some Markdown parsers do not work correctly when definitions brush up against regular text. The most recent research with Babelmark shows that blank lines before and after are both important. Some parsers will output the comment if there is no blank line before, and some parsers will exclude the following line if there is no blank line after.  
In general, this approach should work with most Markdown parsers, since it's part of the core specification. (even if the behavior when multiple links are defined, or when a link is defined but never used, is not strictly specified).  

Placing a comment between `<>` will make it a comment and invisible in a markdown document. Ex. _______ <this is a comment> (there is a comment here)    

This is an example 1 [comment]: <here is the comment> (This is a comment, it will not be included)  
This is an example 2 [//]: <> (This is also a comment.)  
This is an example 3 [//]: # (This may be the most platform independent comment)  

Comments Examples: (3):    
[comment]: <here is the comment> (This is a comment, it will not be included)  
 [//]: <Here is another comment> (This is also a comment.)  
[//]: #This is the comment (This may be the most platform independent comment) **this type of comment does not seems to be working)**    


