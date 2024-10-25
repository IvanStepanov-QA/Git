#### 1. На локальном репозитории сделать ветки для:
#### - Postman
#### - Jmeter
#### - CheckLists
#### - Bag Reports
#### - SQL
#### - Charles
#### - Mobile testing 
git branch Postman
git branch Jmeter
git branch CheckLists
git branch BugReports
git branch SQL
git branch Charles
git branch MobileTesting
#### 2. Запушить все ветки на внешний репозиторий
git push -u origin --all
#### 3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта
git checkout BugReports
vim Bug_Reports.txt
1) ID
2) Date
3) Environment
4) Title
5) Steps
6) Expected result
7) Actual result
8) Attachment

#### 4. Запушить структуру багрепорта на внешний репозиторий
git add Bug_Reports.txt
git commit -m "Add Bug Report"
git push
#### 5. Вмержить ветку Bug Reports в Main
git checkout main
git merge BugReports
#### 6. Запушить main на внешний репозиторий.
git push
#### 7. В ветке CheckLists набросать структуру чек листа.
git checkout CheckLists
cat > Checklist.txt
1) Name
2) Ver
3) Env
4) Dste
5) ID
6) Tests
7) ER
#### 8. Запушить структуру на внешний репозиторий
git add Checklist.txt
git commit -m "Add Check list"
git push
#### 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
- перейти на страницу https://github.com/Liudmila-Papko/Skills
- нажать кнопку Compare & pull request
- Add a title
- Нажать Create pull request
- Нажать Merge pull request
- Нажать Confirm merge
#### 10. Синхронизировать Внешнюю и Локальную ветки Main (находимся в main ветке)
git pull

