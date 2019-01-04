# Évaluation individuelle

## Programmation - Coaching

```
Nom : Paruta	
Prénom : Anaëlle
URL de votre compte Github : https://github.com/AnaelleParuta1995
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
L'interaction client-serveir est l'interaction entre l'interface utilisateur qui permet de receuillir les demandes et d'ensuite les evoyer au serveur pour que la demande soit excuter. 
```



 ### 2. HTML est un langage côté... 	

```
client 
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8"/>
        <titre><!-- Titre de la page--></titre>
    </head>
    <body>

            <!-- Coeur de texte-->
    </body>
</html>

```



### 4. Changez la couleur du texte "J'adore la programmation" en vert en utilisant du CSS.

```html
<div>
   <p class="coulV">J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
.coulV {
    color: green;
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap est une ressource externe, en ligne, qui permet d'integrer des feuilles de codes déjà écrite directement à son code. 
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
    <head>
        <meta charset="utf-8"/>
         <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css" integrity="sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS" crossorigin="anonymous">
        <titre><!-- Titre de la page--></titre>
    </head>
    <body>
            <!-- Coeur de texte-->
        <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.6/umd/popper.min.js" integrity="sha384-wHAiFfRlMFy6i5SRaxvfOCifBUQy1xHdJ/yoi7FRNXMRBu5WHdZYu1hA6ZOblgut" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/js/bootstrap.min.js" integrity="sha384-B0UglyR+jN6CkvvICOB2joaf5I4l3gm9GU6Hc1og6Ls7i6U/mkkaduKaBhlAXv9k" crossorigin="anonymous"></script>
    </body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class=container>
    <div class="row">
       <div class="col-sm">
           Google
    </div>

    <div class="col-sm">
        Microsoft
    </div>

    <div class="col-sm">
        Apple
    </div>
</div>
<!-- On peut très bien utiliser "display: inline" ou "display: inline-block"
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class=container>
    <div class="row">
<div class="col-sm">
    <img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" alt="Logo Google">
</div>

<div class="col-sm">
   <img src="https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RE1Mu3b?ver=5c31" alt="Logo Microsoft">
</div>

<div class="col-sm">
    <img src="https://www.apple.com/ac/structured-data/images/open_graph_logo.png?201810271035" alt="Logo Apple">
    
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div class=container>
    <div class="row">
<div class="col-sm">
    <a href="https://www.google.fr/"><img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" alt="Logo Google"></a>
</div>

<div class="col-sm">
   <a href="https://www.microsoft.com/fr-fr/store/b/home?ef_id=Cj0KCQiApbzhBRDKARIsAIvZue-8NEML0hVKZAvWERix6ND7aJ1M-q25AViwyiz4P7pvV1s8lZkJKvgaAhu2EALw_wcB:G:s&s_kwcid=AL!4249!3!235339983833!e!!g!!microsoft&invsrc=search&cl_vend=google&cl_ch=sem&cl_camp=972169376&cl_adg=48647335139&cl_crtv=235339983833&cl_kw=microsoft&cl_pub=google.com&cl_place=&cl_dvt=c&cl_pos=1t1&cl_mt=e&cl_gtid=aud-380390124936:kwd-11656221&cl_pltr=&cl_dim0=Cj0KCQiApbzhBRDKARIsAIvZue-8NEML0hVKZAvWERix6ND7aJ1M-q25AViwyiz4P7pvV1s8lZkJKvgaAhu2EALw_wcB:G:s&OCID=AID695932_SEM_Cj0KCQiApbzhBRDKARIsAIvZue-8NEML0hVKZAvWERix6ND7aJ1M-q25AViwyiz4P7pvV1s8lZkJKvgaAhu2EALw_wcB:G:s"><img src="https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RE1Mu3b?ver=5c31" alt="Logo Microsoft"></a> 
</div>

<div class="col-sm">
    <a href="https://www.apple.com/fr/"><img src="https://www.apple.com/ac/structured-data/images/open_graph_logo.png?201810271035" alt="Logo Apple"></a>
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
serveur
```



### 11. Listez-moi tous les types de données que vous connaissez en donnant le nom et la syntaxe.

```
integer = un nombre entier
 float = un nombre décimal
 string = chaine de caractere
 boolean = true ou false
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
ist_name="Anaëlle"
puts first_name
last_name="Paruta"
puts last_name
my_account= "https://github.com/AnaelleParuta1995"
puts account
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
a=674
b=311
c=a%b 

puts c
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
librairie externe qu’on rajoute a ruby (il équivaut au link dans le html)
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
 C'est une une interface de programmation, elle s’oppose aux interfaces graphiques (qui est une communication client). Les infos rentrées par l’humain sur le client est transmis au serveur via API.
 Ce qui nous permet de nous y connecter est une clé d'API.
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur
print "Quel est votre prénom ?"
name = gest.chomp

hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom
if hour <12 
    puts "Bonjour #{name}" 
	
    # sinon
	# j'écris mon code permettant de dire Bonsoir prénom
else 
    puts "Bonsoir #{name}"
end

```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]
handles.each do |utilisateur|
	client.follow(utilisateur)

```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

