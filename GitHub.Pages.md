[GitHub Pages](https://pages.github.com/)

## Create a repository
1. Head over to GitHub and create a new repository named username.github.io, where username is your username (or organization name) on GitHub.

2. Clone the repository
Go to the folder where you want to store your project, and clone the new repository:

~~~bash
  git clone https://github.com/username/username.github.io
~~~

3. Hello World
Enter the project folder and add an index.html file:

~~~bash
cd username.github.io

echo "Hello World" > index.html
~~~

4. Push it
Add, commit, and push your changes:
~~~bash
git add --all

git commit -m "Initial commit"

git push -u origin main
~~~

5. …and you're done!
Fire up a browser and go to https://mcastle23.github.io.

