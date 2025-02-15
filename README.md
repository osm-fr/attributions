# Attributions

## Pourquoi ?

La licence [ODbL](https://fr.wikipedia.org/wiki/Open_Database_License) impose aux réutilisateurs des données OpenStreetMap de mentionner la source (et de respecter le partage à l'identique).

La communauté des contributeurs OpenStreetMap est très attachée au respect de l'attribution car :
- C'est une façon de dire merci ;
- C'est une façon de rendre le projet OpenStreetMap visible et de faire naitre de nouvelles vocations de contributeurs… et donc d'alimenter un cercle vertueux.

Donc :
- **« Oublier » l'attribution casse le cercle vertueux du commun ;**  
- La copie sans attribution est un délit de contrefaçon qui peut être puni de trois ans d'emprisonnement et de 300 000 euros d'amende (article [L335-2](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000032655082) et suivants du Code de la propriété intellectuelle).  
  ℹ️ Un juriste doit vérifier l'exactitude des textes de référence — [#368](https://github.com/osm-fr/attributions/issues/368).

## Comment ?

Ce dépôt git est destiné au suivi des manques d'attributions sur les utilisations de carte utilisant OpenStreetMap.  
Ce suivi est fait à l'aide des [« issues »](https://github.com/osm-fr/attributions/issues).

## 📢 Signaler une mauvaise attribution
Pour ajouter un nouveau manque d'attribution sur une carte :
1. **[Vérifiez](https://github.com/osm-fr/attributions/issues?q=is%3Aissue) qu'un signalement n'existe pas déjà** ;
2. **Sinon, ouvrez une nouvelle [« issue »](https://github.com/osm-fr/attributions/issues/new?template=attribution.yml)** ;
3. **Ajoutez un titre** ;<br>
    `paris.fr`<br>
    `[Agence ComWeb]`<br>
    `Appli SNCF`  
    `...`
4. **Décrivez le problème**.
    - Adresse Web, service, produit concerné
    - Date de prise de contact (et par quel moyen ?)

### Bonne pratique

**Un manquement, un signalement.** Lier les signalement d'un organisme commun grâce à un `#` suivi du nom de l'organisme.
| ❌ Regrouper tous les signalement d'une même agence | ✔️ Créer des signalements distincts et les lier à l'agence |
| :-: | :-: |
| ![Non](.github/ISSUE_TEMPLATE/Non-sombre.jpg#gh-dark-mode-only) ![Non](.github/ISSUE_TEMPLATE/Non.jpg#gh-light-mode-only) | ![Oui](.github/ISSUE_TEMPLATE/Oui-sombre.jpg#gh-dark-mode-only) ![Oui](.github/ISSUE_TEMPLATE/Oui.jpg#gh-light-mode-only) |

## Contacter le responsable

<details>
    <summary><b>Proposition de modèle de courriel</b></summary>
  <blockquote>
  Bonjour,

  En tant que cartographe OpenStreetMap, ça me fait plaisir de voir que vous utilisez une carte issue d'OpenStreetMap sur votre site, notamment sur : 

  Cependant, j'ai noté que la carte n'est pas correctement attribuée. En effet, nous demandons que votre crédit comporte la mention « © les contributeurs d’OpenStreetMap ». Vous devez également préciser clairement que les données sont disponibles sous la licence ODbL. Vous pouvez mentionner ceci avec un lien hypertexte vers https://www.openstreetmap.org/copyright.

  Une attribution correcte permet de préciser les sources de la carte ou des données ainsi que ce que les utilisateurs ont le droit d'en faire.
  
  Si vous n'êtes pas directement charge de la conception de ce site, vous pouvez transférer ce courriel au service ou à l'agence concernée.
  Si vous avez besoin d'aide pour effectuer la correction ou si vous avez des questions, ne pas hésiter à répondre à ce message ou à utiliser un de nos canaux de communication : https://wiki.openstreetmap.org/wiki/FR:Canaux_de_contact.

  Enfin, une attribution correcte permet de diffuser l'existence d'OpenStreetMap, d'attirer de nouvelles contributions et d'étendre la communauté. C'est extrêmement important pour améliorer la qualité de la base de données en qui vous et des millions de personnes font confiance.

  Lorsque la correction aura été faite, n'hésitez pas à me le signaler.

  Merci d'avance !<br>
  `signature`
  </blockquote>
</details>

---

## ⚠️ Recommandations obsolètes

En 2021, la Fondation OpenStreetMap a modifiée les règles concernant la mise en œuvre de l'attribution. Les recommandations et liens des paragraphes suivants peuvent être obsolètes, au contraire de celles-ci :
- https://wiki.osmfoundation.org/wiki/Licence/Licence_and_Legal_FAQ
- https://wiki.osmfoundation.org/wiki/Licence/Attribution_Guidelines

---

## Exemples de mauvaises attributions
- Aucune de ces mentions<br>
  `© OpenStreetMap contributors`<br>
  `© OpenStreetMap`<br>
  `© les contributeurs d’OpenStreetMap`<br>
  `© Contributeurs OpenStreetMap`

- Remplacement de la mention par celle du fournisseur de tuiles<br>
  `Mapbox`<br>
  `© Groupe AC3`<br>
  `Mapnik`

- Autres<br>
  `© Open Street Map`<br>
  `© OSM`

## Ressources
- [openstreetmap.org/copyright](https://www.openstreetmap.org/copyright)
- [**Manque d'attribution appropriée** — wiki.openstreetmap.org ](https://wiki.openstreetmap.org/wiki/FR:Manque_d%27attribution_appropri%C3%A9e)
  - [**Proposition de courriel** — wiki.openstreetmap.org](https://wiki.openstreetmap.org/wiki/FR:Manque_d%27attribution_appropri%C3%A9e#Proposition_de_courriel)
- [**Legal FAQ** — wiki.openstreetmap.org](https://wiki.openstreetmap.org/wiki/Legal_FAQ)
- [**Licence** — wiki.osmfoundation.org](https://wiki.osmfoundation.org/wiki/Licence)
  - [**Attribution Guidelines** — wiki.osmfoundation.org](https://wiki.osmfoundation.org/wiki/Licence/Attribution_Guidelines)
  - [**Licence and Legal FAQ** — wiki.osmfoundation.org](https://wiki.osmfoundation.org/wiki/Licence/Licence_and_Legal_FAQ)
  - [Suivi des manques d'attributions par la fondation OpenStreetMap](https://github.com/openstreetmap/tile-attribution)
- [Condition d'utilisation des services de tuiles de l'association OpenStreetMap France](https://www.openstreetmap.fr/usage/)
