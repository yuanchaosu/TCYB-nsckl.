# The demo is used for implementing our NSCKL.
#
# The codes of the work is provided in 'demo_nsckl_IEEE_TCYB.zip'. 
#
# We open the main code in the demo.
#
# Although now some files are encapsulated, we provide their available interfaces.
# Once our manuscript is accepted for publication, we will open all source codes in the GitHub project.
#
# The related paper has been submitted to the IEEE Transactions on Cybernetics, from Nov. 2021.
#
# ----------------------------------------------------------------------------------------
# Recommendation：Please use MATLAB 2020 or later version to run the demo.
# RAM: 16GB
#
# ----------------------------------------------------------------------------------------
# The purpose of this license is to make an operation manual, and the purpose of this demo
# is to conduct academic communication. Copyright of the system development department. 
# The demo may not be commercialized without the permission of the authors.
#
# Authors: Yuanchao Su, Lianru Gao, Mengying Jiang, Antonio Plaza, Xu Sun and Bing Zhang
# Nov.2021
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
# 2) NSCKL_classifi_Given.m (Given training samples, e.g., Houston University data).
