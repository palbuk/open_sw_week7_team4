# Chapter Branches
## 1. Moving through time
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
## 3. Creating Branches
```bash

git checkout Go to the birthday

git branch birthday

git checkout Go to the concert

git branch concert
```

## 4. Branches grow with you!
```bash

git checkout Go to the birthday

git add .

git commit -m "modified"

git checkout concert

git add.

git commit -m "modified concert"


