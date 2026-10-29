Setup on Windows

Create Environment
python3 -m venv n-ai-env

Activate Environment
source n-ai-env/Scripts/activate (not working, so run below .bat file)

cd n-ai-env/Scripts
activate.bat

To De-activate Environment
deactivate

Install Dependencies
pip install -r requirement.txt











\-------------------------------



Alternative: The Quick "Fresh Start" Method



If this is a personal or relatively new project and you don't mind losing your entire commit history, you can simply delete the hidden Git database and start fresh:

1\. Delete local git records: rm -rf .git

2\. Add to gitignore: echo ".env" >> .gitignore

3\. Re-initialize: git init

4\. Commit: git add . \&\& git commit -m "Initial clean commit"

5\. Force push over GitHub history:bash

git remote add origin https://github.com

git push -u origin master --force

Use code with caution.

Let me know if you encounter any errors like "Everything up-to-date" or permission issues while running these commands so we can troubleshoot them!

