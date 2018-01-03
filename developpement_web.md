# Développement web

Vous devez créer un site web pour un café étudiant.

Le site doit permettre :

* L'inscription de bénévoles.
* L'entrée de disponibilités des bénévoles dans un calendrier hebdomadaire,
  où chaque journée est divisée en tranche d'heures.
* L'affichage de l'horaire des bénévoles avec leurs noms dans les plages
  choisies.
* Mise à jour du menu du café qui est visible sur la page d'accueil.

Le site ne doit pas permettre :

* Le dépassement d'un certain nombre de bénévoles par *shift*, habituellement 2.
  La limite est de 3 lors des heures de pointes :
  * 8:00 à 12:00 du lundi au mercredi
  * 7:00 à 11:00 les jeudis et vendredis

## Font-end

Les librairies comme JQuery et les frameworks comme Bootstrap ou même Angular,
React et Vue sont acceptés. Toutefois, vous êtes fortement encouragé à limiter
votre utilisation de JavaScript au strict minimum.

## Back-end

Voici quelques recommandations de frameworks pour votre back-end :

* [Express (JavaScript)](//expressjs.com)
* [Flask (Python)](//flask.pocoo.org)
* [Django (Python)](//djangoproject.com)
* [Rails (Ruby)](//rubyonrails.org)
* [Phoenix (Elixir)](//phoenixframework.org)
* [Rocket (Rust)](//rocket.rs)
* [Laravel (PHP)](//laravel.com)
* [ASP.NET Core (C#)](//asp.net/core)

## Bonus

Ajouter un système de gestion d'inventaire ou de messagerie entre membres,
comme dans un groupe Facebook.
