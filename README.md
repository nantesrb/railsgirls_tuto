# Tutoriel Rails Girls

### Important

Il est important de suivre les instructions spécifiques à votre système d'exploitation (Windows <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="18px"/>, Apple <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> ou Linux <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/>). Les commandes entre Windows et les autres systèmes diffèrent légèrement.

##  1. Création de l'application

Nous allons créer une nouvelle application appelée *railsgirls*.

Ouvrez votre terminal :

* Windows <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="18px"/> : Cliquer sur *Démarrer* et chercher *Command Prompt*, cliquer ensuite sur *Command Prompt with Ruby and Rails*.
* Mac OS X <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> : Ouvrir Spotlight, taper *Terminal* et cliquer sur l’application *Terminal*.
* Linux <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> : Chercher *Terminal* dans le dash et cliquer sur *Terminal*.

Ensuite, taper la commande suivante :

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>

```
mkdir projects
```

Vous pouvez vérifier qu'un répertoire `projects` a été créé en tapant la commande : <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> `ls` ou <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="18px"/> `dir`. Vous pouvez voir le  nom du répertoire `projects` s'afficher. Pour se déplacer à l'intérieur du répertoire `projects`, il faut taper la commande suivante:

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>

```
cd projects
```

Vous pouvez vérifier que votre répertoire est vide en tapant la commande <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> `ls` ou <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/> `dir`. Nous allons maintenant créer notre nouvelle application appelée `railsgirls` en tapant :

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>

```
rails new railsgirls -M -C -T --skip-coffee --skip-yarn
```

Cela va créer une nouvelle application dans le répertoire `railsgirls`. Nous allons à nouveau changer de répertoire pour nous retrouver à l'intérieur de notre application Rails en tapant :

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>

```
cd railsgirls
```

Si vous tapez <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> `ls` ou <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>`dir` depuis ce répertoire, vous devriez voir des dossiers tel que `app` et `config`. Vous pouvez lancer le serveur Rails en tapant la commande :

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>

```
rails server
```

Ouvrez <http://localhost:3000> dans votre navigateur.

Vous devriez voir une page avec le logo de Rails et un message "Yay! You’re on Rails!", qui signifie que votre application est opérationnelle.

**Si ce n'est pas le cas, demandez de l'aide ;)**

Notez que dans cette fenêtre, l'invite de commande n'est pas visible parce que l'on est maintenant dans le serveur Rails. L'invite de commande ressemble à ça :

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>

```
$
```

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/>

```
>
```

Quand l'invite de commande normale n'est pas visible, vous ne pouvez pas exécuter d'autre commande. Si vous essayez de taper `cd` ou une autre commande, ça ne marchera pas. Pour retourner à l'invite de commande normale :
Taper <kbd>Ctrl</kbd>+<kbd>C</kbd> dans le terminal pour quitter le serveur.

##  2. Créer l’échafaudage de *Idea*

Nous allons utiliser la fonctionnalité d’échafaudage (*scaffold*) de Rails pour commencer le développement à un point où l'on peut déjà **lister** (*index*), **ajouter** (*create*), **supprimer** (*remove*), **modifier** (*update*) et **voir** (*show*) des choses, dans notre cas, des idées (*ideas*).

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>

```
rails generate scaffold idea name:string description:text picture:string --no-helper --no-jbuilder
```

Cette commande crée de nouveaux fichiers dans le répertoire du projet, mais pour que tout fonctionne correctement, nous devons lancer quelques commandes supplémentaires pour mettre à jour la base de données et redémarrer le serveur.

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>

```
rails db:migrate
rails server
```

Ouvrez <http://localhost:3000/ideas> dans votre navigateur.

Naviguez dans votre application et explorer ce qu'a rajouté cette commande d’échafaudage.

##  3. Design

L'application n'est pas encore très jolie.
Nous allons utiliser le Framework CSS Bootstrap de Twitter pour rendre les choses un peu plus sympa.

Ouvrez `app/views/layouts/application.html.erb` dans votre éditeur de texte et au dessus de la ligne :

```html
<%= stylesheet_link_tag    'application', media: 'all', 'data-turbolinks-track': 'reload' %>
```

ajouter :

```html
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.0/css/bootstrap.css">
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.0/css/bootstrap-theme.css">
```

et remplacer

```html
<%= yield %>
```

par

```html
<div class="container">
  <%= yield %>
</div>
```

Ajoutons également une barre de navigation et un pied de page (*footer*) au *layout*. Dans le même fichier, sous `<body>` ajouter :

```html
<nav class="navbar navbar-default navbar-fixed-top" role="navigation">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="/">The Idea app</a>
    </div>
    <div class="collapse navbar-collapse">
      <ul class="nav navbar-nav">
        <li class="active"><a href="/ideas">Ideas</a></li>
      </ul>
    </div>
  </div>
</nav>
```

et avant `</body>` ajouter

```html
<footer>
  <div class="container">
    Rails Girls <%= Time.now.year %>
  </div>
</footer>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="//maxcdn.bootstrapcdn.com/bootstrap/3.0.3/js/bootstrap.js"></script>
```

Maintenant, changeons le style du tableau des *Ideas*. Ouvrez `app/assets/stylesheets/application.css` et à la fin de fichier, ajouter :

```css
body { padding-top: 100px; }
footer { margin-top: 100px; }
table, td, th { vertical-align: middle; border: none; }
th { border-bottom: 1px solid #DDD; }
```

Sauvegardez tous les fichiers que vous avez modifiés et rafraîchissez votre navigateur pour voir les changements. Vous pourrez continuer à modifier le code HTML et le CSS plus tard pour personnaliser votre application.

##  4. Prise en charge de l'*upload* d'images

Nous avons besoin d'ajouter un module supplémentaire pour nous permettre d'*uploader* des fichiers grâce à Rails.

Ouvrez le fichier `Gemfile` qui se trouve à la racine du répertoire de notre projet et sous la ligne :

```ruby
gem 'sqlite3'
```

ajouter

```ruby
gem 'carrierwave'
```


Tapez <kbd>Ctrl</kbd>+<kbd>C</kbd> dans le terminal pour quitter le serveur.

Lancer dans le terminal :

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>

```
bundle install
```

Nous pouvons maintenant générer le code qui permettra l'*upload* de fichier, pour notre application, des images.

Dans le terminal, taper la commande :

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>

```
rails generate uploader Picture
```

Relancer le serveur Rails.

---

**Note** : Vous utilisez peut-être deux terminaux pour garder votre serveur Rails en fonction continuellement. Si c'est le cas, vous devez **redémarrer votre serveur Rails** maintenant. C'est nécessaire pour que l'application charge le nouveau module *carrierwave*.

Si vous avez une erreur disant que `uploader cannot be found`, ajouter la ligne suivante au fichier `Gemfile` :

```ruby
gem 'net-ssh'
```

Si vous avez ajouté cette ligne, relancer dans le terminal :

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>

```
bundle install
```

---

Ouvrir `app/models/idea.rb` et sous la ligne

```ruby
class Idea < ApplicationRecord
```

ajouter :

```ruby
mount_uploader :picture, PictureUploader
```

Ouvrir `app/views/ideas/_form.html.erb` et changer

```erb
<%= f.text_field :picture %>
```

par :

```erb
<%= f.file_field :picture, id: :idea_picture %>
```
Dans votre navigateur, ajouter une idée avec une image. Lorsque vous ajouter une image, c'est pas encore très joli parce que ça montre que le chemin (*path*) du fichier, corrigeons ça.

Ouvrir `app/views/ideas/show.html.erb` et changer

```erb
<%= @idea.picture %>
```

par

```erb
<%= image_tag(@idea.picture_url, width: 600) if @idea.picture.present? %>
```

Rafraîchissez maintenant votre navigateur et regardez le résultat.

##  5. Affinons nos routes

Ouvrez <http://localhost:3000>. Nous avons toujours la page avec "Yay! You’re on Rails!". Mettons en place une redirection directe vers la page `ideas`.

Ouvrir `config/routes.rb` et après la première ligne, ajouter :

```ruby
root to: redirect('/ideas')
```

Testez vos changements en ouvrant <http://localhost:3000/>.

## 6. Ajouter une page statique à l'application

Ajoutons une page statique à notre application qui contiendra des informations à propos de l'auteur, vous !

<img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Apple.png&r=38&g=38&b=38" alt="APPLE" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Linux.png&r=38&g=38&b=38" alt="LINUX" width="18px"/> | <img src="http://flaticons.net/gd/makefg.php?i=icons/Brand%20Identity/Windows%208.png&r=38&g=38&b=38" alt="WINDOWS" width="20px"/>

```
rails generate controller pages info --no-helper
```

Cette commande va créer un dossier sous `app/views` appelé `/pages` avec à l'intérieur un fichier `info.html.erb` qui sera la page d'informations.

Ajoutons une simple route au fichier `config/routes.rb`

```ruby
get "pages/info"
```
Vous pouvez maintenant ouvrir le fichier `app/views/pages/info.html.erb` et y ajouter des informations à propos de vous en HTML. Pour voir votre nouvelle page d'informations, rendez-vous depuis votre navigateur à l'adresse <http://localhost:3000/pages/info>.

##  7. La suite ?

* Personnalisez votre design avec du HTML et du CSS.
* Utilisez du JavaScript pour ajouter de l'interaction utilisateur.
* Plusieurs guides pour améliorer votre application sont disponibles (la plupart en anglais) sur <http://guides.railsgirls.com/>.
