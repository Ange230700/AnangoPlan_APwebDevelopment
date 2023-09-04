<!--! PROJECT DESCRIPTION -->

# AnangoPlan_APwebDevelopment - Project Description

This is the full stack development of **AnangoPlan**.\
AnangoPlan is for the mass market.\
This document will detail the process, the steps and the tools necessary to develop the site.\
There will be four major phases in this document :

- The pre-development phase
- The front-end development phase
- The back-end development phase
- The post-development phase

> _Il s'agit du développement complet du site web *AnangoPlan*._\
> _AnangoPlan est pour la vente de masse._\
> _Ce document détaillera le processus, les étapes et les outils nécessaires au développement du site._\
> _Il y aura quatre grandes phases dans ce document :_
>
> - _La phase de pré-développement_
> - _La phase de développement front-end_
> - _La phase de développement back-end_
> - _La phase de post-développement_

## Table of contents / Table des matières

- [I. Pre-development phase / Phase de pré-développement](#pre-development-phase--phase-de-pré-développement)

  - [I. A. Purpose and Goals / But et Objectifs](#purpose-and-goals--but-et-objectifs)

  - [I. B. Website features / Fonctionnalités du site](#website-features--fonctionnalités-du-site)

    - [I. B. 1. Essential features / Fonctionnalités essentielles](#essential-features--fonctionnalités-essentielles)

      - [I. B. 1. a. Home page / Page d'accueil](#home-page--page-daccueil)
      - [I. B. 1. b. About page / Page à propos de la compagnie](#about-page--page-à-propos-de-la-compagnie)
      - [I. B. 1. c. Contact page / Page de contact](#contact-page--page-de-contact)
      - [I. B. 1. d. Login and registration / Connexion et inscription](#login-and-registration--connexion-et-inscription)
      - [I. B. 1. e. Online shop / Boutique en ligne](#online-shop--boutique-en-ligne)
      - [I. B. 1. f. Social media integration / Intégration des réseaux sociaux](#social-media-integration--intégration-des-réseaux-sociaux)
      - [I. B. 1. g. Privacy policy / Politique de confidentialité](#privacy-policy--politique-de-confidentialité)
      - [I. B. 1. h. Terms and conditions / Conditions générales](#terms-and-conditions--conditions-générales)
      - [I. B. 1. i. Cookies policy / Politique de cookies](#cookies-policy--politique-de-cookies)
      - [I. B. 1. j. Site map / Plan du site](#site-map--plan-du-site)

    - [I. B. 2. Less essential features / Fonctionnalités moins essentielles](#less-essential-features--fonctionnalités-moins-essentielles)

      - [I. B. 2. a. Optional Languages / Langues optionnelles](#optional-languages--langues-optionnelles)
      - [I. B. 2. b. Blog / Blog](#blog--blog)
      - [I. B. 2. c. Newsletter / Bulletin d'information](#newsletter--bulletin-dinformation)
      - [I. B. 2. d. FAQ / FAQ](#faq--faq)
      - [I. B. 2. e. chatbot + generative AI / chatbot + IA générative](#chatbot--generative-ai--chatbot--ia-générative)

  - [I. C. Design and Layout / Design et Mise en page](#design-and-layout--design-et-mise-en-page)

    - [I. C. 1. UX design / Design de l'expérience utilisateur](#ux-design--design-de-lexpérience-utilisateur)

      - [I. C. 1. a. User personas / Personas utilisateur](#user-personas--personas-utilisateur)
      - [I. C. 1. b. User stories / Histoires utilisateur](#user-stories--histoires-utilisateur)
      - [I. C. 1. c. User flow / Flux utilisateur](#user-flow--flux-utilisateur)
      - [I. C. 1. d. Wireframes / Maquettes sans design](#wireframes--wireframes)
      - [I. C. 1. e. Mockups / Maquettes avec design](#mockups--mockups)
      - [I. C. 1. f. Prototypes / Prototypes](#prototypes--prototypes)

    - [I. C. 2. UX-UI technical watch / Veille technique UX-UI](#ux-ui-technical-watch--veille-technique-ux-ui)

    - [I. C. 3. UI design / Design de l'interface utilisateur](#ui-design--design-de-linterface-utilisateur)

      - [I. C. 3. a. Layout / Mise en page](#layout--mise-en-page)
      - [I. C. 3. b. Color scheme / Palette de couleurs](#color-scheme--palette-de-couleurs)
      - [I. C. 3. c. Typography / Typographie](#typography--typographie)
      - [I. C. 3. d. Logo / Logo](#logo--logo)
      - [I. C. 3. e. Icons / Icônes](#icons--icônes)
      - [I. C. 3. f. Images / Images](#images--images)
      - [I. C. 3. g. Video / Vidéo](#video--vidéo)
      - [I. C. 3. h. Audio / Audio](#audio--audio)
      - [I. C. 3. i. Animations / Animations](#animations--animations)

    - [I. C. 4. Responsive web design / Design web adaptatif](#responsive-web-design--design-web-adaptatif)

      - [I. C. 4. a. Mobile / Mobile](#mobile--mobile)
      - [I. C. 4. b. Tablet / Tablette](#tablet--tablette)
      - [I. C. 4. c. Laptop / Ordinateur portable](#laptop--ordinateur-portable)

- [Front-end development phase / Phase de développement front-end](#front-end-development-phase--phase-de-développement-front-end)
  - [Front-end technical watch / Veille technique front-end](#front-end-technical-watch--veille-technique-front-end)
  - [Front-end style guide / Guide de style front-end](#front-end-style-guide--guide-de-style-front-end)
    - [Typography / Typographie](#typography--typographie)
    - [Color scheme / Palette de couleurs](#color-scheme--palette-de-couleurs)
    - [Breakpoints / Points de rupture](#breakpoints--point-de-rupture)
  - [Overview / Aperçu](#overview--aperçu)
    - [Screenshots / Captures d'écran](#screenshots--captures-décran)
- [Back-end development phase / Phase de développement back-end](#back-end-development-phase--phase-de-développement-back-end)
  - [Back-end technical watch / Veille technique back-end](#back-end-technical-watch--veille-technique-back-end)
  - [Domain name / Nom de domaine](#domain-name--nom-de-domaine)
  - [Hosting / Hébergement](#hosting--hébergement)
- [Post-development phase / Phase de post-développement](#post-development-phase--phase-de-post-développement)
  - [Testing / Tests](#testing--tests)
  - [Deployment / Déploiement](#deployment--déploiement)
  - [Monitoring / Monitoring](#monitoring--monitoring)
  - [Maintenance / Maintenance](#maintenance--maintenance)
  - [Process / Démarche](#process--démarche)
  - [Website powered by ... / Site web créé avec ...](#website-powered-by--site-web-créé-avec)
  - [Acknowledgements / Mentions spéciales](#acknowledgements--mentions-spéciales)

## I. Pre-development phase / Phase de pré-développement

### I. A. Purpose and Goals / But et Objectifs

### I. B. Website features / Fonctionnalités du site

#### I. B. 1. Essential features / Fonctionnalités essentielles

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

##### I. B. 2. a. Optional Languages / Langues optionnelles

##### I. B. 2. b. Blog / Blog

##### I. B. 2. c. Newsletter / Bulletin d'information

##### I. B. 2. d. FAQ / FAQ

##### I. B. 2. e. chatbot + generative AI / chatbot + IA générative

### I. C. Design and Layout / Design et Mise en page

#### I. C. 1. UX design / Design de l'expérience utilisateur

##### I. C. 1. a. User personas / Personas utilisateur

##### I. C. 1. b. User stories / Histoires utilisateur

##### I. C. 1. c. User flow / Flux utilisateur

##### I. C. 1. d. Wireframes / Maquettes sans design

##### I. C. 1. e. Mockups / Maquettes avec design

##### I. C. 1. f. Prototypes / Prototypes

#### I. C. 2. UX-UI technical watch / Veille technique UX-UI

#### I. C. 3. UI design / Design de l'interface utilisateur

##### I. C. 3. a. Layout / Mise en page

##### I. C. 3. b. Color scheme / Palette de couleurs

##### I. C. 3. c. Typography / Typographie

##### I. C. 3. d. Logo / Logo

##### I. C. 3. e. Icons / Icônes

##### I. C. 3. f. Images / Images

##### I. C. 3. g. Video / Vidéo

##### I. C. 3. h. Audio / Audio

##### I. C. 3. i. Animations / Animations

#### I. C. 4. Responsive web design / Design web adaptatif

##### I. C. 4. a. Mobile / Mobile

##### I. C. 4. b. Tablet / Tablette

##### I. C. 4. c. Laptop / Ordinateur portable

## Front-end development phase / Phase de développement front-end

### Front-end technical watch / Veille technique front-end

### Front-end style guide / Guide de style front-end

#### Typography / Typographie

#### Color scheme / Palette de couleurs

#### Breakpoints / Points de rupture

### Overview / Aperçu

#### Screenshots / Captures d'écran

## Back-end development phase / Phase de développement back-end

### Back-end technical watch / Veille technique back-end

### Domain name / Nom de domaine

### Hosting / Hébergement

## Post-development phase / Phase de post-développement

### Testing / Tests

### Deployment / Déploiement

### Monitoring / Monitoring

### Maintenance / Maintenance

### Process / Démarche

### Website powered by ... / Site web créé avec ...

### Acknowledgements / Mentions spéciales
