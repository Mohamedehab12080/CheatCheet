# Creating a Virtual environment in python
```shell
python -m venv BOB
```
## Activate The Virtual Environment
```shell
BOB\Scripts\activate
```
### Remove from stage area
```shell
git restore --staged README.md
```
### Make a soft reset
* The commit history moves back to the specified commit.
* Changes from the undone commits are kept in the staging area and are still tracked.
* No changes in the working directory are lost.
```shell
git reset --soft HEAD~1
```
