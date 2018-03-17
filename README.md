# cmd_control

a simple control process srv, support batch, auto restart, run order.

## Example

`cmd_control` reads a yaml config file with a description of various processes to run.

example_1:

```
processes:
-
  name: hello
  command: echo 'Hello, World'
  streams: [stdout]
  restart: false

```

END.