📂 Filesystem & File Operations 


ls -la
Lists all files and directories in the current folder in a detailed "long" format, including hidden files (like .git).


cd <directory>
Changes your current working location to the specified directory. Type cd alone to instantly teleport back home (~).


pwd
Prints the absolute path of your current working directory, showing you exactly where you are standing in the system.


mkdir <name>
Creates a brand-new, empty directory (folder) using the name you specify.


touch <filename>
Instantly creates a new, completely empty file, or updates the timestamp if the file already exists.


nano <filename>
Opens a lightweight, text-based text editor directly inside your terminal screen to edit files without a mouse.


mv <source> <destination>
Moves a file or folder from one location to another, or renames it if the destination is a new name in the same folder.


rmdir <directory>
Safely deletes an empty directory. It will refuse to run if there are any files left inside the folder.


rm -rf <target>
Forces the recursive deletion of a folder and everything inside it, completely bypassing all safety warnings. (Use with caution!)



🛠️ Logging, Filtering & Utility


echo "text"
Prints text to the screen, or redirects it into a file when paired with symbols like > (overwrite) or >> (append).


history
Displays a rolling digital logbook of every single command you have typed in your current terminal session.


tail -n <number>
Reads a file or stream and outputs only the final specified number of lines (e.g., tail -n 30 grabs the last 30 lines).


| (The Pipe)
An operator that chains commands together by catching the text output of the left command and feeding it directly as input to the right command.



🚀 Git & GitHub Automation


git pull origin main --no-rebase
Fetches the latest updates from your remote GitHub server and safely merges them into your local Cloud Shell folder.


git add <target>
Stages your new or modified files, placing them onto Git's radar so they are ready to be packed into your next commit.


git commit -m "message"
Wraps up your staged files and locks them into a permanent local snapshot labeled with a meaningful descriptive message.


git push origin main
Uploads your local committed snapshots up the secure conveyor belt to your live repository on GitHub.
