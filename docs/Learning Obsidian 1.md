---
aliases: [Obsidian guide,Teach Obsidian]
---
# What is Obsidian? 
Obsidian is a note taking application that supports linking of notes that helps you connect your thoughts for more productivity and creativity. 

## How does Obsidian help connect thoughts? 
Obsidian uses the feature of [[Backlinks]] . You don't know what they are? Try clicking the Purple text.

### What Next?
Now let's Learn some simple Obsidian Commands 

## Obsidian Commands 
### Headings 
Headings in Obsidian can be written by using # the more amount of hashes you use the smaller the heading will be. [[Examples]]

Also be sure to leave a space after the Hash 

### Backlinks 
To make backlinks type [[]] and the name of the page you want to create a backlink to. More commands will appear on the screen after you type the brackets. 

### Emphasize 
To emphasize texts in your writing use the following commands 

#### Italics 
Start and end your sentence or word with a single asterisk( * ) or underscore ( _ ) or use CTRL + I

 *Italics*

#### Bold
Start and end your sentence or word with double asterisk( * ) or underscore ( _ ) or use CTRL + B 

**Bold**

#### Strikethrough 
use double tildes(~) for this

~~Strikethrough~~

#### Highlight 
Use double equals sign(=)

==Highlight==

#### Horizontal Line
use *** or --- or ___ 

***

### Creating Lists 

#### Bulleted List 
These can be created by using {-(space)'list item'} and nesting - will give u a nested list 

example:-

- item1 
- item 2 
   - item 3
   - item 4 

#### Numbered List
These can be created by using {1.'list item'} and can also be nested 

example:-

1. Item 1 
2. Item 2 
3. Item 3  
    1. Item nest 1
    2. Item nest 2

### Inserting Images 
Just insert Images from your pc. These can be resized by inserting resolution values in the file command after adding a |.
![[Dying Light 2 Stay Human Screenshot 2022.08.17 - 00.09.24.70.png|675]]
### Referring to Links 
This can be done by adding a name by using [] followed by () in which u write the link 

Example:-

[Obsidian](https://help.obsidian.md/How+to/Format+your+notes)

### Quote Blocks 
use > to enter quote blocks 

>You cannot **understand** Quantum Mechanics you can only **do** Quantum Mechanics.

\- David J. Griffiths

$\frac{2}{5} \alpha \sin{}$

>[! Note]
A \\ can be used to cancel out the effect of any command 

example:-

A - will give us a list but when we use \\- it would only appear as a dash 

### Writing Codes in Obsidian 
Anything written between \`\` will be considered code and triple bacticks like \`\`\` can be used to write a code block. Your preffered language can be written after the first 3 backticks to change the highlighting pattern based on the language. Indenting with 'Tab' key can also be used to write a code block.

Example:-

The code to print "Hello, world" in Python is `print("Hello, world")`  and the code to print the addition of 2 numbers is as follows.
```python 
a = 5 
b = 6 

print(a+b)
```

	This is a Tab indented code block


### Task Lists 
List of Tasks can be created by using a - and writng a x in square brackets \[\] like this \-\[x\]

Example:-

- [ ] Task 1 
- [ ] Task 2 

### Table 
Tables can be created by separating each column with a | and a line of hyphens - to separate header from cells

example :-

In code Example 

First Header \| Second Header 
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\|\-\-\-\-\-\-\-\-\-\-\-
This is cell 1 \| This is cell 2 
This is Cell 3 \| This is cell 4

Output Example 

First Header | Second Header 
----------------------|-----------
This is cell 1 | This is cell 2 
This is Cell 3 | This is cell 4 

Tables can also be justified by using colons (:) 

Example(view source code):-

TIME | SEPTEMBER 19 | SEPTEMBER 20 | SEPTEMBER 21
:--------------:|:--------:|:--------:|:-------------:
09:00 - 10:00 | PHY201 | MTH201 | BIO201
16:00 - 17:00 |        | CHM201 | IDC


### Using Advanced Tables Plugin 
Type \| then First heading and press Tab to enter next cell and press Enter to enter next row. Also Shift + Tab can be used to go to the previous cell.  

### Footnotes
Footnotes can be added like this. You need to write \[\^text(without gaps)\] and then in the end specify the value of each footnote by writing it's value after writing \[\^Text of the footnote you are referring\]\: and then write what is the value of the footnote by first giving a space after the colon.

This is a foot note! [^1] Here is another footnote[^anotherone]

[^1]: Foot note has this value 
[^anotherone]: This is yet another footnote 

For inline footnotes write it directly after a sentence and use the carat(^) before the square brackets 

This is an inline footnote ^[Hello I am a footnote]

### Comments 
These are texts that will only show in the source mode and not in the reading mode. 

%%This is a comment%% 

%%
This 
is 
a 
comment 
block 
%%

### Callouts
Callouts can be written by using a > followed by \[\!(Text for callout) \] then you can write multiple links within the callout and it also supports markdown and link embeds
> [!First Callout]
> First Callout 
> here is some **Markdown**
### Math
Math can be written in Obsidian like Latex using Mathjax. 

Inline equations can be written like this \$E=MC^2\$
Output- $E=mc^2$ 

Display equations can be written like this \$\$\int e^x.dx\$\$
Output - $$ \int^b_a e^x.dx$$
Further Reading for Mathjax - [Mathjax Website](http://docs.mathjax.org/en/latest/basic/mathjax.html)
### Diagram 
These can be created using a language called mermaid. I am not learning it right now but will do it later on.

Here is the link to [Mermaid](https://mermaid-js.github.io/mermaid/#/)

and a interactive mermaid editor for easy work [Mermaid Editor](https://mermaid-js.github.io/mermaid-live-editor/edit#pako:eNpVkM1qw0AMhF9F6JRC_AI-BBo7ySWQQnPz5iC8cnZJ9oe1TAm2373rpIVWJ6H5Zhg0Yhs0Y4nXRNHAuVYe8rw3lUm2F0f9BYpiMx1YwAXPjwm2q0OA3oQYrb--vfjtAkE1HheMQYz1t_klVU__yfMEdXOkKCFe_irnrzDBrrEfJsf_V0zi7No3HZUdFS0lqCg9EVyj4-TI6lx9XC4KxbBjhWVeNXc03EWh8nNGh6hJeKethIQ56t7zGmmQ8PnwLZaSBv6Fakv5E-6Hmr8B2pxc3Q)

### Excalidraw
It's a plugin to draw in obsidian. These drawings can be embeded in the notes by directly draging. 