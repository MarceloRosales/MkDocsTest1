# VS code:  
<iframe width="560" height="315" src="https://www.youtube.com/embed/ifTF3ags0XI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>    

**VS Code key shortcuts**  
`Shft+Cmd+P` » 	show all commands, search key shortcuts.  
`Cmd+P` »	 Go to file (open).  
`Cont+Tab` »	 Switch between Tabs/Pages.  
`Cmd+W` »	 close file.  
`Shift+Cmd+F` »		 Find in File.  
`F5` »	 Start debugging.  
`Cont+` »	 Toggle Terminal.  
`shift+Cmd+X` »	 Extensions.  

[Don't Use the Sidebar in VS Code!! vid](https://youtu.be/s3H6PmB4SZ4)  
Extensions Recomended:  
Advanced-new-file by patbenatar.  
File Utils by Steffen Leistner.  

**Setting Sync** on: Account -> Github.  

**Extensions installed**  
How to install extension: -> Open VS code > Extensions (shift+Cmd+X) > search: extension name > ©Install button.  
Top 40+ VSCode Extensions for Developers in 2022 [Link]( https://www.tabnine.com/blog/top-vscode-extensions/)   
[Top 10 VSCode extensions to use in 2022]( https://www.educative.io/blog/top-vscode-extensions)  

+ **Markdown-preview-enhanced** by Yiyi Wang.  
+ **Live Preview** by Microsoft [vid](https://youtu.be/hDh1rGG0pTQ)  
+ **Markdown All in One** by Yu Zhang, [link](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)  
+ **R** by REditorSupport  
+ **GitLens — Git supercharged** by GitKraken  
+ **YAML** by Red hat.  
+ **Auto Rename Tag** by TabNine.  
+ ** Peacock** by John Papa.  
+ ** Colorize** by kamikillerto.  
+ ** Code Runner** by Jun Han.  To run only a small snippet of code.  
+ **Auto rename tag** by Jun Han.   
+ **Vim** by vscodevim (need this emulator? Probably not, it just gives you some special shortcuts **do not install**)..
> Warning.  This extension will Override Rich Text Copy/Paste of VS. **Copy and Paste code into Word, Ignores Syntax Highlighting** (When copy code and paste in Word, code colors will no longer be applied). 
> 1. Make sure that // Code > Preferences> Settings > Text Editor > √ **Editor: Copy With Syntax Highlighting** **(is checked)**. Controls whether syntax highlighting should be copied into the clipboard.  
> 1. To solve: shift+Cmd+P > type: copy > in: Vim: !© Override Copy **(uncheck vim override copy)**. Override VS Code's copy command with our own copy command, which works better with VSCodeVim. Turn this off if copying is not working.  

**VS Code tips:**  
- **Indentation settings and the indentation status bar entry**  
Low right // Tab Sizeˇ > Indent using tabs > © 2.  
Convert indentation to tab/spaces:  
Low right // Tab Sizeˇ > Convert indentation to Spaces || Convert indentation to Tabs.  
or  
VS code panel > R© > Format document > 

- [HTML preview in VS Code](https://youtu.be/kIH1Pyk-bwQ)  
  * Live Server by Ritwick Dey (Opens in Web browser only).  
  *HTML Preview by Thomas Haakon Townsend (Deprecated).  
  * [Markdown preview enhanced]( https://shd101wyy.github.io/markdown-preview-enhanced/#/). Check out shd101wyy/markdown-preview-enhanced (Public).  

- **Unsplit an editor**, go back from 2 code views to 1, same with terminal.  
To "unsplit" editor groups **without closing any open files**, use the menu-bars:  
View > Editor Layout > Single (or, while in the editor, press and release ALT and then type vls).  
Editor groups are also closed by default when they become empty. 


- **Wrap code**  
Settings »	 Cmd+,
//Code > Preferences > Settings > Editor: Word Wrap
Controls how lines should wrap.

- **Types of comments:**  
  1. Single-line comment.  
Syntax  
```
#This is a comment
Example:
#Single line comment
echo "hello world"
```

  1. Multi-line comment.  
Syntax:  
```
: '
This is a
Multi-line comments'
Example:
echo "multiline comments"
: '
Print some word'
```

Types of codes?  
```bash {cmd}
ls .
```
	```javascript {cmd="node"}
const date = Date.now()
console.log(date.toString())
```
	```erd {cdm:true, output:”htlm”, args:[“-i”, “input_file”, “-f”, “svg]}

[Person]
*name
Height
Weight
+birth_location_id

[Location]
*id
City
State
Country

Person *--1 Location
```
	``` {r}
#code written in R
print(‘AIR Forum 2018’)
```





