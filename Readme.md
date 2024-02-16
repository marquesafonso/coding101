# Coding 101

A repository for introductory concepts for coding in python using notebooks.

## Installation and Set up

1. [Install an IDE - VS Code](https://code.visualstudio.com/download)
2. [Install Python](https://www.python.org/downloads/release/python-3121/)
3. Verify the installation by running "python" in the terminal. Tip: you may need to add python to the environment variables for it to be recognized by your computer. See [this](https://realpython.com/add-python-to-path/).
4. [Install Git](https://github.com/git-guides/install-git)
5. [Create a Github account](https://docs.github.com/en/get-started/quickstart/creating-an-account-on-github)
6. [Create SSH key](https://www.digitalocean.com/community/tutorials/how-to-create-ssh-keys-with-openssh-on-macos-or-linux)
7. [Add SSH key to Github Account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
8. Clone this repository to your computer by running
    ```
    git clone git@github.com:marquesafonso/coding101.git
    ```
9. Install a dependency manager. I use [Pipenv](https://pypi.org/project/pipenv/):
    ```
    pip install pipenv
    ```
10. Change directory to the project folder:
    ```
    cd coding101/bmi/
    ```
11. Install the project dependencies by running:
    ```
    pipenv install
    ```

A lot of steps, I know... But this will ensure your projects are battle-proof. Also you will be able to download many projects from other from github to start your journey.

## Body Mass Index (BMI) exercise

In this first exercise you will learn the basics of reading an excel file and working with the *pandas* library to analyse a dataset containing records of people's gender, height, weight to produce their BMI.

Now:
1. open your editor (VS Code if you followed my tips).
2. Open the **body_mass.ipynb** notebook
3. Make sure to go to the top right of the notebook > **Select Kernel** > Choose your environment (This is where the necessary packages are installed - it should have bmi in the name )
4. Then just follow along the exercise! You can run the code cells using the **Execute cell** button on the left of each code block. Feel free to experiment with the code as you go!
