# How to Host a Project Repository on GitHub

Follow these steps to host a website using a project repository on GitHub:

1. **Create a new repository**: Head over to GitHub and create a new repository. You can name it anything you like.

2. **Clone the repository**: Go to the folder where you want to store your project, and clone the new repository:
    ```
    git clone https://github.com/username/repository
    ```

3. **Create a new branch**: GitHub Pages uses a branch in your repository named `gh-pages` to serve the website. So, create a new branch with that name:
    ```
    git checkout -b gh-pages
    ```

4. **Add an index.html file**: Enter the project folder and add an `index.html` file:
    ```
    cd repository
    echo "Hello World" > index.html
    ```

5. **Push it**: Add, commit, and push your changes:
    ```
    git add --all
    git commit -m "Initial commit"
    git push -u origin gh-pages
    ```

6. **Check your website**: Fire up a browser and go to `https://username.github.io/repository`.

Please replace `username` with your actual GitHub username and `repository` with the name of your repository.

This way, you can have many pages set up, but each will be at a different URL based on the repository name. Enjoy building your website!

[caidam.github.io/basic-box-model](https://caidam.github.io/basic-box-model)
