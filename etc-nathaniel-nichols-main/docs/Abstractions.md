# Abstractions principales

    Énumérez et décrivez brièvement les concepts qui définissent le système.
    Typiquement, on trouve dans cette section un résumé des classes 
    d'analyse. On ne devrait pas avoir d'éléments technologiques ici.

    Évitez d'être narratif. Les abstractions prennent généralement la forme 
    d'un diagramme de classe de niveau analyse avec une clarification des 
    termes utilisés. On vise à introduire des notions qui sont du 
    domaine d'affaire.

    Strictement en modèle d'analyse : Classes d'affaires et activités 
    d'affaire, états ou séquences des traitements d'affaire. Restez au niveau de
    ce qui est pertinent pour comprendre le domaine du client.

## Diagramme de classes

    Masquez les attributs et méthodes

```plantuml

hide circle
hide attribute
hide method
class concept1
class concept1

concept1 o- concept2

```

## Glossaire (Langage ubiquitaire)

### mon mot

definition, synonyme..., ne pas confondre avec...