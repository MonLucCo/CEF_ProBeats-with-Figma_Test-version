# CEF_ProBeats-with-Figma_Test-version
Etablissement de la maquette d'un site d'e-commerce (ProBeats) avec l'outil FIGMA et selon les spécifications du CEF

## Versioning du projet
Le projet est découpé en 7 étapes. Pour chacune de ces étapes,  l'export d'un document Figma (.fig) établit l'historique du contenu à cette étape. Cet export est accessible à partir du dossier `designs`.
La dernière étape produit la version qui répond à l'ensemble des exigences et des contraintes du projet selon les spécifications du CEF.

## Objectif du projet
Le projet est un devoir mené dans le cadre d'une formation. Il consiste à réaliser la __maquette d'un site d'e-commerce__ d'une société fictive. La maquette se compose du `wireframe` de chaque page du site (5 pages pour _desktop_, 5 pages pour _mobile_), ainsi que du développement du `prototype` de la page d'accueil du site selon l'_identité graphique_ de l'entreprise.

## Historique des designs

### étape 1 : création du projet
 - Nom du fichier : `CEF_ProBeats-Wireframing Starter Kit_Etape 1.fig`
 - Description : projet _ProBeats_ établi à partir de la bibliothèque _Wireframing Starter Kit_ contenant des pages structurelles vierges à compléter pour la réalisation du sujet.

### étape 2 : définir les éléments structurels du projet
 - Page "Tools & Process" : création du flux utilisateur
 - Page "Wireframe Lo-Fi" : pour la créations des wireframes
 - Page "Desktop Hi-Fi" : pour le prototype du desktop
 - Page "Mobile Hi-Fi" : pour le prototype du mobile

### étape 3 : définir en wireframe les éléments des cibles `desktop` et `mobile`
 - Page "Components" : création de l'ensemble des composants avec des variantes adaptées aux cibles
   - élémnts répétés : Footer et Header (Navbar, Step, Hero)
   - éléments de section : 
     - Flagship Product, Popular Product (Card Product), Testimonials, Product Page, Shopping page
     - About Us (Stories, Benefits), Assistance (Services, FAQ)
     - Authentication, Checkout, Payment, Thanks, Sign In, Sign Up
     - 404-Error page
 - Page "Wireframe Lo-Fi" : création des pages en wireframe pour les cibles `desktop` et `mobile`
   - Page Accueil, Page Produit, Page Commande, Page A Propos, Page Assistance
   - Fonction achat avec les étapes (steps) : Authentication (Sign In, Sign Up), Checkout, payment, Thanks
   - Fonction Contact et Assistance
   - Fonction Error Page 404
 - Page "Tools & Process" : création du flux utilisateur "Buying Process"

### étape 4 : restructurer le document Figma et les pages du projet `ProBeats`
 - Les pages du projet _ProBeats_ sont définies avec un préfixe : 
   - `Source` pour les pages du fichier initial, `Initial` pour les premiers travaux de développement et `ProBeats` pour la version utile du projet.
   - Dans la version de référence, seules les pages `ProBeats` seront conservées.
 - Les composants ont été développés en 2 étapes à partir d'un kit initial
   - Les composants du kit initial se trouvent dans les pages `Source - Components` et `Source - Building Blocks`
   - Les composants de la version d'étude se trouvent dans les pages `Initial - Components`, `Initial - Old-Components` et `Initial _ Building Blocks`
   - Les composants de référence se trouvent dans les pages `ProBeats - Components` et `ProBeats - Building Blocks`
   - Tous les composants qui servent de référence sont nommés avec le préfixe `Widget`
 - Création des pages `wireframe` pour les cibles __Desktop__ et __Mobile__
   - Les pages pour chaque cible sont réparties en pages principales (Main Pages) et secondaire (Secondary Pages)
   - Une animation de navigation est disponible pour les pages principales (Home, Product, About, Help, Shipping)
   - Les pages secondaires servent pour la gestion d'erreur (Error 404) et la fonction __Achat__
 - Création des Users Flows dans la page `ProBeats - Tools & Process`
   - User Flow __Navigation & SHOP - Order Buying__ pour les cibles `Desktop` et `Mobile`
