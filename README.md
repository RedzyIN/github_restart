Command in Git

git init (create new repo)
git status (give summarize for modify file/code(update/delete/new file/folder))
git add (save to staging for update/new changes of file/s or add a file/folder)
git add --all / -A (for commit all change)
git add . (only stage current directory)
git add * (only stage new or modified(not deleted))
git restore (cancel all change)
git reset (out from staging)
git commit -m "Message" (saves permanently to local repos)
git config --global user.email "email@gmail.com" (sets email globally)
git config --global user.name "RedzyIN" (set username globally)
git reset HEAD~ (undo last commit)
git rm filename (remove file and continue to stage)
git log (see all history commit in detail)
git log --oneline (oneline summarize)
git log --oneline --graph --all (just add * at list)
git diff (view unposted changes)
git diff --staged (view posted changes)
git branch (see all branch)
git branch new_name_branch (create new branch)
git merge main -m "message" (combining sub-branch with main branch)
git checkout branch_name/hash_code_commit (change branch position)
git diff (show us changes by detail(not commit))

Github Command
git clone (clone repo from github to local workplace)
git push origin main (only push main branch to github)

Basic Command
cd = Change Directory
pwd = position which directory
rm = remove item
type > filename = create new file (Windows)
touch filename(MacOs)
mkdir = make new directory/folder

All process
Push = sending local changes to the remote
Fetch = Bringing remote changes into your local repository, but not merging them yet
Pull = Fetching plus merging-so your working directory  immediately reflects the remote changes