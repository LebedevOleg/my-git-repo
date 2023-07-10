# my-git-repo

###### _Тренировочный репозиторий_

# Задачи

> ### <input type="checkbox" checked disabled > 1. Создать репозиторий и добавить в него README файл
>
> > _Репозиторий был создан с помощью сайта github_

> ### <input type="checkbox" checked disabled > 2.Клонирование репозитория на своё устройство
>
> > **_Для клонирования нужно ввести команду:_**
> >
> > ```
> > git clone https://github.com/LebedevOleg/my-git-repo.git
> > ```

> ### <input type="checkbox" checked disabled > 3. Добавление файлов и коммит
>
> > В файл README было добавлено описание первых 3 заданий
> >
> > <p>Для просмотра статуса: `git status` <p>
> > Для добавления измененных файлов `git add .` <p> 
> > Чтобы зафиксировать изменения с сообщением `git commit -m  "update README.md"`
> > Далее добавлены еще несколько коммитов с файлом README

> ### <input type="checkbox" checked disabled > 4. Использование `.gitignore`:
>
> > был создан файл _log.txt_ <p>
> > был создан файл _notes.txt_ <p>
> > был создан файл _.gitignore_ и в него была добавлена строка
> >
> > ```
> > log.txt
> > ```
> >
> > Далее _.gitignore_ был добавлен в репозиторий <p>
> > Результат команды `git status` показывал только файл _notes.txt_
> >
> > ```
> > On branch main
> > Your branch is up to date with 'origin/main'.
> >
> > Untracked files:
> > (use "git add <file>..." to include in what will be committed)
> >      notes.txt
> >
> > nothing added to commit but untracked files present (use "git add" to track)
> > ```

> ### <input type="checkbox" checked disabled > 5. Слияние веток и разрешение конфликтов:
>
> > была создана ветка **_feature-branch_** в которую был добавлен файл _index.html_ <p>
> > В этот файл были записаны некие данные и ветка была опубликована <p>
> > Далее в ветке **_main_** так же был создан файл _index.html_
> > но в него были записаны уже другие данные
> > при попытке сделать merge:
> >
> > ```
> > git merge feature-branch
> > ```
> >
> > была получена ошибка из-за конфликта файлов <p>
> > в IDE VisualStudio Code была проведена операция по разрешению конфликта
> > и в основную ветку были добавлены изменения из соседней ветки
