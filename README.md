# minishell

School 42 Group Project (teammate - [fechoa](https://github.com/fechoa)). Create a minimum viable version of a real shell.
<br></br>

# Final grade: 101/100

<img src="./examples/score.png" height="125" alt="Score"> <br></br>

## Shell functionality

- Builtins (`echo` with `-n` option, `cd`, `pwd`, `export`, `unset`, `env`, `exit`)
- Executables (based on `PATH` variables or relative/absolute paths)
- Pipes (`|`)
- Redirections (`<`, `>`, `<<`, `>>`)
- Signals (`ctrl-C`, `ctrl-D`, `ctrl-\`)
- Environment variables
- Exit status handling (`$?`)
- Prompt display
- History

## How to use

- Compile and launch the program:

  ```sh
   $ make
   $ ./minishell
   ```

- Clean generate files:

	```sh
	$ make fclean
	```

## Demo

  <img src="./examples/demo.gif" width="600" alt="demo">