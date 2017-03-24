
# Variables Explanation

---

### The features in this dataset come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

### Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

### Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

### These signals were used to estimate variables of the feature vector for each pattern:  
### *'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.*

tBodyAcc-XYZ

tGravityAcc-XYZ

tBodyAccJerk-XYZ

tBodyGyro-XYZ

tBodyGyroJerk-XYZ

tBodyAccMag

tGravityAccMag

tBodyAccJerkMag

tBodyGyroMag

tBodyGyroJerkMag

fBodyAcc-XYZ

fBodyAccJerk-XYZ

fBodyGyro-XYZ

fBodyAccMag

fBodyAccJerkMag

fBodyGyroMag

fBodyGyroJerkMag


### The set of variables that were estimated from these signals are: 

mean: Mean value

std: Standard deviation

### Additional vectors obtained by averaging the signals in a signal window sample. These are used on the angle() variable:

gravityMean

tBodyAccMean

tBodyAccJerkMean

tBodyGyroMean

tBodyGyroJerkMean

#
#


### These values are then averaged based on the grouping of subject and activity. This is denoted by the variable:
subjectActivity

#
#
---

### The complete list of variables of each feature vector is as below:


subjectActivity                          
averagetBodyAccmeanX                     
averagetBodyAccmeanY                     
averagetBodyAccmeanZ                     
averagetBodyAccstdX                      
averagetBodyAccstdY                      
averagetBodyAccstdZ                      
averagetGravityAccmeanX                  
averagetGravityAccmeanY                  
averagetGravityAccmeanZ                  
averagetGravityAccstdX                   
averagetGravityAccstdY                   
averagetGravityAccstdZ                   
averagetBodyAccJerkmeanX                 
averagetBodyAccJerkmeanY                 
averagetBodyAccJerkmeanZ                 
averagetBodyAccJerkstdX                  
averagetBodyAccJerkstdY                  
averagetBodyAccJerkstdZ                  
averagetBodyGyromeanX                    
averagetBodyGyromeanY                    
averagetBodyGyromeanZ                    
averagetBodyGyrostdX                     
averagetBodyGyrostdY                     
averagetBodyGyrostdZ                     
averagetBodyGyroJerkmeanX                
averagetBodyGyroJerkmeanY                
averagetBodyGyroJerkmeanZ                
averagetBodyGyroJerkstdX                 
averagetBodyGyroJerkstdY                 
averagetBodyGyroJerkstdZ                 
averagetBodyAccMagmean                   
averagetBodyAccMagstd                    
averagetGravityAccMagmean                
averagetGravityAccMagstd                 
averagetBodyAccJerkMagmean               
averagetBodyAccJerkMagstd                
averagetBodyGyroMagmean                  
averagetBodyGyroMagstd                   
averagetBodyGyroJerkMagmean              
averagetBodyGyroJerkMagstd               
averagefBodyAccmeanX                     
averagefBodyAccmeanY                     
averagefBodyAccmeanZ                     
averagefBodyAccstdX                      
averagefBodyAccstdY                      
averagefBodyAccstdZ                      
averagefBodyAccmeanFreqX                 
averagefBodyAccmeanFreqY                 
averagefBodyAccmeanFreqZ                 
averagefBodyAccJerkmeanX                 
averagefBodyAccJerkmeanY                 
averagefBodyAccJerkmeanZ                 
averagefBodyAccJerkstdX                  
averagefBodyAccJerkstdY                  
averagefBodyAccJerkstdZ                  
averagefBodyAccJerkmeanFreqX             
averagefBodyAccJerkmeanFreqY             
averagefBodyAccJerkmeanFreqZ             
averagefBodyGyromeanX                    
averagefBodyGyromeanY                    
averagefBodyGyromeanZ                    
averagefBodyGyrostdX                     
averagefBodyGyrostdY                     
averagefBodyGyrostdZ                     
averagefBodyGyromeanFreqX                
averagefBodyGyromeanFreqY                
averagefBodyGyromeanFreqZ                
averagefBodyAccMagmean                   
averagefBodyAccMagstd                    
averagefBodyAccMagmeanFreq               
averagefBodyBodyAccJerkMagmean           
averagefBodyBodyAccJerkMagstd            
averagefBodyBodyAccJerkMagmeanFreq       
averagefBodyBodyGyroMagmean              
averagefBodyBodyGyroMagstd               
averagefBodyBodyGyroMagmeanFreq          
averagefBodyBodyGyroJerkMagmean          
averagefBodyBodyGyroJerkMagstd           
averagefBodyBodyGyroJerkMagmeanFreq      
averageangletBodyAccMean,gravity         
averageangletBodyAccJerkMean,gravityMean 
averageangletBodyGyroMean,gravityMean    
averageangletBodyGyroJerkMean,gravityMean
averageangleX,gravityMean                
averageangleY,gravityMean                
averageangleZ,gravityMean 
