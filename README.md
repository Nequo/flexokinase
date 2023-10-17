# Flexokinase

Flexokinase is a minimal colorscheme based on [Flexoki](https://github.com/kepano/flexoki).
It comes in a light and a dark variant based on `vim.opt.background`. You can use the following in your config to switch theme depending on the time of day:

```lua
local hr = tonumber(os.date('%H', os.time()))
if hr > 6 and hr < 21 then -- day between 6am and 9pm
  vim.opt.background = 'light'
else -- night
  vim.opt.background = 'dark'
end
```

## Screenshot

