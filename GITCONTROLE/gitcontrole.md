# Compte rendu du projet GIT

## Initialisation

Pour commencer j'ai rejoint le repertoire git crée par Grabiel

Ensuite, nous avons cloné le repository avec cette commande

```bash
git clone https://github.com/gabsdng/github.git

cd github
```

Nous avons fait notre config de username et email.

```bash
git config user.name "wWantedVI"
git config user.email "arthur20051@outlook.fr"
```

## Creation et modifications

Ensuite, nous avons créé notre fichier et l'avons push ( nous étions obligé d'attendre un push puis de pull pour push à notre tour.) Pour ma part c'était le fichie contact.html

```bash
git pull
git add page.html
git commit -m "ajout du fichier contact"
git push -u origin master
```

Tout au long de la matinée, nous devons régulièrement pull pour pouvoir push.

Suite à ça, j'ai créé ma page :

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Liste des meilleurs anime</title>
</head>
<body>

</body>
</html>
```

Pour ensuite y ajouter ma parti contact avec au debut prenom / nom puis mail et telephone

```html
    <h1> NOUS CONTACTER : </h1>

<form action="traitement.php" method="post">

        <input type="text" name="lastname" id="nom" maxlength="100" placeholder="Nom de famille">
        
        <input type="text" name="firstname" id="prenom" maxlength="100" placeholder="Prénom">

        <input type="email" name="email" id="email" maxlength="200" placeholder="email">

        <input type="number" name="N°téléphone" id="telephone" maxlength="10" placeholder="telephone">

        <input type="text" name="N°Voiture" id="Voiture" maxlength="50" placeholder="Voiture">

        <input type="text" name="N°Formule" id="Formule" maxlength="50" placeholder="Formule">




        <input type="submit">
    </form>```

## Branche

Nous avons chacun créé une branche à notre nom, pour faire des modifications de notre coté 

```bash
git branch arthur
git checkout arthur
```

puis apres nous avons commit et push nos modifs sur nos branches, puis nous avons merge

## Fusion

```bash
git checkout master
git merge arthur
```


## Retour dans master et dernières petites modif

j'ai fait en sorte de bien m'alligné par rapport au pages de mes camarades pour un site bien plus propre.
j'ai aussi fait la parti mobile css

```css

@media (max-width: 768px) {

  body {
    padding: 10px;
    font-size: 16px;
  }

  .container {
    flex-direction: column; 
  }

  .box {
    width: 100%;
    margin-bottom: 10px;
  }

}


```
J'ai aussi du resoudre un probleme avec mon ficher contact.html

Nous avons donc un site fait en équipe et fonctionnel.

Voici aussi la liste des differente commande que j'ai pu utiliser:

cd documents

mkdir projetgit

cd projetgit

git init

ls -a

git remote add origin https://github.com/Gabsdng/projetgit.git

git config user.name wWantedVI
git config user.email arthur20051@outlook.fr

nano contact.html

git add contact.html

git commit -m "Ajout de la page Arthur : Contact.html"

git push -u origin master

git pull

nano contact.html

git add contact.html

git commit -m "J'ai fait ma page html, je commence a faire la parti contact avec nom et prenom"

git push -u origin master

nano contact.html

git pull

git add contact.html

git commit -m "Ajout de la parti contact Email et Numéro de telephone"

git push -u origin master

nano contact.html

git add contact.html

git commit -m "j'ai ajouter la parti nav avec la liaison entres les pages, mettez la chacun dans votre page"

git push -u origin master

git pull

git branch arthur

git checkout Arthur

git add contact.html

git nano contact.html

git commit -m "j'ai ajouter ma branche arthur, et j'ai mis le nav en dessous du header pour qu'on soit toussent alligne"

git push -u origin arthur

git pull

git checkout master

git merge Arthur

nano liste.html
nano index.html

nano contact.html

git add contact.html

git commit -m "ajout liaison css!"

git pull

git nano style.css

git status

git add contact.html

git pull --no-base

git nano style.css

git commit -m "j'ai ajouter la parti mobile pour que le site soit adapté pour mobile au niveau du css","j'ai aussi résolu un probleme avec mon contact.html"

git push -u origin master



