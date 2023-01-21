# First seminar

> + __git init__ – инициализация локального репозитория
> + **git status** – получить информацию от git о его _**текущем**_ состоянии
> - __git add__ – добавить файл или файлы к следующему коммиту
> - __git commit -m “message”__ – создание коммита

<br>
<br>

# Second seminar

> 5. **git log** – вывод на экран истории всех коммитов с их хеш-кодами
> 6. **git branch** – посмотреть список веток в репозитории
> 7. **git branch <название ветки>** – создать новую ветку
> 8. __git checkout <название ветки>__ – переход к другой ветке
> 9. **git branch -d <название ветки>** – удалить ветку

### <code> New AMAZING second seminar's git commands: </code>

     11. __git add .__ — добавить __*все*__ файлы из репозитория к отслеживанию.

     12. __git commit -am "комментарий"__ - обьединение команд *"git add ..."* и *"git commit -m ..."*; т.е. файл одновременно добавляется к отслеживанию и коммитится.

     13. __git log --graph__ - лог в виде дерева, где *"--graph"* это параметр.

     14. __git checkout -b branch_name__ - создать и перейти в новую ветку, где *"-b"* это параметр *"branch"*.

     15. **git merge name_branch** - слияние двух веток и подстановка на место **_текущей_** ветки.

     16. **git merge --abort** - отмена слияния (при конфликте).

<br>

___
<details>
<summary>
Play with images and links
</summary>

> ___
>![Is_that_poop_image?](poop.png)
> — Oh nah, is that poop emoji? It's so uncivilized!
> 
> — Yeahhh, that's it! And take the [3D-model link](https://clck.ru/33JsAL) too.
> 
> — Oh Gosh, you are abnormal.

</details>

___

<details>
<summary>
Тест отмены слияния
</summary>

> Тут, на 45-й строке в ветке master должен возникнуть конфликт и текстом из ветки test_aborting. Посмотрим к чему это приведёт.
>
> ___
>
> Текст, который должен конфликтовать, записаный на 45 строке в ветке test_aborting
>
> > ## Тест отмены пройден.
> ### Затем при возникшем конфликте оставлены обе строки.
</details>

___

<br>
<br>
<br>

# Third seminar

> 17. __git clone <url-адрес репозитория>__ – клонирование внешнего репозитория на  локальный ПК
> 18. __git pull__ – получение изменений и слияние с локальной версией
> 19. __git push__ – отправляет локальную версию репозитория на внешний
> 20. **git remote rm origin** - удалить
> 21. **git remote add origin https://github.com/microsindotnet/gitnew** - добавить
> 22. **git remote set-url origin https://github.com/microsindotnet/gitnew** - заменить