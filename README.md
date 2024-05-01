-- Fonction pour charger le script en fonction de l'ID de place du jeu

function charger_script()
    if game.PlaceId == 5712833750 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/animal-simulator-/main/animal%20simulator"))()
    elseif game.PlaceId == 13110267312 then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xpzrmodzz/hub-for-UW/main/README.md"))()
    else
        print("ID de place non reconnu")
    end
end

-- Utilisation de la fonction pour charger le script approprié

charger_script()
