# Найдите полный хеш и комментарий коммита, хеш которого начинается на aefea

commit aefead2207ef7e2aa5dc81a34aedf0cad4c32545

Update CHANGELOG.md

# Какому тегу соответствует коммит 85024d3?

commit 85024d3100126de36331c6982bfaac02cdab9e76 (tag: v0.12.23)

Сколько родителей у коммита b8d720? Напишите их хеши.
3 родителя

b8d720f8340221f2146e4e4870bf2ee0bc48f2d5 

56cd7859e05c36c06b56d013b55a252d0bb7e158 

9ea88f22fc6269854151c571162c5bcf958bee2b

# Перечислите хеши и комментарии всех коммитов, которые были сделаны между тегами v0.12.23 и v0.12.24.

commit 33ff1c03bb960b332be3af2e333462dde88b279e (tag: v0.12.24)

Author: tf-release-bot terraform@hashicorp.com

Date:   Thu Mar 19 15:04:05 2020 +0000

    v0.12.24

commit b14b74c4939dcab573326f4e3ee2a62e23e12f89

Author: Chris Griggs cgriggs@hashicorp.com

Date:   Tue Mar 10 08:59:20 2020 -0700

    [Website] vmc provider links

commit 3f235065b9347a758efadc92295b540ee0a5e26e

Author: Alisdair McDiarmid alisdair@users.noreply.github.com

Date:   Thu Mar 19 10:39:31 2020 -0400

    Update CHANGELOG.md

commit 6ae64e247b332925b872447e9ce869657281c2bf

Author: Alisdair McDiarmid alisdair@users.noreply.github.com

Date:   Thu Mar 19 10:20:10 2020 -0400

    registry: Fix panic when server is unreachable

    Non-HTTP errors previously resulted in a panic due to dereferencing the
    resp pointer while it was nil, as part of rendering the error message.
    This commit changes the error message formatting to cope with a nil
    response, and extends test coverage.

    Fixes #24384

commit 5c619ca1baf2e21a155fcdb4c264cc9e24a2a353
Author: Nick Fagerlund nick.fagerlund@gmail.com

Date:   Wed Mar 18 12:30:20 2020 -0700

# Найдите коммит, в котором была создана функция func providerSource, её определение в коде выглядит так: func providerSource(...) (вместо троеточия перечислены аргументы).

commit 5af1e6234ab6da412fb8637393c5a17a1b293663

commit 8c928e83589d90a031f811fae52a81be7153e82f


# Найдите все коммиты, в которых была изменена функция globalPluginDirs.

commit 7c4aeac5f30aed09c5ef3198141b033eea9912be

Author: Liam Cervante liam.cervante@hashicorp.com

Date:   Tue Nov 5 16:13:08 2024 +0100

commit 65c4ba736375607b6af6c035972f7f151232b6c6

Author: Valeriy Pastushenko i@combin.name

Date:   Sat May 21 19:53:24 2022 +0300

commit 125eb51dc40b049b38bf2ed11c32c6f594c8ef96

Author: Alisdair McDiarmid alisdair@users.noreply.github.com

Date:   Thu May 5 10:12:00 2022 -0400

commit 22c121df8631c4499d070329c9aa7f5b291494e1

Author: Anna Winkler 3526523+annawinkler@users.noreply.github.com

Date:   Tue May 3 12:28:41 2022 -0600

# Кто автор функции synchronizedWriters?
Author: Martin Atkins <mart@degeneration.co.uk>
