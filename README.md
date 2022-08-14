# Workflow

1) Pull this repo before you start some work and push it, when you have done something
2) Attach meaningful messages to your commits, give your notebooks and other files clear names 
2) Branch, if you modified something, that other person also modified
3) Before uploading the notebook, please, restart it and run all the cells to make sure, that all is ok
4) Notebooks should be well formated: structure it with headings in Markdown and briefly explain what is going on

### Proposed notebook structure
- Imports and set up
- Get the data (read file into df, make API requests etc)
- Prepare the data (clean etc)
- `Do something meaningful`
- `Do something else`
- Save the results (export some data if needed, save important figs etc)

### Paths

In many  notebooks there are some path constants, which should be changed to run the notebook, because  you can store data in different places. Please, create such constants and add them to the beginning of your notebook into `Imports ant set up` section (like `HTML_PATH`)

# Data

Data is NOT stored here, it is on our cluster. If you place some large datafiles in this folder locally, please, add it to `.gitignore`. 


# Useful links

Here is the main folder on Google drive (access restricted):
https://drive.google.com/drive/folders/1FeQQMyMXL3b7PiAs62wSqhbSsZpQOe76?usp=sharing

# Folders

### preprocessing

Different scrpits and small text files with data related to data preprocessing

### biochemistry
