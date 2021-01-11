# Cherry Pick

Существует еще один способ, слияния это *сherry pick*

# Что это? Зачем?
  Данный способ позволяет объединять вам не всю ветку, а только выборочные коммиты. Это 
  бывает достаточно удобно когда в каком-то коммите реализована нужная фича, но сама ветка 
  в стадии разработки.  
  Можно скопировать код, но представьте сложную реализацию, когда работа велась во множестве 
  файлов?

## Задание 
1. **Работа ведется в вашей основной ветке**
2. Перейдите на вашу основную ветку и выполните команду **git cherry-pick commit**. Где 
   *commit* имя или хэш необходимого вам коммита. В нашем случае это *4th paragraph* и 
   *5th paragraph* из ветки **dev-task_5**
3. В результате на вашей ветке появятся коммиты с соответствующими абзацами.
4. Отправьте изменения в свой удаленный репозиторий, и сделайте PR.
5. Сообщите своему наставнику, о выполнении задания.

## На что обратить внимание
1. Обязательно посмотрите структуру коммитов в ветке  **dev-task_5**.
2. Обязательно посмотрите на структуру вашей основной ветки **до** и **после** сherry pick.
3. Команда сherry pick выполняется **на ветке в которую вы переносите** коммиты.

