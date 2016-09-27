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

## Running the tests

## Authors

* **Lola Yan** - *Initial work* - [LolaYan](https://github.com/LolaYan)

