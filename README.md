# Rebase

  Второй способ объединения изменений **git rebase**.  
  Объединять ваши ветки можно не только командой **git merge** но и командой **git rebase**.
  Многие могут спросить, зачем второй способ. Все дело в том как происходит объединение изменений. 
  Помните я говорил, что результатом мержа будет новый коммит? Так вот при *rebase* все коммиты 
  перенесутся в ветку последовательно, как будто разработка велась в одной ветке.  
  Давайте попробуем на практике.


## Задание 

1. **Работа ведется в вашей основной ветке**
2. **Обязательно** просмотрите структуру коммитов в ветке *dev-task_4* и в вашей основной ветке
3. Перейдите на ветку *dev-task_4* и выполните команду *git rebase <name_surname>*
4. **Обязательно** просмотрите структуру коммитов в вашей основной ветке. В каждом коммите будет
   по одной строке стихотворения. Теперь у вас есть 3 столбца, нашего стихотворения
   
## На что обратить внимание
1. На разницу выполнения команд:
    * *git merge* выполняется на ветке **в** которую вы хотите вмержить, 
    * *git rebase* на ветке **которую** вы хотите перенести
2. На итоговую историю коммитов:
    * при *merge* результат две ветки с общим коммитом мержа
    * при *rebase* результат все коммиты располагаются линейно
    
## Что использовать?
  В описанных случаях слияния есть как свои преимущества, так и свои недостатки. Данная тема 
  очень обширна и для использования того или иного способа могут быть различные предпосылки. 
  В любом случае надо уметь использовать оба, т.к. в разных командах или на разных проектах 
  вас могут попросить использовать какой-либо конкретный способ.
