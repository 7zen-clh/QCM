# QCM en ligne

Un quiz en ligne interactif utilisant HTML, CSS et JavaScript. Ce projet permet aux utilisateurs de répondre à un ensemble de questions de choix multiple (QCM), avec un calcul du score à la fin du quiz.

## Fonctionnalités

- Chargement dynamique des questions à partir d'un fichier XML.
- Sélection des réponses avec des boutons radio.
- Calcul du score en fonction des réponses correctes.
- Affichage du score à la fin du quiz.

## Prérequis

Avant de commencer, assurez-vous d'avoir un environnement compatible pour exécuter le projet :

- Un navigateur web moderne (Chrome, Firefox, Edge, Safari).
- Un serveur local ou un hébergement en ligne (par exemple, Netlify, GitHub Pages) pour charger le fichier XML si vous ne testez pas en local.
- Si vous testez en local, assurez-vous d'utiliser un serveur pour éviter les erreurs liées aux requêtes AJAX.

## Installation

### Étapes pour exécuter le projet en local :

1. Clonez ce projet :
    ```bash
    git clone https://github.com/votre-utilisateur/qcm-en-ligne.git
    ```

2. Naviguez dans le répertoire du projet :
    ```bash
    cd qcm-en-ligne
    ```

3. Ouvrez le fichier `index.html` dans un navigateur ou servez-le via un serveur local (par exemple, avec **Live Server** dans VSCode).

4. Le fichier XML (`question.xml`) peut être hébergé en ligne ou localement. Si vous le mettez en ligne (par exemple sur Netlify), mettez à jour l'URL dans le code JavaScript.

## Structure du projet

- `index.html` : Le fichier HTML contenant la structure du quiz.
- `styles.css` : Le fichier CSS pour la mise en page et la présentation.
- `script.js` : Le fichier JavaScript qui gère la logique du quiz.
- `question.xml` : Le fichier XML contenant les questions et réponses (modifiez ce fichier pour ajouter vos propres questions).

## Personnalisation

- **Questions et Réponses** : Modifiez le fichier `question.xml` pour ajouter vos propres questions et réponses. Chaque question doit être sous l'élément `<question>`, et chaque réponse sous `<answer>`.
- **Style** : Modifiez `styles.css` pour ajuster l'apparence du quiz selon vos préférences.

## Déploiement

Vous pouvez déployer votre projet sur des plateformes telles que [Netlify](https://www.netlify.com/) ou [GitHub Pages](https://pages.github.com/) pour le rendre accessible en ligne.

## Contribuer

Si vous souhaitez contribuer à ce projet, suivez ces étapes :

1. Fork ce repository.
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature-name`).
3. Commitez vos modifications (`git commit -am 'Ajout d\'une nouvelle fonctionnalité'`).
4. Poussez la branche (`git push origin feature-name`).
5. Ouvrez une Pull Request.
