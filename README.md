# myproject
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Formulaire</title>
</head>
<body>
    <form>
        <fieldset>
            <legend>Vos coordonnées</legend>
            <label for="nom">Nom* :</label>
            <input type="text" id="nom" name="nom" placeholder="votre nom" required><br><br>

            <label for="prenom">Prénom* :</label>
            <input type="text" id="prenom" name="prenom" placeholder="votre prénom" required><br><br>

            <label for="date_naissance">Date de naissance :</label>
            <input type="text" id="date_naissance" name="date_naissance" placeholder="jj/mm/aaaa"><br><br>

            <label for="mail">Mail :</label>
            <input type="email" id="mail" name="mail" placeholder="votre mail"><br><br>

            <label for="site">Votre site :</label>
            <input type="url" id="site" name="site" placeholder="http://www."><br><br>

            <label for="code">Code :</label>
            <input type="text" id="code" name="code"><br><br>

            <label>Genre :</label>
            <input type="radio" id="homme" name="genre" value="homme">
            <label for="homme">Homme</label>
            <input type="radio" id="femme" name="genre" value="femme">
            <label for="femme">Femme</label><br><br>

            <label for="pays">Votre pays :</label>
            <select id="pays" name="pays">
                <option value="">Sélectionnez</option>
                <option value="france">France</option>
                <option value="belgique">Belgique</option>
                <option value="suisse">Suisse</option>
                <!-- Add more countries as needed -->
            </select>
        </fieldset>
    </form>
</body>
</html>

