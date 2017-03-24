
=====================================================================================================================
This repo is a project submission for the subject Getting and Cleaning Data under the Coursera Data Science Specialization.
by: Amir Azmi
email: amirmazmi@gmail.com


March 2017

=====================================================================================================================


The data is taken from the UCI Machine Learning Repository
info: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip


As part of further learning of the concepts for getting and cleaning data, this repo is intended to process the original data set into a specific data format that can be used to further investigate and analyse the possibilty of classifying human activity using data collected from a smartphone, Samsung Galaxy S. The data comes from a combination of the embedded accelerometer and gyroscope sensors. 


Extract of the Readme.txt from the original dataset:

	==================================================================
	Human Activity Recognition Using Smartphones Dataset
	Version 1.0
	==================================================================
	Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto.
	Smartlab - Non Linear Complex Systems Laboratory
	DITEN - Università degli Studi di Genova.
	Via Opera Pia 11A, I-16145, Genoa, Italy.
	activityrecognition@smartlab.ws
	www.smartlab.ws
	==================================================================
	
	The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

	The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain. See 'features_info.txt' for more details. 


	
=====================================================================================================================
	

The repo contains the following files:

1. "README.md" 

2. "Codebook.md" : Describes the information for variables.

3. "run_analysis.R" : Performs the data processing - see below for explanation. 

4. "tidySamsungGalaxyS.txt" : Output of the script.




=====================================================================================================================


The script run_analysis.R does the following:
1. Downloads the data 
2. Extracts only the mean and standard deviation data 
3. Combines the separate pieces of data into a single data frame
4. Calculates the mean for each variable based on both subject and activity 
4. Outputs the results into a file called "tidySamsungGalaxyS.txt"

Please review the file Codebook.md for further explanation of the variables.


