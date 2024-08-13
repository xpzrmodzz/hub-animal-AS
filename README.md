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
    else
        print("ID de place non reconnu")
    end
end

charger_script()
