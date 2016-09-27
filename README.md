# SoapUI_Script

This project will help us to structure a way to have a library of scripts in SoapUI (Free Version), 
which help us to access anywhere else within SoapUI Free Version through scripts.

Creating a Test Suite and name it as "Script Library" to store all of the common scripts and library of classes.
(We need to disable this Test Suite if a user is to run all of the Test Suites in the project from the Project View dialog.)
Using the structure already built within SoapUI, 
here we utilize the Test Cases within my "Script Library" Test Suite to organize my scripts/classes into logical space, 
much like namespaces or different libraries of classes. This way they can be easily located and called from other scripts.

## Prerequisities

Download following jars, and put them under $SOAPUI_PATH\bin\ext, then restart the SoapUI tool to run the tests.
```
db2jcc.jar: http://www-01.ibm.com/support/docview.wss?uid=swg21363866
mysql-connector-java-5.1.38-bin.jar: https://dev.mysql.com/downloads/connector/j/
jtds-1.2.5.jar: https://sourceforge.net/projects/jtds/files/
```

## Content
The Script Library will cover content below, with Guiding Docs Link shared via OneDrive:

- Data Source and Data Loop - xls: https://1drv.ms/b/s!ArzKMXZxNUTxhFDa6nOfoSdd1Cim
- Data Source and Data Loop - txt: https://1drv.ms/b/s!ArzKMXZxNUTxhFHX_8iNVSVQkOVh
- CSV output of Test Case results: https://1drv.ms/b/s!ArzKMXZxNUTxhFIztgYvoaYYPMEh
- HTML file output of Test Case results
- Logging info of test running
- Confluence API connection: https://1drv.ms/b/s!ArzKMXZxNUTxhE4g9TgNJ8OxnW83
- Batch Operation
- Set and get properties info
- JDBC Connection via JDBC TestStep or Groovy Script: https://1drv.ms/b/s!ArzKMXZxNUTxhE8JOF-PUih6LY1u
- NZ Bank Account Generator
- jwt parser (jason web token)
```
```
And more content will be added ......

## Running the tests
 

## Authors

* **Lola Yan** - *Initial work* - [LolaYan](https://github.com/LolaYan)

