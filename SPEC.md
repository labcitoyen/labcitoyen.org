# **Spécification de Développement Web : LabCitoyen.org (Montréal)**

## **1\. Contexte du Projet et Objectifs**

**LabCitoyen.org** est un tremplin (hub) montréalais pour des projets de **technologies citoyennes (civic tech)**. L'objectif est de démocratiser les données ouvertes, d'outiller les citoyens et de proposer un espace d'expérimentation (laboratoire) pour de nouveaux systèmes d'implication citoyenne et de démocratie participative.

**Objectifs principaux :**

* **Convaincre les élus locaux (tous partis confondus)** de la valeur de l'hyper-local et de l'implication citoyenne par la technologie de pointe.  
* **Éduquer et outiller les citoyens** : vulgarisation des données ouvertes (ex: portail de la Ville de Montréal), ateliers de sensibilisation technologique et politique.  
* **Incuber de nouveaux systèmes** : servir de laboratoire de recherche et développement pour des outils civiques concrets, en explorant des technologies émergentes comme l'IA, l'identité décentralisée et les plateformes de participation (ex: Decidim).

## **2\. Identité Visuelle et Design**

* **Nouveau Logo (à créer) :** Le concept doit s'éloigner de l'ancien microscope pour illustrer plutôt le lien entre le numérique, la ville de Montréal et les citoyens (ex: réseau, pixels, urbanisme interactif).  
* **Palette de couleurs et Style :** *\[À définir : en attente du choix de la direction (Institutionnelle, Urbaine ou Minimaliste/Data)\]*  
* **Typographie :** Claire, lisible, moderne (sans-serif) pour inspirer confiance et rigueur technique.  
* **Inspiration UX/UI :** Style épuré, orienté vers la visualisation de données et la clarté de l'information (exemple d'inspiration : https://velo.gabfortin.com/). Tonalité professionnelle, neutre, inclusive et orientée vers l'action citoyenne.

## **3\. Contraintes Techniques**

* **Hébergement :** Github Pages.  
* **Technologies strictement requises :** Fichiers statiques purs (HTML5, CSS, Vanilla JavaScript). **Aucun générateur de site statique** (pas de Jekyll, Astro, etc.) ni framework nécessitant un build (pas de React/Next.js).  
* **Styling :** Tailwind CSS (intégré via CDN pour un prototypage sans étape de compilation).  
* **Données :** Fetch API en Vanilla JS pour charger d'éventuels fichiers JSON/CSV locaux ou interroger des API de données ouvertes.

## **4\. Architecture du Site (Sitemap \- Version Single Page Application HTML)**

### **4.1. Page d'Accueil (/index.html)**

* **Hero Section :** Message fort sur l'empowerment citoyen, la civic tech, et le prototypage de la démocratie de demain à Montréal.  
* **Pitch pour les Élus & Citoyens :** Pourquoi comprendre et utiliser les technologies civiques hyper-locales transforme nos quartiers.  
* **Les 3 Piliers du LabCitoyen :**  
  1. *Exploration de Données* (Exploiter le portail de la Ville, vulgarisation).  
  2. *Développement et Expérimentation* (Laboratoire de création de systèmes civiques et R\&D technologique).  
  3. *Ateliers et Sensibilisation* (Agir et s'impliquer techniquement et politiquement).

### **4.2. Section Projets et Laboratoire d'Innovation (Idéation & Démo)**

* **Démocratie participative et Plateformes :** Expérimentation et déploiement d'outils reconnus comme **Decidim** pour structurer les consultations citoyennes de quartier.  
* **Technologies Émergentes (R\&D) :**  
  * **Identité numérique décentralisée** : Recherche sur la vérification citoyenne respectueuse de la vie privée pour les consultations locales.  
  * **Intelligence Artificielle** : Application de l'IA pour l'analyse de données urbaines, la vulgarisation d'informations complexes ou l'assistance aux requêtes citoyennes.  
* **Systèmes d'implication de quartier :** Développement de plateformes d'engagement pragmatiques (ex: système de participation à la propreté urbaine en cours de réflexion pour quartierneuf.ca).  
* **Visualisation de données locales :** Projets exploitant les données ouvertes (ex: tableaux de bord sur les passages cyclistes).

### **4.3. Section Ateliers et Implication**

* Exemples d'ateliers proposés :  
  * *Introduction à l'application des technologies à l'implication politique.*  
  * *Comment lire et utiliser le portail de Données Ouvertes de Montréal ?*  
  * *Démystifier l'IA et l'identité numérique pour l'action citoyenne.*

### **4.4. Section Équipe & Communauté (Contact)**

* **Le Lab :** Espace neutre d'innovation, d'expérimentation et d'engagement citoyen.  
* **L'Équipe :** Nous sommes en train de bâtir notre noyau dur \! Nous recherchons des profils avec de fortes compétences techniques (logiciel, données, IA, design) qui sont de véritables amoureux de Montréal et de la vie de quartier.  
* **Appel à l'action :** Adresse courriel (et GitHub/Discord futur) pour inviter les talents technologiques à se joindre au lab, ainsi que les organismes et élus à collaborer sur des preuves de concept (PoC).

## **5\. Stratégie de Contenu (Directives pour la génération de texte)**

* **Accroche locale inclusive :** Mentionner des enjeux montréalais globaux qui touchent tous les arrondissements sans cibler de secteur ou de parti politique précis : la mobilité sécuritaire, la propreté, et la cohabitation urbaine.  
* **Vocabulaire clé :** Civic tech, technologies citoyennes, données ouvertes, démocratie participative, Decidim, intelligence artificielle (IA), identité numérique décentralisée, laboratoire d'idées, action de quartier.

## **6\. Instructions pour le modèle IA générant le code**

1. Générer un fichier index.html unique (Single Page) contenant toute la structure du site.  
2. Utiliser \<script src="https://cdn.tailwindcss.com"\>\</script\> dans le \<head\> pour le style.  
3. Créer un menu de navigation "Sticky" (Accueil, Projets & R\&D, Ateliers, Équipe/Contact) avec défilement fluide vers les sections d'ancrage.  
4. Intégrer des icônes SVG directement dans le code HTML pour illustrer les piliers et les projets.  
5. *Le design précis et les couleurs devront suivre les directives établies dans la section 2\.*  
6. Inclure des maquettes visuelles intégrées en HTML/CSS (ex: bloc de graphique stylisé ou schéma réseau) pour illustrer la section des projets.
