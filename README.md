Voici un exemple de code HTML fonctionnel pour une page d'inscription de paris sportifs. Ce code inclut un simple formulaire d'inscription ainsi qu'un peu de CSS pour le style. Tu peux utiliser ce modèle comme point de départ pour ton site de paris sportifs.

### Exemple de Code HTML

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inscription - Paris Sportifs</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            padding: 50px;
            margin: 0;
        }
        .container {
            max-width: 500px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        h2 {
            text-align: center;
            color: #333;
        }
        label {
            display: block;
            margin: 15px 0 5px;
        }
        input[type="text"],
        input[type="email"],
        input[type="password"] {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #28a745;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Inscription</h2>
        <form action="inscription.php" method="POST">
            <label for="username">Nom d'utilisateur:</label>
            <input type="text" id="username" name="username" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Mot de passe:</label>
            <input type="password" id="password" name="password" required>

            <button type="submit">S'inscrire</button>
        </form>
    </div>
</body>
</html>
```

### Comment Utiliser ce Code :

1. **Copie et colle** le code ci-dessus dans un fichier avec l'extension `.html` (par exemple `inscription.html`).
2. **Ouvre le fichier** dans un navigateur web pour voir le formulaire d'inscription.
3. **Adaptation** : Tu peux modifier le style CSS, ajouter des champs supplémentaires (comme le numéro de téléphone), ou changer la méthode d'envoi du formulaire en fonction de tes besoins.

### Traitement du Formulaire :
Le formulaire envoie les données à `inscription.php`. Tu devras créer un fichier `inscription.php` pour traiter les données soumises (enregistrement des utilisateurs dans une base de données, par exemple).

Si tu veux des exemples de code pour le traitement côté serveur ou d'autres fonctionnalités, fais-le moi savoir !
