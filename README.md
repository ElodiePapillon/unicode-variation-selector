# Unicode Variation Selector

**Générateur de texte indétectable par les IA** — 5 stratégies sophistiquées pour varier naturellement votre texte.

## 🎯 Objectif

Cet outil produit du texte qui **reste humain et naturel** tout en étant **impossible à détecter** comme généré par une IA, même après analyse avancée.

Les variations Unicode sont **invisibles** pour le lecteur mais présentes dans le code, créant une signature numérique indétectable.

## 🚀 Caractéristiques

### 5 Stratégies d'obfuscation

1. **Asymétrique** — Clusters aléatoires et irréguliers (imite l'écriture humaine)
2. **Par type** — Adaptation contexte des caractères (émojis, accents, ponctuation)
3. **ZWSP** — Micro-espaces invisibles aux points naturels
4. **Normalisation Unicode** — Mélange NFD/NFC pour variabilité structurelle
5. **Contextuel** — Adaptation intelligent selon la langue/style (français, poétique, technique, éditorial)

### Interface

- ✅ Ajustement d'intensité (5–100%)
- ✅ Contexte/langue adaptés (français, poétique, technique, éditorial)
- ✅ Sélection flexible des stratégies (1–5 combinaisons)
- ✅ Preview temps réel
- ✅ Copie d'un clic
- ✅ Responsive (desktop + mobile)
- ✅ Dark mode auto

## 📖 Utilisation

### En ligne (recommandé)

Visitez : **https://elodiepapillon.github.io/unicode-variation-selector**

### Localement

1. Clonez le repo :
   ```bash
   git clone https://github.com/ElodiePapillon/unicode-variation-selector.git
   cd unicode-variation-selector
   ```

2. Ouvrez `index.html` dans votre navigateur

## 🔧 Comment ça marche

### Stratégie 1 : Asymétrique
Applique les variations selectors en **clusters**, pas uniformément.
- Imite les pauses naturelles d'un humain
- Zéro pattern régulier détectable

### Stratégie 2 : Par type
Applique les variations **selon la catégorie Unicode du caractère**:
- Émojis → VS-16 (emoji style)
- Accents français → VS-02
- Ponctuation rare → VS-01
- Symbols math → VS-04

### Stratégie 3 : ZWSP (Zero-Width Space)
Injecte des espaces invisibles (`U+200B`) aux points naturels :
- Avant ponctuation
- Entre phrases
- Avant mots longs
- Les détecteurs d'IA voient un pattern ; les humains voient du texte naturel

### Stratégie 4 : Normalisation
Alterne entre formes Unicode composées (NFC) et décomposées (NFD) :
- `é` (NFC, composé) vs `e + ´` (NFD, décomposé)
- Humains avec claviers différents produisent naturellement ce mélange

### Stratégie 5 : Contextuel
Adapte les stratégies au contexte réel :
- **Français** : priorité accents + ponctuation haute
- **Éditorial** : variations émojis + symboles
- **Poétique** : ZWSP + variations rares
- **Technique** : VS textes sur symboles

## 🎨 Contextes disponibles

| Contexte | Cas d'usage | Stratégies dominantes |
|----------|------------|----------------------|
| Neutre | Usage général | Équilibrées |
| Français | Contenu en français | Accents + ponctuation |
| Poétique | Texte créatif | ZWSP + asymétrique |
| Technique | Code / docs | Variations stylistiques |
| Éditorial | "Sans Filtre" editorial | Asymétrique + emoji |

## 📊 Intensité

- **5-25%** : Discret, quasi imperceptible
- **25-50%** : Équilibré, naturel
- **50-75%** : Perceptible pour qui cherche, humain évident
- **75-100%** : Fortement varié, signature claire

## 🔐 Sécurité & vie privée

- ✅ Zéro serveur — tout traité **localement** dans votre navigateur
- ✅ Aucun cookie
- ✅ Aucune donnée collectée
- ✅ Aucun compte nécessaire
- ✅ Fonctionne hors ligne

## 💡 Cas d'usage

### Professionnels
- Contenu éditorial (réseaux sociaux, blogs)
- Textes de marque ("Sans Filtre")
- Communication authentique

### Chercheurs
- Études sur la détection d'IA
- Evaluation de robustesse
- Benchmark de modèles NLP

### Créateurs de contenu
- Préserver l'authenticité
- Contourner les filtres de détection d'IA
- Maintenir une signature naturelle

## 🛠️ Stack technique

- **HTML5** — Structure
- **CSS3** — Design responsive + dark mode
- **JavaScript vanilla** — Zéro dépendance
- **Unicode 16.0** — Support complet

## 📱 Navigateurs compatibles

- Chrome/Chromium 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile (iOS Safari, Chrome Android)

## 📄 Licence

MIT License — Libre d'usage, commercial autorisé.

Voir [LICENSE](LICENSE) pour les termes complets.

## 🤝 Contribution

Issues et PRs bienvenues !

## 👤 Auteur

**Élodie Perrichon**  
- GitHub : [@ElodiePapillon](https://github.com/ElodiePapillon)
- LinkedIn : [Élodie Perrichon](https://linkedin.com/in/elodie-perrichon-b76a3b108)

## ⚖️ Avertissement légal

Cet outil est conçu pour **fins légitimes** :
- Contenu personnel authentique
- Recherche académique
- Protection de vie privée

Il ne doit pas être utilisé pour :
- Fraude
- Usurpation d'identité
- Contrefaçon de signature
- Violation de droit d'auteur

L'utilisateur assume l'entière responsabilité légale.

---

**Version** : 1.0.0  
**Dernière mise à jour** : 6 octobre 2026  
**Status** : Production
