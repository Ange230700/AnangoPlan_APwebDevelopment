<!--! PROJECT DESCRIPTION -->

# AnangoPlan_APwebDevelopment - Project Description

This is the full stack development of **AnangoPlan (AP)**.\
**AP** is for the mass market.\
This document will detail the process, the steps and the tools necessary to develop the site.\
There will be four major phases in this document :

- The pre-development phase
- The front-end development phase
- The back-end development phase
- The post-development phase

> _Il s'agit du développement complet du site web **AnangoPlan (AP)**._\
> _**AP** est pour la vente de masse._\
> _Ce document détaillera le processus, les étapes et les outils nécessaires au développement du site._\
> _Il y aura quatre grandes phases dans ce document :_
>
> - _La phase de pré-développement_
> - _La phase de développement front-end_
> - _La phase de développement back-end_
> - _La phase de post-développement_

## Table of contents / Table des matières

- [I. Pre-development phase / Phase de pré-développement](#i-pre-development-phase--phase-de-pré-développement)

  - [I. A. Purpose / Objectif](#i-a-purpose--objectif)

  - [I. B. Website features / Fonctionnalités du site](#i-b-website-features--fonctionnalités-du-site)

    - [I. B. 1. Essential features / Fonctionnalités essentielles](#i-b-1-essential-features--fonctionnalités-essentielles)

      - [I. B. 1. a. Home page / Page d'accueil](#i-b-1-a-home-page--page-daccueil)
      - [I. B. 1. b. About page / Page à propos de la compagnie](#i-b-1-b-about-page--page-à-propos-de-la-compagnie)
      - [I. B. 1. c. Contact page / Page de contact](#i-b-1-c-contact-page--page-de-contact)
      - [I. B. 1. d. Login and registration / Connexion et inscription](#i-b-1-d-login-and-registration--connexion-et-inscription)
      - [I. B. 1. e. Online shop / Boutique en ligne](#i-b-1-e-online-shop--boutique-en-ligne)
      - [I. B. 1. f. Social media integration / Intégration des réseaux sociaux](#i-b-1-f-social-media-integration--intégration-des-réseaux-sociaux)
      - [I. B. 1. g. Privacy policy / Politique de confidentialité](#i-b-1-g-privacy-policy--politique-de-confidentialité)
      - [I. B. 1. h. Terms and conditions / Conditions générales](#i-b-1-h-terms-and-conditions--conditions-générales)
      - [I. B. 1. i. Cookies policy / Politique de cookies](#i-b-1-i-cookies-policy--politique-de-cookies)
      - [I. B. 1. j. Site map / Plan du site](#i-b-1-j-site-map--plan-du-site)

    - [I. B. 2. Less essential features / Fonctionnalités moins essentielles](#i-b-2-less-essential-features--fonctionnalités-moins-essentielles)

      - [I. B. 2. a. Optional Languages / Langues optionnelles](#i-b-2-a-optional-languages--langues-optionnelles)
      - [I. B. 2. b. Blog / Blog](#i-b-2-b-blog--blog)
      - [I. B. 2. c. Newsletter / Newsletter](#i-b-2-c-newsletter--newsletter)
      - [I. B. 2. d. FAQ / FAQ](#i-b-2-d-faq--faq)
      - [I. B. 2. e. chatbot + generative AI / chatbot + IA générative](#i-b-2-e-chatbot--generative-ai--chatbot--ia-générative)
      - [I. B. 2. f. Dark Mode / Dark Mode](#i-b-2-f-dark-mode--dark-mode)

  - [I. C. Design and Layout / Design et Mise en page](#i-c-design-and-layout--design-et-mise-en-page)

    - [I. C. 1. UX-UI technical watch / Veille technique UX-UI](#i-c-1-ux-ui-technical-watch--veille-technique-ux-ui)

    - [I. C. 2. UX design / Design de l'expérience utilisateur](#i-c-2-ux-design--design-de-lexpérience-utilisateur)

      <!-- - [I. C. 1. a. User personas / Personas utilisateur](#i-c-1-a-user-personas--personas-utilisateur)
      - [I. C. 1. b. User stories / Histoires utilisateur](#i-c-1-b-user-stories--histoires-utilisateur)
      - [I. C. 1. c. User flow / Flux utilisateur](#i-c-1-c-user-flow--flux-utilisateur)
      - [I. C. 1. f. Prototypes / Prototypes](#i-c-1-f-prototypes--prototypes) -->

    - [I. C. 3. UI design / Design de l'interface utilisateur](#i-c-3-ui-design--design-de-linterface-utilisateur)

      - [I. C. 3. a. Layout / Mise en page](#i-c-3-a-layout--mise-en-page)
      - [I. C. 3. b. Wireframes / Maquettes sans design](#i-c-3-b-wireframes--maquettes-sans-design)
      - [I. C. 3. c. Color scheme / Palette de couleurs](#i-c-3-c-color-scheme--palette-de-couleurs)
      - [I. C. 3. d. Typography / Typographie](#i-c-3-d-typography--typographie)
      - [I. C. 3. e. Logo / Logo](#i-c-3-e-logo--logo)
      - [I. C. 3. f. Icons / Icônes](#i-c-3-f-icons--icônes)
      - [I. C. 3. g. Images / Images](#i-c-3-g-images--images)
      - [I. C. 3. h. Mockups / Maquettes avec design](#i-c-3-h-mockups--maquettes-avec-design)
      - [I. C. 3. i. Video / Vidéo](#i-c-3-i-video--vidéo)
      - [I. C. 3. j. Audio / Audio](#i-c-3-j-audio--audio)
      - [I. C. 3. k. Animations / Animations](#i-c-3-k-animations--animations)

    - [I. C. 4. Responsive web design / Design web adaptatif](#i-c-4-responsive-web-design--design-web-adaptatif)

      - [I. C. 4. a. Mobile / Mobile](#i-c-4-a-mobile--mobile)
      - [I. C. 4. b. Tablet / Tablette](#i-c-4-b-tablet--tablette)
      - [I. C. 4. c. Laptop / Ordinateur portable](#i-c-4-c-laptop--ordinateur-portable)

- [II. Front-end development phase / Phase de développement front-end](#ii-front-end-development-phase--phase-de-développement-front-end)
  - [II. A. Front-end technical watch / Veille technique front-end](#ii-a-front-end-technical-watch--veille-technique-front-end)
  - [II. B. Front-end style guide / Guide de style front-end](#ii-b-front-end-style-guide--guide-de-style-front-end)
    - [II. B. 1. Typography / Typographie](#ii-b-1-typography--typographie)
    - [II. B. 2. Color scheme / Palette de couleurs](#ii-b-2-color-scheme--palette-de-couleurs)
    - [II. B. 3. Breakpoints / Points de rupture](#ii-b-3-breakpoints--points-de-rupture)
  - [II. C. Overview / Aperçu](#ii-c-overview--aperçu)
    - [II. C. 1. Screenshots / Captures d'écran](#ii-c-1-screenshots--captures-décran)
- [III. Back-end development phase / Phase de développement back-end](#iii-back-end-development-phase--phase-de-développement-back-end)
  - [III. A. Back-end technical watch / Veille technique back-end](#iii-a-back-end-technical-watch--veille-technique-back-end)
  - [III. B. Domain name / Nom de domaine](#iii-b-domain-name--nom-de-domaine)
  - [III. C. Hosting / Hébergement](#iii-c-hosting--hébergement)
- [IV. Post-development phase / Phase de post-développement](#iv-post-development-phase--phase-de-post-développement)
  - [IV. A. Testing / Tests](#iv-a-testing--tests)
  - [IV. B. Deployment / Déploiement](#iv-b-deployment--déploiement)
  - [IV. C. Monitoring / Monitoring](#iv-c-monitoring--monitoring)
  - [IV. D. Maintenance / Maintenance](#iv-d-maintenance--maintenance)
  - [IV. E. Process / Démarche](#iv-e-process--démarche)
  - [IV. F. Website powered by ... / Site web créé avec ...](#iv-f-website-powered-by---site-web-créé-avec-)
  - [IV. G. Acknowledgements / Mentions spéciales](#iv-g-acknowledgements--mentions-spéciales)

## I. Pre-development phase / Phase de pré-développement

This phase is to define the action plan.

> _Cette phase consiste à définir le plan d'action._

### I. A. Purpose / Objectif

The plan is to create an e-commerce website.

> _Le plan est de créer un site web d'e-commerce._

### I. B. Website features / Fonctionnalités du site

I consider two kind of features : the essential ones and the less essential ones.\
The essential features are the ones that are necessary for the website to have a proper website. They are PRIOR!\
The less essential features are the ones that are not necessary for the website. They are OPTIONAL!

> _Je considère deux types de fonctionnalités : les essentielles et les moins essentielles._\
> _Les fonctionnalités essentielles sont celles qui sont nécessaires pour avoir un site web conventionnel. Elles sont PRIORITAIRES!_\
> _Les fonctionnalités moins essentielles sont celles qui ne sont pas nécessaires pour le site web. Elles sont OPTIONNELLES!_

#### I. B. 1. Essential features / Fonctionnalités essentielles

So, the essential ones are:

- Home page
- About page
- Contact page
- Login and registration
- Online shop
- Social media integration
- Privacy policy
- Terms and conditions
- Cookies policy
- Site map

> _Donc, les essentielles sont :_
>
> - _Page d'accueil_
> - _Page à propos de la compagnie_
> - _Page de contact_
> - _Connexion et inscription_
> - _Boutique en ligne_
> - _Intégration des réseaux sociaux_
> - _Politique de confidentialité_
> - _Conditions générales d'utilisation_
> - _Politique de cookies_
> - _Plan du site_

##### I. B. 1. a. Home page / Page d'accueil

##### I. B. 1. b. About page / Page à propos de la compagnie

##### I. B. 1. c. Contact page / Page de contact

##### I. B. 1. d. Login and registration / Connexion et inscription

##### I. B. 1. e. Online shop / Boutique en ligne

##### I. B. 1. f. Social media integration / Intégration des réseaux sociaux

##### I. B. 1. g. Privacy policy / Politique de confidentialité

##### I. B. 1. h. Terms and conditions / Conditions générales

##### I. B. 1. i. Cookies policy / Politique de cookies

##### I. B. 1. j. Site map / Plan du site

#### I. B. 2. Less essential features / Fonctionnalités moins essentielles

And, the less essential ones are:

- Optional languages
- Blog
- Newsletter
- FAQ
- chatbot + generative AI
- Dark Mode

> _Et, les moins essentielles sont :_
>
> - _Langues optionnelles_
> - _Blog_
> - _Newsletter_
> - _FAQ_
> - _chatbot + IA générative_
> - _Dark Mode_

##### I. B. 2. a. Optional Languages / Langues optionnelles

##### I. B. 2. b. Blog / Blog

##### I. B. 2. c. Newsletter / Newsletter

##### I. B. 2. d. FAQ / FAQ

##### I. B. 2. e. chatbot + generative AI / chatbot + IA générative

##### I. B. 2. f. Dark Mode / Dark Mode

### I. C. Design and Layout / Design et Mise en page

This part is all about visuals.

> _Cette partie concerne tout ce qui est visuel._

#### I. C. 1. UX-UI technical watch / Veille technique UX-UI

This part is to search and identify all the UX/UI good practices when it comes to create an e-commerce website.\
That's where we'll look for inspiration.

> _Cette partie consiste à rechercher et identifier toutes les bonnes pratiques UX/UI lorsqu'il s'agit de créer un site web d'e-commerce._\
> _C'est là que nous chercherons l'inspiration._

#### I. C. 2. UX design / Design de l'expérience utilisateur

This part is about all the psychology behind users habits when it comes to use an e-commerce website.\
We'll try to apply all the good practices we found in the UX-UI technical watch in order to enhance the user experience.

> _Cette partie concerne toute la psychologie derrière les habitudes des utilisateurs lorsqu'il s'agit d'utiliser un site web d'e-commerce._\
> _Nous essaierons d'appliquer toutes les bonnes pratiques que nous avons trouvées dans la veille technique UX-UI afin d'améliorer l'expérience utilisateur._

<!--
##### I. C. 2. a. User personas / Personas utilisateur

##### I. C. 2. b. User stories / Histoires utilisateur

##### I. C. 2. c. User flow / Flux utilisateur

##### I. C. 2. f. Prototypes / Prototypes -->

#### I. C. 3. UI design / Design de l'interface utilisateur

This part is about the design of the website.\

> _Cette partie concerne la conception du site web._

##### I. C. 3. a. Layout / Mise en page

##### I. C. 3. b. Wireframes / Maquettes sans design

##### I. C. 3. c. Color scheme / Palette de couleurs

##### I. C. 3. d. Typography / Typographie

##### I. C. 3. e. Logo / Logo

##### I. C. 3. f. Icons / Icônes

##### I. C. 3. g. Images / Images

##### I. C. 3. h. Mockups / Maquettes avec design

##### I. C. 3. i. Video / Vidéo

##### I. C. 3. j. Audio / Audio

##### I. C. 3. k. Animations / Animations

#### I. C. 4. Responsive web design / Design web adaptatif

##### I. C. 4. a. Mobile / Mobile

##### I. C. 4. b. Tablet / Tablette

##### I. C. 4. c. Laptop / Ordinateur portable

## II. Front-end development phase / Phase de développement front-end

This part is about the development of the part of the website that customers will see.

> _Cette partie concerne le développement de la partie du site web que les clients verront._

### II. A. Front-end technical watch / Veille technique front-end

### II. B. Front-end style guide / Guide de style front-end

#### II. B. 1. Typography / Typographie

#### II. B. 2. Color scheme / Palette de couleurs

#### II. B. 3. Breakpoints / Points de rupture

### II. C. Overview / Aperçu

#### II. C. 1. Screenshots / Captures d'écran

## III. Back-end development phase / Phase de développement back-end

This part is about the development of the part of the website that customers won't see.\
It's the part where we manage all the logic that will make the website functional.\
It's the part where we manage the data of the customers or any other kind of data.

> _Cette partie concerne le développement de la partie du site web que les clients ne verront pas._\
> _C'est la partie où nous gérons toute la logique qui rendra le site web fonctionnel._\
> _C'est la partie où nous gérons les données des clients ou tout autre type de données._

### III. A. Back-end technical watch / Veille technique back-end

### III. B. Domain name / Nom de domaine

### III. C. Hosting / Hébergement

## IV. Post-development phase / Phase de post-développement

This part is about the deployment of the website.

> _Cette partie concerne le déploiement du site web._

### IV. A. Testing / Tests

### IV. B. Deployment / Déploiement

### IV. C. Monitoring / Monitoring

### IV. D. Maintenance / Maintenance

### IV. E. Process / Démarche

### IV. F. Website powered by ... / Site web créé avec ...

### IV. G. Acknowledgements / Mentions spéciales
