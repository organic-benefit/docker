### What is the tty?


example

 `$docker exec -t -i 589f2ad30138 /bin/bash`

- t : Allocate a pseudo-TTY
- i : Keep STDIN open even if not attached

pseudo-TTY? - https://mug896.gitbooks.io/shell-script/content/tty.html

- TTY의 이름은 [TeleTYpe](https://en.wikipedia.org/wiki/Teleprinter)에서 유래되었다.
- 외부 터미널 장치와 연결하기 위해 사용된다.
- 가상(pseudo) TTY는 가상의 터미널을 emulation하는 것을 말한다.

 - 쉘과 가상의 터미널을 연결

 - xterm, telnet, ssh 등
