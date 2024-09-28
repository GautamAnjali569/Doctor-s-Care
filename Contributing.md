## Creating an Issue
Read on how to create and issue adhering to community guidelines [here](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/creating-an-issue)

## Creating a Pull Request

### Fork the Project:
Click on the "Fork" button at the top right corner of the repository's page on GitHub to create your own copy of the project.

### Clone Your Forked Repository:
Clone the forked repository to your local machine using the following command:

```bash
git clone https://github.com/Ramsey99/fest-registration
```
### Create a New Branch and Move to the Branch:
Create a new branch for your changes and move to that branch using the following commands:

```bash
git checkout -b <branch-name>
```
### Add Your Changes:
After you have made your changes, check the status of the changed files using the following command:
```bash
git status -s
```
Add all the files to the staging area using the following command:
```bash
git add .
```
or add specific files using:
```bash
git add <file_name1> <file_name2>
```
### Commit Your Changes:
Commit your changes with a descriptive message using the following command:
```bash
git commit -m "<EXPLAIN-YOUR_CHANGES>"
```
### Push Your Changes:
Push your changes to your forked repository on GitHub using the following command:
```bash
git push origin <branch-name>
```

### Open a Pull Request:
Go to the GitHub page of your forked repository, and you should see an option to create a pull request. Click on it, provide a descriptive title and description for your pull request, and then submit it.
