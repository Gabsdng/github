# Compte rendu du projet GIT

## Initialisation

Pour commencer j'ai créer un new repository nommé github sur git et j'ai invité mes camarades.

Ensuite, nous avons cloné le repository avec cette commande

```bash
git clone https://github.com/gabsdng/github.git

cd github
```

Nous avons fait notre config de username et email.

```bash
git config user.name "gabsdng"
git config user.email "gabriel.dienga@efrei.net"
```

## Creation et modifications

Ensuite, nous avons créé notre fichier et l'avons push ( nous étions obligé d'attendre un push puis de pull pour push à notre tour.) Pour ma ârt c'était le fichier liste.html

```bash
git pull
git add liste.html
git commit -m "ajout du fichier liste"
git push -u origin master
```

Tout au long de la matinée, nous devons régulièrement pull pour pouvoir push.

Suite à ça, j'ai créé mon site 

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

J'ai commit la base puis j'ai ajouté ma liste 

```html
<ul>
  <li>L'Attaque des Titans (Shingeki no Kyojin)</li>
  <li>Death Note</li>
  <li>Fullmetal Alchemist: Brotherhood</li>
  <li>One Piece</li>
  <li>Naruto</li>
  <li>Demon Slayer (Kimetsu no Yaiba)</li>
  <li>Jujutsu Kaisen</li>
  <li>My Hero Academia (Boku no Hero Academia)</li>
  <li>Hunter x Hunter</li>
  <li>Tokyo Ghoul</li>
</ul>
```
## Branche

Nous avons chacun créé une branche à notre nom, pour faire des modifications de notre coté 

```bash
git branch gabriel
git checkout gabriel
```

puis apres nous avons commit et push nos modifs sur nos branches, puis nous avons merge

## Fusion

```bash
git checkout master
git merge gabriel
```


## Retour dans master et derneres petites modif

J'ai ajouté qlq chose sur le fichier contact.html d'arthur.

puis j'ai fait et push le css ( tres simple )

```css
*{
    margin:0;
    padding:0;
}
nav{
    background:lightblue;
}
```

Nous avons donc un site fait en équipe et fonctionnel.

