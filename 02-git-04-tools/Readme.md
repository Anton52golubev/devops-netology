## 1) Найдите полный хеш и комментарий коммита, хеш которого начинается на aefea.
## Ответ:
Полный хэш - "aefead2207ef7e2aa5dc81a34aedf0cad4c32545"<br>
Комментарий коммита - "Update CHANGELOG.md"<br>
Команда - "git show aefea"
	
## 2) Какому тегу соответствует коммит 85024d3?
## Ответ:
v0.12.23<br>
Команда - "git show -s 85024d3"<br>

## 3) Сколько родителей у коммита b8d720? Напишите их хеши.
## Ответ:
"56cd7859e05c36c06b56d013b55a252d0bb7e158"<br>
"9ea88f22fc6269854151c571162c5bcf958bee2b"<br>
Команда - "git show --pretty=%P b8d720"<br>

## 4) Перечислите хеши и комментарии всех коммитов, которые были сделаны между тегами v0.12.23 и v0.12.24.
## Ответ:
Команда - "git show -s v0.12.23..v0.12.24"<br>

commit 33ff1c03bb960b332be3af2e333462dde88b279e (tag: v0.12.24)<br>
Author: tf-release-bot <terraform@hashicorp.com><br>
Date:   Thu Mar 19 15:04:05 2020 +0000<br>

    v0.12.24<br>

commit b14b74c4939dcab573326f4e3ee2a62e23e12f89<br>
Author: Chris Griggs <cgriggs@hashicorp.com><br>
Date:   Tue Mar 10 08:59:20 2020 -0700<br>

    [Website] vmc provider links<br>

commit 3f235065b9347a758efadc92295b540ee0a5e26e<br>
Author: Alisdair McDiarmid <alisdair@users.noreply.github.com><br>
Date:   Thu Mar 19 10:39:31 2020 -0400<br>

    Update CHANGELOG.md<br>

commit 6ae64e247b332925b872447e9ce869657281c2bf<br>
Author: Alisdair McDiarmid <alisdair@users.noreply.github.com><br>
Date:   Thu Mar 19 10:20:10 2020 -0400<br>

    registry: Fix panic when server is unreachable<br>

    Non-HTTP errors previously resulted in a panic due to dereferencing the<br>
    resp pointer while it was nil, as part of rendering the error message.<br>
    This commit changes the error message formatting to cope with a nil<br>
    response, and extends test coverage.<br>

    Fixes #24384<br>

commit 5c619ca1baf2e21a155fcdb4c264cc9e24a2a353<br>
Author: Nick Fagerlund <nick.fagerlund@gmail.com><br>
Date:   Wed Mar 18 12:30:20 2020 -0700<br>

    website: Remove links to the getting started guide's old location<br>

    Since these links were in the soon-to-be-deprecated 0.11 language section, I<br>
    think we can just remove them without needing to find an equivalent link.<br>

commit 06275647e2b53d97d4f0a19a0fec11f6d69820b5<br>
Author: Alisdair McDiarmid <alisdair@users.noreply.github.com><br>
Date:   Wed Mar 18 10:57:06 2020 -0400<br>

    Update CHANGELOG.md<br>

commit d5f9411f5108260320064349b757f55c09bc4b80<br>
Author: Alisdair McDiarmid <alisdair@users.noreply.github.com><br>
Date:   Tue Mar 17 13:21:35 2020 -0400<br>

    command: Fix bug when using terraform login on Windows<br>

commit 4b6d06cc5dcb78af637bbb19c198faff37a066ed<br>
Author: Pam Selle <pam@hashicorp.com><br>
Date:   Tue Mar 10 12:04:50 2020 -0400<br>

    Update CHANGELOG.md<br>

commit dd01a35078f040ca984cdd349f18d0b67e486c35<br>
Author: Kristin Laemmert <mildwonkey@users.noreply.github.com><br>
Date:   Thu Mar 5 16:32:43 2020 -0500<br>

    Update CHANGELOG.md<br>

commit 225466bc3e5f35baa5d07197bbc079345b77525e<br>
Author: tf-release-bot <terraform@hashicorp.com><br>
Date:   Thu Mar 5 21:12:06 2020 +0000<br>

    Cleanup after v0.12.23 release<br>

    Update CHANGELOG.md<br>

commit d5f9411f5108260320064349b757f55c09bc4b80<br>
Author: Alisdair McDiarmid <alisdair@users.noreply.github.com><br>
Date:   Tue Mar 17 13:21:35 2020 -0400<br>

    command: Fix bug when using terraform login on Windows<br>

commit 4b6d06cc5dcb78af637bbb19c198faff37a066ed<br>
Author: Pam Selle <pam@hashicorp.com><br>
Date:   Tue Mar 10 12:04:50 2020 -0400<br>

    Update CHANGELOG.md<br>

commit dd01a35078f040ca984cdd349f18d0b67e486c35<br>
Author: Kristin Laemmert <mildwonkey@users.noreply.github.com><br>
Date:   Thu Mar 5 16:32:43 2020 -0500<br>

    Update CHANGELOG.md<br>

commit 225466bc3e5f35baa5d07197bbc079345b77525e
Author: tf-release-bot <terraform@hashicorp.com>
Date:   Thu Mar 5 21:12:06 2020 +0000

    Cleanup after v0.12.23 release
(END)
    Update CHANGELOG.md

commit d5f9411f5108260320064349b757f55c09bc4b80<br>
Author: Alisdair McDiarmid <alisdair@users.noreply.github.com><br>
Date:   Tue Mar 17 13:21:35 2020 -0400<br>

    command: Fix bug when using terraform login on Windows<br>

commit 4b6d06cc5dcb78af637bbb19c198faff37a066ed<br>
Author: Pam Selle <pam@hashicorp.com><br>
Date:   Tue Mar 10 12:04:50 2020 -0400<br>
<br>
    Update CHANGELOG.md<br>

commit dd01a35078f040ca984cdd349f18d0b67e486c35<br>
Author: Kristin Laemmert <mildwonkey@users.noreply.github.com><br>
Date:   Thu Mar 5 16:32:43 2020 -0500<br>

    Update CHANGELOG.md<br>

commit 225466bc3e5f35baa5d07197bbc079345b77525e<br>
Author: tf-release-bot <terraform@hashicorp.com><br>
Date:   Thu Mar 5 21:12:06 2020 +0000<br>

    Cleanup after v0.12.23 release<br>

## 5) Найдите коммит, в котором была создана функция func providerSource, её определение в коде выглядит так: func providerSource(...) (вместо троеточия перечислены аргументы).
## Ответ:
8c928e83589d90a031f811fae52a81be7153e82f<br>
Команда - "git log -S "func providerSource(""<br>

## 6) Найдите все коммиты, в которых была изменена функция globalPluginDirs.
## Ответ:
78b1220558 Remove config.go and update things using its aliases<br>
52dbf94834 keep .terraform.d/plugins for discovery<br>
41ab0aef7a Add missing OS_ARCH dir to global plugin paths<br>
66ebff90cd move some more plugin search path logic to command<br>
8364383c35 Push plugin discovery down into command package<br>

Команда - "git grep "func globalPluginDirs(" - находим файл с данной функцией"<br>
          "git log -s -L :globalPluginDirs:plugins.go --oneline - находим коммит<br>

## 7) Кто автор функции synchronizedWriters?
## Ответ
Martin Atkins <mart@degeneration.co.uk><br>

Команда - "git log -S"func synchronizedWriters(" - ищем коммит"<br>
          "git show 5ac311e2a91e381e2f52234668b49ba670aa0fe5 - просматриваем коммит и смотрим автора"<br>

