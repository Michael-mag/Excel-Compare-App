### File Compare App

    **TASK DESCRIPTION**
    
    - For a car manufacturer, it is important to know if the same sensor in different cars produce different  
         readings under the same conditions. The data is recorded in large files, for instance, excel files  
         or other types of files.
    - Given two identical excel files, write an application that compares for any differences in the cells.
    - If two identical columns have cells which do not have the same value, colour the cell red.
  
### How to use
    - run python file_compare_app.py and supply the excel sheets to compare.
    - Example sheets and the result are found in examples folder

### Extra steps
    - Make it into an app using pyinstaller using the following commands
``` bash
pip install pyinstaller
pyinstaller file_compare_app.py 
```
