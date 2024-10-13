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
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/animal-simulator-/main/animal%20simulator"))()
    elseif game.PlaceId == 13110267312 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/hub-for-UW/main/README.md"))()
    elseif game.PlaceId == 1234567890 then  -- Remplace cet ID par l'ID de la nouvelle place
        loadstring(game:HttpGet("https://example.com/nouveau_script.lua"))()  -- Remplace l'URL par celle de ton script
    else
        print("ID de place non reconnu : " .. game.PlaceId)
    end
end

charger_script()  -- Appelle la fonction pour charger le script
