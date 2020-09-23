1$ git clone [ssh-url] [folder-name]
2$ cd [folder-name]
1$ git checkout -b [new-feature]
1$ git add .
2$ git commit -m «information added in readme»
3$ git checkout master
git push [git-remote-alias] [branch-name]
1$ git clone [ssh-url] [folder-name]
2$ cd [folder-name]

$ git branch
* master
1readme
2$ git remote -v
3origin git@github.com:[forked-repo-owner-username]/[repo-name].git
4(fetch)
5origin git@github.com:[forked-repo-owner-username]/[repo-name].git
6(push)
7$ git push origin readme
