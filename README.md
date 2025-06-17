Сначала проверили версию git --version 
Потом mdir Galkina-Barinova, cd  Galkina-Barinova, git init инициировали репозиторий и создали папку Galkina-Barinova.
echo "Галкина Баринова">>Galkina-Barinova.txt создали файл.
git add Galkina-Barinova.txt добавили файл в индекс.
git commit -m "Первый коммит" сделали коммит файла в индексе.
git remote add origin https://github.com/dasha-7/Galkina-Barinova-2IS1 - связали созданный репозиторий на гитхабе и локальный.
Дальше git branch -M main переименовали ветку в main.
git push -u origin main сделали пуш.
