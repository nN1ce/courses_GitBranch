1. На локальном репозитории сделать ветки для:
- Postman ( $ git branch Postamn )
- Jmeter ( $ git branch Jmeter )
- CheckLists ( $ git branch CheckLists )
- Bag Reports ( $ git branch Bag_Reports )
- SQL ( $ git branch SQL )
- Charles ( $ git branch Charles )
- Mobile testing ( $ git branch Mobile_Testing )

2. Запушить все ветки на внешний репозиторий ( $ git push --all origin )
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта ( 1. git checkout Bag_Reports. 2. > bug_report.txt. 3. vim bug_report.txt )
4. Запушить структуру багрепорта на внешний репозиторий ( $ git push --set-upstream origin Bag_Reports )
5. Вмержить ветку Bag Reports в Main (1. $ git checkout main 2. $ git merge Bag_Reports)
6. Запушить main на внешний репозиторий. ( $ git push )
7. В ветке CheckLists набросать структуру чек листа. (1. $ git checkout CheckLists 2. $ > checklist.txt 3. $ vim checklist.txt)
8. Запушить структуру на внешний репозиторий ( $ git push --set-upstream origin CheckLists )
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main (Compare & pull request => Create pull request=> Merge pull request => Confirm merge)
10. Синхронизировать Внешнюю и Локальную ветки Main ( 1. $ git checkout main 2. $ git pull )


