## Final Project: Rocket Design and "Fly"
### UB-MAE 423: Introduction to Propulsion


The project aims to design a sounding rocket given a set of design parameters, with the focus of maximizing the efficiency.

### Table 1: Design Input Parameters

| Input Parameter  |    Description of Parameter          |    Assigned value    |
|:----------------:|---------------------------------------|----------------------|
|        M_L       |    Payload mass                       |    1 Kg              |
|        h_max     |    Maximum altitude                   |    10k, 20k, 20k     |
|       a_star_max |    Normalized max. acceleration       |    5, 10, 20         |
|       SM         |    Static margin = (X_CP - X_CG)/D    |    1, 2, 3           |
|       rho_s      |    Shell (Aluminum) density           |    2700              |
|       rho_p      |    Propellant density                 |    1772              |
|       sigma_s    |    Shell working stress               |    60 MPa            |
|         N        |    Number of fins                     |    3                 |

### Table 2: Design Output Parameters

|    Output Parameter    |    Description of Parameter                                       |
|------------------------|-------------------------------------------------------------------|
|       R                |    Initial to burnout mass ratio                                  |
|       W_eq             |    Equivalent/effective velocity of gas at nozzle exhaust         |
|       t_b              |    Burn time                                                      |
|       P_o              |    Exit Pressure                                                  |
|       D                |    Diameter of the rocket tube/ Height of rocket nose and fins    |
|       L                |    Length of the rocket tube                                      |
|      delta/D           |    Thickness to D ratio                                           |
|       X_CG             |    Center of mass/gravity                                         |
|       X_CP             |    Center of pressure                                             |
|       M_P              |    Propellant mass                                                |
|       M_o              |    Total mass                                                     |
|       lambda           |    The ratio of the specific heats                                |
|       epsilon          |    The ratio of mass, M_s/(M_P + M_s)                             |

![Rocket Geometry](/figures/rocket_geometry.png = 65x60)


You can use the [editor on GitHub](https://github.com/K-ayesha/Rocket_Design_Class_Project/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/K-ayesha/Rocket_Design_Class_Project/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
