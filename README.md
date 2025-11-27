# 🐚 Minishell Project
*As beautiful as a shell*

## 📝 Overview
Create a simple shell in C, similar to bash. Learn about **processes**, **file descriptors**, and building a functional command-line interface.

## 📖 Project Description
- Display a prompt for new commands.
- Maintain command history.
- Execute commands using PATH, relative, or absolute paths.
- Minimal use of global variables (1 maximum).
- Handle single (') and double (") quotes properly.
- Support environment variables ($VAR) and $? for exit status.

### Redirections
- `<` input redirection
- `>` output redirection
- `>>` append output
- `<<` heredoc input

### Pipes
- Support `|` to chain commands.

### Built-in Commands
- `echo -n`
- `cd`
- `pwd`
- `export`
- `unset`
- `env`
- `exit`

### Signal Handling
- Ctrl-C: new prompt
- Ctrl-D: exit shell
- Ctrl-\: ignored

## 💡 Key Concepts Learned
- Forking processes and executing programs.
- Managing input/output using file descriptors.
- Handling pipes and redirections.
- Working with environment variables.
- Implementing a command-line interface with readline.
- Signal handling and interactive user input.

## 🛠️ Compilation and Usage
```
make
./minishell
```
The shell supports interactive mode with prompts and command history, as well as proper handling of built-ins, pipes, and redirections.
