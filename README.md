# proveeeeee
#
name: Test

on: [push, workflow_dispatch]

jobs:
  test:
    name: Test
    runs-on: ubuntu-latest

    steps:
      - run: echo "Hello world"
