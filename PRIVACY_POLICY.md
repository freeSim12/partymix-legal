---
title: Privacy Policy
permalink: /PRIVACY_POLICY.html
---

# Politique de confidentialité — PartyMix

_Dernière mise à jour : 14 juin 2026_

La présente politique décrit comment l'application **PartyMix** (« l'Application », « nous ») collecte, utilise et protège les informations lorsque vous utilisez l'Application sur iOS ou Android.

---

## 1. Éditeur

L'Application est éditée par **PartyMix**, joignable à l'adresse **simondouz81150@gmail.com**.

## 2. Données collectées

PartyMix est conçu pour minimiser la collecte de données. Voici exhaustivement ce que l'Application traite :

### 2.1 Identifiant de l'appareil
- **Quoi :** un identifiant technique généré par l'appareil (pas votre nom, pas votre e-mail).
- **Pourquoi :** associer un éventuel **code premium** à votre appareil, afin que vous n'ayez pas à le re-saisir.
- **Où :** stocké dans Google Firebase Firestore (collection `users`).
- **Durée :** jusqu'à ce que vous désinstalliez l'Application ou demandiez la suppression.

### 2.2 Rapports de crash (Firebase Crashlytics)
- **Quoi :** nature de l'erreur, ligne de code, version de l'app, modèle d'appareil, version d'OS, langue.
- **Pourquoi :** détecter et corriger les bugs.
- **Ce qui n'est PAS collecté :** aucun contenu saisi, aucune photo, aucun nom de joueur.
- **Durée :** 90 jours (politique Firebase par défaut).

### 2.3 Statistiques d'usage (Firebase Analytics)
- **Quoi :** événements anonymes (ouverture de l'application, démarrage de session, navigation entre écrans), modèle d'appareil, version d'OS, pays approximatif, langue.
- **Pourquoi :** mesurer l'usage de l'Application (nombre d'utilisateurs actifs, rétention, popularité des jeux) pour orienter les améliorations futures.
- **Ce qui n'est PAS collecté :** aucun identifiant publicitaire (IDFA/AAID), aucun nom de joueur, aucune donnée saisie.
- **Tracking :** PartyMix ne suit **pas** les utilisateurs à travers d'autres applications ou sites web.
- **Durée :** par défaut 2 mois (paramétrable depuis Firebase Console).

### 2.4 Achats intégrés
- Lorsque vous achetez une option premium, la transaction est traitée par **Google Play Billing** (Android) ou **App Store** (iOS). PartyMix reçoit uniquement un accusé de réception anonymisé — pas votre moyen de paiement, pas votre identité.

### 2.5 Photos (jeu « Photo Roulette »)
- Les photos que vous choisissez depuis votre pellicule **ne quittent jamais le réseau Wi-Fi local**.
- Elles sont partagées de téléphone à téléphone via un serveur HTTP local pendant la partie, puis **supprimées** à la fin de la session.
- **Aucune photo n'est envoyée à nos serveurs ou à un tiers.**

### 2.6 Ce que nous NE collectons PAS
- Nom, adresse, date de naissance.
- Géolocalisation précise ou approximative.
- Contacts, SMS, historique d'appels.
- Historique de navigation.
- Données biométriques.
- Identifiants publicitaires (IDFA, AAID) — **aucun tracking publicitaire**.

## 3. Sous-traitants

Les prestataires suivants traitent des données pour notre compte dans le cadre de l'Application :

| Prestataire | Rôle | Données traitées | Base juridique |
|---|---|---|---|
| **Google Firebase** (Google Ireland Ltd) | Hébergement Firestore, Authentification, Crashlytics, Analytics | ID appareil, logs de crash, événements anonymes d'usage | Intérêt légitime / exécution contractuelle |
| **Google Play Billing** | Facturation Android | Identifiant de transaction | Exécution contractuelle |
| **Apple App Store / StoreKit** | Facturation iOS | Identifiant de transaction | Exécution contractuelle |

Les données Firebase peuvent être transférées hors de l'Union européenne. Google est certifié EU-US Data Privacy Framework.

## 4. Vos droits (RGPD / CCPA)

Conformément au RGPD (UE) et au CCPA (Californie), vous disposez des droits suivants :

- **Accès** : savoir quelles données nous détenons sur vous.
- **Rectification** : faire corriger une donnée inexacte.
- **Effacement** (« droit à l'oubli ») : obtenir la suppression de vos données.
- **Opposition** : refuser certains traitements (ex : Crashlytics).
- **Portabilité** : recevoir vos données dans un format structuré.

Pour exercer ces droits, écrivez à **simondouz81150@gmail.com**. Nous répondons sous **30 jours maximum**.

Vous pouvez également déposer une réclamation auprès de l'autorité de contrôle (CNIL en France : cnil.fr).

## 5. Conservation des données

- **ID appareil + statut premium** : jusqu'à désinstallation ou demande de suppression.
- **Logs Crashlytics** : 90 jours.
- **Photos Photo Roulette** : supprimées en fin de session.

## 6. Sécurité

Les communications avec Firebase utilisent **HTTPS/TLS 1.2+**. L'Application n'expose de serveur HTTP qu'en réseau local Wi-Fi pour Photo Roulette, inaccessible depuis Internet.

## 7. Enfants

L'Application est destinée à un public de **16 ans et plus**. Certains jeux contiennent des défis à consommer de l'alcool de manière responsable et des thèmes adultes. Nous ne collectons sciemment aucune donnée de mineurs de moins de 13 ans.

## 8. Modifications

Cette politique peut être modifiée. La date de « dernière mise à jour » en tête de page reflète la dernière révision. Les modifications substantielles seront notifiées à l'ouverture de l'Application.

## 9. Droit applicable

Cette politique est régie par le droit de **France**. Tout litige sera porté devant les juridictions compétentes de ce ressort.

## 10. Contact

Pour toute question : **simondouz81150@gmail.com**.

---

# Privacy Policy — PartyMix (English)

_Last updated: 2026-06-14_

This Privacy Policy describes how **PartyMix** (the "App", "we") collects, uses, and protects information when you use the App on iOS or Android.

## 1. Publisher

The App is published by **PartyMix**, contact: **simondouz81150@gmail.com**.

## 2. Data we collect

PartyMix minimizes data collection. Here is the exhaustive list:

- **Device ID** — a technical identifier (not your name, email, or any personal info) used to link a premium code to your device. Stored in Google Firestore.
- **Crash reports** (Firebase Crashlytics) — error type, stack trace, app version, device model, OS version, locale. **No user content, no photos, no player names.** Retained 90 days.
- **Usage analytics** (Firebase Analytics) — anonymous events (app opens, session starts, screen views), device model, OS version, approximate country, language. **No advertising IDs, no player names, no content.** We do **NOT** track you across other apps or websites. Default retention: 2 months.
- **In-app purchases** — processed by Google Play / App Store. We only receive an anonymized receipt.
- **Photos (Photo Roulette game)** — never leave your local Wi-Fi. Shared peer-to-peer during the session and deleted afterward. **Never uploaded to our servers.**

### What we do NOT collect
Name, address, birthdate, location, contacts, SMS, browsing history, biometrics, advertising IDs. **No ad tracking.**

## 3. Processors

| Processor | Purpose |
|---|---|
| Google Firebase (Ireland Ltd) | Firestore, Auth, Crashlytics |
| Google Play Billing | Android IAP |
| Apple App Store / StoreKit | iOS IAP |

Firebase data may be transferred outside the EU. Google is EU-US Data Privacy Framework certified.

## 4. Your rights (GDPR / CCPA)

You can request access, correction, deletion, or portability of your data by emailing **simondouz81150@gmail.com**. We respond within 30 days. You may also lodge a complaint with your local data protection authority.

## 5. Retention

- Device ID + premium status: until uninstall or deletion request.
- Crashlytics logs: 90 days.
- Photo Roulette photos: deleted at session end.

## 6. Security

Communications with Firebase use HTTPS/TLS 1.2+. The local HTTP server (Photo Roulette) is only reachable on the local Wi-Fi and not exposed to the internet.

## 7. Children

The App is intended for users **16+**. Some games contain responsible-drinking challenges and adult themes. We do not knowingly collect data from children under 13.

## 8. Changes

We may update this policy. The "last updated" date reflects the latest revision. Material changes will be announced in-app.

## 9. Governing law

This policy is governed by the law of **France**. Any dispute will be brought before the competent courts of this jurisdiction.

## 10. Contact

For any question: **simondouz81150@gmail.com**.
