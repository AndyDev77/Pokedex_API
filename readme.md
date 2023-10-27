## 📕 Introduction

Ce projet est une application mobile Pokémon conçue pour afficher des informations sur divers Pokémon à partir de l'API "https://pokeapi.co/". Il utilise React Native avec TypeScript comme langage de programmation principal. Cette documentation couvrira l'approche générale du projet, les choix techniques, et comment il peut être utilisé.

## 💻 Technologies utilisées

Le projet a été fait en utilisant les technologies suivantes

- Expo
- React Native
- Styled-Components
- React Navigation
- Typescript
- Axios
- Reanimated V2

---

## 🗃 Structure du projet

- Le projet est organisé en composants réutilisables, regroupés en dossiers selon leur fonctionnalité. Les principaux dossiers sont : "components", "routes", "screens", "services", et "styles".

- Les composants de l'application sont répartis en différentes parties de l'application, par exemple, "Card" pour afficher les détails d'un Pokémon, et "Home" pour la page d'accueil de la Pokédex.

## 📂 Gestion de l'État

- L'état global de l'application est géré à l'aide de l'état local de React et de hooks.
- Les données des Pokémon sont récupérées depuis l'API et stockées dans l'état de l'application.

## Styles et Thèmes

- Les styles de l'application sont gérés à l'aide de Styled-Components, ce qui permet une personnalisation facile des composants.

- Un thème global est défini pour les couleurs de l'application, ce qui permet de changer rapidement le style de toute l'application.

## Navigation

- React Navigation est utilisé pour gérer la navigation entre les écrans de l'application.
- L'application comporte des écrans de liste de Pokémon, de détails de Pokémon, et d'autres écrans liés à la navigation.

## 📦 Comment télécharger le projet

```bash
  # Cloner le dépôt
  $ git clone https://github.com/AndyDev77/Pokedex_API.git

  # Entrez dans le dossier du projet
  $ cd my-pokedex

  # Installer les dépendances
  $ yarn

  #Démarrer le projet avec cette commande
  $ expo start


```

---

## 💻 Fonctionnalités

- Liste de Pokémon: Création d'un écran qui affiche une liste de Pokémon. Chaque élément de la liste
  doit montrer au minimum le nom du Pokémon

- Détails du Pokémon: Lorsqu'on clique sur un Pokémon dans la liste, l'application montre un
  autre écran avec plus de détails sur un Pokémon

- Liste des capacités
