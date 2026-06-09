# Dự án đầu tiên của tôi
First commit
Hello GitHub
chmod +x git-push.sh

./git-push.sh                    # commit với message "update"
./git-push.sh "fix login bug"    # commit với message tùy chọn
alias gp='f() { git add . && git commit -m "${1:-update}" && git push; }; f'
xin chao coome
