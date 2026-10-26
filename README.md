return function(message)
    local args = {
        [1] = message
    }
    game:GetService("ReplicatedStorage").Remotes.ChatEvent:FireServer(unpack(args))
end
