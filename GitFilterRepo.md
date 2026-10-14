


```bash
# 
git log --all -- "folder3/password.txt"

git filter-repo 

# python -m git_filter_repo --sensitive-data-removal --invert-paths --path "secret/sample_secret.txt"


git filter-repo --path /folder3/password.txt --invert-paths

git filter-repo --path /folder3/passsword.txt --invert-paths


# 結論から言うと、git filter-repo を実行した瞬間に、そのリポジトリは「別の全く新しいリポジトリ（赤の他人）」に生まれ変わってしまうからです。
# 切れてしまった「GitHub」とのつながりをもう一度結び直す

git remote add origin https://github.com/yurayuramen/try-git
git push origin --force --all
git push origin --force --tags



git fetch origin
git reset --hard origin/master

# git clean -fd


```
