# Provitöö 4. osa: Jõudlustestmine
#### Prerequirement
1. Java is installed (java --version)
2. Jmeter is installed
3. Jmeter folder path is known 

#### Steps to run the script
1. Download the script code from Github
1.1. Press "Code" button
1.2. Press "Download ZIP"
2. Extract skript into Jmeter's "bin" folder
3. Open terminal
4. Navigate to the folder where Jmeter is installed
cd <path-to-folder>
5. Navigate to bin folder
cd bin
6. Run the script in headless mode
bin % sh jmeter.sh -n -t Joudlust_Script.jmx -Jusers=<x> -l testResults.jtl -e -o testResults
  
#### Steps to open Jmeter Dashboard to view results:
1. Open testResults folder
2. Open index.html file
