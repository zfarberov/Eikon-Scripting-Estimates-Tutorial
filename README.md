# Company Tearsheet Estimates
# Eikon Scripting Tutorial
# Python

We would like to start this tutorial where Eikon Scrpting Proxy Quickstart has left off.  This brief tutorial will discuss the steps required to retrieve the data that is presented in the Estmates section of "Company Tearsheet" Eikon Excel example.

### Prerequisites

Please refer to [Quick Start](https://developers.thomsonreuters.com/tr-eikon-scripting-apis-eap-limited-access/eikon-web-and-scripting-apis-beta/quick-start) for the details

1. TR Eikon Scripting Proxy is installed
2. Python is installed
3. Eikon Python API is installed

### Expected Result

This is how the Estimates look in Eikon Excel Company Tearsheet template example

![alt text](https://github.com/zfarberov/TR-Tutorials/blob/master/excelEstimatesCropped.jpg "Excel Company Tearsheet Estimates")

We learn how to retrieve the same data content via Eikon scripting from python

![alt text](https://github.com/zfarberov/TR-Tutorials/blob/master/pythonEstimatesCropped.jpg "Same data content, python")

### Approach

1. Using Eikon Excel for Lookup
2. Using DIB as reference
3. Laying out the data

### Using Excel for Lookup

1. From All Programs menu, we expand Thomson Reuters menu item and select Thomson Reuters Eikon - Microsoft Excel.
2. Once Excel is open, from Thomson Reuters menu item we choose "Sign In" option, and enter your Thomson Reuters Eikon credentials, hitting "Sign In" button.  The status should change to "Online"

![alt text](https://github.com/zfarberov/TR-Tutorials/blob/master/EikonExcelSignIn.jpg "Eikon Excel Online")

3. Next, from Thomson Reuters menu item, we choose Templates

![alt text](https://github.com/zfarberov/TR-Tutorials/blob/master/EikonExcelTemplates.jpg "Eikon Excel Templates")

And select from the Template Library first "Fundamentals" on the left, then "Company Tearsheet" on the right,
then click "Open":

![alt text](https://github.com/zfarberov/TR-Tutorials/blob/master/EikonExcelTearsheet.jpg "Eikon Excel Company Tearsheet")

4.  We are looking at the template, or example "Company Tearsheet".  In this tutorial we will aim to replicate the data
retrieval in Estimates parts of this example by using eikon scripting from python.  Let's start by clicking on ""
