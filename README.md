[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mmorphew/UNet_Remote_Sensing/master)

# UNet_Remote_Sensing
A project designed to demonstrate applying semantic segmentation to remote sensing data

This was a fun project I did during my last year of undergraduate, as part of an extension to my remote sensing class. It effectively acted as an independent study and allowed me to apply concepts from a prior internship to another form of geophysical data. It's also a great example of one of the many ways that geophysical data and machine learning can mesh.

The ISPRS has graciously allowed me to host their data, and I cannot be more thankful to them. While most of the code here is my own, all images, labels, and geodata are property of the ISPRS. The 2D Vaihingen data, as well as other datasets, can be requested here if you wish to obtain the data directly from the source: http://www2.isprs.org/commissions/comm3/wg4/data-request-form2.html.

# Dependencies
A binder link is included for your benefit, such that you may run the code in your browser without having to worry about Python versions and required modules. Be patient with Binder; it will take a few minutes to set up the environment for the first time.

If you wish to run locally, you will need Python 3 (3.8 preferrably), all Anaconda base modules, as well as Tensorflow 2.0+, opencv-python, and tifffile.
