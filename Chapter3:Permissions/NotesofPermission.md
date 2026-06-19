🔐 The Core Concept: Who Are You?

Every single file and folder in Linux has a security tag attached to it. When you try to read, write, or run a file, the Linux kernel looks at your account and checks three distinct layers of ownership:

User (u): The specific individual account that owns the file (usually the person who created it).

Group (g): A collection of users who share the same access level (e.g., a team of developers or system admins).

Others (o): Everybody else in the entire system.

For each of these three layers, Linux defines exactly three types of actions they are allowed to do:

Read (r): Can they look inside the file or list the folder?

Write (w): Can they modify, edit, or delete the file?

Execute (x): Can they run the file like a program or a script?
