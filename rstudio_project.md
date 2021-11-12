# Creating an RStudio project

A project is a folder that contains everything concerning your analysis and may include code, data and documentation. It is a complete research object that can be used to describe and reproduce your research.

Create a new project in RStudio as follows:

**File** -> **New Project** -> **New Directory**

<img src="assets/project_screen1.png" width="500"> 

In the **Project Type** screen, click on **Empty Project**.

<img src="assets/project_screen2.png" width="500"> 

In the **Create New Project** screen, give your project a name and ensure that **create a git repository** is checked. Click on **Create Project**.

<img src="assets/project_screen3.png" width="500"> 

RStudio will create a new folder containing an empty project and set R's working directory to within it.

![](./assets/project_files.png)

Two files are created in the otherwise empty project:-

* **.gitignore** - Specifies files that should be ignored by the version control system.
* **data_analysis.Rproj** - Configuration information for the RStudio project

There is no need to worry about the contents of either of these for the purposes of this tutorial.  

***

[Previous](./SSH.md) | [Next](./analysis_start.md)
