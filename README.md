# gitcolab

Use Git on Google Colab super fast

## Usage

This notebooks acts as Version Control on Colab by letting you call git commands in cells.

Use it to clone a repo, pull and push to and from your google drive. \
This way you can run entire python projects on Colab.


1.   Open this notebook in colab, and connect your google drive with the mount cell.
2.   Now you can clone a repo with the clone cell (*), and then run git commands for it.
3. If you already have a repo on your drive, specify the repo name that all subsequent git commands will refer to (the folder name on google drive where you cloned a repo) (**).\


> (*) The default folder for colab notebooks on google drive is `/Colab Notebooks`.
The repos will be cloned inside that folder.

> (**) When you clone, the repo name is set automatically.

## Authentication

You should place a `google_colab_git_credentials` file containing:
```
username
access_token
```
inside the colab folder.
