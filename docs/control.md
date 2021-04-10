## Control of Versions


### Initialize a Git Repository

* 'git init' - Initialize Git.
###### Initialized empty Git repository in /home/flc/pyproj/test_mkdocs/.git/

* 'nano .gitignore' - Create a .gitignore file from: [gitignore.io](gitignore.io)

## Management of Dependencies
### Install pip-tools and create requirements files

* 'pip install pip-tools' - Install pip-tools
* 'nano requirements.in' - immediate dependencies
* 'pip-compile --generate-hashes requirements.in --output-file requirements.txt' - compile and generate hashes


