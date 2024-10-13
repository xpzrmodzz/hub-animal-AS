--[[ 
 ________  _______   ______  ________  ________ 
|        \|       \ |      \|        \|        \
| $$$$$$$$| $$$$$$$\ \$$$$$$ \$$$$$$$$| $$$$$$$$
| $$__    | $$__| $$  | $$     | $$   | $$__    
| $$  \   | $$    $$  | $$     | $$   | $$  \   
| $$$$$   | $$$$$$$\  | $$     | $$   | $$$$$   
| $$      | $$  | $$ _| $$_    | $$   | $$_____ 
| $$      | $$  | $$|   $$ \   | $$   | $$     \
 \$$       \$$   \$$ \$$$$$$    \$$    \$$$$$$$$ 
]]--

function charger_script()
    local scripts = {
        [5712833750] = "https://raw.githubusercontent.com/xpzrmodzz/animal-simulator-/main/animal%20simulator",
        [13110267312] = "https://raw.githubusercontent.com/xpzrmodzz/hub-for-UW/main/README.md",  -- À vérifier
        [5569431582] = "https://raw.githubusercontent.com/xpzrmodzz/little-world/refs/heads/main/README.md"  -- À vérifier
    }
    
    local scriptUrl = scripts[game.PlaceId]
    
    if scriptUrl then
        local success, err = pcall(function()
            loadstring(game:HttpGet(scriptUrl))()
        end)
        
        if not success then
            warn("Erreur lors du chargement du script : " .. err)
        end
    else
        print("ID de place non reconnu : " .. game.PlaceId)
    end
end

charger_script()
