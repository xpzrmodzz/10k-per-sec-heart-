--create by FRITE--
while true do wait()
local args = {
    [1] = {
        ["action"] = "heart",
        ["reward"] = "ValOctopus2"
    }
}

game:GetService("ReplicatedStorage").DamageEvent:FireServer(unpack(args))
end
