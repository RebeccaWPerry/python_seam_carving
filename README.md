@SHEHACKS Boston, January 2018

## Required Prework
During this workshop, you will be writing Python code on your own laptop to analyze images. You will walk away from the workshop with code to use on images in the future and insight into interacting with images as data! To make this possible, I ask that you do some setup on your laptop before arriving. If you run into trouble installing the necessities, please come to the workshop early to get assistance

To complete the workshop, you will need Python and a few image processing libraries. Here are separate instructions for those who have used Python before and for newbies: 

### This is all new to me
My recommendation is to install the Anaconda Python distribution. This is a way to install Python bundled up with a lot of really helpful libraries and the Jupyter notebook.

You can choose between 3.6 and 2.7. If you are just starting out and aren't tied to any legacy code, I recommend going for 3.6. You can download either version [here](https://www.anaconda.com/download/){:target="_blank"} (https://www.anaconda.com/download/).

After completing the installation (could take up to 30 minutes), you will need to verify that it installed correctly following the steps below.


### I already have Python on my computer
Great -- let's check that you have the Jupyter notebook and a few really helpful libraries.

1. Open a terminal (linux/apple) or command prompt (windows) and type ipython followed by enter.
```markdown
jupyter notebook
```
If you see a web browser open to a tab with Jupyter in the top left, then you have the Jupyter notebook correctly installed! If you see an error instead of these things, then you will need to install the Jupyter notebook in addition to the Python you have on your computer. I recommend going back to "This is all new to me," but you can also forge ahead by [installing Jupyter on its own](http://jupyter.org/install.html){:target="_blank"}.

2. Now check for packages that we will use in class by starting a new notebook and typing these lines followed by shift-enter:
```markdown
%matplotlib inline
import scipy
import numpy as np
import matplotlib.pyplot as plt
import cv2
```
If these packages are already installed, then the notebook will simply return a new input line. If you are missing any of these libraries, you will see a message like "ModuleNotFoundError: No module named 'cv2'." If that is the case, you can try installing the missing packages individually ([https://matplotlib.org/users/installing.html](https://matplotlib.org/users/installing.html){:target="_blank"}) or go back to This is all new to me.

3. Now let's try to generate a plot. In the Jupyter notebook where you have already imported run the import statements, type this in the next input cell:
```markdown
plt.plot([1,2],[2,3],'-ro')
```
The intended output is plot with a line connecting two points. If you got an error instead, Google will be the best avenue to troubleshoot the error. 

4. Great! You know how to start up an interactive python console and can import the necessary libraries. Please bring this laptop to the workshop. See you there!

### Resources

[Seam Carving](https://en.wikipedia.org/wiki/Seam_carving){:target="_blank"}

[Seam carving for content-aware image resizing](https://inst.eecs.berkeley.edu/~cs194-26/fa16/hw/proj4-seamcarving/imret.pdf){:target="_blank"}, Shai Avidan, Arie Shamir, ACM SIGGRAPH 2007 papers Article No. 10.

[Google](https://www.google.com/){:target="_blank"} How did people learn how to code before there was Google?

[Stack Overflow](https://stackoverflow.com/){:target="_blank"} Many of your Google searches may land you here

[Software Carpentry](https://software-carpentry.org/){:target="_blank"}

[Scipy Lecture Notes](http://www.scipy-lectures.org/){:target="_blank"}

Please feel free to reach out to me at reperry@wayfair.com
