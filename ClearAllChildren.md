# ClearAllChildren
Self explanatory, can also destroy RobloxLocked. What isn't known is how to break ClearAllChildren
```Failed to fully clear all children```

```lua
game.Players.LocalPlayer.PlayerGui.ChildRemoved:Connect(function(v)
	Instance.new("Part").Parent = game.Players.LocalPlayer.PlayerGui
end)
```

# Credits

This Document was written by SylveLabs (Several, Setmetatables) without use of AI

 “All men can see the tactics whereby I conquer, but what none can see is the strategy out of which victory is evolved.”  
― Sun Tzu, The Art of War
