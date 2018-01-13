## this is repo for my recipe

1. create new repo named "recipe" in github and copy URL of the "recipe" repo

    ```
    https://github.com/qingshi7252/recipe.git
    ```

2. clone "recipe" to local machine 
    * open terminial and change to the directory where to store the "recipe" repo 
        ```
        cd /Users/vannizhang/Desktop/Qing 
        ```
    * clone the "recipe" repo from github to local machine
        ```
        git clone https://github.com/qingshi7252/recipe.git
        ```

3. create a new file named "README.md" in the cloned folder using Viusal Studio Code

4. Add any untracked (such as "README.md") files to local git repo
    ```
    git add . 
    ```
5. commit untracked changes to local git repo
    ```
    git commit -m "first commit" 
    ```
6. push changes from loal git repo to the remote github repo 
    ```
    git push origin master
    ```
7. Syncronize the local git repo to the remote github repo
    ```
    git pull origin master
    ```
