# Class 04: HTML

## Review

### Git

- git: way for humans to interact with your computer (software),  gives us a platform / framework for transfering files / organizing.  Tracks changes!!!
  - Contains history of all changes made.
  - Allows you to see previous changes, revert back to previous versions (new commit, new verions).

### Github

- github: post your work in a collaborative environment.

### Git Commands

- `git status`: gives you information about your current local repository.
  - red things are not tracked by git (yet).
  - green things are tracked and ready to commit.
  - `.gitignore`: is placed at the root of your repository.
- `git add`: adds to the list of files that have changed for a commit.
  - `git add *` - adds  all changes (perhaps starting from current working directory)
  - `git add README.md folder/` (adds all changes from the paths specified)
  - `git add ./` - adds all changes starting from the current working directory.
- `git commit`: commit (saving) changes to your version history on your local machine(and are then ready to send to github).
  - `git commit -m 'saves family photo"`
- `git push`: Pushes "it" (Every change that has been commited) to github!
  - `git push origin main` - push all changes to the main branch on github.

## HTML

What is HTML??

- hyper text markup language.
  - Code for a web page.
  - Defines the composition of the content, gives you tools to interact with web pages.
  - Runs nativly in the browser.
  - Made up of elements!

### HTML Elements

- Types:
  - p (paragraph)
  - h1 ... h1 (heading)
  - a (anchor / link to another web site)
  - li (list item)
  - button (a clickable button)
  - nav (navigation)
  - ul / ol (unordered / ordered list)
  - article / section / ....
- Syntax contains brackets (angle brackets) `< >`
  - `<p> text to display does here </p>`: close each element with a / before the ending element tag.
- preset keywords that define different parts of the document.
  - keywords are often semantic (has meaning to a human).
  - What is the role of our content / vs how the content looks.


