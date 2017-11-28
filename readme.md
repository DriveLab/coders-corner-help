# Drive Lab Coders' Corner

Hi! and welcome to the Drive Lab Coders' Corner, the platform that hosts a collection of up-to-date programs to implement techniques that are used across different projects in the lab (calculating indices, trimming or winsorizing, etc.). The files for each program are stored in a separate folder (GitHub calls it a *Repo*), and all repos are listed [here](https://github.com/DriveLab?tab=repositories).

Together with the [Drive Lab Coders' Best Practice Guide](https://docs.google.com/document/d/1ZMEm-IMgLdDFYQQ4PpuxUdXs_IAXKM5oDhl6rfe8848/edit?usp=sharing), which provides guidance on how to implement techniques and how to deal with problems you might run into, the platform serves four main purposes:

1. It ensures that techniques are used consistently across different projects.

2. It documents and offers solutions to problems you might run into.

3. It provides code to implement the best-practice approach for various stages of the research process, from cleaning the data to producing neat output tables.

4. It aggregates the know-how of all collaborators and makes it available to the Drive Lab community.



## Your contribution matters

- For yourself, because the better maintained the programs on this platform are, the better the platform can serve the functions above and help you produce better research in less time.

- For the community, because everyone relies on everyone else to contribute and to share their knowledge.



## Help with using GitHub

If you have no experience with Git and GitHub, invest about half an hour to work through these guides in sequence:

1. [The very basics](https://guides.github.com/activities/hello-world/).

2. [Using GitHub Desktop](https://guides.github.com/introduction/getting-your-project-on-github/).

3. [Contribute to a project](https://guides.github.com/activities/forking/).

4. [Markdown](https://guides.github.com/features/mastering-markdown/).

After this, you'll be ready to use the platform. If you want to learn more, IPA provides a useful collection of [resources](https://github.com/PovertyAction/github-training/blob/master/resources/External%20resources.md). 



## How to use the platform

### Use a program from the platform

1. Navigate to the main page of the program you want to use (e.g. https://github.com/DriveLab/stata-latex-integration).

2. **Fork** the repo to your own GitHub account and then **clone** it ([Guide](https://guides.github.com/activities/forking/)). Cloning produces a copy of the program repo on your local machine. The copy will look like any other folder, and you can specify where you want to save it. One option is the analysis/code folder of your project; another is a separate folder where you keep all cloned programs. (Choose whatever works best for you.)

3. Copy/paste the code into your do-file and adapt it as needed. Mark off the code clearly and add the following line of comment at the beginning: `Program from https://github.com/DriveLab/name-of-repo, cloned on: date` (the path identifies the program, the cloning date makes it easier to check whether your do-file uses the latest version of it).


### Propose changes to a program

If you find bugs in the code or make improvements that could benefit the community, please share your work with others ([Guide](https://guides.github.com/activities/forking/)).

1. Improve your local clone of the program repo. 

2. Push the changes to the forked repo on your GitHub account.

3. Start a pull request to propose that the improvement be merged into the original DriveLab repo. In the message of the request, explain what you did and why it matters.



### Suggest that your program gets added to the platform

If you use a program that is not on the platform but could be useful for others, please get in touch and suggest that your program is being added. This works like so:

1. Create a separate folder that contains all relevant files, then push it to your GitHub account. ([Guide](https://guides.github.com/introduction/getting-your-project-on-github/))

2. Go to (https://github.com/DriveLab/coders-corner-help), navigate to **Issues**, and create a new issue where you provide the link to your program repo and explain what the program does and why it should be added.

3. We'll have a look at your repo and might get in touch for questions and suggestions. Once your request has been approved, you can transfer the repo from your account to DriveLab's. To do this, navigate to the main page of your program repo on GitHub, click **Settings**, then scroll all the way down into the Danger Zone and click **Transfer**. ([Guide](https://help.github.com/articles/transferring-a-repository-owned-by-your-personal-account/))

A few style guidelines for new repos to follow:

- Add a readme.md file that explains what your directory contains, what all the files do, and how to deal with known issues. Provide a link to the relevant section of the [Best Practice Guide](https://docs.google.com/document/d/1ZMEm-IMgLdDFYQQ4PpuxUdXs_IAXKM5oDhl6rfe8848/edit?usp=sharing) if you give more detail there (it would be nice if you did!). 

- Use lower-case for all letters, and hyphens instead of spaces in all directory- and file names (consistent use of lower- and upper case makes folders and documents easier to skim, spaces make it cumbersome to use GitHub from the command-line). 

- Choose a meaningful name for the directory (mean-comparison) and for all files (mean-comparison.do, example-data.dta, readme.md).

- Add relevant literature in a separate *lit* subfolder.

For an example, see [here](https://github.com/fabiangunzinger/drivelab-code/tree/master/code/stata-latex-integration).



### Request that a new program gets added to the platform.

If you think there is a program that would be useful to have on the platform but don't have time to write it yourself, raise an [issue](https://github.com/DriveLab/coders-corner-help/issues).


## Questions

If you have any questions, raise an [issue](https://github.com/DriveLab/coders-corner-help/issues).



