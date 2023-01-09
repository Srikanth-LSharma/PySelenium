# PySelenium
Installation guide and project setup for pyselenium and robot framework

* Install Latest version of [Python](https://www.python.org/downloads/).

* Navigate to the scripts folder after installation and set the environment path variable for the Scripts folder.

* Check the version of python and pip by executing the following commands in command prompt

  > ### `python --version`
  > ### `pip --version`

* Download and install PyCharm for IDE 

* Install Selenium by executing the following command in command prompt

  > ### `pip install selenium`

* Install robot framework using the following command: 
  > ### `pip install robotframework`

* To check the current installation use the command:
  > ### `pip show robotframework`

* Other commands (Optional) : 
  * To upgrade to latest version of RF:
    > ### `pip install --upgrade robotframework`

  * To install specific version of RF (example) :
    > ### `pip install robotframework==2.9.2`

  * To uninstall:
    > ### `pip uninstall robotframework`

  * Others: 
    > ### `pip list`
    > ### `pip check robotframework`

* Install Robot Framework Selenium Library
  > ### `pip install robotframework-seleniumlibrary`
  
* Install the same three packages in pycharm project 
  > Selenium  
  > Robot Framework  
  > Robot Framework-Selenium Library

* Install ***IntelliBot #patched*** plugin in your PyCharm for smart editing with Robot Framework

  > If there's any IDE exception that might be because of the version incompatibility  
  > Alternate solution would be to download the ***intellibot.jar*** file from [IntelliBot](https://github.com/lte2000/intellibot) and manually add the plugin from disk. 

* Restart your IDE to apply these changes
