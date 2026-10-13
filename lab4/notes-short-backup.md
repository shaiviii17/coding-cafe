Coding Café- Lab 4 Answers

Question 1
The `--global` option saves my Git name and email for all repositories belonging to my user account. Without it, the settings apply only to the current repository if I run the command inside one.

Question 2
The `.git` directory appeared when I ran `ls -a`. It stores Git's internal information, including commit history, configuration and references to branches. It should not be deleted.

Question 3
In my correct `coding-cafe` folder, Git initially showed two untracked files: `Untitled.rtf` and `notes.md`, along with a modified `.DS_Store` file. The untracked files were not yet part of the repository's committed history.

Question 4
After creating `.gitignore`, the ignore rules were added to the project. Files matching those rules, such as `.DS_Store`, are ignored if they are not already tracked by Git.

Question 5
The `.gitignore` file should be committed, not ignored. It tells Git which unnecessary files to leave out, helping everyone working on the project follow the same rules.

Question 6
After running `git add README.md`, the README moved from the untracked section to the staged changes section. This means it moved from the working directory into the staging area, ready to be included in a commit.

Question 7
After running git commit, Git displayed a summary containing the commit message and the number of files changed. In my earlier commit (4b4b578), Git reported 9 files changed and 1,983 insertions.

Question 8
The first seven characters of a commit's hash form its short commit ID. For example, my existing commit has the short ID `4b4b578`. This ID helps me identify and refer to a specific commit without typing its entire hash.

Question 9
The four steps of the Git workflow are edit, stage, commit, and repeat. I edit files, use `git add` to stage the changes, use `git commit` to save a snapshot, and repeat the process when I make further changes.

Question 10
`README.md` is a standard name recognized by GitHub and many other code-hosting platforms. GitHub displays it prominently on the repository's front page, so visitors can quickly understand the project's purpose and contents.

Question 11
The `gh auth login` command authenticates the GitHub CLI with my GitHub account. It stores authentication credentials so GitHub CLI and Git can authenticate future operations without asking me to enter my account password for every push.

Question 12
The `README.md` file appears on the GitHub repository's front page as formatted text. GitHub automatically renders Markdown in README files to make the project description and contents easier to read.

Question 13
Pushing does not change my local commit history. It uploads my existing commits to GitHub, creating an online copy of the history already stored on my computer.

Question 14
A private repository exists on GitHub but is visible only to its owner and people or teams granted access. A repository that does not exist on GitHub has no online repository page or hosted history for collaborators to access.