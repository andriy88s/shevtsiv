1. я використав команду git clone https://github.com/andriy88s/shevtsiv.git
2. поітм використав команду git log (вивелось 3b6fa8f9a50bf731e4232996e245b67f91dd2401)
3. створив нову гілку
4. Перейшов на гілку main та перевірив, що зміни, зроблені в гілці new-branch,
не відображаються у файлі README.md. Це тому,
що зміни були зроблені в іншій гілці, і зараз ми перебуваємо в гілці master.
Я додав новий запис у файл README.md, пояснивши це:
зміни не відображаються у файлі README.md на гілці main, оскільки вони були внесені на іншу гілку new_branch.
git add README.md
git commit -m"lab_2"

commands:

git clone
git log
git new-branch
git checkout new-branch
