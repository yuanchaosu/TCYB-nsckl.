All source codes will be published after the paper is accepted.
In addition，for easy use, we will publish our NSC codes in two type (Matlab and Python).

----------------------------------------------------------------------------------------
The demo is used for displaying NSCKL.
Title: "NSCKL: Normalized Spectral Clustering With Kernel-Based Learning for 
# Semisupervised Hyperspectral Image Classification"
#
# ----------------------------------------------------------------------------------------
# This demo was made by Yuanchao Su.
# It was checked and improved by Lianru Gao, Mengying Jiang, and Antonio Plaza.
# Recommendation：Please use MATLAB 2020 or later version to run the demo.
# RAM: 16GB
#
# ----------------------------------------------------------------------------------------
# The purpose of this license is to make an operation manual, and the purpose of this demo
# is to conduct academic communication. Copyright of the system development department. 
# The demo may not be commercialized without the permission of the developer.
#
# Authors: Yuanchao Su, Lianru Gao, Mengying Jiang, Antonio Plaza, Xu Sun and Bing Zhang
# July.2021
#
# ----------------------------------------------------------------------------------------
# This demo contains four published hyperspectral data sets.
#
# Test 1 and Test 2: Experiment with Indian Pines data
#
# Test 3: Experiments with Salinas data
#
# Test 4 and Test 5: Experiments with Houston University data
#
# Test 6: Experiments with WHU-Hi data
#
# ----------------------------------------------------------------------------------------
# NSCKL.m is main function of feature representation. 
# NSC.m is our new SC algorithm.
# Other .m file are auxiliaries of NSCKL.
#
# ----------------------------------------------------------------------------------------
# Two ways can select training samples.
# 1) Training samples are randomly selected from ground-truth;
# 2) Training samples are given by Publishers
# 1) NSCKL_classifi_Random.m (Random training samples, e.g., Indian Pines data, Salinas data, 
# Pavia University data, and WHU-Hi datasets)
# 2) NSCKL_classifi_Given.m (Given training samples, e.g., Houston University 2013 data).
#
# ----------------------------------------------------------------------------------------
