# DirectMediationAutomaticDeleter
 Script to remove the folders in the Direct Mediation

# Requirements:
Have Python 3.8 or later installed on your workspace (This current iteration is not compatible with Windows!)

# How it works:
1) Download source code from GITHub 
2) Open your Terminal (IDE)
3) cd to downloaded source code folder
4) cd venv/bin
5) mkdir log
6) chmod 777 log
7) chmod 777 python3
8) Run below command
./python3 ../../AutoDelete.py -n <YourUsername> -p <YourPassword>

9) That's it. The script will now run, print off what it is doing and automaticaly upload a log file on the direct mediation FTP folder.
10) Vailidate that new log file is present and non zero in size at "DirectMediationWebSite/cronus/viamail logfiles/"

