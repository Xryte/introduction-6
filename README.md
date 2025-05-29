git pull https://github.com/Xryte/introduction-1

git pull https://github.com/Xryte/introduction-2
git rm README.md
git checkout FETCH_HEAD -- README.md
git add README.md
git commit -m "Разрешил конфликт: остановил README из introduction-2"

git pull https://github.com/Xryte/introduction-3
git rm README.md
git checkout FETCH_HEAD -- README.md
git add README.md
git commit -m "Разрешил конфликт: остановил README из introduction-3"

git pull https://github.com/Xryte/introduction-4
git rm README.md
git checkout FETCH_HEAD -- README.md
git add README.md
git commit -m "Разрешил конфликт: остановил README из introduction-4"

git pull https://github.com/Xryte/introduction-5
git rm README.md
git checkout FETCH_HEAD -- README.md
git add README.md
git commit -m "Разрешил конфликт: остановил README из introduction-5"

git push origin main
