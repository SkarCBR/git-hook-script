# git-hook-script
Git hook to add Jira ID automatically on each commit

Instructions:
- Download the script file
- Place it in the project Git folder ( lidl-plus-android/.git/hooks , if it doesn't exist just create it)
- Make sure the name of the file is prepare-commit-msg (Git will look for that name)
- Make the file executable with chmod +x prepare-commit-msg

Done!

Now, every time you commit with a message it will append the Jira task ID to the commit message.
