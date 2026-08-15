# FSDev Brand Guide

> Version : 1.0.0
> Statut : En cours

---

# 1. Identité

**FSDev** est un écosystème d'ingénierie logicielle consacré à la conception de logiciels fiables, sécurisés, documentés et durables.

La signature officielle est :

> **Engineering Better Software**

L'identité visuelle doit refléter les principes fondamentaux de FSDev :

* ingénierie ;
* fiabilité ;
* sécurité ;
* rigueur ;
* modernité ;
* pérennité.

---

# 2. Logo

Le logo FSDev repose sur un monogramme géométrique constituant le symbole principal de l'écosystème.

Il doit rester immédiatement identifiable et être utilisé de manière cohérente sur l'ensemble des projets FSDev.

## Logo principal

Le logo vectoriel SVG constitue la version de référence.

```text
assets/logo/logo-fs-bleu.svg
```

Le fichier SVG doit être privilégié lorsque le format le permet.

---

# 3. Palette officielle

## FSDev Blue

```text
#0A63D8
```

Couleur principale de l'identité FSDev.

Utilisations :

* logo ;
* liens ;
* éléments graphiques principaux ;
* éléments d'identification de la marque.

---

## FSDev Cyan

```text
#18BFF2
```

Couleur d'accent.

Utilisations :

* dégradés ;
* détails du logo ;
* éléments graphiques secondaires ;
* mises en valeur.

---

## Deep Blue

```text
#063B87
```

Couleur de profondeur.

Utilisations :

* dégradés ;
* ombres ;
* variantes graphiques ;
* surfaces secondaires.

---

## Midnight

```text
#07111F
```

Fond sombre principal de l'identité FSDev.

---

## Slate

```text
#182536
```

Utilisé pour les surfaces secondaires, cartes et séparateurs sur interfaces sombres.

---

## Silver

```text
#B8C4D1
```

Utilisé pour les éléments graphiques et textes secondaires.

---

## White

```text
#FFFFFF
```

Utilisé principalement pour les textes et les versions du logo destinées aux fonds sombres.

---

# 4. Dégradé principal

Le dégradé de marque FSDev associe Cyan, FSDev Blue et Deep Blue.

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

---

# 5. Typographie

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

L'utilisation d'un nombre limité de graisses permet de conserver une identité visuelle cohérente.

---

## JetBrains Mono — Typographie technique

**JetBrains Mono** est utilisée pour les contenus techniques nécessitant une police monospace.

Elle est notamment destinée :

- au code source ;
- aux commandes ;
- aux chemins de fichiers ;
- aux journaux techniques ;
- aux exemples de configuration ;
- aux données techniques nécessitant un alignement monospace.

---

## Principes d'utilisation

L'identité FSDev privilégie :

- la lisibilité ;
- la sobriété ;
- une hiérarchie visuelle claire ;
- la cohérence entre les différents projets ;
- un usage limité et maîtrisé des variantes typographiques.

**Inter** doit rester la typographie dominante.

**JetBrains Mono** est réservée aux contenus techniques.

---

# 6. Variantes du logo

Le kit graphique devra progressivement contenir :

```text
assets/logo/
├── logo-fs-bleu.svg
├── logo-dark.svg
├── logo-light.svg
├── logo-monochrome.svg
├── logo-horizontal.svg
├── icon.svg
└── favicon.svg
```

---

# 7. Zone de protection

Une zone libre doit toujours entourer le logo.

Aucun texte, bord, pictogramme ou autre élément graphique ne doit être placé immédiatement contre le symbole.

La zone de protection définitive sera déterminée lors de la finalisation du fichier vectoriel de référence.

---

# 8. Utilisations à éviter

Le logo ne doit pas être :

* déformé ;
* étiré ;
* incliné ;
* recoloré arbitrairement ;
* utilisé avec des effets graphiques non prévus ;
* placé sur un fond réduisant fortement sa lisibilité ;
* modifié pour les besoins particuliers d'un projet.

Les projets FSDev peuvent disposer de leur propre identité, mais le logo principal FSDev doit rester cohérent.

---

# 9. Cohérence de l'écosystème

L'identité FSDev constitue la base commune de l'écosystème.

Elle pourra être utilisée sur :

* GitHub ;
* la documentation ;
* les sites web ;
* les applications ;
* CyberLab ;
* FSBackup ;
* Radio Lotus ;
* EMS ;
* Devis Express Artisan ;
* FSDev Engineering Standards ;
* les futurs projets de l'écosystème.

Chaque projet peut posséder sa propre identité tout en conservant une filiation visuelle avec FSDev.

---

# 10. Évolution

Cette charte est conçue pour évoluer progressivement.

Les futures versions pourront notamment définir :

* la typographie officielle ;
* les variantes définitives du logo ;
* les règles précises d'espacement ;
* le favicon ;
* les icônes ;
* le Design System FSDev ;
* les composants graphiques communs.

Les évolutions doivent préserver la cohérence et la reconnaissance de l'identité existante.

---

> **Engineering Better Software**

---

© FSDev — Ce document fait partie de la documentation officielle de l'écosystème FSDev.
