local facts = {
	"am fluent in Lua!",
	"am learning Python!",
	"suck at sfm!",
	"have been modeling in blender for 1.5 years!",
}

local function funfact()
	print(facts[math.random(1,4)])
end

game.Workspace.aboutMe.Activated:Connect(function()
	funfact()
end)
