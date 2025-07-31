# choeshey-todo
Go to https://github.com and log in.

Navigate to the repository you want to delete.

Click on Settings tab (top-right of the repo).

Scroll down to the "Danger Zone" section.

Click “Delete this repository”.

GitHub will ask you to:

Confirm the repo name (e.g., your-username/repo-name)

Click “I understand the consequences, delete this repository”

✅ Option 2: Remove Git Repository from WebStorm (without deleting GitHub repo)
If you just want to remove Git from a local project in WebStorm (not delete on GitHub):

Steps:
Go to your project folder in WebStorm.

Delete the .git hidden folder:

Mac/Linux: Press Cmd+Shift+. to show hidden files

Windows: Enable hidden files in Explorer

Then delete .git folder manually

Your project is no longer tracked by Git.

Now you can re-init Git or use it as a normal folder.