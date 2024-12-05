# to update the book - 

cd /home/breezy/Documents/GitHub/Jupyter-Books

jupyter-book build cryptography-guide

or rebuild with

jupyter-book build --all cryptography-guide

# to push the book to GitHub Pages -

cd /home/breezy/Documents/GitHub/Jupyter-Books/cryptography-guide

make sure in main - 

ghp-import -n -p -f _build/html
