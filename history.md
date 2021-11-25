# Отчет о проделанной работе

### Автор: Мурзенко Артур Сергеевич 
Ссылка на репозиторий с уроком про животных:  https://github.com/MurzenkoA/wild_animals

#### Ход работы:
* cd Desktop 
* git clone https://github.com/smartiqaorg/geometric_lib.git cd geometric_lib/ 
* git merge --no-ff develop 
* git checkout develop 
* git log --all --pretty=oneline --graph 
* git checkout main 
* git merge --no-ff develop 
* git log --all --pretty=oneline --graph
* git reset --hard HEAD^
* git log --all --pretty=oneline --graph
* git merge --ff develop 
* git log --all --pretty=oneline --graph 
* git rebase -i main 
* git config merge.conflictstyle diff3 
* git config --global merge.tool meld 
* git config --global mergetool.meld.path "C:\Program Files (x86)\Meld\Meld.exe" 
* git mergetool 
* git rebase --continue 
* git mergetool 
* git rebase --continue 
* git log --all --pretty=oneline --graph 
* git checkout main 
* git merge release --ff 
* git log --pretty=oneline --graph
* git push origin1 main
