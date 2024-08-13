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
        [13110267312] = "https://raw.githubusercontent.com/xpzrmodzz/hub-for-UW/main/README.md"
    }

    local url = scripts[game.PlaceId]

    if url then
        local success, err = pcall(function()
            loadstring(game:HttpGet(url))()
        end)

        if not success then
            warn("Erreur lors du chargement du script : " .. err)
        end
    else
        print("ID de place non reconnu : " .. game.PlaceId)
    end
end

charger_script()

