commit test

remote test

push test


```
git config --global user.email "내 이메일", git config --global user.name "내 이름"
# 로그인 안해두면 commit 이 안된다는데 그렇지는 않았음. 차피 이거 안해도 push 할때 로그인 나옴.

git clone https://github.com/Deplim/git_command_test.git
git remote -v
git remote remove origin
git remote add origin "https://github.com/Deplim/git_command_test"

touch git_command_master.md
vim git_command_master.md
git add git_command_master.md
git status
git commit -m "add git_command_master.md"

git push origin main

# 원격저장소에서 파일이 수정된 이후
git pull

```