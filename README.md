# minishell
### from [@byte-pusher](https://github.com/byte-pusher) and [@gjupy](https://github.com/gjupy)<br>

### The basic structure of our minishell
Just like most of the other shells we have divided our shell into 4 parts:
1. [Lexer](https://github.com/gjupy/minishell/tree/main/lexer)
2. [Parser](https://github.com/gjupy/minishell/tree/main/parser)
3. [Expander](https://github.com/gjupy/minishell/tree/main/expander)
4. [Executor](https://github.com/gjupy/minishell/tree/main/executor)

### Usage
- this is a shell that can be compiled by running<br>`make`<br>and then to run it<br>`./minishell`<br>or instead you can run<br>`make test`
- now you are greeted with a prompt `teshno-1.0$ `&nbsp;waiting for input just like any other shell
- this project uses the readline libraries `readline/history.h` and `readline/readline.h` you can install those via `brew install readline` or `apt-get install libreadline-dev`, thanks to those there is a working history of used commands
- there is some memory-leaks caused by the readline-library

### Helpful ressources we used
- [Rodriguez-Rivera; Ennen (2014): Introduction to Systems Programming - chapter 5](https://www.cs.purdue.edu/homes/grr/SystemsProgrammingBook/Book/Chapter5-WritingYourOwnShell.pdf)
- [The Open Group Base Specifications Issue 6 (2004)](https://pubs.opengroup.org/onlinepubs/009695399/utilities/xcu_chap02.html)
- [Brennan (2015): Tutorial - Write a shell in C](https://brennan.io/2015/01/16/write-a-shell-in-c/)
