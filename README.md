# TUTO COMPLET WAGTAIL
Source : [documentation de Wagtail](https://docs.wagtail.org/en/stable/index.html)
(version stable au 25/02/2025 : 6.4).

Ce dépôt comprend l'intégralité du tutoriel de Wagtail, incluant le [Getting started](https://docs.wagtail.org/en/stable/getting_started/index.html) 
et le [tutoriel avancé](https://docs.wagtail.org/en/stable/tutorial/index.html).

## Utilisation
Chaque étape importante est enregistrée dans une branche propre, ce qui permet de refaire 
facilement certaines étapes à partir de la bonne base de code. Les branches sont numérotées 
et nommées avec la dernière étape achevée qu'elles contiennent. Par exemple, une branche nommée 
'08_blog_creation' contiendra l'étape de création du blog. Si on veut refaire cette étape, il
faudra donc se positionner sur la branche précédente ('07_...'). La branche 'main' contient 
le tutoriel intégralement complété.

## Infos utiles
- La base de données est volontairement versionnée pour ne pas avoir à recréer les pages 
à chaque fois.
- Vous devez créer votre propre super-utilisateur pour accéder à l'administration, 
avec la commande suivante dans le terminal : `python manage.py createsuperuser`.
