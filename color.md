# Color Theory

* **Use high contrast between colors**<br>
Consider a wider audience! A significant number of the population are color blind. Using high contrast colors helps _everyone_ read the content on your site.
  * [Test your color contrast](http://colorfilter.wickline.org/) <br>
  * [Test background and foreground text color](http://leaverou.github.io/contrast-ratio/)

* **Code fall-backs into color** <br>
If you decide to code a color with `rgba()`, include a fall-back above it which is a solid `rgb()` value for older browsers that can't read `rgba()`: <br>
  `color: rgb(12,15,134);`
  `color: rgba(12,15,134,.6);`