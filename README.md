# Recipes
A recipe site I am making to practice HTML

I am making a website with a main index page and links to a few recipes.
I will have to demonstrate my knowldege of basic elements and tags.

I'll demonstrate my ability to produce the basic HTML boilerplate.
I can create the HTML boilerplate from memory or with ! in VScode

Once I have the boilerplate I will have to add content.
To add content I will use head, body, text, list, and anchor/link elements.
I may also add some photos using the img tag to jazz it up.

Lastly, I am going to try to create good atomic commit habits while working on this project. 

Wish me luck!



Step 1: Create main index in the odin-recipes directory called index.html.

Step 2: Use VScode to create the HTML boilerplate in the index.html file. By typing ! and hitting enter.
This includes <!DOCTYPE html> , <html lang="en"> , <head> within the head: <meta charset="UTF-8"> and <title> , and finally the <body> element. 

Step 3: Now that you've made a meaningful change to the code, it's time for a git commit. 
    - type git status into the command line, you will see both files (README.md and index.html) are red because you have made changes to them
    - type add and then the file names you want to add to the staging area (or . to add them all)
    - typing git status again wil show the README.md and index.html files are now green instead of red
    - type git commit -m "add index.html README.md" to add a commit message
    - finally, type git push to upload your local commit to the repository on github.
    
CHEAT SHEET Commands related to a remote repository:
git clone git@github.com:USER-NAME/REPOSITORY-NAME.git
git push or git push origin main (Both accomplish the same goal in this context)

Commands related to the workflow:
git add .
git commit -m "A message describing what you have done to make this snapshot different"

Commands related to checking status or log history:
git status
git log
The basic Git syntax is program | action | destination.