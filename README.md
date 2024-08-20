# Background-Extraction-Project

An important task when processing sensor data is to 
distinguish relevant from irrelevant data. This project 
describes a method for an iterative singular value 
decomposition that maintains a model of the background via 
singular vectors spanning a subspace of the image space,
thus providing a way to determine the amount of new 
information contained in an incoming frame. By decomposing 
video frames into dominant spatial variations and foreground 
dynamics, the proposed technique aims to enhance object 
tracking, motion analysis, and scene understanding.

We update the singular vectors spanning the background 
space in a computationally efficient manner and provide the 
ability to perform block wise updates, leading to a fast and 
robust adaptive SVD computation. The effects of those two 
properties and the success of the overall method to perform 
a state-of-the-art background subtraction are shown in both 
qualitative and quantitative evaluations
