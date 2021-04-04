atomic_coder

Day 5 #100dysofcode challenge
Today I revised git commands.
▪️
The https://learngitbranching.js.org website provides a visual way of learning git commands. It has a very user friendly interface. I learnt the commands for making branches, merging them, rebase command. Although this rebase command works similar to merge but the advantage is that it makes a nice linear sequence of commits, so it makes commit log repository very cleaner to understand.
▪️
Then I learnt about detaching HEAD. Detaching HEAD means attaching it to a commit instead of a branch.
🔸For example :
Initially : HEAD->main->commit1
After detaching HEAD i.e. executing below command

git checkout commit1

It'll detach HEAD from main branch and attach it to a commit so, this represented as

HEAD->commit1
▪️
▪️
And next I learnt about relative reference which are of two types ^ (caret ) and ~ (tidle ).
1) ^ (caret ) : is used to find parent of specified commit.
🔸Ex. git checkout HEAD^
.
2) ~ (tidle ) : This operator takes the trailing number that specifies the number of parents you would like to ascend.
🔸Ex. git checkout HEAD~3
▪️
Then for reversing/undo changes in git there are mainly two ways
1) git reset :
🔸Used for for local branches on local machine.
🔸It reverts changes by moving a branch reference backwords in time to an older commit.
🔸Ex. git reset HEAD~1
.
2) git revert :
🔸used for remote branches
🔸It reverses the changes & share those changes with others
🔸Ex. git revert HEAD
.
.
.

Do check out this website to master git commands
👉 https://learngitbranching.js.org 👈
.
.
Thank you
@atomic_coder
@atomic_coder .
.

Happy coding :)
.
.
.
.
.
.