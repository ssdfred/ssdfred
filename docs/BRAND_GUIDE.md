# FSDev Brand Guide

> Version : 1.0.0  
> Statut : Officiel

---

# 1. Identité

**FSDev** est un écosystème d'ingénierie logicielle consacré à la conception de logiciels fiables, sécurisés, documentés et durables.

La signature officielle est :

> **Engineering Better Software**

L'identité visuelle de FSDev repose sur plusieurs principes :

- ingénierie ;
- fiabilité ;
- sécurité ;
- rigueur ;
- modernité ;
- pérennité.

L'objectif est de construire une identité reconnaissable et suffisamment durable pour accompagner l'évolution de l'écosystème.

---

# 2. Logo

Le logo FSDev repose sur un monogramme géométrique constituant le symbole principal de l'écosystème.

Sa géométrie ne doit pas être modifiée selon les projets ou les supports.

## Logo principal

La version vectorielle couleur constitue la référence officielle :

```text
assets/logo/logo-fs-bleu.svg
```

Le format SVG doit être privilégié lorsque le support le permet.

---

# 3. Variantes du logo

Plusieurs variantes officielles sont disponibles afin de garantir une bonne lisibilité sur différents supports.

```text
assets/logo/
├── logo-fs-bleu.svg
├── logo-fs-dark.svg
├── logo-fs-light.svg
├── logo-fs-monochrome.svg
├── icon.svg
└── favicon.svg
```

## Logo couleur

```text
logo-fs-bleu.svg
```

Version principale et version à privilégier.

---

## Logo clair

```text
logo-fs-light.svg
```

Version destinée aux fonds sombres.

---

## Logo sombre

```text
logo-fs-dark.svg
```

Version destinée aux fonds clairs.

---

## Logo monochrome

```text
logo-fs-monochrome.svg
```

Version destinée aux usages nécessitant une seule couleur, notamment certains documents ou supports d'impression.

---

# 4. Icône officielle

L'icône FSDev reprend le symbole principal sans élément textuel.

```text
assets/logo/icon.svg
```

Elle peut notamment être utilisée pour :

- les avatars ;
- les interfaces ;
- les applications ;
- les profils ;
- les éléments nécessitant une représentation compacte de FSDev.

---

# 5. Favicon

Le favicon officiel est disponible ici :

```text
assets/logo/favicon.svg
```

Il est optimisé pour représenter FSDev dans les navigateurs et les contextes nécessitant une icône de petite taille.

---

# 6. Palette officielle

L'identité FSDev repose principalement sur une palette de bleus associée à des tons neutres.

## FSDev Blue

```text
#0A63D8
```

Couleur principale de l'identité.

Utilisations :

- logo ;
- liens ;
- éléments graphiques principaux ;
- éléments d'identification de la marque.

---

## FSDev Cyan

```text
#18BFF2
```

Couleur d'accent.

Utilisations :

- dégradés ;
- détails graphiques ;
- éléments secondaires ;
- mises en valeur.

---

## Deep Blue

```text
#063B87
```

Couleur de profondeur.

Utilisations :

- dégradés ;
- variantes graphiques ;
- éléments secondaires.

---

## Midnight

```text
#07111F
```

Couleur sombre principale.

Elle peut notamment être utilisée pour les fonds et les éléments nécessitant un contraste important.

---

## Slate

```text
#182536
```

Couleur destinée aux surfaces secondaires et aux éléments graphiques intermédiaires.

---

## Silver

```text
#B8C4D1
```

Couleur secondaire destinée notamment aux textes et éléments graphiques secondaires.

---

## White

```text
#FFFFFF
```

Utilisée pour les textes et éléments graphiques sur fonds sombres ainsi que pour la variante claire du logo.

---

# 7. Dégradé officiel

Le dégradé principal FSDev associe les trois couleurs fondamentales de l'identité :

```text
#18BFF2 → #0A63D8 → #063B87
```

Référence CSS :

```css
linear-gradient(
    135deg,
    #18BFF2 0%,
    #0A63D8 55%,
    #063B87 100%
)
```

Ce dégradé doit rester cohérent lorsqu'il est utilisé dans les supports officiels.

---

# 8. Typographie

L'identité FSDev utilise deux familles typographiques complémentaires.

## Inter — Typographie principale

**Inter** est la typographie officielle de FSDev.

Elle est utilisée pour :

- les titres ;
- les textes ;
- les interfaces utilisateur ;
- les sites web ;
- la documentation ;
- les supports de communication.

### Graisses recommandées

- **Regular 400** — texte courant ;
- **Medium 500** — éléments d'interface ;
- **SemiBold 600** — sous-titres et éléments importants ;
- **Bold 700** — titres principaux.

Inter doit rester la typographie dominante de l'identité.

---

## JetBrains Mono — Typographie technique

**JetBrains Mono** constitue la typographie technique de FSDev.

Elle est utilisée pour :

- le code source ;
- les commandes ;
- les chemins de fichiers ;
- les journaux techniques ;
- les exemples de configuration ;
- les données nécessitant un affichage monospace.

---

# 9. Principes typographiques

La typographie FSDev doit privilégier :

- la lisibilité ;
- la sobriété ;
- une hiérarchie visuelle claire ;
- la cohérence entre les différents projets ;
- un nombre limité de variantes typographiques.

**Inter** est utilisée pour la communication générale.

**JetBrains Mono** est réservée aux contenus techniques.

---

# 10. Zone de protection

Une zone libre doit toujours être conservée autour du logo.

Aucun texte, bord, pictogramme ou autre élément graphique ne doit être placé directement contre le symbole.

La zone de protection recommandée correspond au minimum à environ **10 % de la largeur du logo** sur chacun de ses côtés.

Cette règle peut être adaptée lorsque le logo est utilisé comme favicon ou comme petite icône.

---

# 11. Taille minimale

Le logo doit toujours rester suffisamment grand pour conserver sa lisibilité.

Pour les usages numériques :

- symbole seul : **24 px minimum** ;
- logo principal : **32 px minimum recommandé**.

Pour les très petites tailles, le fichier `favicon.svg` doit être privilégié.

---

# 12. Utilisations à éviter

Le logo FSDev ne doit pas être :

- déformé ;
- étiré ;
- compressé ;
- incliné ;
- recoloré arbitrairement ;
- entouré d'effets non prévus ;
- placé sur un fond compromettant sa lisibilité ;
- modifié pour répondre aux besoins particuliers d'un projet.

Les proportions originales doivent toujours être conservées.

---

# 13. Identité des projets

Les projets de l'écosystème peuvent disposer de leur propre identité visuelle.

Ils doivent néanmoins conserver une cohérence générale avec les principes de FSDev.

L'identité FSDev peut notamment accompagner :

- CyberLab ;
- FSBackup ;
- Radio Lotus ;
- EMS ;
- Devis Express Artisan ;
- FSDev Engineering Standards ;
- les futurs projets de l'écosystème.

L'objectif n'est pas d'imposer une apparence identique à tous les produits, mais de maintenir une filiation reconnaissable avec l'écosystème FSDev.

---

# 14. Supports

L'identité FSDev est conçue pour fonctionner sur différents supports :

- GitHub ;
- documentation technique ;
- sites web ;
- applications web ;
- applications mobiles ;
- interfaces logicielles ;
- documents ;
- présentations ;
- supports de communication.

La version du logo utilisée doit toujours être choisie en fonction du contraste et du support.

---

# 15. Évolution de l'identité

Cette charte constitue la **version 1.0 de l'identité visuelle FSDev**.

Elle pourra évoluer avec l'écosystème.

Les futures versions pourront notamment intégrer :

- un logo horizontal ;
- des modèles de documents ;
- une bibliothèque d'icônes ;
- des composants graphiques communs ;
- un Design System ;
- un kit média complet.

Toute évolution doit préserver la reconnaissance et la cohérence de l'identité existante.

---

# Signature

> **Engineering Better Software**

---

© FSDev — Ce document fait partie de la documentation officielle de l'écosystème FSDev.