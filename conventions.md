feat: introduces a new feature or enhancement to the codebase
Examle ==> feat(search): implement search functionality
fix: The commit addresses and resolves a bug, error, or issue in the codebase.
refactor: A code change that neither fixes a bug nor adds a feature, involves code refactoring, which means restructuring or reorganizing the code without changing its external behavior.
docs: The commit updates or adds documentation, such as README files, comments, or user guides, without affecting the code's functionality.
Example ==> docs: correct spelling of CHANGELOG
perf: The commit makes code changes aimed at improving performance or optimizing existing functionality.
revert: The commit undoes a previous commit, reverting the codebase to a previous state.
build: The commit introduces a change that affect the build system or external dependencies.(nodejs, etc)
ci: The commit involves changes to the continuous integration (CI) configuration or scripts used to automate build, testing, and deployment processes.


when removing something, use !, as removing something always causes a breaking change
Commit message with ! to draw attention to breaking change
refactor!: remove something

cheat sheet:
https://kapeli.com/cheat_sheets/Conventional_Commits.docset/Contents/Resources/Documents/index

External links:
https://eagerworks.com/blog/conventional-commits
