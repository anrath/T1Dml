Patient data from 2 clinical trials we conducted here at UVA. Each contain data for the data collection period leading up to the trial admission where the patient was asked to act like they normally would. For each patient, there are 12 .csv files and 3 .mat files. The .csv files are probably what you want to use as inputs, the .mat's are there because I used them as a way of combining info to use as an input into a function.  

Some important files are, 
- basal - basal insulin rates (times correspond to when the rate was changed, reading is in U/hr)
- bolus - delivered meal or correction insulin
- cgm - BG values measured using CGM
- meal  - recorded meals
- steps - step count from fitbit
-subject - subject parameters (BMI, height , ...) 
