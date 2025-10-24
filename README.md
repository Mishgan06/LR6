# LR6
Лабораторная работа №6
**Цель лабораторной работы**: изучение базовых возможностей системы управления версиями, опыт работы с Git API, опыт работы с локальным и удалённым репозиторием.

**Ход работы**
1. Клонирование репозитория, настройка клиента git, создание текстового файла, первого коммита с ним и выгрузка коммита на локальный репозиторий
<img width="697" height="540" alt="image" src="https://github.com/user-attachments/assets/41cd8edc-ba46-4050-a9a4-4a9f9c5ef4dc" />
<img width="634" height="431" alt="image" src="https://github.com/user-attachments/assets/514c6ff3-e839-4f75-8d15-555304ab597d" />
<img width="846" height="971" alt="image" src="https://github.com/user-attachments/assets/7e4b27f4-73c1-4c1d-b630-6d003c531639" />

2.Создание новой ветки и обзор изменений в ней, а также созданние коммита
<img width="742" height="972" alt="image" src="https://github.com/user-attachments/assets/f3dd8c2e-6d99-431c-83a7-c7d37da2a5c1" />
<img width="811" height="499" alt="image" src="https://github.com/user-attachments/assets/a18906db-dc75-4e6b-8b3b-8704aa3ca240" />

3.Удаление созданной ветки
<img width="483" height="80" alt="image" src="https://github.com/user-attachments/assets/b7398d2c-d17c-44a0-b2b1-b1a3566ccdbc" />

4.Просмотр комиитов
<img width="856" height="511" alt="image" src="https://github.com/user-attachments/assets/7b3a8d59-37ea-4a19-a058-e93f10b2b8e5" />
<img width="672" height="492" alt="image" src="https://github.com/user-attachments/assets/f974cd45-7b2f-44f4-88ce-dd49866116da" />

5.Были внесены другие изменения в репозиторий: добавлена картинка. А также просмотр коммитов
<img width="821" height="584" alt="image" src="https://github.com/user-attachments/assets/2f7431eb-a715-45ef-86f0-b7444dc98072" />
<img width="793" height="917" alt="image" src="https://github.com/user-attachments/assets/83da15e4-e93b-4c76-aefd-533f98a1a747" />

6.Был добавлен существующий файл с изменениями, а два других файла были удалены. После чего был сделан коммит. Затем был создан коммит с добавлением картинки, который впоследствии был откатан.
<img width="546" height="169" alt="image" src="https://github.com/user-attachments/assets/2ac8b114-3909-42df-a1b5-b46b4461e7ab" />
<img width="962" height="1078" alt="image" src="https://github.com/user-attachments/assets/3f858ed8-851a-4016-942a-b175fbf8193b" />
<img width="954" height="328" alt="image" src="https://github.com/user-attachments/assets/96181976-f787-4af0-8b1c-2750e4d840d4" />

7.Всплывающее окно при откате коммита
<img width="1243" height="1004" alt="image" src="https://github.com/user-attachments/assets/4703b338-f2e7-4519-8617-c229f230b278" />

8.Просмотр коммитов
<img width="1013" height="727" alt="image" src="https://github.com/user-attachments/assets/a7b036b2-108b-4d2e-a0cc-0f1f7bb936ed" />
<img width="935" height="472" alt="image" src="https://github.com/user-attachments/assets/c1d0d18b-a40b-4f4b-8fdf-5d9b65563970" />

9.Создаение ветки для отчёта и файла README.md
<img width="452" height="123" alt="image" src="https://github.com/user-attachments/assets/e8621139-7c2e-4066-96ff-1cd4eadaf487" />
<img width="904" height="974" alt="image" src="https://github.com/user-attachments/assets/73d0be60-a2f7-4a54-8892-1c49b49cb649" />

10.Добавление папки со скриншотами
<img width="761" height="706" alt="image" src="https://github.com/user-attachments/assets/1567c12c-f0a0-455e-9096-345b196bac1a" />

11.История операций в форматированном виде, где:
-%h — это сокращённый хеш коммита.
*%an — это имя автора коммита.
+%ar — это время, прошедшее с момента коммита.
-%s — это сообщение коммита.

<img width="791" height="277" alt="image" src="https://github.com/user-attachments/assets/43d47610-bf94-40fe-9361-78a19af45534" />

**Лог команд**
>git clone
>git add
>git commit -m
>git push
>git show *хэш коммита*
>git branch
>git checkout
>git log
>git merge
>git branch -d
>git rm
>git revert HEAD
>git push --set-upstream origin 
>git log --pretty=format:"%h - %an, %ar : %s"

**Вывод**
>В данной лабораторной работе были изучены базовые возможности системы управления версиями, был получен опыт работы с Git Api и опыт работы с локальным и удаленным репозиторие, также был получен опыт работы с >Markdown
