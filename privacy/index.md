# Politique de confidentialité — Privacy Policy

**Application :** LUBB<br>
**Exploitant / Operator :** Ismael Badache, entreprise individuelle / sole proprietor<br>
**Nom d'entreprise / Business name :** Application mobile LUBB<br>
**Lieu d'exploitation / Place of operation :** Saint-Charles-Borromée (Québec), Canada<br>
**Responsable de la protection des renseignements personnels / Privacy Officer :** Ismael Badache<br>
**Contact :** lubb.support@gmail.com<br>
**Dernière mise à jour / Last updated :** 2026-07-22<br>

---

## Français

### 1. Résumé

LUBB regroupe des fonctions de nutrition, d'entraînement, de budget personnel, de suppléments, d'objectifs corporels et d'analyse assistée par intelligence artificielle (« Lumen »). Certaines de ces informations peuvent être sensibles.

Nous utilisons vos renseignements pour fournir et sécuriser LUBB, synchroniser vos données, générer les fonctions que vous demandez, gérer les abonnements, comprendre l'utilisation du produit et corriger les erreurs. Nous ne vendons pas vos renseignements personnels et nous ne les utilisons pas pour de la publicité comportementale entre applications.

### 2. Renseignements recueillis

| Catégorie | Exemples | Source et finalité |
|---|---|---|
| Compte et profil | Courriel, identifiant UUID, langue, nom affiché, fuseau horaire, préférences et progression d'accueil | Fournis par vous ou générés lors de la création du compte; utilisés pour l'authentification, la personnalisation et la synchronisation. Le mot de passe est traité et haché par Supabase Auth; LUBB ne le conserve pas en clair. |
| Nutrition et hydratation | Objectifs, repas, descriptions, calories, macronutriments, eau, recettes, ingrédients, coûts et horaires | Saisis par vous ou produits à partir d'une Capture que vous confirmez; utilisés pour Fuel, Lumen et le Débrief. |
| Entraînement et corps | Âge, sexe, taille, poids, objectifs, blessures ou limitations, sommeil, stress, courbatures, séances, exercices, séries, répétitions, charges, notes, phases corporelles et pesées | Saisis par vous; utilisés pour Kinetix, Body Goal, Lumen et le Débrief. Ces renseignements peuvent être sensibles. |
| Budget personnel | Devise, revenus, soldes, dates de paie, dépenses, catégories, montants, transferts, fonds, provisions, objectifs d'épargne et clôtures mensuelles | Saisis ou confirmés par vous; utilisés pour Wealth, Capture et Lumen. LUBB n'est pas un service bancaire et ne se connecte pas directement à votre banque. |
| Suppléments et rappels | Nom, dose, quantité, forme, horaire, règles alimentaires, notes, avertissements, coût et confirmations de prise | Saisis par vous; utilisés pour Pill Stack, les rappels locaux et Lumen. |
| Capture, Lumen et données inférées | Texte libre soumis à Capture, actions structurées confirmées, agrégats quotidiens, tendances, signaux, réactions, mémoire Lumen, analyses et débriefs | Fournis par vous ou générés à partir de votre historique; utilisés pour transformer vos captures et personnaliser Lumen. |
| Achats et abonnement | Identifiant d'utilisateur d'application, produit, transaction ou reçu, statut d'essai, renouvellement, abonnement et droit d'accès `lubb_plus` | Reçus d'Apple et de RevenueCat; utilisés pour valider, restaurer et gérer l'accès payant. LUBB ne reçoit pas votre numéro de carte. |
| Utilisation du produit | UUID pseudonymisé, langue, écrans visités, cycle de vie de l'app et événements agrégés comme l'accueil terminé ou une fonction utilisée | Recueillis automatiquement par PostHog afin de mesurer l'utilisation et améliorer LUBB. Dans la configuration actuelle, le texte Capture, les noms de repas, les montants et les valeurs corporelles ne sont pas envoyés à PostHog. |
| Diagnostics et sécurité | UUID, langue, écran, version de l'app, appareil et système, sessions, traces de performance échantillonnées, erreurs et piles d'exécution | Recueillis automatiquement par Sentry, Supabase et l'infrastructure afin de détecter les pannes, abus et problèmes de sécurité. |
| Soutien | Adresse courriel et contenu que vous choisissez d'envoyer au soutien | Utilisés pour répondre à votre demande. N'envoyez jamais votre mot de passe, vos données de carte ou des renseignements sensibles inutiles. |

### 3. Caméra, notifications et stockage local

La caméra est utilisée pour lire un code-barres alimentaire. L'image de la caméra n'est pas enregistrée ni téléversée par LUBB; le code-barres peut être transmis à Open Food Facts pour rechercher le produit. LUBB peut conserver sur l'appareil des caches, brouillons, préférences, confirmations d'accès payant et notifications locales. Ces données locales sont normalement effacées lors de la suppression du compte ou de la désinstallation, sous réserve du fonctionnement du système d'exploitation.

### 4. Intelligence artificielle et profilage Lumen

Capture et Lumen peuvent transmettre à **OpenAI** ou **Anthropic**, selon la fonction et la configuration active :

- le texte libre que vous soumettez à Capture;
- des résumés ou agrégats concernant la nutrition, l'entraînement, le budget, les suppléments, le sommeil, le poids et vos objectifs;
- le contexte nécessaire pour produire une analyse ou un débrief.

Nous n'ajoutons pas volontairement votre courriel ou votre UUID aux requêtes envoyées aux modèles, mais votre texte libre peut contenir des renseignements identifiants. Évitez d'y inscrire des renseignements qui ne sont pas nécessaires.

Lumen analyse votre historique, repère des tendances, classe des signaux et adapte ses observations avec le temps. Ce traitement peut constituer du profilage. Il sert uniquement à personnaliser l'expérience LUBB; il ne décide pas de votre admissibilité à un crédit, une assurance, un emploi ou un produit financier et ne produit aucune décision juridiquement contraignante.

Les résultats peuvent être incomplets ou inexacts. Ils ne remplacent jamais un professionnel de la santé, de la nutrition, de la finance, de la fiscalité ou du droit. Lorsque la loi l'exige, une information claire et une permission distincte doivent être présentées avant la transmission de renseignements personnels à un fournisseur d'IA. Vous pouvez vous opposer au traitement futur par Lumen ou retirer votre consentement en écrivant à lubb.support@gmail.com; certaines fonctions d'IA pourront alors être désactivées.

### 5. Analyse produit et diagnostics

PostHog relie les événements à un UUID pseudonymisé afin de mesurer l'adoption et la rétention. Cet identifiant n'est pas anonyme puisqu'il peut être relié à votre compte. L'autocapture des interactions et la répétition de session ne sont pas activées dans la configuration actuelle.

Sentry reçoit les erreurs, les piles d'exécution, la route active et certains renseignements techniques. Nous cherchons à ne pas lui transmettre volontairement le contenu de vos repas, vos montants, votre texte Capture ou vos sorties Lumen.

Pour retirer votre consentement à une analyse facultative ou demander la suppression d'un profil analytique associé, contactez le responsable de la vie privée. Le retrait n'affecte pas les traitements déjà effectués légalement et peut limiter certaines fonctions tant qu'un contrôle intégré à l'app n'est pas disponible.

### 6. Achats et abonnements

Apple traite le paiement et les données de facturation. RevenueCat reçoit un identifiant d'utilisateur LUBB ainsi que l'historique et le statut nécessaires pour valider les reçus, prévenir la fraude, synchroniser l'abonnement et accorder l'accès. Supprimer le compte LUBB n'annule pas automatiquement un abonnement Apple et ne supprime pas les registres qu'Apple ou RevenueCat doivent conserver.

### 7. Fournisseurs de services

| Fournisseur | Rôle et renseignements concernés |
|---|---|
| [Supabase](https://supabase.com/privacy) | Authentification, base de données, fonctions serveur, journaux et sauvegardes; reçoit le compte et les données applicatives. |
| [OpenAI](https://openai.com/policies/privacy-policy/) et [Anthropic](https://privacy.anthropic.com/) | Traitement des requêtes Capture, Lumen et Débrief; reçoivent uniquement le contexte envoyé par les fonctions serveur. |
| [RevenueCat](https://www.revenuecat.com/privacy/) et [Apple](https://www.apple.com/legal/privacy/) | Paiement, validation des reçus, historique d'achat, statut d'abonnement et droits d'accès. |
| [PostHog](https://posthog.com/privacy) | Analyse produit pseudonymisée et événements d'utilisation. |
| [Sentry](https://sentry.io/privacy/) | Diagnostic d'erreurs, sessions et performance. |
| [Open Food Facts](https://world.openfoodfacts.org/terms-of-use) | Recherche de produit à partir d'un code-barres. |
| [Expo / EAS](https://expo.dev/privacy) | Infrastructure de développement et de distribution des versions de l'app. |
| Google / Gmail | Réception et traitement des courriels envoyés volontairement au soutien. |
| GitHub Pages | Hébergement public des présentes pages légales. |

Nous utilisons ces fournisseurs pour exploiter LUBB et leur demandons de protéger les renseignements conformément à leurs obligations et à leurs engagements applicables. Nous ne les autorisons pas à vendre le contenu LUBB ni à l'utiliser pour faire de la publicité ciblée pour leur propre compte.

### 8. Traitement hors Québec

Certains fournisseurs peuvent traiter ou conserver des renseignements à l'extérieur du Québec ou du Canada, notamment aux États-Unis. Les renseignements peuvent alors être soumis aux lois du territoire concerné. Nous cherchons à limiter les renseignements transmis et à utiliser des mesures contractuelles, organisationnelles et techniques adaptées. LUBB demeure responsable de ses obligations relativement aux renseignements confiés à ses fournisseurs.

### 9. Conservation et suppression

| Catégorie | Critère de conservation |
|---|---|
| Compte et données principales | Conservés pendant l'existence du compte. La suppression dans l'app vise à supprimer immédiatement le compte d'authentification et les principales données reliées. Une demande vérifiée par courriel est traitée dans un délai maximal de 30 jours. |
| Signaux Lumen | Les événements de signal Lumen sont supprimés après environ 90 jours. Les autres analyses, mémoires et débriefs sont normalement conservés jusqu'à leur suppression ou celle du compte. |
| Achats et abonnements | Conservés aussi longtemps que nécessaire pour gérer les droits, les remboursements, la fraude, la comptabilité et les obligations d'Apple ou de RevenueCat. |
| Analyse, diagnostics et journaux | Conservés pendant une durée limitée déterminée par la configuration et les obligations du fournisseur. Ils peuvent subsister après la suppression du compte jusqu'à l'expiration de leur rétention ou au traitement d'une demande applicable. |
| Soutien | Conservé le temps nécessaire pour répondre, assurer le suivi et respecter les obligations applicables. |
| Sauvegardes et registres opérationnels | Peuvent subsister pendant leur cycle de rotation ou lorsqu'une conservation est nécessaire à la sécurité, à la prévention de la fraude ou au respect de la loi. Leur accès est limité. |

La suppression du compte ne garantit pas l'effacement immédiat de renseignements détenus indépendamment par Apple ni de chaque copie technique chez un fournisseur. Pour demander la suppression de tout renseignement restant que LUBB peut raisonnablement relier à vous, utilisez la [page de suppression](/lubb-legal/delete-account/) ou contactez-nous.

### 10. Sécurité et incidents

LUBB utilise notamment HTTPS/TLS, le hachage des mots de passe par Supabase Auth, des contrôles d'accès, Row Level Security et des clés serveur séparées. Aucun système n'est parfaitement sûr. En cas d'incident présentant un risque de préjudice sérieux, nous prendrons les mesures requises et aviserons les personnes et autorités concernées lorsque la loi l'exige.

### 11. Vos droits et vos choix

Selon la loi applicable, vous pouvez demander :

- l'accès à vos renseignements;
- la correction de renseignements inexacts;
- la suppression ou la désindexation lorsque applicable;
- une copie portable des renseignements informatisés recueillis auprès de vous;
- le retrait d'un consentement ou une opposition à certains traitements;
- des précisions sur l'utilisation, les fournisseurs et les décisions automatisées.

Écrivez à **lubb.support@gmail.com** avec l'objet « Vie privée LUBB ». Nous pouvons demander une vérification raisonnable de votre identité; n'envoyez jamais votre mot de passe. Nous répondrons dans les délais prévus par la loi. Vous pouvez également déposer une plainte auprès de la [Commission d'accès à l'information du Québec](https://www.cai.gouv.qc.ca/).

### 12. Mineurs

LUBB n'est pas destiné aux personnes de moins de 14 ans. Une personne mineure ne doit utiliser LUBB que si elle peut valablement consentir selon la loi applicable et, lorsque requis, avec le consentement d'un parent ou tuteur. Si nous apprenons qu'un compte a été créé en violation de cette règle, nous prendrons les mesures appropriées, pouvant inclure sa suppression.

### 13. Modifications

Nous pouvons modifier cette politique lorsque LUBB, ses fournisseurs ou les lois changent. Une modification importante sera signalée de manière raisonnable avant son entrée en vigueur lorsque requis. La date ci-dessus indique la version en vigueur.

---

## English

### 1. Summary

LUBB combines nutrition, training, personal budgeting, supplements, body goals, and artificial-intelligence-assisted analysis (“Lumen”). Some of this information may be sensitive.

We use your information to provide and secure LUBB, synchronize your data, generate the features you request, manage subscriptions, understand product use, and fix errors. We do not sell personal information or use it for cross-app behavioural advertising.

### 2. Information we collect

| Category | Examples | Source and purpose |
|---|---|---|
| Account and profile | Email, UUID, language, display name, time zone, preferences, and onboarding progress | Provided by you or generated when the account is created; used for authentication, personalization, and synchronization. Passwords are processed and hashed by Supabase Auth; LUBB does not store them in plain text. |
| Nutrition and hydration | Goals, meals, descriptions, calories, macronutrients, water, recipes, ingredients, costs, and times | Entered by you or generated from a Capture you confirm; used for Fuel, Lumen, and the Debrief. |
| Training and body | Age, sex, height, weight, goals, injuries or limitations, sleep, stress, soreness, workouts, exercises, sets, reps, loads, notes, body phases, and weigh-ins | Entered by you; used for Kinetix, Body Goal, Lumen, and the Debrief. This information may be sensitive. |
| Personal budget | Currency, income, balances, pay dates, expenses, categories, amounts, transfers, funds, provisions, savings goals, and monthly close operations | Entered or confirmed by you; used for Wealth, Capture, and Lumen. LUBB is not a bank and does not connect directly to your bank account. |
| Supplements and reminders | Name, dose, quantity, form, schedule, food rules, notes, warnings, cost, and intake confirmations | Entered by you; used for Pill Stack, local reminders, and Lumen. |
| Capture, Lumen, and inferred data | Free text submitted to Capture, confirmed structured actions, daily aggregates, trends, signals, reactions, Lumen memory, analyses, and debriefs | Provided by you or generated from your history; used to transform captures and personalize Lumen. |
| Purchases and subscription | App User ID, product, transaction or receipt, trial, renewal, subscription, and `lubb_plus` entitlement status | Received from Apple and RevenueCat; used to validate, restore, and manage paid access. LUBB does not receive your card number. |
| Product use | Pseudonymous UUID, language, screens visited, app lifecycle, and aggregate events such as onboarding completion or feature use | Automatically collected through PostHog to measure use and improve LUBB. Under the current configuration, Capture text, meal names, amounts, and body values are not sent to PostHog. |
| Diagnostics and security | UUID, language, screen, app version, device and operating system, sessions, sampled performance traces, errors, and stack traces | Automatically collected by Sentry, Supabase, and infrastructure to detect crashes, abuse, and security problems. |
| Support | Email address and the content you choose to send | Used to answer your request. Never send your password, card data, or unnecessary sensitive information. |

### 3. Camera, notifications, and local storage

The camera is used to read a food barcode. LUBB does not save or upload the camera image; the barcode may be sent to Open Food Facts to find the product. LUBB may keep caches, drafts, preferences, paid-access confirmations, and local notifications on the device. Local data is normally cleared when the account is deleted or the app is uninstalled, subject to operating-system behaviour.

### 4. Artificial intelligence and Lumen profiling

Capture and Lumen may send the following to **OpenAI** or **Anthropic**, depending on the feature and active configuration:

- free text you submit to Capture;
- summaries or aggregates about nutrition, training, budget, supplements, sleep, weight, and goals;
- context required to create an analysis or debrief.

We do not intentionally add your email or UUID to model requests, but free text can itself contain identifying information. Avoid entering information that is not necessary.

Lumen analyzes your history, identifies trends, ranks signals, and adapts its observations over time. This may constitute profiling. It is used only to personalize LUBB; it does not decide eligibility for credit, insurance, employment, or a financial product and does not make legally binding decisions.

Outputs may be incomplete or inaccurate. They do not replace a health, nutrition, financial, tax, or legal professional. Where required by law, clear notice and separate permission must be presented before personal information is shared with an AI provider. You may object to future Lumen processing or withdraw consent by emailing lubb.support@gmail.com; some AI features may then be disabled.

### 5. Product analytics and diagnostics

PostHog links events to a pseudonymous UUID to measure adoption and retention. This identifier is not anonymous because it can be linked to your account. Interaction autocapture and session replay are not enabled under the current configuration.

Sentry receives errors, stack traces, the active route, and some technical information. We seek not to intentionally send meal content, amounts, Capture text, or Lumen outputs to Sentry.

To withdraw consent to optional analytics or request deletion of an associated analytics profile, contact the Privacy Officer. Withdrawal does not affect processing already lawfully completed and may limit some features until an in-app control is available.

### 6. Purchases and subscriptions

Apple processes payments and billing information. RevenueCat receives a LUBB user identifier and the history and status required to validate receipts, prevent fraud, synchronize the subscription, and grant access. Deleting a LUBB account does not automatically cancel an Apple subscription or delete records Apple or RevenueCat must retain.

### 7. Service providers

| Provider | Role and information involved |
|---|---|
| [Supabase](https://supabase.com/privacy) | Authentication, database, server functions, logs, and backups; receives account and application data. |
| [OpenAI](https://openai.com/policies/privacy-policy/) and [Anthropic](https://privacy.anthropic.com/) | Processing Capture, Lumen, and Debrief requests; receive only the context sent by server functions. |
| [RevenueCat](https://www.revenuecat.com/privacy/) and [Apple](https://www.apple.com/legal/privacy/) | Payment, receipt validation, purchase history, subscription status, and entitlements. |
| [PostHog](https://posthog.com/privacy) | Pseudonymous product analytics and usage events. |
| [Sentry](https://sentry.io/privacy/) | Error, session, and performance diagnostics. |
| [Open Food Facts](https://world.openfoodfacts.org/terms-of-use) | Product lookup using a barcode. |
| [Expo / EAS](https://expo.dev/privacy) | Development and app-distribution infrastructure. |
| Google / Gmail | Receiving and processing email voluntarily sent to support. |
| GitHub Pages | Public hosting of these legal pages. |

We use these providers to operate LUBB and require them to protect information under their applicable obligations and commitments. We do not authorize them to sell LUBB content or use it for their own targeted advertising.

### 8. Processing outside Québec

Some providers may process or store information outside Québec or Canada, including in the United States. Information may then be subject to the laws of that location. We seek to limit the information transferred and use appropriate contractual, organizational, and technical safeguards. LUBB remains responsible for its obligations concerning information entrusted to providers.

### 9. Retention and deletion

| Category | Retention criterion |
|---|---|
| Account and primary data | Kept while the account exists. In-app deletion is intended to immediately delete the authentication account and primary linked data. A verified email request is processed within no more than 30 days. |
| Lumen signals | Lumen signal events are deleted after approximately 90 days. Other analyses, memories, and debriefs are normally kept until they or the account are deleted. |
| Purchases and subscriptions | Kept as needed to manage entitlements, refunds, fraud, accounting, and Apple or RevenueCat obligations. |
| Analytics, diagnostics, and logs | Kept for a limited period determined by provider configuration and obligations. They may remain after account deletion until retention expires or an applicable request is processed. |
| Support | Kept as needed to answer, follow up, and meet applicable obligations. |
| Backups and operational records | May remain during their rotation cycle or when retention is required for security, fraud prevention, or legal compliance. Access is restricted. |

Account deletion does not guarantee immediate deletion of information independently held by Apple or every technical copy held by a provider. To request deletion of any remaining information LUBB can reasonably link to you, use the [deletion page](/lubb-legal/delete-account/) or contact us.

### 10. Security and incidents

LUBB uses measures including HTTPS/TLS, password hashing through Supabase Auth, access controls, Row Level Security, and separate server keys. No system is perfectly secure. If an incident presents a risk of serious harm, we will take required steps and notify affected people and authorities where required by law.

### 11. Your rights and choices

Depending on applicable law, you may request:

- access to your information;
- correction of inaccurate information;
- deletion or de-indexation where applicable;
- a portable copy of computerized information collected from you;
- withdrawal of consent or objection to certain processing;
- information about uses, providers, and automated decisions.

Email **lubb.support@gmail.com** with the subject “LUBB Privacy.” We may reasonably verify your identity; never send your password. We will respond within the time required by law. You may also complain to the [Commission d'accès à l'information du Québec](https://www.cai.gouv.qc.ca/).

### 12. Minors

LUBB is not intended for anyone under 14. A minor should use LUBB only if they can validly consent under applicable law and, where required, with consent from a parent or guardian. If we learn that an account was created in violation of this rule, we will take appropriate steps, which may include deletion.

### 13. Changes

We may update this policy when LUBB, its providers, or applicable laws change. A material change will be communicated reasonably before taking effect where required. The date above identifies the current version.
