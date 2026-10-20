# 🎨 Charte Graphique & Design System — Aix en Vue (AEV)

Ce dossier regroupe l'ensemble des éléments d'identité visuelle, typographies, palettes de couleurs, composants graphiques et règles d'accessibilité d'**Aix en Vue**. Il sert de socle de référence pour la création de vos **prochaines affiches, flyers, kakémonos, visuels réseaux sociaux et supports print/web**.

---

## 1. Identité de la Marque & Coordonnées Officielles

* **Nom officiel :** Aix en Vue (sigle : **AEV**)
* **Signature / Slogan principal :** *« Pour et avec les déficients visuels. »*
* **Conviction / Phrase forte :** *« Parce que voir moins ne signifie pas vivre moins. »*
* **Statut juridique :** Association Loi 1901 Reconnue d'intérêt général (fondée en 2024)
* **SIRET :** `928 552 512 00016`
* **Siège social :** 23 boulevard François et Émile Zola, 13100 Aix-en-Provence
* **Téléphone :** `07 44 99 94 38`
* **Email :** `info@aixenvue.fr`
* **Site web :** `www.aixenvue.fr`
* **Réseaux sociaux :**
  * Facebook : `facebook.com/aix.en.vue`
  * Instagram : `@aixenvue`
  * LinkedIn : `Aix en Vue (AEV)`

---

## 2. Le Logo & La Signature Typographique

L'identité repose sur l'association du **pictogramme de l'œil** (`assets/logos/oeil_logo.webp` et `assets/logos/logo-aev.png`) et d'une composition typographique hiérarchisée en **Playfair Display Black (900)** où les initiales **A - E - V** sont mises en valeur en **Rouge Signature (`#D80000`)** :

* **`A`ix** — Taille : `100%` (ex. `1.5rem` / `24pt`) — **A** en `#D80000`, **ix** en `#111111` (ou `#F8F9FA` sur fond sombre)
* **`E`n** — Taille : `77%` (ex. `1.15rem` / `18.5pt`) — **E** en `#D80000`, **n** en `#111111`
* **`V`ue** — Taille : `60%` (ex. `0.9rem` / `14.5pt`) — **V** en `#D80000`, **ue** en `#111111`

> **Astuce pour vos affiches :** Cet effet d'échelle décroissante (*Aix > En > Vue*) évoque subtilement les lignes d'un tableau d'acuité visuelle d'ophtalmologiste (échelle Monoyer), tout en restant élégant et éditorial.

---

## 3. Palette de Couleurs

L'univers chromatique d'Aix en Vue s'inspire des **terres de Provence et de l'atelier de Paul Cézanne** (papier grainé, ocre, crème, vert garrigue, bleu profond), réveillé par un **Rouge Vermillon** vibrant qui assure à la fois une signature mémorable et un repère visuel à très fort contraste pour les personnes malvoyantes.

### 3.1. Palette Principale (Thème Clair / Print & Affiches sur fond papier)

| Nom | Variable CSS | Code HEX | Code RVB | CMJN (Print approx.) | Usage recommandé sur les affiches |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Rouge Signature** | `--rouge` | `#D80000` | `216, 0, 0` | `C:5 M:100 J:100 N:0` | Initiales AEV, mots-clés en italique, bandeaux d'accent, badges, appels à l'action (CTA), filets coup de pinceau. |
| **Noir Encre** | `--noir` | `#111111` | `17, 17, 17` | `C:70 M:65 J:65 N:85` | Grands titres, textes principaux, blocs de contraste fort. |
| **Papier Cézanne** | `--papier` | `#F4F2EB` | `244, 242, 235` | `C:4 M:4 J:8 N:0` | Fond principal d'affiche (remplace avantageusement le blanc pur trop éblouissant pour les malvoyants). |
| **Crème Lumineux** | `--creme` | `#FBF8F0` | `251, 248, 240` | `C:1 M:2 J:5 N:0` | Fond de mise en avant (zone Hero, encarts clairs). |
| **Papier Foncé / Sable** | `--papier-fonce` | `#E8E4D9` | `232, 228, 217` | `C:9 M:9 J:15 N:0` | Fond de cartes secondaires, bordures douces, séparateurs. |
| **Ocre de Provence** | `--ocre` | `#C8860A` | `200, 134, 10` | `C:18 M:48 J:98 N:4` | Surtitres (*eyebrows*), étiquettes de rubriques, tirets au pinceau sur fond clair. |
| **Ocre Clair / Or** | `--ocre-clair` | `#F0C060` | `240, 192, 96` | `C:5 M:24 J:68 N:0` | Surtitres, chiffres clés et accents lumineux lorsqu'ils sont posés sur fond noir (`#111111`). |
| **Bleu Profond** | `--bleu` | `#1A3A5C` | `26, 58, 92` | `C:92 M:68 J:30 N:20` | Accent institutionnel froid, bouton « Adhérer », encarts d'information. |
| **Vert Sauge / Nature** | `--vert` | `#5C7A5C` | `92, 122, 92` | `C:65 M:35 J:65 N:15` | Thématiques nature, randonnée, jardinage et plein air. |
| **Gris Anthracite** | `--gris` | `#333333` | `51, 51, 51` | `C:65 M:58 J:58 N:60` | Textes courants et paragraphes descriptifs. |

### 3.2. Palette Haute Lisibilité / Fond Sombre (Expositions & Mode Contraste Inversé)

Pour les affiches d'exposition artistique (type *Projet Cézanne* ou *Aix au-delà du regard*) ou les supports privilégiant le contraste inversé (lettres claires sur fond sombre mat, très confortable contre la photophobie) :

* **Fond Noir Mat :** `#121212` ou `#0D0D0D`
* **Surface Carte Sombre :** `#1E1E1E`
* **Texte Blanc Pur :** `#F8F9FA`
* **Texte Secondaire :** `#E0E0E0`
* **Rouge Éclatant :** `#FF4D4D` (ou `#D80000` en aplat avec texte blanc)
* **Ocre Doré :** `#F5BA42` / `#C9A45A` (Or exposition sonore)

---

## 4. Typographies Officielles

Le duo typographique combine le caractère éditorial et artistique d'une **Serif à fort contraste** avec la lisibilité géométrique irréprochable d'une **Sans-Serif moderne** adaptée aux publics malvoyants. Toutes deux sont disponibles gratuitement sur **Google Fonts**.

### 4.1. Titres & Accroches : **Playfair Display**
* **Lien Google Fonts :** `https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;0,900;1,400&display=swap`
* **Graisses utilisées :**
  * **Black (900) :** Tous les grands titres d'affiches (`H1`, `H2`), les chiffres clés et le logo `Aix En Vue`. Interlignage serré (`1.1` à `1.15`), approche légèrement resserrée (`-0.025em`).
  * **Italic (400 / 700) :** **Signature stylistique majeure d'Aix en Vue !** Dans chaque titre principal, **un mot-clé fort est mis en italique et en Rouge `#D80000`** (parfois souligné d'un coup de pinceau).
    * *Exemples :* « Pour et avec les *déficients* visuels », « Des activités pour *tout vivre* », « Ils voient Cézanne *autrement* », « Agir pour l'*autonomie* et l'inclusion ».

### 4.2. Corps de texte, Surtitres & Informations pratiques : **Manrope**
* **Lien Google Fonts :** `https://fonts.googleapis.com/css2?family=Manrope:wght@300;400;500;600;700;800&display=swap`
* **Graisses utilisées :**
  * **ExtraBold (800) :**
    * **Surtitres (Eyebrows) :** En MAJUSCULES, taille modérée, espacement des lettres très large (`letter-spacing: 0.2em`), couleur Ocre (`#C8860A` sur fond clair, `#F0C060` sur fond sombre), précédés du tiret coup de pinceau.
    * **Boutons, Badges, Dates & Lieux importants :** En MAJUSCULES (`letter-spacing: 0.08em`).
  * **Medium (500) & SemiBold (600) :** Textes de présentation, horaires, adresses, informations pratiques (interlignage aéré `1.6` à `1.75` pour faciliter la lecture).

---

## 5. Marqueurs Graphiques & Formes Signatures

Pour qu'une affiche soit immédiatement reconnue comme une création **Aix en Vue**, utilisez ces 4 marqueurs visuels (disponibles dans `assets/svg-elements/`) :

1. **La découpe trapézoïdale dynamique (`clip-path`) :**
   * Les boutons, étiquettes et badges ne sont pas de simples rectangles droits : leurs côtés gauche et droit sont légèrement biseautés en oblique (`polygon(0 0, 100% 0, 97% 100%, 3% 100%)` ou l'inverse `polygon(3% 0, 100% 0, 97% 100%, 0% 100%)`).
   * Pour les grands cadres ou modales, les coins opposés (haut-gauche et bas-droite) sont coupés à 45° (`15px`).
2. **Les coups de pinceau SVG (Brush Strokes) :**
   * **Soulignement rouge (`brush-underline-rouge.svg`) :** Placé sous le mot en italique rouge du titre principal.
   * **Tiret ocre (`brush-dash-ocre.svg` / `brush-dash-ocre-clair.svg`) :** Placé juste à gauche du surtitre (*eyebrow*).
   * **Filet ondulé rouge (`separator-wave-rouge.svg`) :** Sépare l'en-tête ou le pied de page du reste de la composition.
3. **Le grain papier subtil (`texture-grain-papier.svg`) :**
   * Donne un toucher chaleureux, artisanal et artistique (clin d'œil au papier aquarelle de Cézanne) sur les aplats `#F4F2EB` et `#FBF8F0`.
4. **Le Badge flottant en italique :**
   * Sur le coin inférieur droit de la photo principale d'une affiche, un bloc rouge `#D80000` légèrement biseauté chevauche le bord de l'image avec une phrase courte en *Playfair Display Italic Bold* blanc (ex. *« Entrée libre & ouverte à tous »* ou *« Exposition sensorielle & audiodécrite »*).

---

## 6. Règles d'Or d'Accessibilité Visuelle pour vos Affiches

Puisque **Aix en Vue** s'adresse aux personnes déficientes visuelles ainsi qu'au grand public :

1. **Contraste maximal (WCAG AAA) :** Ne jamais écrire de texte informatif en gris clair ou sur une photo chargée sans un aplat de fond sombre ou clair uni derrière le texte.
2. **Tailles de police généreuses :** Sur une affiche A3/A4, les informations clés (**Date, Heure, Lieu, Téléphone**) doivent être lisibles de près comme de loin, en **Manrope Bold/ExtraBold**.
3. **Éviter le blanc pur éblouissant :** Préférez toujours le fond **Papier (`#F4F2EB`)** ou **Crème (`#FBF8F0`)**, ou à l'inverse un **Noir mat profond (`#111111`)** avec textes blancs/ocres.
4. **QR Code contrasté :** Si vous intégrez un QR Code (vers `www.aixenvue.fr`, HelloAsso ou une piste d'audiodescription), entourez-le d'un cadre blanc franc avec une bordure nette et une légende explicite (*« Scannez pour écouter la présentation audio / vous inscrire »*).

---

## 7. Contenu de ce Dossier

* 📄 **`CHARTE_GRAPHIQUE_AIXENVUE.md`** : Ce guide complet.
* 🎨 **`VITRINE_DESIGN_SYSTEM.html`** : Une planche de style interactive (ouvrez-la dans votre navigateur !) présentant visuellement toutes les couleurs (avec copie des codes HEX en 1 clic), les typographies, les logos, les boutons et les composants.
* 🖼️ **`templates/MODELE_AFFICHE_A4_AEV.html`** : Un gabarit d'affiche A4 prêt à l'emploi (en version **Fond Papier Clair** ET en version **Fond Noir Exposition**), directement modifiable et imprimable en PDF haute définition depuis votre navigateur (`Ctrl + P` -> *Enregistrer au format PDF*).
* 💻 **`design-tokens.css`** & **`design-tokens.json`** : Toutes les variables CSS et tokens JSON pour réutiliser le design system dans n'importe quel outil (Canva, Figma, site web, générateur d'affiches).
* 📁 **`assets/logos/`** :
  * `oeil_logo.webp` : Le pictogramme œil officiel utilisé dans l'en-tête et le pied de page.
  * `logo-aev.png` : Le logo officiel complet utilisé sur les documents administratifs et PDF.
  * `icon-512.png`, `icon-192.png`, `favicon.png` : Icônes carrées haute résolution.
  * `nos_partenaires_bandeau.webp` : Le bandeau officiel des partenaires institutionnels (Département 13, Métropole, Ville d'Aix, etc.) à placer en bas de vos affiches !
* 📁 **`assets/svg-elements/`** : Les coups de pinceau vectoriels SVG (`brush-underline-rouge.svg`, `brush-dash-ocre.svg`, `brush-dash-ocre-clair.svg`, `separator-wave-rouge.svg`, `texture-grain-papier.svg`) importables dans Illustrator, Affinity, Figma ou Canva.
* 📁 **`assets/photos/`** : Quelques visuels emblématiques haute qualité pour vos maquettes.
