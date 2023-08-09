# CMPG_323_OVERVIEW_39909476
## REPOSITORIES

** Bug **

This repository will be used for Project 1.

All the other projects from 2-5 will have a separate repository created using a naming convention as follows: "CMPG323 <project_number> - <student_number>".
Therefore:

### Project2: "CMPG323_Project2_39909476"

### Project3: "CMPG323_Project3_39909476"

### Project4: "CMPG323_Project4_39909476"

### Project5: "CMPG323_Project5_39909476"

If code from the previous repositories is needed, it will be copied over to the relevant repository.

## DIAGRAM_REPRESENTATION:

This diagram illustrates the integration between the projects and their respective repository contexts:
![Untitled Diagram (1)](https://github.com/XoXoTheFrozenFox/CMPG_323_OVERVIEW_39909476/assets/104361159/2b7bacdf-c453-4251-bbe5-b13c45355f1c)

There are no lines that indicate integration between repositories because of code being moved as needed.

## BRANCHING:

### Project1:

Doesn't need a branch because of the project being administrive and more of a detailing for the project.

### Project2-5:

#### MAIN: 

Each project will have a main branch. Commonly referred to as the "master" branch, is a critical branch in version control systems like Git. It serves as the default branch that represents the latest stable version of the project's codebase. The main branch typically contains the most up-to-date and production-ready code that is free of any major bugs or issues.

#### DEVELOPMENT: 

This branch primarily serves as the main development area for working on specific features. It is where the majority of code is written, thoroughly tested, and refined. Once everything functions correctly and is deemed stable, the code is merged into the main branch. The DEVELOPMENT branch allows for focused and iterative development, ensuring that changes are thoroughly validated before being integrated into the main codebase.

#### TESTING(Experimental): 

This branch serves as a dedicated environment for testing new technologies, untraditional optimization strategies, or any other ideas proposed by the project team that they are unsure about. It provides a safe space to conduct experiments and validate these changes before integrating them into the main system. The purpose of this branch is to mitigate risks, foster innovation, and facilitate collaboration among team members. It allows for thorough testing, learning from each other's experiments, and making informed decisions about the suitability of these changes for the project. Successful experiments can be selectively integrated into the main system, while unsuccessful ones can be refined or discarded based on the insights gained during the testing phase.

## GIT-IGNORE_FILES

The central objective of a .gitignore file is to prevent non-essential files and directories, which are not directly related to the project's source code, from being tracked by Git. Moreover, it aids in avoiding conflicts that may arise from tracking files better left out, contributing to a smoother collaborative development process.

The following git-ignore formats given are proposed git-ignore files I found online but will be updated when I actually start doing the projects:

### Project2:

.NET Core build output
bin/
obj/

Visual Studio files
.vs/
*.suo
*.user
*.csproj.user

NuGet packages
*.nuget.props
*.nuget.targets
packages/

Build results
*.dll
*.exe
*.pdb

Debug logs
*.log

### Project3:

Design tool artifacts
design_tool/
design_file.psd

Exported files
exports/
design_file_export.png

Temporary files
temp/
*.temp

IDE-specific files
.idea/

### Project4:

UiPath project files
project.json
project.settings
Main.xaml

NuGet packages
packages/

Logs
*.log

### Project 5:

Power BI output files
*.pbix
*.pbit

Data model cache
DataModelCache/

Temporary files
*.tmp

Logs
*.log

## Storage of credentials and sensitive information

The following strategies will be used to store credentials and sensitive information:

### Configuration Files: 

Use of configiration files like YAML or JSON files to store sensitive information and then later exclude them with a .gitignore file.

### Version Control Exclusion: 

Ensure that configuration files containing sensitive data are added to the .gitignore file.

### Restrict access: 

Restrict access to certain sensitive data to only authorized personel(in this instance I am the "authorized personel").

### Audit and Rotation: 

Regularly audit and review stored credentials. 

### Avoid Hardcoding Credentials:

Never hardcode passwords, API keys, or any sensitive data directly into the source code.

## Citations
Silva, D., Tsantalis, N. and Valente, M.T., 2016, November. Why we refactor? confessions of github contributors. In Proceedings of the 2016 24th acm sigsoft international symposium on foundations of software engineering (pp. 858-870).

Nakazawa, S. and Tanaka, T., 2015, August. Prototype of kanban tool and preliminary evaluation of visualizing method for task assignment. In 2015 International Conference on Computer Application Technologies (pp. 48-49). IEEE.

Abrahamsson, P., Salo, O., Ronkainen, J. and Warsta, J., 2017. Agile software development methods: Review and analysis. arXiv preprint arXiv:1709.08439.

Al-Saqqa, S., Sawalha, S. and AbdelNabi, H., 2020. Agile software development: Methodologies and trends. International Journal of Interactive Mobile Technologies, 14(11).

Da Silva, F.Q., Costa, C., Franca, A.C.C. and Prikladinicki, R., 2010, August. Challenges and solutions in distributed software development project management: A systematic literature review. In 2010 5th IEEE International Conference on Global Software Engineering (pp. 87-96). IEEE.

Vice Dev. (2020). Project management with Basic Kanban board on GitHub.. [Online Video]. 26 September 2020. Available from: https://www.youtube.com/watch?v=G2VKydGXk54. [Accessed: 5 August 2023].

freeCodeCamp.org. (2020). Git and GitHub for Beginners - Crash Course. [Online Video]. 28 May 2020. Available from: https://www.youtube.com/watch?v=RGOj5yH7evk. [Accessed: 2 August 2023].

