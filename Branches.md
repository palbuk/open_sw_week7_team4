# Branches
## Chapter Branches
### 1. Moving through time
```bash
git checkcout Little sister does something
# little sister 수정
git add little_sister
git commit little_sister

git checkout Little sister does something

#piggy_bank 수정
git add piggy_bank
git commit piggy_bank
```
### 2. Make parallel commits
```bash
git checkcout HEAD~2
# case/lion 수정
git add .
git commit 

git checkout Little sister does something
```
### 3. Creating Branches
```bash

git checkout Go to the birthday

git branch birthday

git checkout Go to the concert

git branch concert
```

### 4. Branches grow with you!
```bash

git checkout Go to the birthday

git add .

git commit -m "modified"

git checkout concert

git add.

git commit -m "modified concert"
```
### 5. Deleting branches
```bash
git checkout refs/heads/leap

git branch -D friend
git branch -D music
git branch -D ice-cream
```
### 6. Moving branches around
```bash
git checkout baguette
git reset --hard You eat the baguette

git checkout coffee
git reset --hard You drink the coffee

git checkout donut
## You ate a donut 수정
git add .
git commit
#commit You eat a donut으로 수정

