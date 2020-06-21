# githubcreaterepo - A bash script that Creates a Github repo using an existing local git repo.

Ever wonder if you can create/push a local git repo to Github without creating it first on Github? :-)

# Requirements
* git
* curl

## Installation

* git clone https://github.com/Jetchisel/githubcreaterepo
* Replace the X's in the opt with your own token from github, see https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line
* Use the optional **add_token** script to add the Github token to the githubcreaterepo script. (Requires ed command base editor.)
* cd inside the local git repo and run: githubcreaterepo reponame

# Sypnosis
```shell
githubcreaterepo local-git-reponame
