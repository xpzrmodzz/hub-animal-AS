local function charger_script()
    local PlaceId = game.PlaceId -- Obtient l'ID de la place actuelle

    -- Définir les scripts selon l'ID de la place
    if PlaceId == 5712833750 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/animal-simulator-/main/animal%20simulator"))()
    elseif PlaceId == 13110267312 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/hub-for-UW/main/README.md"))()
    elseif PlaceId == 5569431582 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/little-world/main/README.md"))() -- Assurez-vous que ce chemin est correct
    else
        print("ID de place non reconnu : " .. PlaceId) -- Affiche un message si l'ID n'est pas reconnu
    end
end

charger_script() -- Appelle la fonction pour charger le script
