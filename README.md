# THE FRIENDS OF SECK LIGHT YAGAMI 
Juste pour les amis proches

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Retrouvailles entre amis</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; text-align: center; }
        form { max-width: 400px; margin: auto; }
        input, button { width: 100%; padding: 10px; margin: 5px 0; border-radius: 5px; border: 1px solid #ccc; }
        button { background-color: #4CAF50; color: white; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <h1>Retrouvons nos amis !</h1>
    <p>Entrez vos informations pour que tout le monde puisse rester en contact.</p>
    <form id="registerForm">
        <input type="text" id="name" placeholder="Nom complet" required>
        <input type="email" id="email" placeholder="Email" required>
        <input type="tel" id="phone" placeholder="Numéro de téléphone" required>
        <button type="submit">S'inscrire</button>
    </form>
    <script>
        document.getElementById('registerForm').addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Merci pour votre inscription !');
        });
    </script>
</body>
</html>

