# Список команди

- clear (очистити весь список)
- git init (створює в новому проєкті GIT)
- git config --list
- git status
- git add . (додати всі файли)
- git commit -m "ім'я коміта" (додати коміт)
- git commit --amend -m "ім'я коміта" (змінити назву коміта)
  - git commit -a -m "ім'я коміта" (не користуватись)
- git restore --staged "ім'я файлу" (відміна змін файлу)
- git restore . (відміна останнього коміта)
- git log --pretty=format:"%h - %an, %ar - %s" (перегляд комітів)
- git reset --hard HEAD (відмінити всі зміни)
- git reset --hard HEAD~3 (відмінити коміт (~цифра - означає скільки комітів відмінити))
