AnimationId="282574440"

A=Instance.new("Animation")

A.AnimationId="rbxassetid://"..AnimationId

k=game:GetService("Workspace")[game:GetService("Players").LocalPlayer.Name]:FindFirstChild("Humanoid"):LoadAnimation(A)

k:Play()
