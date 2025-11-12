# claude-code-generator
install claude-code (pre-required)
```
npm install -g @anthropic-ai/claude-code
```

then install generator via npm
```
npm install -g @gguf/claude-code-generator
```

check current version
```
ccg version
```

update generator (if outdated)
```
npm update -g @gguf/claude-code-generator
```

launch ui for settings
```
ccg ui
```

start coding
```
ccg code
```

![banner](banner.png)
*** note: start the custom server with `ccg ui` then launch to claude-code with `ccg code` instead of claude

![screenshot](https://raw.githubusercontent.com/anthropics/claude-code/master/demo.gif)
** demo gif from anthropics/claude-code

ensure the current environment is safe (i.e., offline); add this tag for auto completion
```
ccg code --dangerously-skip-permissions
```

## reference
https://github.com/calcuis/claude-code-router
