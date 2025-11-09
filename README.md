# dj100nc
Sample Git Repo for basic Git commands class
# Welcome to Data Jungle 100!!
Repo to practice basic github commands
We will use this repository to practice the following Git Operations:
1. Clone a repo
2. Make a new branch
3. Make a commit
4. Push a branch
5. Submit a PR
6. Merge it in.


## Instructions

```bash
# 1. Get the repo, using HTTPS
git clone https://github.com/omkarmore83/dj100nc.git

# 2. Create your branch
cd dj100nc
git checkout -b "{yourfirstname}-{enter a branchname of choice}"
    # ex: git checkout -b "madhura-first-branch"

# 3. Add your file in Gurukul_100_NC
touch Gurukul_100_NC/{your_name}
    # ex: touch Gurukul_100_NC/Madhura_Kshirsagar

# 4. Add your commits to your topic branch
git add Gurukul_100_NC/{your_name}
# or if you want to add all your unstaged files
git add --all
git commit
# this will prompt you to add a meaningful commit message

# 5. Push your commit
git push origin "<your-branch-name>"

# 6. Go to the https://github.com/madhura-codes/data_jungle_100_nc/pulls

# 7. Open a new PR for your new topic branch

# 8. Get a friend or teacher or a TA to approve your PR.

# 9. Merge it!
```
