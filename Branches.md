# Branches
## Chapter Branches
### 1. Moving through time
```bash
git checkcout Little sister does something
# little sister 수정 우클릭으로 하면 주소 나옴
# Has 10coins를 piggyback에 추가
git add .
git commit 

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
```

## Merge
### 1.Merging timelines
```bash
git merge faf956f527dbba524e37253fdc11706b5d04c5d6
git merge a80b36b4c682056858a6c517282faa0cdf96d7f0
```
### 2. Contradictions
```bash
git switch main
git merge muesli
git merge pancakes
#충돌 해결 <<<>>> === 지우기?
git add .
git commit
```