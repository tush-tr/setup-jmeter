# setup-jmeter
A github action that allows you to install and setup jmeter inside your github actions workflow.

## How to use in your workflow?

```yml
- name: Setup Jmeter
  uses: tush-tr/setup-jmeter@v1.1.0
```

## Example workflow

```yml
name: Test Action
on:
  push
jobs:
  test-action:
    runs-on: ubuntu-latest
    steps:
      - name: Setup Jmeter
        uses: tush-tr/setup-jmeter@v1.1.0
```
