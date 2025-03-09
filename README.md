# ChromeDriverUpdator
This script automates the updating of ChromeDriver for ease of use.

This is a bash script designed for use on **Mac devices only**.

## Script Requirements / Dependencies

This script assumes the following in order to function properly:
  1) That you have updated the Declarations section of the bash file with your local system's values.
  2) Any existing ChromeDriver files on your system that you want to be updated must be named exactly "chromedriver".
  3) That you have homebrew installed. If not details can be found at https://brew.sh/
  4) The script assumes that all of the repositories that you wish to update are stored in a central localtion. If not then you can specify detailed pathways in the files section.

## Running This Script

After downloading this script and updating the dependencies as mentioned above the script can be run with the given base command below followed by one of several given additional parameters to trigger different functionality.
```
bash path/to/file/fileName.sh <insert_additional_parameter>
```
If you do not define an additional parameter instructions will be printed to show the different functionality that is available.
