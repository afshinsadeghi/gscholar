1. Install the requiements, see macos_chrom_install_manual.txt and requirements.txt,and driver_path in getwebpage.py
2. set keywords and first_page and last_page  to srape in run_gscholar.py
3. run the scholar searcher : python run_gscholar.py

v1:
most part of the code is adopted from https://github.com/michael-act/Senginta.py
That code does not run anymore because google recognizes the robot and blocks it. 
I replaced it with a code that goes around this problem using google chrom driver.


v2 : 
debugged for entries that have no url
output is saved both as json and csv files




Disclaimer: 
This code is for educational purposes only and the user is responsibe for any usage of the code.
