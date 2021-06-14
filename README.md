# cmrtc_cse_team_7_fakejobposting_predictionsystem
REREQUSITES:
Jupyter Notebook with all the important  packages installed.

DEPLOYMENT: 
These are the steps to deploy the project on our system:
	⁃	They are 5 important ipnby files in the entire folder. They are: 
                     Data Preprocessing.ipnby
                     Baseline_Models_(1).ipnby
                     All_features_models_.ipnby
                     Oversampling.ipnby
		AIT_590_NN.ipnby
	⁃	They first file that has to be run is the Data preprocessing.ipnby. This file contains the data preprocessing and text preprocessing code. The csv file that has to be used to run this file is job_postings.csv
	⁃	Running this first file will generate two more csv files named job_text.csv and job_data.csv
	⁃	The next file that has to be run is the Baseline_Models_(1).ipnby. The csv file we will use is job_text.csv that was generated earlier. Run the code to see the results of our analysis.
	⁃	The next file we run is the All_features_models_.ipnby. The csv file we use is job_data.csv which is again the csv file generated after running the first ipnby file.
	⁃	The next file we run is the Oversampling.ipnby. We again use the job_data.csv file here and run the code. After the code is run, two more csv files are generated called the trainset.csv and testset.csv. Keep these files aside for later and analyze the results.
	⁃	The last file we will run is the AIT_590_NN.ipnby. We use the above generated transit.csv and testset.csv files in this ipnby file and the results can be seen after execution. You will also need Glove 300d.txt file for this code to execute.

Additional Details: 
We are attaching all the ipnby files as well as the dataset “job_postings.csv”. We are also going to attach the csv files that were generated for us after executing Data preprocessing.ipnby and Oversampling.ipnby. We will also include the Glove 300d.txt.zip file in the zip folder along with all the html files of the ipnby files
