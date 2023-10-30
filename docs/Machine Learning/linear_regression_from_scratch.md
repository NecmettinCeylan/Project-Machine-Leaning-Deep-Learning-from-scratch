


![Image title](https://colab.research.google.com/img/colab_favicon.ico){ align=left style="height:30px;width:30px" }
[**View in Colab**](https://link-url-here.org)




---
# Linear Regression Fram scratch
---

Let's start with simplest case of linear regression which is one dependent variable and one independent variable, simple linear regression. The equation of simple linear regression is given by:


$$
y(x) = a + bx 
$$


## Dataset
---

<center>

|   index |   feature |   target |
|--------:|----------:|---------:|
|       0 | -0.469474 | -9.23956 |
|       1 | -0.234153 | -3.44105 |
|       2 | -0.234137 | -5.78107 |
|       3 | -0.138264 | -3.43807 |
|       4 |  0.496714 |  8.46012 |
|       5 |  0.54256  |  7.72548 |
|       6 |  0.647689 |  9.16405 |
|       7 |  0.767435 | 13.2115  |
|       8 |  1.52303  | 28.6429  |
|       9 |  1.57921  | 28.286   |

</center>

Since in the dataset we have y: target and x: feature, the goal is to find the best values for a and b.

