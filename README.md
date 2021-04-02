# Git-Commit-Editor

### A utility to change timestamp of any of your previous git commit.

### For installation use Setup.exe 

**TL;DR:** Use this to change time of your old git commits.

Warning: Use at your own risk. We are in no way responsible if your code breaks :)

## Requirements
- Please make sure you have added bash and git in your environment variable.
  - E.g.: C:\Program Files\Git\bin  
- **Important**: After changing the date with this utility in your local git repository, you need to force push to your remote (e.g.: github). Force pushing may cause all your peers to pull from the repository, take care of that.

#### Example:

- Notice how **Commit 3** timestamp is changed.

**BEFORE:**

- Commit 1: Jan 2 18:08:21 2021 +0530
- Commit 2: Apr 6 10:05:23 2021 +0530
- Commit 3: Dec 2 08:08:21 2021 +0530

**AFTER:**

- Commit 1: Jan 2 18:08:21 2021 +0530
- Commit 2: Apr 6 10:05:23 2021 +0530
- Commit 3: **Jul 6** 08:08:21 2021 +0530
