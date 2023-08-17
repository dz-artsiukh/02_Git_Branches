## Homework #2

### 1. На локальном репозитории сделать ветки для:

- Postman - `git branch Postman`
- Jmeter - `git branch Jmeter`
- CheckLists - `git branch Checklists`
- Bag Reports - `git branch "Bug_Reports"`
- SQL - `git branch SQL`
- Charles - `git branch Charles`
- Mobile testing - `git branch "Mobile_testing"`

### 2. Запушить все ветки на внешний репозиторий - 

- `git push -u origin Postman Jmeter Checklists Bug_Reports SQL Charles Mobile_testing`

### 3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

- `git checkout bug_reports`
- `nano bug_report.txt`

### 4. Запушить структуру багрепорта на внешний репозиторий

- `git add .` 
- `git commit -a -m "bug_report"`
- `git checkout main`
- `git push -u origin Bug_Reports`

### 5. Вмержить ветку Bag Reports в Main 

- `git merge bug_reports`

### 6. Запушить main на внешний репозиторий.

- `git push`

### 7. В ветке CheckLists набросать структуру чек листа. - nano checklist.txt

### 8. Запушить структуру на внешний репозиторий - 

- `git add .`
- `git commit -a -m "checklist"`
- `git checkout main`
- `git push -u origin Checklists`

### 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main 

- в ветке Checklist нажать кнопку  Merge and pull request и подтвердить

### 10. Синхронизировать Внешнюю и Локальную ветки Main 

- `git fetch`
- `git pull`
