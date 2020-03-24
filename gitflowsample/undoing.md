git switch -c feature1
echo asdaljdaks > b.md
git log --oneline -all  um alle commits zu sehen
git cherry-pick bd6d278 hier übernimmt man nicht alle commits von dem neuen branch, sondern nur bis zum angegebenen commit die Änderungen

Rückgängig machen von lokalen Commits
neuen branch erstellen
einpaar dateien erstellen
einige Datein adden und committen
git reset ... ich resette zurück auf diese id oder wir gehen von HEAD aus und wie viele commit wir zurück gehen wollen 
-> git reset HEAD~2 hier bleiben commits noch in working tree
git reste --hard HEAD~2 da werden commits mit Inhalten auch aus den working tree gelöscht

git reset --help

git add forgottenfile
git commit --amend

revert pushed commits
Commits rückgängig machen
git revert c4711c

wir arbeiten in einem branch und falls git pull schief geht
1. Möglichkeit : git fetch und git merg

2.Möglichkeit (bessere)
lokale Änderungen werden verworfen aber für späte abholbar
dann git pull und man holt sich die Änderungen
git stash
git stash list
git stash show
git stash pop  ... um zurückzuholen

wenn bei pull commit was shief geht und man seine Änderungen verwerfen will
git reset --hard <commitid>

