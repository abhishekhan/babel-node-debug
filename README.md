# **NO LONGER SUPPORTED**

*Due to [official V8 DevTools debugging support via the `--inspect` flag](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27#.28zdald4m), supported by `babel-node`.*

# `babel-node-debug`

Use [`node-inspector`](https://github.com/node-inspector/node-inspector)'s [`node-debug`](https://github.com/node-inspector/node-inspector#start) command with [`babel-node`](https://babeljs.io/docs/usage/cli/#babel-node)!

Execute on any file to immediately run and inspect with Chrome Developer Tools.

## Install

```bash
npm install -g babel-node-debug
```

## Run

```bash
# Option 1
babel-node-debug path/to/file.js

# Option 2 (alias)
bode-debug path/to/file.js
```

## Happy Debugging :smile:
