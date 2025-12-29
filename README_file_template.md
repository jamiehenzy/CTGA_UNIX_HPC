## What IS a README file?

A README file is typically used to describe all aspects of a program or computational project in enough detail that someone can use and reproduce the program or contribute to the code/project. The template below describes the various sections of such a README file. Read through the description ("Template for a README file") to get a basic idea of what a README file is. At the bottom is a description of what is expected of _your_ README files for this course.

___

## Template for a README file

This readme file was generated on * YYYY-MM-DD * by * NAME *
<!---
Visit [Writing READMEs for Research Code & Software](https://data.research.cornell.edu/data-management/sharing/writing-readmes-for-research-code-software/) guidance for more details

-->


### GENERAL INFORMATION

+ **Project name:** Provide a descriptive project title (note: this title should be distinct from publications or datasets)
+ **Version:** Provide a version using semantic versioning, so that it is clear how earlier versions relate to the most current version of the code (e.g., v1.2.0)
+ **Short description:** Provide a one sentence summary of the software's purpose or functionality. This should serve as a quick overview, distinct from the full project description below. (e.g., Python tool for visualizing climate model outputs)
___

### PROJECT OVERVIEW

+ **Full description:** Provide a detailed description of the software's purpose, including notable features 
+ **Date of creation:**Provide the date of creation of the software or the latest version release (single date(YYYY-MM-DD), or a range (YYYY-MM-DD - YYYY-MM-DD))
+ **Project Organization:** Provide information on the following as applicable: source code, pre-compiled binaries, tests, configuration files, build scripts, dependencies, documentation, static resources
+ **Software project size:** Provide the total size of the project or its components (uncompressed)

___

### INSTALLATION

+ **Step by step instructions:** Provide step-by-step installation instructions to install and set up your software project on a user's system 
+ **System requirements:** Provide system requirements, such as the operating system and any other system-level dependencies
+ **Required libraries, packages, modules:** Provide a list of required dependencies (e.g., libraries, packages, modules, etc.)
+ **Setup requirements:** Provide a description of any setup requirements (e.g., environment variables, configuration files)
+ **Known issues:** Provide any known issues or caveats during installation. (e.g., compatibility issues or known bugs)

___

### USAGE
 
+ **Step by step instructions:** Provide instructions on how run the software or execute the code after all of the required software project has been installed and include a brief description of what the expected output or behaviour should be
- Provide usage examples
- Include screenshots where appropriate
- Document how to run any built-in tests
+ **Known limitations:** Note any known caveats or limitations

___

### LICENSE

+ **Software License:** Provide a license (e.g., MIT) and LICENSE file and/or explain any restrictions on use
[!Note] This should also be in the source code as well
Visit https://choosealicense.com for useful and short summaries on the licenses
+ **Preferred citation:** Provide a citation that users can reference in publications

___

### CONTACT INFORMATION
[!Note] Provide at least two contacts; repeat block for additional contributors as needed

**Contact**
Name:
Role: (e.g., principal investigator, programmer, developer, maintainer, copyright owner)
ORCID:
Institution:
Email:

**Contact**
Name:
Role: (e.g., principal investigator, programmer, developer, maintainer, copyright owner)
ORCID:
Institution:
Email:

___

### ACKNOWLEDGEMENTS

+ **Funding:** Provide a list of funding sources that supported the creation of the software project; include funder name and grant number(s)
+ **Publications using our software:** Add citations to any publications using this software project
+ **Project is available:** Add a link to other locations where the software project is available (e.g., Zenodo, GitHub, institutional repository)
+ **Related relationships:** List relationships to ancillary scripts, applications, or data sets
+ **Contributors:** List all contributors and their roles

___

## YOUR README files

For purposes of this course, you'll supply a README file for each assignment you submit to the cluster. In fact, having a README file is so important that no assignment will be graded without one. Compared to a full-on README file that would accompany a coding project, however, your README file will be much shorter and simpler. The main point is to make it user-friendly, especially since the user is ME, the one who assigns your grade! What to include:

+ Purpose of submitted work
+ Absolute path of each file
+ Short description of what each file contains
+ Name and version of any program you used
+ Notes on any editing you performed on saved Terminal sessions
+ Notes on anything else that will make my use of your files easier

### Purpose, contents, location

For example, your first assignment will be the UNIX/HPC tutorial. In your student directory, at the top level for the assignment, you'll supply a README file that describes the purpose of the submission (for example, "This directory contains all files and data associated with the UNIX/HPC tutorial"). The file will also include a sort of table-of-contents: the absolute paths of all the files, and a short description of what each file contains. 

### Program versions

For UNIX/HPC, the only programs you're using are the bash shells that interpret  your command-line commands on your computer and on the Explorer cluster. Later you'll use programs such as samtools or angsd. In each case, you need to specify the version you used. Usually the best way to learn which version you are using is to type at the command line the name of the program you're currently using followed by '--version'. Try this when you are on the command line:

```
bash --version
```
The bash version on your laptop (local) will likely be different from the version running on the cluster (remote). Sometimes different versions behave slighly differently under specific contexts, so including this information for the user ensures they can reproduce your commands in the way you intended them.

### Notes on editing or other specifics

In addition to the absolute requirement of including a README file, your submissions also absolutely MUST NOT CONTAIN EXTRANEOUS LINES OF TEXT. What do I mean by this? Let's say you are asked to do something with a large file and your first attempt results in a display of the entire file on your screen, making up hundreds of lines of text. I ABSOLUTELY WILL NOT SCROLL THROUGH THIS TO TRY TO FIND YOUR WORK. Instead, after saving your Terminal session as a text file, you'll open it with a text editor like TextEdit on Mac or Notepad on Windows and delete all those extra lines. Or, say you are asked to print the contents of your Download file but you have never once in your life removed a file so there are a hundred. To know that you carried out the command correctly, I only need to see a few lines of content from your Downloads and you can delete the rest after saving the file and before submitting it. 

In either case, include a note in your README file that says something like, "I deleted content to save space in exercise U24", etc.

You only need one README file for any submission, and it should be placed at the top level of your submitted files. For example, your UNIX/HPC submission might be in a directory called Tutorials, with a subdirectory called, "UNIX_HPC". The logical place for the README file would be at the same level as "UNIX_HPC". Again, think about the user and how best to help them navigate your files so that they will be more inclined to evaluate your work generously ("Ahem").
