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
    if game.PlaceId == 5712833750 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/animal-simulator-/refs/heads/main/animal%20simulator"))()
    elseif game.PlaceId == 13110267312 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/hub-for-UW/main/README.md"))()
    elseif game.PlaceId == 5569431582 then  -- Remplace ceci par l'ID du nouveau jeu
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/little-world/refs/heads/main/README.md"))()
    elseif game.PlaceId == 16432271978 then  -- Remplace ceci par l'ID du nouveau jeu
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/aninal-adventure/refs/heads/main/README.md"))()
    elseif game.PlaceId == 3823781113 then  -- Remplace ceci par l'ID du nouveau jeu
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/saber-simultor/refs/heads/main/README.md"))()
    elseif game.PlaceId == 6273865312 then  -- Remplace ceci par l'ID du nouveau jeu
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/Supernatural-Simulator/refs/heads/main/README.md"))()
            elseif game.PlaceId == 16732694052 then  -- Remplace ceci par l'ID du nouveau jeu
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/fisch/refs/heads/main/fisch"))()
    else
        print("ID de place non reconnu : " .. game.PlaceId)
    end
end
charger_script()
