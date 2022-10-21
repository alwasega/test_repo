# Single-folder workspaces

You don't have to do anything for a folder to become a VS Code workspace other than open the folder with VS Code. Once a folder has been opened, VS Code will automatically keep track of things such as your open files and editor layout so the editor will be as you left it when you reopen that folder. You can also add other folder-specific configurations such as workspace-specific settings (versus global user settings), task definitions, and debugging launch files (see below in the workspace settings section).

From within the BASH shell or terminal window, you can invoke the default Git editor through the following command:

`git config --global --edit`

On Ubuntu, this opens the Nano text editor, which I’m not a huge fan of. Fortunately, the global git config file can be used to change the default Git editor to something you find more user friendly.