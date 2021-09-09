# DirectMediationAutomaticDeleter
 Script to remove the folders in the Direct Mediation

# Requirements:
Have Python 3.8 or later installed on your workspace (This current iteration is not compatible with Windows!)

# How it works:
1) Download source code from GITHub 
2) Open your Terminal (IDE)
3) Check if Python is installed and if you have the good version using the following command: python3 -v
4) cd to downloaded source code folder
5) cd venv/bin
6) mkdir log
7) chmod 777 log
8) chmod 777 python3
9) Run below command
python3 ../../AutoDelete.py -n <YourUsername> -p <YourPassword>

9) That's it. The script will now run, print off what it is doing and automaticaly upload a log file on the direct mediation FTP folder.
10) Vailidate that new log file is present and non zero in size at "DirectMediationWebSite/cronus/viamail logfiles/"

