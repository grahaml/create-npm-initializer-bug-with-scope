# create-npm-initializer-bug-with-scope

This repository is a contrived example to show a potential bug that I think I found with npm 7.x.x.

## Usage

This repository contains a module that has been published to `npm` under my personal scope (@glosee). To see the bug in action try running

```
npm init @glosee/npm-initializer-bug-with-scope
```

You should get the error "could not determine executable to run"