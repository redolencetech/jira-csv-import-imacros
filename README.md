# JIRA iMacros Upload Script
iMacros script to automate the pulling of data into JIRA, written for test steps

Steps to use:

1. Install iMacros for your browser
2. Install the File Access module if using Chrome
3. Add your file with test steps in the `DATASOURCE` folder in the following format: [`Test step`, `Test Data`, `Test result`]
4. Copy the `.iim` file to your `Macros` folder, and check that it shows up in your macro list
4. In iMacros, run the file as a loop by clicking on the `Play Loop` button, with the number of rows in the file as your max
5. Repeat data-add process for next ticket
