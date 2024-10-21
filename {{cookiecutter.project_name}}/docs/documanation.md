# Project Documentation 

[Github Documentation](https://docs.github.com/en/pages)

## Installing Dependencies

1. Install Python 3.7 or later
2. Install [mkdocs](https://pypi.org/project/mkdocs/)
   
3. Install dependencies:
    ```sh
    $ pip3 install mkdocs
    ```
## Creating the documentation 

1. Create a "mkdocs.yml" file in the root 

    -   configuration Documentaion using this file [mkdocs.yml](https://www.mkdocs.org/user-guide/configuration/#introduction)

## Building the Documentation Locally

1. Run `mkdocs serve`

    - check it locally how it working  "http://127.0.0.1:8000/"

## Deploying it Documentation on the github pages 

1. create a github actions to create a github page 

2. create a docs.yml file in the "/.github/workflows/" 


3. After merging the code into master/main we need setup github page [LINK](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

4. setup of github pages
    - Under your repository name, click  Settings. 
    - In the "Code and automation" section of the sidebar, click  Pages.
    - Select the Source  "Deploy from a branch
    - Select the branch gh-pages