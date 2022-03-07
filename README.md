# Provitöö 1. osa: Jõudlustestmine
#### Prerequirement
1. Java is installed (java --version)
2. Jmeter is installed
3. Jmeter folder path is known 

#### Download the script code from Github
1. Press "Code" button
2. Press "Download ZIP"

#### Extract skript into Jmeter's "bin" folder
#### Open terminal
#### Navigate to the folder where Jmeter is installed
cd <path-to-folder>
  
#### Navigate to bin folder
cd bin
  
#### Run the script in headless mode
bin % sh jmeter.sh -n -t Joudlust_Script.jmx -Jusers=<x> -l testResults.jtl -e -o testResults
  

