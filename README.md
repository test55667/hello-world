name: shell commands

on: [Push]

Jobs:
  run-shell-commands:
    runs-on: ubentu-latest
    steps:
      - name: echo a string
        run: echo "hello world"
      - name: multiple string
        run: |
          node -v
          npm -v
