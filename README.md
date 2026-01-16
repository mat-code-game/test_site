 lien court : [https://urlr.me/ygqv7h](urlr.me/ygqv7h)
🧩 Code secret (admin)
Description
Ce script HTML/JavaScript génère et affiche un code secret temporaire destiné à être utilisé dans un espace administrateur ou de vérification sécurisée.
Le code change automatiquement toutes les 5 minutes et est conservé localement dans le navigateur à l’aide de LocalStorage. Cela évite de regénérer un code à chaque rechargement, sauf lorsque la durée limite est dépassée.

Fonctionnement
Lors du chargement de la page, le script :

Vérifie si un code est déjà stocké dans localStorage.

Si le code existe et date de moins de 5 minutes, il est réutilisé.

Sinon, le script génère un nouveau code aléatoire de 6 caractères (lettres et chiffres).

Le code est affiché dans la page et sauvegardé dans le navigateur.

L’affichage se met à jour automatiquement toutes les 10 secondes, sans changer le code avant la prochaine période de rotation (5 min).