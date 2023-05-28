# animated_plots_with_python_for_LaTeX
Create animated plots with python to implement in LaTeX

##Creat animated plots of 1D or 2D mathematical objects to eventually implement in LaTeX for publishing. 

Every part of this project contains sample code to do the following: 
* Create 1D animated plots (e.g. graphs of functions) and implement them in LaTeX
* Create 2D animated region plots and implement them in LaTeX
* Create 2D colorized plots (e.g. levelsets of 2D function) and implement them in LaTeX
* Make sure that text in figures is automatically aligned with text in LaTeX (same font, size, etc.) and searchable using PGF format

Using Matplotlib and Numpy we create mathematical plots that depend on a parameter and animate them as the parameter varies. I show sample code on how to animate these plot in python and save them directly as gif. However, this is not a good option if you want to implement these plots in LaTeX. For the latter purpose, we create individual pictures with python and animate them later with LaTeX itself. For compatability I use the PGF format to save these pictures. I also present an alternative in case the PGF files get to big (can be the case for 2D plots) by rasterizing the plot but not the text in the figure. 

I started this project during my PhD where I needed to do exactly this for some papers. I'll cite them as soon as they published. As i'm a novice in programming, my code is surely far from oprimal. Though it is reasonably fast and prouces exactly the output I wanted. Since it took me a lot of work to figure out how to do it, I though the time would be wasted if i don't share it. Maybe, somebody needs to accomplish a similar task and finds this project useful and timesaving. Another reason for putting the project online was that, usually, in the mathematical community software like Mathematica and MatLab are preferd for this task. However, neither of these softwares are open source and, moreover, If found the way to do it in python very satisfying and nice. Thus I'd also like to promoe python for this kind of tasks which, in my opinion, works just as fine. 
