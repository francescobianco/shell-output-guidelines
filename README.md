# Shell Output Guidelines

> Discussion about shell output

[![Markdown](https://github.com/francescobianco/shell-output-guidelines/actions/workflows/markdown.yml/badge.svg)](https://github.com/francescobianco/shell-output-guidelines/actions/workflows/markdown.yml)
[![Spellcheck](https://github.com/francescobianco/shell-output-guidelines/actions/workflows/spellcheck.yml/badge.svg)](https://github.com/francescobianco/shell-output-guidelines/actions/workflows/spellcheck.yml)

The purpose of this repository is collect and discuss guidelines, rules, suggestion for presenting output in a shell (Looking for the best way or a standard way todo).
The mission is define the right way to use something like `...` at the end of a sentence to notify user for on-going process and stuff like that.

## Candidate Topics

- Use of pseudo plural with `/s` in counted elements (eg. `The are 1 item/s on the list`)
- Use symbol at the beginning of each line of output (eg. `>>> This is a message`)

## Questions

1. Use full-stop in sentences of a shell output messages?

```
$ command run --process
Processing is stated...
Process is done.
```

## Defining Process

Guidelines growth from a Topics synthesys, We put in place a Decisioning/Definining process based on facts extracted from Decision Tools results. Enteire Defining Process is described in the following file

- [GUIDELINES.md](GUIDELINES.md)

## Decision Tools

Decisions tools are described and repeatable actions that can be administered and performed by users or developers to add value and knowledge. So that they can make decisions based on their results.

- [SCORECARD.md](SCORECARD.md)
