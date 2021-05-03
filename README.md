# Entraînement au checkpoint 2 : Rick & Morty

Créer un composant <Home> qui affiche un titre "Rick & Morty" dans une balise <h1> et une description dans une balise <p>

Créer le composant <CharacterItem> qui affiche les propritétés name et status (Alive ou Dead) d'un personnage de l'univers de Rick & Morty.

Faire en sorte d'afficher ces informations à partir des props.

Créer un composant <CharacterList> qui affiche la liste des 20 premiers personnages de Rick & Morty.
Chaque personnage sera affiché avec le composant <CharacterItem>.
L'API à appeler est la suivante : https://rickandmortyapi.com/api/character

Ajouter un bouton "Dead" en haut du composant <CharacterList>.
Au clic sur ce dernier, filtrer la liste pour n'afficher que les personnages dont la propriété status à la valeur "Dead".

Créer un <Router> pour afficher les vue suivantes :
- sur l'url '/', afficher le composant <Home>
- sur l'url '/characters', afficher le composant <CharacterList>

Créer un composant <Navigation> qui contient deux liens 'Home' et 'Characters', permettant de naviguer respectivement sur les deux urls '/' et 'characters'.

Créer un composant <CharacterDetails> qui affiche plus de détails sur un personnage : name, status, species et image.
Afficher les informations du personnage à partir d'un appel d'API : https://rickandmortyapi.com/api/character/1

Modifier l'appel d'API afin de pouvoir changer l'identifiant du personnage à afficher à partir d'une variable.

Créer une route '/characters/:id' permettant d'afficher le composant <CharacterDetails>.
Afficher le personnage correspondant à l'identifiant passé en url, ex : /characters/2 devra afficher les informations de Morty Smith.

Ajouter un lien dans <CharacterItem>, permettant d'accéder à la fiche du personnage correspondant.
