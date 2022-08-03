# bashnotes
## basic redirections
- `> filename` redirect stdout
- `>> filename` redirect stdout apending to file
- `< filename` redirect stdin
- `2> filename` redirect stderr
- `/dev/stdout` (also stderr, and stdin) for when you need to name a file, but want one of these.
- Here doc : 

```
<< end
some test
some more text
end
```

- `<<< "text message"` here string: direct the string to stdin

## substitutions
- `$name` substitute variable
- `$(command)` substitute output of command
- `$(<file)` substitute in file content: is a substitution and a redirect.
- `<(command)` substitute in name of a named-pipe that is connected to the stdout of the command.
- `>(command)` similar to above
