# gunashree
new repo
steps:
- uses: actions/checkout@v3

- run: mkdir -p path/to/artifact

- run: echo hello > path/to/artifact/world.txt

- uses: actions/upload-artifact@v3
  with:
    name: guna
    path: path/to/artifact/world.txt
