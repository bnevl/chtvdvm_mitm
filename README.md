Simple 'MITM' script for transferring messages between tabs @ http://chatvdvoem.ru
Only Firefox!

How to use:
1. Open and start two different chatrooms. Then disconnect by clicking 'Отключиться'.
2. Open console at the each tab. Use 'Ctrl+Shift+K' combination.
3. Copy code from 'copy_from_here' file and insert into each console.
4. Run & Enjoy.

For more, see video-overview: https://youtu.be/BUYkYj16s3k (5 min)

if bugs - restart.

p.s.

[en]: To break effects from one tab to another you need insert string 'clearInterval(time);' into console at side from which you want stop that. [ru]: В консоль вкладки, сессию которой предстоит завершить вручную без влияния на соседнюю, перед нажатием на 'Отключиться', следует без кавычек ввести 'clearInterval(time);'
