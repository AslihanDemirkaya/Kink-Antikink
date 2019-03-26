X433-3 Python for Data Analysis and Scientific Computing Project

Title: Moving Kinks and Antikinks

Members: Aslihan Demirkaya 

Project Goal:
    Using Python and necessary packages, studying the kink-antikink solutions of \phi^4 model.

Inside the folder:
1. a_demirkaya_project.ipynb: jupyter notebook that has the code.
2. a_demirkaya_project.pdf: .pdf version of the code.
3. a_demirkaya_presentation.pdf: Presentation slides
4. InitialData.mat: has data with 600 rows and 100 columns. Each column represents an initializer vector.
5. moving kink.gif, kink_antikink1.gif, kink_antikink2.gif: The pdf slides do not show the animation, so these files are included. Please open them with Google Chrome or some internet browser.

Note that the slides for the presentation can be found here:
https://docs.google.com/presentation/d/1CQ3Xk-2c3S2mcLsx5_MbPMF1ePw1hzri6SUnzUtuhQQ/edit#slide=id.g543828bc9a_1_127


Overview:
    Project consist of two major modules:
        1) fsolve
        2) odeint
    fsolve:
        Using fsolve, we solve the steady state solutions of the phi4 model.

    odeint:
	Using odeint, we solve the ordinary differential equation of the corresponding 	 	phi4 model.
        


Platform:
    - Mac OS HighSierra on Macbook Pro
    - Jupyter Notebook 5.5.0
    - Python 3.6.5


Packages:
    - matplotlib 3.0.2
    - numpy 1.14.3
    - pandas 0.23.0
    - scipy 1.1.0
    - IPython 6.4.0


Execution Sequences:

    1) launch a_demirkaya_project.ipynb from Jupyter Notebook
    2) Random initializers will be saved to InitialData.mat and then .mat file will be    called again.