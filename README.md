# bootsys
Для "Способ 1. init=/bin/sh" приходится рутовую систему еще монтировать в роежим Read-Write дополнительно (mount -o remount,rw /)
В "Способ 2. rd.break"- тоже приходится рутовую систему еще монтировать в роежим Read-Write дополнительно (mount -o remount,rw /)
В "Способ 3. rw init=/sysroot/bin/sh" сразу монтируется в режим Read-Write.

В скрипте для драката вместо пингвина вывел "KU". На скриншоте "KU!!!" это видно.
