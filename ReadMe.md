Design Concept:
- To replace keywords in thousands of files without affecting things in other files
- Can choose a certain directory you want
- Use depth first search with recursive function, combined with file system in Node.js to traverse the whole directory, find certain keywords in certain file type, and replace those with your customized keywords.

How to Use this tool:
- Copy replace.js
- Added it into your project in root directory
- Open replace.js and scroll to the bottom
- Change the arguments to what you need
    - let directory = 'www.bates.edu' -> the directory of the folder you want to traverse
    - let extension = [".html" ] -> the files type you want to change, eg. ".aspx" / ".json". You can add more than one file types here.
    - let target_keyword = 'https://www.bates.edu'  -> the keyword you want to find
    - let replace_keyword = "" -> the customed keyword you want to use to replace
- Run command in the terminal: node replace.js 