---
title: "A Great Title"
author: John Doe
date: January 1, 2000
slideNumber: true
theme: monokai
highlightjs-theme: monokai
width: 1920
height: 1080
transition: fade
---


## Lovely Slide Title
- Bullet points galore
- Nested bulleted lists
	- like this
		- and this
	- Support links like [this](#)
- **Bold some things**
- and _emphasize_ others


## Multicolumn support

::::::cols

::::col
Option A:
 : Description A

 Option B:
  : Description B
  : - with some
  : - bullet points

::::

::::col
- and then some content
- over here as well

::::
::::::




## Images
![A lovely image](../images/example_image.jpeg)




## Mathjax support

::::cols

:::{.col .block name="Theorem"}
We will use a theorem

$$\sum_i^{10} 5i^2 + 4$$
:::

:::col
- here I will
- include some more things
- that I want
:::
::::


## Code Test!
Here we have some code with sections highlighted, using reveals built in functionality alongside highlightjs.

``` {.python-repl data-line-numbers="-|1-3|4,5|6-7|9-15|16-22"}
>>> A = 10
>>> A
10
>>> int(23.45)
23
>>> type(A)
int
>>> # this is a comment! 123
>>> for i in range(5):
		print(i)
0
1
2
3
4
>>> for i in range(5):
		print(i)
0
1
2
3
4
>>> print("yay this works!")
yay this works!
```

<!-- Presenter notes -->
:::notes
Here I should talk about some things
:::


## Extra inline test
What about if I want code inline like this: `print(10)`{.python}? That works as well.


## Tables
Tables can be created using several different supported markdown flavors

| Command     | Description                              |
|-------------|------------------------------------------|
| Red Light   | One should stop immediately and not move |
| Green Light | One should start walking forwards        |
