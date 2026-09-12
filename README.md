# Clean the WORLD!
**(hybrid/pro only)**

simple inf cash, auto buy & auto rebirth script.

## Features
* infinite cash (1000 Trillion)
* fully autobuys the skill tree
* auto rebirths after fully buying the skill tree

## How to use
change `local runs` to set how many times it loops/rebirths, and `local speed` to set how fast it buys.

```luau
local runs = 3
local speed = 0.05
local url = "https://raw.githubusercontent.com/3heyem/Clean-the-WORLD-/refs/heads/main/CtW?v="..tick()
local src = game:HttpGet(url)

loadstring("runs = "..runs.."\nspeed = "..speed.."\n"..src)()
```

## Support
Message @prodordie on Discord.
