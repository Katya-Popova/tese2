# test1

## hello from add Popova

Создаём репо test-remote-1
[] Add a README file

clone в ту же папку (Семинары)

cd test-remote-1

git remote -v
Увидим два пути (push и fetch)

в README добавляем вторую строку
## Hello from dev biramax

git add
git commit -m "Add second line to readme"

git remote show origin
смотрим вывод

git remote remove origin
git remote show origin
смотрим вывод
git remote -v
тоже ничего не выведет

Создаём test-remote-2
пустой, без файлов

на локале пишем
git remote add origin ссылка на второй репо

git remote -v
смотрим вывод

git push origin main
произойдёт выгрузка во второй репо

заходим на гитхаб, убеждаемся, что второй репо обновился, а в первом репо только одна строка в ридми