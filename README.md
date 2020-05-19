## Final Project: Rocket Design and "Fly"
### UB-MAE 423: Introduction to Propulsion

The project aims to design a sounding rocket given a set of design parameters, with the focus of maximizing the efficiency.

#### Table 1: Design Input Parameters

| Input Parameter  |    Description of Parameter           |    Assigned value    |
|:----------------:|---------------------------------------|----------------------|
|        M_L       |    Payload mass                       |    1 Kg              |
|        h_max     |    Maximum altitude                   |    10k, 20k, 20k     |
|       a_star_max |    Normalized max. acceleration       |    5, 10, 20         |
|       SM         |    Static margin = (X_CP - X_CG)/D    |    1, 2, 3           |
|       rho_s      |    Shell (Aluminum) density           |    2700              |
|       rho_p      |    Propellant density                 |    1772              |
|       sigma_s    |    Shell working stress               |    60 MPa            |
|         N        |    Number of fins                     |    3                 |

#### Table 2: Design Output Parameters

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


![Rocket Geometry](/figures/rocket_geometry.png)

#### Figure 1: Parameterized Rocket Geometry. 

### Results:
### Part I
#### Design changes with maximum altitude, h_max variation:
Figure 2 (a & b) below shows that for the increase in maximum height from10,000 ft to 30,000 ft, the required burn time and velocity increases by around 40%. While the burn time and equivalent velocity are so impactful to attain a higher destination, the X_CG  and X_CPdoes not change drastically for the higher altitude. The changes in the X_CG  and X_CP are in fact less than 1% for variations in h_max.

![Altitude_Effect](/figures/fig_hmax_1.png)                 ![Altitude_Effect](/figures/fig_hmax_2.png)

	                    	(a)                                                           (b)
#### Figure 2: Design changes for h_max variation

#### Design changes with normalized maximum acceleration, a_max^* variation: 
The lower value of 5 and the upper value of 20 was under consideration to understand the effect of a_max^* change. For higher acceleration, the burn time and velocity logarithmically decrease in around 50%. Therefore, it shows that to achieve a higher acceleration for a rocket, it is very crucial to select a propellant and rocket structure that can efficiently minimize burn time. Also, the weight of the propellant, as well as the overall structure has a negligible (around 2%) effect on acceleration. 

![Acceleration_Effect](/figures/fig_amax_1.png)                 ![Altitude_Effect](/figures/fig_amax_2.png)

 	                    	(a)                                                           (b)
#### Figure 3: Design changes for a_max^* variation

### Part II
The designed rocket was simulated with the baseline condition h_max=20,000 ft,a_max^*=10,SM=2
The simulated results as ovserved from OpenRocket are lsited below:

#### Ideal Vertical Case: 
In an ideal situation we neglect the drag effect, which allows assuming ideal case with maximum efficiencies. So, the expected performance is much higher than the realistic condition.
For idealized case, the h_max,V_(r,max)  and a_max^*, with respect to the flight time is shown in the Fig.4 below:

![Ideal Case](/figures/plot_sim1.png)             
#### Figure 4: Rocket performance profile for ideal case (Drag force=0)



For more details please see [GitHub Repository](https://https://github.com/K-ayesha/Rocket_Design_Class_Project).
<!-- 
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
-->
