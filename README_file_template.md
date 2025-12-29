## What IS a README file?

A README file is typically used to describe all aspects of a program or computational project in enough detail that someone can use and reproduce the program or contribute to the code/project. The template below describes the various sections of such a README file. Read through the description ("Template for a README file") to get a basic idea of what a README file is. At the bottom is a description of what is expected of _your_ README files for this course.

___

## Template for a README file

This readme file was generated on * YYYY-MM-DD * by * NAME *
<!---
Visit [Writing READMEs for Research Code & Software](https://data.research.cornell.edu/data-management/sharing/writing-readmes-for-research-code-software/) guidance for more details

-->


### GENERAL INFORMATION

**Project name:** Provide a descriptive project title (note: this title should be distinct from publications or datasets)
**Version:** Provide a version using semantic versioning, so that it is clear how earlier versions relate to the most current version of the code (e.g., v1.2.0)
**Short description:** Provide a one sentence summary of the software's purpose or functionality. This should serve as a quick overview, distinct from the full project description below. (e.g., Python tool for visualizing climate model outputs)
___

### PROJECT OVERVIEW

**Full description:** Provide a detailed description of the software's purpose, including notable features 
**Date of creation:**Provide the date of creation of the software or the latest version release (single date(YYYY-MM-DD), or a range (YYYY-MM-DD - YYYY-MM-DD))
**Project Organization:** Provide information on the following as applicable: source code, pre-compiled binaries, tests, configuration files, build scripts, dependencies, documentation, static resources
**Software project size:** Provide the total size of the project or its components (uncompressed)

___

### INSTALLATION

**Step by step instructions:** Provide step-by-step installation instructions to install and set up your software project on a user's system 
**System requirements:** Provide system requirements, such as the operating system and any other system-level dependencies
**Required libraries, packages, modules:** Provide a list of required dependencies (e.g., libraries, packages, modules, etc.)
[!Tip] * A package management tool can generate a list of dependencies for a project (e.g., Python’s pip freeze will output a list of installed packages in a format that can be used to create a “requirements.txt” file)
**Setup requirements:** Provide a description of any setup requirements (e.g., environment variables, configuration files)
**Known issues:** Provide any known issues or caveats during installation. (e.g., compatibility issues or known bugs)

___

### USAGE
 
**Step by step instructions:** Provide instructions on how run the software or execute the code after all of the required software project has been installed and include a brief description of what the expected output or behaviour should be
- Provide usage examples
- Include screenshots where appropriate
- Document how to run any built-in tests
**Known limitations:** Note any known caveats or limitations

___

### LICENSE

**Software License:** Provide a license (e.g., MIT) and LICENSE file and/or explain any restrictions on use
[!Note] This should also be in the source code as well
Visit https://choosealicense.com for useful and short summaries on the licenses
**Preferred citation:** Provide a citation that users can reference in publications

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

**Funding:** Provide a list of funding sources that supported the creation of the software project; include funder name and grant number(s)
**Publications using our software:** Add citations to any publications using this software project
**Project is available:** Add a link to other locations where the software project is available (e.g., Zenodo, GitHub, institutional repository)
**Related relationships:** List relationships to ancillary scripts, applications, or data sets
**Contributors:** List all contributors and their roles

___

For purposes of this course, you'll supply a README file for each assignment you submit to the cluster. For example, your first assignment will be the UNIX/HPC tutorial. In your student directory, at the top level for the assignment, you'll supply a README file that describes the purpose of the submission (for example, "This directory contains all files and data associated with the UNIX/HPC tutorial"). The file will also include a sort of table-of-contents: the absolute paths of all the files, and a short description of what each file contains. If you used particular programs such as samtools or angsd, you'll also specify which versions were used.
