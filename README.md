# Maquettes pen.dev

Maquettes de sites et d'interfaces conçues avec **pen.dev**.

| Dossier | Sujet | Pages |
|---|---|---|
| [`forge-landing/`](forge-landing/) | Landing page pour un agent de code en terminal | 1 |
| [`boulangerie/`](boulangerie/) | Site vitrine d'une boulangerie artisanale | 1 (avec section boutique) |
| [`ecommerce-aura/`](ecommerce-aura/) | E-commerce audio haut de gamme, style Apple | 3 (accueil, liste, fiche produit) |

## Apercu

### forge-landing

![forge-landing](forge-landing/screenshots/forge-landing.png)

### boulangerie

![boulangerie](boulangerie/screenshots/boulangerie.png)

### ecommerce-aura

![accueil](ecommerce-aura/screenshots/aura-accueil.png)

![liste produit](ecommerce-aura/screenshots/aura-plp.png)

![fiche produit](ecommerce-aura/screenshots/aura-pdp.png)

## Contenu de chaque dossier

```
<maquette>/
├── design.pen        document source pen.dev, editable dans le canevas
├── screenshots/      rendus PNG (et PDF quand disponible)
└── photos/           photos sources + CREDITS.json (attributions)
```

## Demarche

Chaque maquette part du **contenu avant le visuel** : le message et la narration
sont fixes d'abord, la mise en forme ensuite.

1. **Guides** — les principes viennent des guides pen.dev (`Landing Page`,
   `Web App`). Deux regles structurantes : la couleur d'accent est **reservee aux
   actions**, et chaque section tient sur **un seul axe d'alignement**.
2. **Composition** — une page de 1440 px de large, construite section par section,
   en alternant densite et valeurs de fond.
3. **Photographie** — images sous licence libre (Openverse, Wikimedia Commons),
   choisies sur planche contact, attributions conservees.
4. **Verification** — chaque section est controlee visuellement avant de passer a
   la suivante.
5. **Livraison** — PNG pour la lecture, PDF pour l'archivage, fichiers `.pen`
   comme sources editables.

## Licence

**MIT** — voir [LICENSE](LICENSE). Vous pouvez réutiliser, modifier et
redistribuer ces maquettes, y compris commercialement, à condition de conserver
la mention de copyright.

Elle couvre les documents de conception et le texte : `design.pen`, captures,
`README.md`. Elle **ne couvre pas** les photographies de `photos/`, qui restent
sous leurs licences Creative Commons — le détail est dans
[THIRD-PARTY.md](THIRD-PARTY.md).

## Photos et attributions

Les photos proviennent d'**Openverse** et de **Wikimedia Commons**. Plusieurs sont en
**CC BY** ou **CC BY-SA**, qui imposent de citer l'auteur : les attributions sont dans
le tableau de chaque dossier et dans les `CREDITS.json`.

> **Les `design.pen` ne contiennent pas les photos.** Le document ne contient que les
> emplacements (degrades) ; les photos sont collees dans le rendu apres export, pour
> la raison expliquee ci-dessus. Rouvrir un `.pen` et le reexporter **efface les
> photos**. Pour les integrer au document, il faut ouvrir le canevas dans le
> navigateur : l'editeur, lui, dispose d'une URI de base.
