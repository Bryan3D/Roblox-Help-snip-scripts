
# Welcome to Roblox Snippet Codes to helping others

## General Counter code snippet

``` 
local textLabel = script.Parent.TextLabel
 for i=5,0,-1  do
	
	textLabel.Text = i
	wait(1)
	
end 

```

## Bomb
```
local explodingPart = workspace.Bomb

local function explodeBomb(part)
	local explosion = Instance.new("Explosion")
	explosion.Position = part.Position print("Exploding")
	explosion.Parent = explodingPart
end

wait(7)

explodeBomb(explodingPart)

```
