# Drive Lab Coders' Corner

Hi! and welcome to the Drive Lab Coders' Corner. This platform (GitHub calls it a *Repo*) contains up-to-date programs to implement techniques that are used across different projects (calculating indices, trimming or winsorizing, etc.). 

Together with the [Drive Lab Coders' Best Practice Guide](https://docs.google.com/document/d/1a_O0SiyN1AAlTNnpYiN5TNaeGCnhgc2uKr0enuORYHE/edit), which provides guidance on how to implement techniques in different circumstances and documents problems you might run into, the platform serves four main purposes:

1. It ensures that techniques are used consistently across different projects.

2. It documents and offers solutions to problems you might run into.

3. It provides code to implement the best-practice approach for various stages of the research process, from cleaning the data to producing neat output tables.

4. It aggregates the know-how of all collaborators and makes it available to the Drive Lab community.


## Your contribution matters

- For yourself, because the better maintained the programs on this platform are, the better the platform can serve the functions above and help you produce better research in less time.

- For the community, because everyone relies on everyone else to contribute and to share their knowledge.


## Help with using GitHub

If you're new to GitHub, have a look at the [resources provided by IPA](https://github.com/PovertyAction/github-training). A great way to get started quickly is to read [*GitHub User Guide.md*](https://github.com/PovertyAction/github-training/blob/master/resources/GitHub%20User%20Guide.md) in the resources directory. To delve deeper, have a look at [*External learning resources.md*](https://github.com/PovertyAction/github-training/blob/master/resources/External%20resources.md), and check out the [GitHub Guides](https://guides.github.com) website. 



## How to use the platform

### Use a program from the platform

1. Navigate to the main page of the program you want to use (e.g. https://github.com/DriveLab/stata-latex-integration).

2. **Fork** the repo to your own GitHub account and then **clone** it to your local machine ([Guide](https://guides.github.com/activities/forking/)). Cloning produces a copy of the program repo on your local machine. The copy will look like any other folder, and you can specify where you want to save it. One option is the analysis/code folder of your project; another, a separate directory where you keep all cloned programs--choose the workflow that works best for you. 

3. Copy/paste the code into your do-file and adapt it as needed.


### Propose changes to a program

If you find bugs in the code or make improvements that could benefit the community, please share your work with others ([Guide](https://guides.github.com/activities/forking/)).

1. Improve your local copy of the program repo. 

2. Push the changes to the fork of the repo on you GitHub account.

3. Make a pull request to propose that the improvement be added to the DriveLab repo. In the message of the request, summarise what you did and why it matters.


### Suggest that your program gets added to the platform

If you use a program that is not on the platform but could be useful for others, please get in touch and suggest that your program is being added to the platform. This works like so:

1. Create a separate folder that contains all relevant files, then push it to your GitHub account. ([Guide](https://guides.github.com/introduction/getting-your-project-on-github/))

2. Go to (https://github.com/DriveLab/coders-corner-help), navigate to **Issues**, and create a new one explaining what your program does and why it should be added.

3. If your request has been approved, you can transfer the repo from your account to DriveLab's: navigate to the main page of your program repo on GitHub, click **Settings**, then **Transfer**. ([Guide](https://help.github.com/articles/transferring-a-repository-owned-by-your-personal-account/))

A few style guidelines to follow:

- Use lower-case for all letters, and hyphens instead of spaces in all directory- and file names (consistent use of lower- and upper case makes folders and documents easier to skim, spaces make it cumbersome to use GitHub from the command-line). 

- Choose a meaningful name for the directory (mean-comparison) and for all files (mean-comparison.do, example-data.dta, readme.md).

- Add relevant literature in a separate *lit* subfolder.

- Add a readme.md file that explains what your directory contains, what all the files do, and how to deal with known issues. Provide a link to the relevant section of the [Best Practice Guide](https://docs.google.com/document/d/1a_O0SiyN1AAlTNnpYiN5TNaeGCnhgc2uKr0enuORYHE/edit) if you give more detail there (it would be nice if you did!). 

For an example, see [here](https://github.com/fabiangunzinger/drivelab-code/tree/master/code/stata-latex-integration).


### Request that a new program gets added to the platform.

If you think there is a program that would be useful to have on the platform but don't have time to write it yourself just now, raise an [issue](https://github.com/DriveLab/coders-corner-help/issues).

## Questions

If you have any questions, raise an [issue](https://github.com/DriveLab/coders-corner-help/issues).
