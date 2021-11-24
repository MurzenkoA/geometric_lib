cd Desktop
git clone https://github.com/smartiqaorg/geometric_lib.git
cd geometric_lib/
git merge --no-ff develop
git checkout develop
git log --all --pretty=oneline --graph
git checkout main
git merge --no-ff develop
git log --all --pretty=oneline --graph
git reset --hard HEAD^
git log --all --pretty=oneline --graph
 git merge --ff develop
 git log --all --pretty=oneline --graph
git rebase -i main
git config merge.conflictstyle diff3
git config --global merge.tool meld
 git config --global mergetool.meld.path "C:\Program Files (x86)\Meld\Meld.exe"
git mergetool
git rebase --continue
git mergetool
git rebase --continue
git log --all --pretty=oneline --graph
git checkout main
git merge release --ff
git log --pretty=oneline --graph