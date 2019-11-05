# Acronym/abbreviation finder

This tool finds the acronym from the docx file or any other txt/tex file. 
I am sure there might be tools already available for this. But this is my version. The tool is pretty simple and matches caps word. This can easily extended to more complex abbreviations/acronyms. I have wrapped this file in exe using pyinstaller. 
## How to use:
The tool is easy to use and self explanatory. Still I am providing the steps:
<br/>
- Double click `acronym_finder.exe`. Enter the file name with the extension (docx, txt, tex) 
<br/>

![step one](https://github.com/geekonloose/abbreviation_finder/tree/master/readme_files/1.png)
- Enter the minimum length of acronym you want to find (this option is to remove single character words word like `A`, `(A)`, `(B)` etc.) 
<br/>

![step two](https://github.com/geekonloose/abbreviation_finder/tree/master/readme_files/2.png)

- Press enter. This will generate text file with name `<acronym.txt>`. Where all alphabetically ordered abbreviations are listed.
<br/>

![step three](https://github.com/geekonloose/abbreviation_finder/tree/master/readme_files/3.png)

## python source
- The python source file is provided. You can change python source file as per your need. 
- Following dependencies are required to run program:
  - docx
  - re