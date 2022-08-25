# live_tests_busted.nvim

This is just quickly hacked together based on TJ's video about integrated test results in Neovim: https://www.youtube.com/watch?v=cf72gMBrsI0

Currently configured to work with vusted, a wrapper around the Lua testing framework busted (https://github.com/notomo/vusted).

## Installation
```lua
use {
  "smjonas/live-tests-busted.nvim",
  config = function()
    require("live_tests_busted")
  end,
}
```

## Usage
Requires [vusted](https://github.com/notomo/vusted).
Save a lua file that ends with `spec.lua` and you should see the diagnostics when you save the file.
