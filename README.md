function start(player)
 local clasament = Instance.new('IntValue')
 clasament.Name = "leaderstats"
 clasament.Parent = player
 local scorul = Instance.new('IntValue')
 scorul.Name = 'Scor'
 scorul.Parent = clasament
end
game.Players.PlayerAdded:connect(start)
