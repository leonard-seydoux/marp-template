---
marp: true
theme: presentation
math: katex
paginate: true
---

<!-- _class: titlepage -->

# A template scientific presentation made with the Marp ecosystem

`Léonard Seydoux` 

Last updated on September 2024 at the [institut de physique du globe de Paris](https://www.ipgp.fr). 
You can contact me at seydoux@ipgp.fr. 

<div class="logo">

![height:100px](images/logo/ipgp-upcite.svg) 
![height:90px](images/logo/cnrs.svg) 
![height:90px](https://avatars.githubusercontent.com/u/20685754?s=280&v=4)
![height:90px](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/768px-Visual_Studio_Code_1.35_icon.svg.png)

</div>

[<img src="images/logo/logo-github.svg" width=25 align="left" style="margin-top:10px; margin-right: -23px; "/>  `leonard-seydoux/marp-template`](https://github.com/leonard-seydoux/marp-template) 

---

## Typical slide with bullet points and an illustration

- The right image shows Earth
- The continents are colored in green
- The oceans are colored in blue

![width:300px](images/logo/ipgp-upcite.svg) 
![width:300px](images/logo/ipgp-upcite.svg) 
Drawing of the Earth 

> It confirms that Earth isn't flat (sorry flat-earthers)

<!-- _footer: Image: [www.twinkl.fr/parenting-wiki/earth](https://www.twinkl.fr/parenting-wiki/earth) -->

---

## Showing a table

| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| A        | B        | C        |
| D        | E        | F        |
| G        | H        | I        |
| J        | K        | L        |

> I'm sure this is way better with actual (and useful) data

---

## Boxes

### A subtitle for this slide

<div class="frames">

- __Axe 1__: Fouille de données par IA et fusion de données

- __Axe 2__: Extension de donnée par adaptation de domaine

- __Axe 3__: Physique des sources par IA générative + physique

</div>

###

---

## A slide with code


```python
import numpy as np

def my_function(x):
    return np.sin(x)

x = np.linspace(0, 2*np.pi, 100)
y = my_function(x)
plt.plot(x, y)
```

![width:500](https://media.geeksforgeeks.org/wp-content/uploads/20221120032916/2.png)

<span>

- This code allows to plot the sine function as a function of time
- The plot is shown on the right
- The plotting library used is `matplotlib`

</span>

--- 

## Scroll directly a webpage in a slide

<iframe src="https://fr.wikipedia.org/wiki/Terre" width="100%" height="500px"></iframe>

<!-- _footer: Source: [Wikipedia](https://fr.wikipedia.org/wiki/Terre) -->

---

<!-- _class: titlepage -->

#
# Thank you for your attention!
#