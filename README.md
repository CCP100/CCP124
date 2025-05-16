This file is we are created for testing purpose.
echo "AWS_SECRET_ACCESS_KEY=AKIAFAKETESTKEY12345678" > pushblock.txt
git add pushblock.txt
git commit -m "Test push protection"
git push

remote:   —— GitHub Personal Access Token ——————————————————————
remote:    locations:
remote:      - commit: 8728dbe67
remote:        path: README.md:4
remote:      - commit: 03d69e5d3
remote:        path: README.md:4
remote:      - commit: 8053f7b27
remote:        path: README.md:4
git@github.com:CCP100/CCP124.git
....................

