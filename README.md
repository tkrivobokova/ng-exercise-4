# Provitöö 4. osa: Jõudlustestmine
#### Pre-requirements:
1. Java is installed 
``` java --version ```
2. Jmeter is installed
> If not, follow the instructions: https://jmeter.apache.org/download_jmeter.cgi
4. Jmeter folder path is known 

#### Steps to run the script:
1. Download the script code from Github
1.1. Press the "Code" button
1.2. Press "Download ZIP"
2. Extract script into Jmeter's "bin" folder
3. Open a terminal (or a Command-Line console if using Windows)
4. Navigate to the folder where Jmeter is installed
``` cd <path-to-folder> ```
5. Navigate to the bin folder
``` cd bin ```
6. Run the script in headless mode
```sh jmeter.sh -n -t Joudlust_Script.jmx -Jusers=<y> -Jramp-up=<k> -Jloops=<x> -Jduration=<z> -l demoresult66.jtl -e -o test ```

> You have to specify y, k, x, and z for parameters (if the value is not defined default value "1" will be used)

> The parameter "-Jusers" indicates the number of threads (users). Should be a positive integer

> The parameter "-Jramp-up" indicates ramp-up periods specified in seconds

> The parameter "-Jloops" indicates loop count. Should be a positive integer

> The parameter "-Jduration" indicates duration specified in seconds
  
#### Steps to open Jmeter Dashboard to view results:
1. Open testResults folder
2. Open index.html file
