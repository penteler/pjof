### 16:12
|key| function|
 -- | -- |
|`ctrl tab`      |select tabs of opened files|
|`ctrl shift tab`|select tabs of opened files in reverse|
|`ctrl  b`       |toggle sidepane with the explorer etc|
|`ctrl shift p`  |command palette|
|`ctrl p`        |search files in the opened folder|
|`ctrl shift f`  |find in sidepane|
|`ctrl  f`       |find in the opened file|
|`ctrl w`        |close file, the files are autosaved|
|`ctrl shift e`  |explorer in sidepane|
|`ctrl shift g`  |git/source/version conrolin sidepane|
|`ctrl shift d`  |Debug and run in the side panel|
|ctrl backtick(`)|Show/hide bottom terminal panel|
                |the debugger also runs here|
|key| function|
 -- | -- |
|ctrl shift `    |new terminal|
|`ctrl shift x`  |extensions in sidepane|
16:12
|`ctrl arows`    |hop over spaces|
|`end`           |go to the end of the line|
|`home`          |start of the line|
### 19
You don't have to select lines to do
`ctrl c` and `ctrl v`
|key| function|
 -- | -- |
|`ctrl d`        |can be used for selecting a word|
|`ctrl f` |can be then used to find and replace it|
### 22
## html shortcuts
# Emmet Abbreviations
|key| function|
 -- | -- | 
|`! bang symbol`  |for generating initial boilerplate|
|`h1`             |h1 tag|
|`div.classname`  |for a div with the class name|
|`div.container#e`|<div class="container" id="e"></div>|
                 do this without the `div`
|key| function|
 -- | -- |
|`.container#e`   |same output as above for any div
                 for any other element the tag
                 has to be specified|
|key| function|
 -- | -- |
|`<ul> li*3`      |for 3 list elements|
|`input:text`    |input of text type with black name & id|
## css shortcuts
|key| function|
 -- | -- |
`cur`           cursor: pointer;
`m10`           margin: 10px;
`p10`           padding: 10px;
# 25
`ctrl ,`        for settings
# font ligature
Enable it in the the settings.json and try out these
if you see this as your font preference:
Consolas, 'Courier New', monospace
change it to: 'cascadia code'
with font ligatures turned on this 
should appear as an equals sign striked out,
three lines striked out  an arrow sign,
an arrow sign a long arrow and two straight lines
both of these can be extended endlessly. 
After that there's atriple equals
!= !==  => ===> ==== ===
This should appear as an exclaim and an equals sign,
! and two equals signs, = and greater than symbol,
three =s and a >, four equals and three equals both
of wich are spaced out.
This table should make this data more readable:
# Table
| ON       | Input  | OFF     |
| -------- | ------ | --------|
| = striked| !=     |! and =  |
| 3-striked| !==    |!and 2=  |
| arrow    | =>     | =and >  |
| 3-striked| ===>   | 3=and > |
| 4equals  | ====   | 4= |
| 3equals| ===>   | 3= |

this is how you insert table in markdown
and it seems like the spacing doesn't matter it 
will look seam less in the output.

```markdown
| ON       | Input  | OFF     |
| -------- | ------ | --------|
| = striked| !=     |! and =  |
| 3-striked| !==    |!and 2=  |
| arrow    | =>     | =and >  |
| 3-striked| ===>   | 3=and > |
| 4equals  | ====   | 4= |
| 3equals| ===>   | 3= |
```
# ****27****
You can set font size in pixels in the settings
for the code and there's a zoom level for 
everything including the interface you can also 
use shortcuts:
`ctrl mousewheel up`
`ctrl mousewheel down`
`ctrl +`
`ctrl -`
# word wrap
There's word wrap in the settings by default 
it is off and wrap column set to 80 characters
## files: exculde
you see the directories and files that don't 
show up in the explorer you can also add 
files to this list by clicking on `Add Pattern` 
and then type in the name of the file 
or the name of the directory with two asterisk 
in front of them as such:
`**/src`
There are also `search: exlcude` settings
for search specific excludes and 
`explorer: exclude git ignore` settings
for ingnoring files based on your 
.gitignore. 
when you add patterns you're configuring
glob patterns for exluding file and 
folders.
### 30
#### use the command palette for cycling themes
themes can be searched for in extensions Or use 
`ctrl shift p` type in theme and select color 
theme. After this as you hover or scrol through 
the themes you'll see them changing in real 
time.