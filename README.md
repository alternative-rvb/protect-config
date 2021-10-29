# Comment protégez un dossier de site Web en utilisant .htaccess et .htpasswd

Repo : 

1. Créer un fichier `.htaccess` dans le dossier  à protéger
2. Ajouter les lignes dans `.htaccess`

        AuthType Basic
        AuthName "restricted area"
        AuthUserFile /path/to/the/directory/you/are/protecting/.htpasswd
        require valid-user

3. Créer un fichier `.htpasswd`
4. Créer un identifiant et générer un mot de passe en vous aidant du générateur suivant 

https://hostingcanada.org/htpasswd-generator/

5. Insérer la ligne générée dans `.htpasswd``.htpasswd`
