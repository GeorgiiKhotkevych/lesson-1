# lesson-1

1. Create a repo on GitHub (or GitLab/Bitbucket) that contains a markdown file with chapter “18.6 Commit best practices” https://r-pkgs.org/git.html

2. go to course https://githowto.com/uk

Как сделал:
1. Скачал содержимое div id="commit-best-practices" со страницы https://r-pkgs.org/git.html используя Chrome DevTools
2. Исполльзовал конвертор HTML to Markdown https://codebeautify.org/html-to-markdown
3. Проверил внешний вид md файла используя Markdown Preview в редакторе Atom
4. Создал на GitHub репозиторий lesson-1 и скопировал ссылку для кллонирования по HTTPS https://github.com/GeorgiiKhotkevych/lesson-1.git
5. git clone https://github.com/GeorgiiKhotkevych/lesson-1.git
6. cd lesson-1
7. nano 'Commit best practices.md'
8. Вставил markdown текст, ctrl+x y
9. git add .
10. git commit -m "Create markdown file with chapter 18.6"
11. git push origin
12. Создал токен для доступа в GitHub
13. Имя пользователи и токен вместо пароля

Какие проблемы:
1. Долго думал как можно вытянуть конкретный div со страницы в файл. Не придумал. Нужно спросить.
2. Никогда не работал с markdown, использовал онлайн сервис для конвертации html в markdown.
3. Токен для GitHub не был описан в инструкции которой я пользовался для выполнения задания

Что нового узнал:
1. Markdown
2. Как подключить локальный git к GitHub по https
3. Как делать push и clone
