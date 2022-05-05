File extension should be ".md" and then click "**ctrl + shift + p**" and select **markdown: open preview to the side**

1- How to give headings in markdown
# Heading 1 (underline is auto added)

## Heading 2

### Heading 3

#### Heading 4


# 2- block f words

Normal text

> greater sign is added for this special text
>
>to keep all words in same block with space a greater sign in those skipped line is must. Just pressing enter will actually make a new block of text.



# 3- Line breaks

By pressing 'enter' or by adding\reverse slash\
to avoid stacking of below line with upper one.


# 4- Combine 2 things
Block of words and headings
>## heading 


# 5- Face of text

**Bold**\
*italic*\
***3 asterics for bold and italics***

- or bold by placing 2 underscores on both sides of word\
__Bold 2 underscores both sides__\
_Italic 2 underscores both sides_\
___for both bold and italics 3 underscores___

# 6- Bullet points

- we put a dash
- before text
- to make bullet points
- remember to put space after dash
    - press "tab" and then dash to make a subpoint
    - that's easy
        - further 2nd tab and dash
        - gives a thirds bullet line
         
# 7- Numbering

1. numbering wih dot and automatic numbering will be done
2. even if you do a mistake 
4. Markdown will correct numbering automatically
5. Just like in here i put 4 and 5 numbering skipping 3 while in output markdown automatically figured it out and continued with 3.

* we can also make a bullet by asteric and then enter

+ or we can also make a bullet by Plus sign and then enter


# 7- Line or Page breaks

for creating a line between two blocks of words we can do it by three dashes and then enter
        
---
---
- or we can also create a line between two blocks of words  by three underscores and then enter

___
___


- or we can also create a line between two blocks of words  by three asterics and then enter

***
***


# 8- Links & Hyperlinks

- to write a hyperlink first write link in square brackets and then __without space__ add url

[link](https://www.techprevue.com/decision-tree-perfect-visualisation-data/)

- or use less than signs to add link

<https://www.techprevue.com/decision-tree-perfect-visualisation-data/>

- within text link, write text in square bracket and then add url in parenthesis

[click to read about data visualization in detail](https://www.techprevue.com/decision-tree-perfect-visualisation-data/)


## Saving Links in a key
- To save a link in a key, write key in square brackets then a colon then url **no** parenthesis\

---
[web]:https://stackoverflow.com
Now I can recall key instead of using url by simply writting here and key in spearate square brackets\
we can see graphs web [here][web]

# 9- Images and Figures with link

> Images from local directory

Save that image in the same folder as th markdown file is and then mention that in markdown file.firstly Write QR in sq.bracket then image name with extension in parenthesis.. For example, QR code png can be add like:-

![QR](qr.png)

> Images from Online sources 

- remember to put ! mark before to retrieve image

![Earth](https://www.google.com/url?sa=i&url=https%3A%2F%2Fquizlet.com%2F234641392%2Fdraw-and-label-the-layers-of-the-earths-interior-including-moho-lithosphere-and-asthenosphere-diagram%2F&psig=AOvVaw04eP_Hk_U9V3W280zOXSHy&ust=1651768750381000&source=images&cd=vfe&ved=0CA0QjhxqFwoTCMisnrKkxvcCFQAAAAAdAAAAABAE)

# commenting in Markdown uses HTML

---
[//]: # (This may be the most platform independent comment)
---

# 10- Adding code or code block
  back comma, above" ~ "to make code appearnce separate from text `print(like this code)`

>Now adding a block will be done by 3 same commas ( *`* )
```

same commas repeater three times above and below make this block 

```
- we can even add programming language above block name to get its syntax

```python
x=1
y=5
g=x+y
g
```

# 11- adding tables

> using "|" will help making table.


| species | sepal_length | sepal_width |
|---------|--------------|-------------|
|virginica|    18.6      |     89      |
|versicolor|    18    |     6      |
|Setosa|    14      |     8     |


> To make table right alligned colon will be added on right of second dashed line after column name

| species | sepal_length | sepal_width |
|---------:|--------------:|-------------:|
|virginica|    18.6      |     89      |
|versicolor|    18    |     6      |
|Setosa|    14      |     8     |



> To make table left alligned colon will be added on left of second dashed line after column name

| species | sepal_length | sepal_width |
|:---------|:--------------|:-------------|
|virginica|    18.6      |     89      |
|versicolor|    18    |     6      |
|Setosa|    14      |     8     |



>To make table middle alligned colon will be added on both sides of second dashed line after column name


# 12- Contents

- It will draw table of contents

[1- Headings](#heading-1-underline-is-auto-added)\
[2- 2--block-f-words](#2--block-f-words)\
[3- line-breaks](#3--line-breaks)\
[4- combine-2-things](#4--combine-2-things)\
[5- face-of-text](#5--face-of-text)\
[6- bullet-points](#6--bullet-points)\
[7- line-or-page-breaks](#7--line-or-page-breaks)\
[8- links--hyperlinks](#8--links--hyperlinks)\
[9- images-and-figures-with-link](#9--images-and-figures-with-link)
[10- adding-code-or-code-block](#10--adding-code-or-code-block)
[11- adding-tables](#11--adding-tables)




# 13 Install extensions
Installed all required. Now we can use same code as in microsoft word, like ctrl + b for making bold..

or you  can select text u want to format and right click to get all formatting options


# 14 colour change of text

<span style= "color: yellow">
"write the line in middle for which you wanna change color"
</span>


# 15 writing math formula
> In-line math

To insert in-line math use the $ symbol within a Markdown cell. For example,\
$this_{is}^{inline}$

> Math blocks

To use a block equation, wrap the equation in either $$ or \begin statements.

$$
  \int_0^\infty \frac{x^3}{e^x-1}\,dx = \frac{\pi^4}{15}
$$

