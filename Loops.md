# Lua Loops Tutorial

This guide covers basic loops in Lua. Loops help you repeat actions multiple times without writing the same code over and over.

## 1. `while` Loop

The `while` loop runs as long as the condition is `true`.

```lua
local count = 1

while count <= 5 do
    print("Count is:", count)
    count = count + 1
end
