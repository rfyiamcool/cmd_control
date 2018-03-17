# cmd_control

a simple control process srv, support batch, auto restart, run order.

## Example

example_1:

*test.yaml*

```
processes:
-
  name: hello
  command: echo 'Hello, World'
  streams: [stdout]
  restart: false

```

END.