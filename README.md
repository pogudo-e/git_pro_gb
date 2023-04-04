# git_pro_gb

# Урок 1
```
git clone https://github.com/pogudo-e/git_pro_gb.git
```

```
cd git_pro_gb/
```

```
echo "print('hello word!')" > main.py
```

```
git add .
```

```
git commit -m 'commit'
```

```
git push
```

# Урок 2
Данное домашнее задание является продолжением домашнего задания, которое вы выполняли на предыдущем семинаре в репозитории с собственным проектом.

1. Просмотрите историю коммитов в своём проекте и выберите три случайных коммита. Просмотрите изменения, которые были в них сделаны.

```
git log
```

```
commit 15b769e9c69c61aa4b7672df86eb00937477eeb4 (HEAD -> main, origin/main, origin/HEAD)
Author: Evgeny Pogudo <sensesbit@gmail.com>
Date:   Tue Apr 4 22:05:47 2023 +0300

    lesson2 started

commit 791f5c19dd8e6a6c5d2b79fa0a312261f291e815
Author: Evgeny Pogudo <sensesbit@gmail.com>
Date:   Sat Apr 1 00:15:05 2023 +0300

    edit readme

commit b690b4990de454a9411d40c5f2e562d20fba36f5
Author: Evgeny Pogudo <sensesbit@gmail.com>
Date:   Sat Apr 1 00:13:39 2023 +0300

    commit

commit 793af0ec9d51af4044cce9b5de659d1274bfbfd4
Author: pogudo-e <94831645+pogudo-e@users.noreply.github.com>
Date:   Sat Apr 1 00:07:28 2023 +0300

    Initial commit
```

```
git diff 15b76 791f5

git diff 791f5 b690b4

git diff 791f5 793af
```

2. Верните эти изменения командой git revert последовательно, чтобы в итоге получилось тоже три коммита.

```

```