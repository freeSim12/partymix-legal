---
title: EarthVision — Politique de confidentialité
permalink: /earthvision/PRIVACY_POLICY.html
---

**Français** · [English](./en/PRIVACY_POLICY.html) · [Español](./es/PRIVACY_POLICY.html)

# Politique de confidentialité — EarthVision

_Dernière mise à jour : 1er octobre 2026_

La présente politique décrit comment l'application **EarthVision** (« l'Application », « nous ») collecte, utilise et protège les informations lorsque vous l'utilisez sur Android ou iOS.

EarthVision affiche sur un globe des **webcams publiques en direct** appartenant à des tiers (chaînes YouTube, services de transport, offices de tourisme…). Nous ne filmons rien, n'enregistrons rien et ne rediffusons rien : l'Application affiche le flux fourni par le propriétaire de chaque caméra.

---

## 1. Éditeur

L'Application est éditée par **EarthVision**, joignable à l'adresse **simondouz81150@gmail.com**.

## 2. Données traitées

EarthVision est conçu pour collecter le minimum. Voici la liste exhaustive.

### 2.1 Identifiant anonyme
- **Quoi :** un identifiant technique aléatoire créé au premier lancement (connexion anonyme). Aucun nom, aucun e-mail, aucun numéro de téléphone.
- **Pourquoi :** rattacher vos favoris à votre appareil et les synchroniser.
- **Où :** Supabase (hébergement en Union européenne, Irlande).
- **Durée :** jusqu'à ce que vous supprimiez vos données (voir section 6).

### 2.2 Favoris
- **Quoi :** la liste des caméras que vous avez mises en favori.
- **Pourquoi :** vous les retrouver, et calculer le classement anonyme « Favoris des gens » (nombre de favoris par caméra, sans jamais indiquer qui a mis quoi).
- **Où :** sur votre appareil et chez Supabase.

### 2.3 Notes et signalements
- **Notes :** si vous notez l'application dans l'app, la note (1 à 5 étoiles) est enregistrée avec votre identifiant anonyme, pour nous aider à l'améliorer.
- **Signalements :** si vous signalez une caméra, nous enregistrons l'identifiant de la caméra et la date.

### 2.4 Localisation
- **Quand :** **uniquement** si vous la demandez (« Me localiser », onglet « Près d'ici », alertes de passage de l'ISS) et acceptez la permission. Jamais en arrière-plan sans votre accord, jamais de suivi continu.
- **Pourquoi :** centrer le globe sur vous, trier les caméras par distance et, si vous activez les alertes de passage de l'ISS ou d'aurores (EarthVision+), calculer ce qui sera visible au-dessus de chez vous.
- **Où :** **uniquement sur votre appareil.** Pour les alertes, une position **arrondie à environ 10 km** y est conservée, puis mise à jour à l'ouverture de l'Application. **Elle n'est jamais envoyée à nos serveurs.**

### 2.5 Notifications et alertes
- **Notifications de découverte :** au plus **deux par semaine** (un coucher de soleil, un lieu à découvrir).
- **Alertes EarthVision+ (si vous les activez) :** coucher de soleil sur un de vos favoris (une par jour au plus), passages visibles de l'ISS, nuits d'aurores.
- **100 % locales :** programmées par l'Application sur votre appareil, sans serveur. Pour les aurores, l'Application consulte environ toutes les heures la prévision publique de l'indice Kp de la NOAA (voir section 3) : aucune donnée vous concernant n'est envoyée, hormis l'adresse IP inhérente à toute connexion.
- **Désactivation :** dans l'Application (Profil, Favoris) ou dans les réglages du téléphone.

### 2.6 Widget d'écran d'accueil
- Le widget affiche l'image du moment de la caméra que vous choisissez. Votre choix et l'image sont conservés **sur votre appareil** ; l'image est téléchargée directement chez le fournisseur de la caméra.

### 2.7 Préférences
- Langue, types de caméras affichés, réglages des alertes : conservés **sur votre appareil** uniquement.

### 2.8 Abonnement EarthVision+
- Le paiement est traité par **Google Play** ou l'**App Store** : nous ne recevons ni votre moyen de paiement, ni votre nom, ni votre e-mail.
- L'état de votre abonnement est géré par **RevenueCat**, qui reçoit du store le reçu d'achat (produit, date, renouvellement) associé à un identifiant d'utilisateur anonyme créé par l'Application.

### 2.9 Ce que nous ne collectons PAS
Nom, e-mail, adresse, date de naissance, contacts, photos, historique de navigation, identifiant publicitaire. **Aucun suivi publicitaire.** Aucune statistique d'usage ni rapport de plantage à ce jour.

## 3. Services tiers

| Service | Rôle | Données concernées |
|---|---|---|
| **Supabase** (Supabase Inc., serveurs en Irlande) | Base de données, connexion anonyme, liste des caméras | Identifiant anonyme, favoris, notes, signalements, adresse IP (journaux techniques) |
| **RevenueCat** (RevenueCat Inc., États-Unis) | Gestion de l'abonnement EarthVision+ | Identifiant anonyme d'achat, reçus d'achat transmis par le store, adresse IP ([politique RevenueCat](https://www.revenuecat.com/privacy)) |
| **Mapbox** (Mapbox Inc., États-Unis) | Carte et globe | Adresse IP, données techniques et télémétrie anonyme du SDK ([politique Mapbox](https://www.mapbox.com/legal/privacy)) |
| **YouTube** (Google) | Lecture des lives YouTube | Données collectées par le lecteur YouTube lorsque vous regardez une vidéo ([règles de confidentialité Google](https://policies.google.com/privacy)) |
| **Windy** et autres **fournisseurs des caméras** (TfL, Fintraffic, départements des transports…) | Envoi des images et vidéos | Adresse IP, comme pour toute page web consultée |
| **MET Norway** (Institut météorologique norvégien) | Météo affichée sur la page d'une caméra | Coordonnées **de la caméra** (pas les vôtres), adresse IP |
| **Wikipédia** (Wikimedia Foundation) | Carte « À propos de ce lieu » | Coordonnées **de la caméra**, adresse IP |
| **NOAA** (agence américaine, prévisions de météo spatiale) | Prévision des aurores | Adresse IP uniquement |
| **Google Play / App Store** | Téléchargement, notes, achats | Selon leurs propres politiques |

Certaines données peuvent être traitées hors de l'Union européenne (RevenueCat, Mapbox, Google), dans le cadre de garanties appropriées (EU-US Data Privacy Framework ou clauses contractuelles types).

## 4. Base légale

- **Exécution du service** : identifiant anonyme, favoris, abonnement, localisation à la demande.
- **Intérêt légitime** : notes, signalements, journaux techniques (sécurité, amélioration de l'app).
- **Consentement** : localisation et notifications (permissions système, retirables à tout moment).

## 5. Tâche de fond

Pour les alertes d'aurores et le widget, l'Application effectue environ une fois par heure une courte tâche en arrière-plan (programmée par Android, uniquement avec une connexion Internet) : consultation de la prévision de la NOAA et rechargement de l'image du widget. Elle ne transmet aucune donnée personnelle.

## 6. Vos droits (RGPD / CCPA)

Vous pouvez accéder à vos données, les rectifier, les supprimer, vous opposer à leur traitement ou demander leur portabilité.

- **Suppression immédiate :** dans l'Application, **Profil → Supprimer mes données**. Votre identifiant anonyme, vos favoris et vos notes sont effacés de nos serveurs et de votre appareil.
- **Par e-mail :** **simondouz81150@gmail.com**. Réponse sous **30 jours maximum**. Voir aussi la [page de suppression des données](./DATA_DELETION.html).
- Vous pouvez déposer une réclamation auprès de la **CNIL** (cnil.fr).

## 7. Conservation

- Identifiant anonyme, favoris, notes : jusqu'à la suppression de vos données.
- Signalements : conservés sans lien avec vous après suppression de vos données.
- Données d'abonnement chez RevenueCat : pendant la durée nécessaire à la gestion de l'abonnement et aux obligations légales.
- Données sur l'appareil (préférences, position arrondie, widget) : effacées à la désinstallation.
- Journaux techniques : quelques jours, selon la politique de chaque hébergeur.

## 8. Sécurité

Toutes les communications avec nos serveurs sont chiffrées (**HTTPS / TLS**). Les accès à la base sont protégés par des règles de sécurité par ligne : chaque utilisateur ne peut lire et modifier que ses propres favoris.

## 9. Enfants

Les webcams montrent des lieux publics en direct, dont le contenu n'est pas contrôlé à l'avance. L'Application est destinée à un public de **13 ans et plus**. Nous ne collectons sciemment aucune donnée d'enfants de moins de 13 ans.

## 10. Personnes filmées

Les caméras filment des lieux publics et appartiennent à leurs exploitants. Si vous pensez qu'une caméra porte atteinte à votre vie privée, utilisez « Signaler un problème » dans le lecteur ou écrivez-nous : nous la retirons de l'Application sous **7 jours**.

## 11. Modifications

Cette politique peut évoluer (par exemple à l'arrivée de la publicité). La date de mise à jour en tête de page indique la dernière version ; les changements importants seront annoncés dans l'Application.

## 12. Droit applicable et contact

Cette politique est régie par le droit **français**. Pour toute question : **simondouz81150@gmail.com**.
