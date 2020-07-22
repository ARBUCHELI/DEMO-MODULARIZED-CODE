# DEMO-MODULARIZED-CODE

## Created by AWS Machine Learning Foundations Course, UDACITY. Adaptation as a repository: Andrés R. Bucheli.

Example of how manage directories and modules using the terminal.


So far the coding exercises have been in Jupyter notebooks. Jupyter notebooks are especially useful for data science applications because you can wrangle data, analyze data and 
share a report all in one document; however, they're not ideal for writing modular programs, which require separating code into different files.

In the 2_modularized_code folder, you'll find three files. You can double click on the folder in the list to the left hand side of the workspace. Look at how the Distribution
class and Gaussian class are modularized into different files. 

The Gaussiandistribution.py imports Distribution class from the Generaldistribution.py file. The line of code:

from Generaldistribution import Distribution

essentially pastes the Distribution code to the top of the Gaussiandistribution file when you run the code. You'll see in the example_code.py file an example of how to use the
Gaussian class.

The example_code.py file then imports the Gaussian distribution class. 

![image1](https://raw.githubusercontent.com/ARBUCHELI/DEMO-MODULARIZED-CODE/master/Sin%20t%C3%ADtulo1.jpg)


![image2](https://raw.githubusercontent.com/ARBUCHELI/DEMO-MODULARIZED-CODE/master/Sin%20t%C3%ADtulo2.jpg)

![image3](https://raw.githubusercontent.com/ARBUCHELI/DEMO-MODULARIZED-CODE/master/Sin%20t%C3%ADtulo3.jpg)

![image4](https://raw.githubusercontent.com/ARBUCHELI/DEMO-MODULARIZED-CODE/master/Sin%20t%C3%ADtulo4.jpg)


## Adaptation as a Repository: Andrés R. Bucheli.
