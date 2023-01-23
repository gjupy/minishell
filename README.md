# minishell
### Recreation of some of the functionalities of bash (Version 3.2).<br>
### from [@byte-pusher](https://github.com/byte-pusher) and [@gjupy](https://github.com/gjupy)<br>

## Our Minishell
### The basic functionalities of the project
- this is a shell that can be compiled by running<br>`make all`<br>and then to run it<br>`./minishell`<br>or instead you can run<br>`make run`
- now you are greeted with a prompt `minishell$ `&nbsp;waiting for input just like any other shell
- this project uses the readline libraries `readline/history.h` and `readline/readline.h` you can install those via `brew install readline` or `apt-get install libreadline-dev`, thanks to those there is a working history of used commands
- there is some memory-leaks caused by the readline-library

### The basic structure of our minishell
Just like most of the other shells we have divided our shell into 4 parts:
1. [Lexer](https://github.com/toni-schmitt/minishell#lexer)
2. [Parser](https://github.com/toni-schmitt/minishell#parser)
3. [Expander](https://github.com/toni-schmitt/minishell#expander)
4. [Executor](https://github.com/toni-schmitt/minishell#executor)
