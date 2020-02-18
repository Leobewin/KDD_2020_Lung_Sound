# KDD_2020_Lung_Sound

Unzip the files to get two folders, train and test, which are the training dataset and testing dataset used in a study currently 
submitted to KDD 2020.

Inside the folders you can find 15-second-long lung sound recordings and the corresponding labels. In total, including 6868 15-second 
long audio files, 24259 inhalation labels and 14958 exhalation labels.

The filename of the truncated 15-second long audio files recorded by the digital stethoscope Littmann 3200 is prefixed by “steth_”. 
The filename of 15-second-long audio files recorded by a multichannel acoustic recording device, AccurSound, is prefixed by “trunc_”.  
The information of the date and time of the recording follows the prefix, e.g., 
“steth_yyyyMMdd_HH_mm_ss” or “trunc_yyyy-MM-dd-HH-mm-ss”. 
For the files from the AccurSound, the additional information of auscultation locations and truncated order trail on the filename, e.g., 
“trunc_yyyy-MM-dd-HH-mm-ss-LX_N”, where LX stands for the auscultation location and the number N stands for the Nth 15 seconds 
truncation from the original sound recording, where L1 represents the 2nd intercostal space (ICS) in the right midclavicular line (MCL), 
L2 represents the 5th ICS in the rigt MCL, L3 repsresents the 4th ICS in the right midaxillary line (MAL), L4 represents the 10th ICS in 
the right MAL, L5 represents the 2nd ICS in the left MCL, L6 represents the 5th ICS in the left MCL, L7 represents the 4th ICS in the 
left MAL and L8 represents the 10th ICS in the left MCL.

The inhalation and exhalation labels are saved in Text (.txt) format. 
The filename of the labels has the same beginning as the filename of corresponding audio file but is suffixed by “_label”. 
The date on the filename is randomly shifted for the purpose of de-identification.

It should be noted that the labels in a single label file is made only by one annotator. Even the anotators were kept having good 
agreement on labeling criteria by holding regular meetings, the labeling is not perfect. 

A more detailed informaiton about the files will be found in the paper, which is currently under submission, after it is published.
The open source code related to the study will be uploaed by June 23, 2020.

KDD_2020_Lung_Sound_Database by Heroic-Faith Medical Science Corp. is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.
Based on a work at https://github.com/heroic-faith/KDD_2020_Lung_Sound.
