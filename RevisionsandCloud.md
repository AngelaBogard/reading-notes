# Revisions and Cloud

- A different way to make changes to Github is cloning a repository onto my computer, then using the Terminal and VS Code to make the changes.

## Here are the *Steps to Edit* your GitHub repository on your computer via Terminal and VS Code
> - On GitHub, select the specific repository you want to work on and then click the green 'Code' button. A new window will appeared labeled as "Clone". 
> - Copy your HTTPS .git link.
> - Next, open the Terminal then carefully navigate to the directory that you want to clone the repository to such as `cd Desktop`.
> - Once you're in the right directory folder, type `git clone` and then paste your copied .git link. This will make a copy of the repository in the location you specified. 
> - Enter `ls` to see the file to make sure the  project name is correct. 
> - Enter `cd` followed by the name of your project of your new directory (e.g. cd reading-notes) and press enter to navigate into this directory. 
> - Type `code .` to open VS Code referencing this specific project with its files from GitHub.
> - Minimize your Terminal window but do not exit it. 
> - Within the VS Code app, review your Markdown and other files to fix errors and concerns. You can add or edit files through VS Code. *Make sure you consistently save your work with command/control `s`.* 

**When changes are complete and saved on VS Code, go to your Terminal window and complete the following steps to your changes that are *pushed* to your repository GitHub competely.**
> 1. Enter `git status`, which will show the changes. 
> 2. Input `git add .`, which will create a "stage" to be used by git to add all changes. 
> 3. Then type in `git commit -m 'brief commit message'`. The "brief commit message" should be a message why you did what you did to add this to the repository version record. e.g. `git commit -m 'fix errors on all files'`
> 4. Enter 'git status" and you'll see the commits ready to be pushed (but not yet integrated with GitHub).
> 5. Finally, input `git push` to add or "push" the changes to your GitHub repository. 

**Once these steps are complete, check your main repository to see if the changes are successfully completed.** 

# Website Pages
- [*About Me*](README.md)
- [*Growth Mindset*](GrowthMindset.md)
- [*Learn more about Markdown*](Learning_Markdown.md)
- [*Coders Computer*](CodersComputer.md)
- [*Revisions and Cloud*](RevisionsandCloud.md)
- [*Learning HTML structure*](LearningHTMLstructure.md)
- [*Design Website with CSS*](Design_web_pages_with_CSS.md)
- [*Building Dynamic Webpages with JavaScript*](Dynamic_web_pages_with_JavaScript.md)
- [*Programming with JavaScript*](Programming_with_JavaScript.md)
- [*Operators_and_Loops*](Operators_and_Loops.md)













     

