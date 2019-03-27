# Enron-Ham-Spam-Email-FIlter

Before runnning this script:

Download the Enron Email Ham and Spam Dataset: https://drive.google.com/file/d/1c0Zbp4tSRsRPcxbswYDCYzmE66GRGv_L/view?usp=sharing

Extract the files. You will see two folders: Ham Unprocessed and Spam Unprocessed

In the python script, set these directories as:

hamdir = r'....\Ham Unprocessed' (remove 'r' for MacOS)
spamdir = r'.....\Spam Unprocessed (remove 'r' for MacOS)

If the google drive link doesn't work you can download the data from the original source:

Go to: http://www2.aueb.gr/users/ion/data/enron-spam/

Download all files under 'Enron-Spam in raw form'

Extract the ham folders to a folder of your choice eg. ..../ham
Extract the spam folders to a folder of your choice eg. ..../spam

In the python script, set these directories as:

hamdir = r'....\ham (remove 'r' for MacOS)
spamdir = r'.....\spam (remove 'r' for MacOS)

You can now run the script.

note: the n_jobs argument in gridsearch allows it to utilize all cores and 100% of your CPU. 
If you are experiencing problems with this section remove the n_jobs argument entirely. 
