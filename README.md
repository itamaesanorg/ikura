Important for security Reasons we removed all prisma related files, obviusly, just delete the folder, and install prisma again.

Go to: 

- [Recover](#Recover)

prisma/db.sqlite
prisma/schema.prisma

![ITAMAESAN SushiJS Wallpaper Best Light NNextJS Framework with Husky fixed](https://user-images.githubusercontent.com/5947268/185643867-81854585-1f24-470e-9836-2a8b9c62c8dd.png)

# SushiJS trpc Beta is called "ikura"

SushiJS, is a Typescript, NextJS, TailwindCSS with Framer Framework based on Agile. Intriduces NRNx2, an evolution of Next Right Now and Agile subsystem folder structure and development methodology. Makes anybody to understand the folder structure. A new revolutionary and evolved folder "modular" structure, developed in a week (1 week exactly) by the Harvard University student of Project Management, Miguel Gargallo, @miguelgargallo. ITAMAESAN ORG is an Open Source Code Foundation, leading in the development industry based on Agile and Project Management Methodologies applied to developments.

SushiJS, está programado en Typescript a través de la tecnología NextJS, TailwindCSS con Framer, es un Framework basado en Agile. Introduce NRNx2, una evolución de la estructura de carpetas del subsistema Next Right Now y Agile y la metodología de desarrollo. Hace que cualquiera entienda la estructura de carpetas. Una nueva estructura "modular" de carpetas revolucionaria y evolucionada, desarrollada en una semana (1 semana exactamente) por el estudiante de Gestión de Proyectos de la Universidad de Harvard, Miguel Gargallo, @miguelgargallo. ITAMAESAN ORG es una Fundación de Código Abierto, líder en la industria del desarrollo basada en Metodologías Ágiles y de Gestión de Proyectos aplicadas a los desarrollos.

SushiJS is a Typescript, tRPC, NextJS, TailwindCSS and Motion Framer project to help developers build great tools!

✨ We are proud to announce, ITAMAESAN, a project to help developers, exclusive working with Open Source MIT License on our code.

✨ ITAMAESAN は、オープンソースの MIT ライセンスで開発する開発者を支援するプロジェクトです。
# Project Organizer

- [Main Features](#Main-Features)
- [Agile in NextJS](#Agile-in-NextJS)
- [Introduction to Common Internet Language also CIL](#Introduction-to-Common-Internet-Language-also-CIL)
- [Code Internet Language in a real case use](#Code-Internet-Language-in-a-real-case-use)
- [NRNx2 Agile by ITAMAESAN](#NRNx2-Agile-by-ITAMAESAN)
- [Project Management System](#Project-Management-System)
- [Features](#Features)
- [Why NRNx2](#Why-NRNx2)
- [HowTo](#HowTo)
- [Recover](#Recover)
- [Directories](#Directories)
- [NRNx2 Agile](#NRNx2-Agile)
- [npm](#npm)
- [Support](#Support)
- [License](#license)
- [We run on](#we-run-on)
- [Fix](#ix)
- [Next-Auth.js](https://next-auth.js.org)
- [Prisma](https://prisma.io)
- [TailwindCSS](https://tailwindcss.com)
- [tRPC](https://trpc.io)

## Main Features

    ✨ Typescript
    📘 NextJS
    🌗 CSS
    😶‍🌫️ Framer Motion
    🦄 Favicons
    📱 Responsive Nav
    🍱 Easy, git clone & npm install/run
    🎉 Folder organized structure

- [Back to top 🔼](#Project-Organizer)


### Agile in NextJS

First we would have to draw 4 column system.

🧠 Backlog | 👷 In Progress | ✅ Publish | 🎯 Review

Once you put the tasks on the board, you can see the order of the tasks from: 🧠 Backlog > 👷 In Progress > ✅ Publish > 🎯 Review and then, once you ended to code that component, as obviusly, you will need to develop the next one, so you return to 🧠 Backlog > 👷 In Progress > ✅ Publish > 🎯 Review with the new component, and one after one, repeatit until you have all the components done.
Then to upgrade components or add new components, you can just move the component to the next folder, and the order of the imports will be added susbecuencely the enumerations.

The second main feature of The SushiJS Framework is the ability to create components that are reusable but not necessarily general for all the pages. This is the reason why we have created the "uncommon" folder. This folder is part of the framework, and it is an extra way create components that are not general for all the pages. It contains, the same strcuture until you navigate to the "elements" folder, and the order of the imports is customizable 100% by the developer.

For example:
 - src/uncommon/components/elementsbypage/Home
 - src/uncommon/components/elementsbypage/AboutUs
 - src/uncommon/components/elementsbypage/ContactUs
 - src/uncommon/components/elementsbypage/Menu

Inside this folders you will encounter a basic folder:

    - 00 Header
    - 01 Head
    - 02 Body
    - 03 Footer

In every page, that is the reason why we have created the "uncommon" folder, it is not a folder you will use everyday, it's uncommonly to use, but is there in case you need for example, to create a specific component, for a specific page for: testing purpouse, SEO or a specific component as mentioned before, like a custome menu.

- [Back to top 🔼](#Project-Organizer)


## Introduction to Common Internet Language also CIL

Code Internet Language also CIL defined and term designed by ITAMAESAN from Miguel Gargallo in Andorra La Vella, Andorra, is to enumarate folders into a web dynamic project, to ensure a faster, reliable and efficient identification for:

    - Fast Error enclave communication.
    - Fast Error identification
    - Easy Dev to Dev communication language
    - Efficient shortened  name of high paths of files
    
eg

    -   ./src/common/components/elements/02 Body/03 Carrousel/index.ts:1:10
    
it converts into CIL, the ans is:
    
   -    C0203 or C-02/03
       
If we see the folder Strucuture:

        🔪---src
            ▒   🎋---app
            ▒   ▒   🥓---components
            ▒   ▒   🥓---styles
            ▒   🎋---common 👈👈👈 HERE FIRST REFERENCE ID FROM CIL
            ▒   ▒   🥓---components
            ▒   ▒   ▒   🔲elements
            ▒   ▒   ▒       ⬜️---00 Header
            ▒   ▒   ▒       ▒   ⬛️---00 Meta
            ▒   ▒   ▒       ⬜️---01 Head
            ▒   ▒   ▒       ▒   ⬛️---01 Menu
            ▒   ▒   ▒       ▒   ⬛️---02 SecondaryMenu
            ▒   ▒   ▒       ⬜️---02 Body 👈👈👈 HERE SECOND REFERENCE ID FROM CIL
            ▒   ▒   ▒       ▒   ⬛️---03 Carrousel 👈👈👈 HERE THIRD REFERENCE ID FROM CIL
            ▒   ▒   ▒       ⬜️---03 Footer
            ▒   ▒   ▒       ▒   ⬛️---04 Legal
            ▒   ▒   ▒       ▒   ⬛️---05 TermsAndConditions
            ▒   ▒   🥓---hooks
            ▒   ▒   🥓---types
            ▒   ▒   🥓---utils
            ▒   🎋---modules
            ▒   ▒   🥓---auth
            ▒   🎋---pages
            ▒       🥓---api
            ▒   🎋---uncommon
            ▒   ▒   🥓---components
            ▒   ▒   ▒   🔲elementsbypage
            ▒   ▒   ▒       ⬜️---01 Home
            ▒   ▒   ▒       ▒   ⬛️---00 Header
            ▒   ▒   ▒       ▒   ⬛️---01 Head
            ▒   ▒   ▒       ▒   ⬛️---02 Body
            ▒   ▒   ▒       ▒   ⬛️---03 Footer    
            ▒   ▒   ▒       ⬜️---02 404
            ▒   ▒   ▒       ▒   ⬛️---00 Header
            ▒   ▒   ▒       ▒   ⬛️---01 Head
            ▒   ▒   ▒       ▒   ⬛️---02 Body
            ▒   ▒   ▒       ▒   ⬛️---03 Footer    

You will notice, there is no error identifyn between a common and an ucommon component.
This how at SushiJS we solved many problems, making quicker, easier and common understandable, between devs, and non devs, also PM who knows to code but do need to know how the folder file system strcututire is, why and how to arrive to their destination.

- [Back to top 🔼](#Project-Organizer)


# Code Internet Language in a real case use.

We use 00 01 02 03 and many more identifications to locate so fast, efficient and reliable an error when is higlighted on the compile, server or in this case, VERCEL.

![image](https://user-images.githubusercontent.com/5947268/186480899-6200dc29-5b22-4fbc-a463-e547f4d2e63b.png)

As you may see in this picture,

        ./src/common/components/elements/02 Body/27 Carrousel/index.ts:1:10
        
If we looked deeper:

        ./...common/.../02...27...

Here is the reference: C0227 or also C-02/27, where the error is being easely to remember, anotate on your Agile tools and pas throught the notes into devs to fix ASAP, with an easy message, "fix please C0227", here is where we introduce the Code Internet Language also CIL.

- [Back to top 🔼](#Project-Organizer)


# NRNx2 Agile by ITAMAESAN

SuhsiJS introduced the NRNx2 Agile subsystem folder structure and development methodology.

This is the first main aspects of SushiJS, here you will find out a Project Management System, a simple and easy to use system to manage your folders.

- [Back to top 🔼](#Project-Organizer)


## Project Management System

It's based on Agile methodology, it's a system to manage your projects and tasks.

- [Back to top 🔼](#Project-Organizer)


### Features

Directories are the main feature of this system, you can create, delete, rename and move directories, but always under a precise level of numerical identification.
The following identification levels are available:
 - 00 Header
 - 01 Head
 - 02 Body
 - 03 Footer

Inside those directories, you will encounter a second independent system of enumeration, this system is called the NRNx2 Agile, introduced by Miguel Gargallo, a software engineer student and a project manager. He studied at Harvard University and is the main developer at SushiJS.

- [Back to top 🔼](#Project-Organizer)


# Why NRNx2
NRN means Next Right Now, and x2 means the addition of SushiJS Agile, a Numerical Reference Number, NRN, a system to manage the numerical identification of the directories.

- [Back to top 🔼](#Project-Organizer)


## HowTo

    01: 🍚, Cook rice. <- Prepare all your pages.
    02: 🧂, Mix Vinegar, Oil, Sugar & Salt.
    03: ⏲,  Cook until sugar is dissolved.
    04: 🥣, Stir into rice.
    05: 🐟, Prepear fillings.
    06: ⬛️, Put Nori on a bamboo mat.
    07: ⬜️, Put rice with hands.
    08: 🔲, Spride rice over the nori.
    09: 🥓, Lay the filling.
    10: 🎋, Roll the bamboo mat and press.
    11: 🔪, Cut with wet knife.
    12: 🍣, Enjoy!

Take a look into the following directory structure:


- [Back to top 🔼](#Project-Organizer)

# Directories

    🍣 SUSHIJS FRAMEWORK
    🔪---fonts
    🔪---lib
    🔪---public
    ▒   🎋---fonts
    ▒   🎋---static
    ▒       🥓---favicons
    🔪---src
    ▒   🎋---app
    ▒   ▒   🥓---components
    ▒   ▒   ▒   🔲---GlobalStyles
    ▒   ▒   🥓---styles
    ▒   🎋---common
    ▒   ▒   🥓---components
    ▒   ▒   ▒   🔲elements
    ▒   ▒   ▒       ⬜️---00 Header
    ▒   ▒   ▒       ▒   ⬛️---00 Meta
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Meta.tsx
    ▒   ▒   ▒       ⬜️---01 Head
    ▒   ▒   ▒       ▒   ⬛️---01 Menu
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Sushisho.tsx
    ▒   ▒   ▒       ▒   ⬛️---02 SecondaryMenu
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Sushiten.tsx
    ▒   ▒   ▒       ▒   ⬛️---03 MenuNotAnimated
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 SushishoUsed.tsx
    ▒   ▒   ▒       ▒   ⬛️---04 SecondaryMenuNotAnimated
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 SushitenUsed.tsx
    ▒   ▒   ▒       ▒   ⬛️---05 ToggleDarkModeButton
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Izakaya.tsx
    ▒   ▒   ▒       ⬜️---02 Body
    ▒   ▒   ▒       ▒   ⬛️---06 WelcomeDescriptionText
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Bento.tsx
    ▒   ▒   ▒       ▒   ⬛️---07 CardsProps
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Arubamu.tsx
    ▒   ▒   ▒       ▒   ⬛️---08 AboutUsImages
    ▒   ▒   ▒       ▒   ⬛️---09 BrandImages
    ▒   ▒   ▒       ▒       🐟-----🧂 logo1.png
    ▒   ▒   ▒       ▒       🐟-----🧂 logo2.png
    ▒   ▒   ▒       ▒       🐟-----🧂 logo3.png
    ▒   ▒   ▒       ▒   ⬛️---10 Container
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Container.tsx
    ▒   ▒   ▒       ▒   ⬛️---12 OurServices
    ▒   ▒   ▒       ▒   ⬛️---13 CardsPropsImproved
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 ShashinArubamu.tsx
    ▒   ▒   ▒       ▒   ⬛️---14 OurServicesText
    ▒   ▒   ▒       ▒   ⬛️---15 Bottom
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Bottom.tsx
    ▒   ▒   ▒       ▒   ⬛️---16 Appbar
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Appbar.tsx
    ▒   ▒   ▒       ▒   ⬛️---17 BigText
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 BigText.tsx
    ▒   ▒   ▒       ▒   ⬛️---18 BigTextExport
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 BigTextExport.tsx
    ▒   ▒   ▒       ▒   ⬛️---20 Section
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Section.tsx
    ▒   ▒   ▒       ▒   ⬛️---21 Page
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Page.tsx
    ▒   ▒   ▒       ▒   ⬛️---22 Carrousel
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Carrousel.tsx
    ▒   ▒   ▒       ▒   ⬛️---22 CarrouselCards
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Carrousel.tsx
    ▒   ▒   ▒       ▒   ⬛️---23 CoolError404
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 CooltError.tsx
    ▒   ▒   ▒       ▒   ⬛️---24 CoolError404Exporter
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Arubamu.tsx
    ▒   ▒   ▒       ⬜️---03 Footer
    ▒   ▒   ▒       ▒   ⬛️---25 Footer
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Footer.tsx
    ▒   ▒   🥓---hooks
    ▒   ▒   🥓---types
    ▒   ▒   🥓---utils
    ▒   🎋---modules
    ▒   ▒   🥓---auth
    ▒   ▒       🔲---api
    ▒   ▒       🔲---components
    ▒   🎋---pages
    ▒       🥓---api
    ▒           🔲---authAPI
    ▒           🔲---helloAPI
    ▒   🎋---uncommon
    ▒   ▒   🥓---components
    ▒   ▒   ▒   🔲elementsbypage
    ▒   ▒   ▒       ⬜️---01 Home
    ▒   ▒   ▒       ▒   ⬛️---00 Header
    ▒   ▒   ▒       ▒   ⬛️---01 Head
    ▒   ▒   ▒       ▒   ⬛️---02 Body
    ▒   ▒   ▒       ▒   ⬛️---03 Footer    
    ▒   ▒   ▒       ⬜️---02 404
    ▒   ▒   ▒       ▒   ⬛️---00 Header
    ▒   ▒   ▒       ▒   ⬛️---01 Head
    ▒   ▒   ▒       ▒   ⬛️---02 Body
    ▒   ▒   ▒       ▒   ⬛️---03 Footer    
    🔪---static
    ▒   🎋---favicons
    🔪---styles

- [Back to top 🔼](#Project-Organizer)


## NRNx2 Agile

Between 00 Header and 01 Head there is no main difference at all. The only difference is the order of the imports internally.
When you navigate to 02 Body, you will see that the order of the imports is a continuation of the order of the imports in 00 Header, and not a reset of the order in every directory.
If you delete the main folders:
    - 00 Header
    - 01 Head
    - 02 Body
    - 03 Footer

    More precisely, the following files are exported:

    ▒   ▒   ▒       ⬜️---00 Header
    ▒   ▒   ▒       ▒   ⬛️---00 Meta
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Meta.tsx
    ▒   ▒   ▒       ⬜️---01 Head
    ▒   ▒   ▒       ▒   ⬛️---01 Menu
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Sushisho.tsx
    ▒   ▒   ▒       ▒   ⬛️---02 SecondaryMenu
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Sushiten.tsx
    ▒   ▒   ▒       ▒   ⬛️---03 MenuNotAnimated
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 SushishoUsed.tsx
    ▒   ▒   ▒       ▒   ⬛️---04 SecondaryMenuNotAnimated
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 SushitenUsed.tsx
    ▒   ▒   ▒       ▒   ⬛️---05 ToggleDarkModeButton
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Izakaya.tsx
    ▒   ▒   ▒       ⬜️---02 Body
    ▒   ▒   ▒       ▒   ⬛️---06 WelcomeDescriptionText
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Bento.tsx
    ▒   ▒   ▒       ▒   ⬛️---07 CardsProps
    ▒   ▒   ▒       ▒       🐟-----🥣 index.ts
    ▒   ▒   ▒       ▒       ⏲-----🍚 Arubamu.tsx
    ▒   ▒   ▒       ▒   ⬛️---08 AboutUsImages
    ▒   ▒   ▒       ▒   ⬛️---09 BrandImages
    ▒   ▒   ▒       ▒       🐟-----🧂 logo1.png
    ▒   ▒   ▒       ▒       🐟-----🧂 logo2.png
    ▒   ▒   ▒       ▒       🐟-----🧂 logo3.png

And move all directories to the root of the elements project folder, you will see that the order of the imports is functional too.
The system is developed to be easy for non relates heavy developers, or also called head of areas, or project managers Who know the basis of the programming skills, but do not know the order of the imports or projects specifications at all.
This also enables a way to order tasks as the Agile Scrum Manifesto states.

- [Back to top 🔼](#Project-Organizer)


## Getting started

    ⬇️ git clone https://github.com/itamaesanorg/SushiJS.git
    🔄 npm install
    ➡️ npm run dev
    ✨ Enjoy

- [Back to top 🔼](#Project-Organizer)


## npm

    npm i @itamaesanorg/sushijs


    ⬜⬜⬜⬜⬜⬜⬜🟧🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧⬜⬜⬜⬜
    ⬜⬜⬜⬜⬜🟧🟧🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧🟧⬜
    ⬜⬜⬜⬜🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧
    🟧🟧⬜🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧🟧
    🟧🟧🟧🟧🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧🟧⬜🟧
    ⬜🟧🟧🟧🟧🟧🟧🟧🟧🟧🟧🟧🟧🟧🟧🟧🟧🟧🟧🟧⬜🟧🟧
    ⬜🟧🟧🟧⬛⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜🟧🟧🟧⬜
    🟧🟧🟧⬜⬛⬜⬛⬜⬜⬜⬜⬜⬜⬜⬜⬜⬛⬜⬜⬛⬜⬜⬜
    🟧🟧⬜⬜⬛⬜⬛⬛⬜⬜⬜⬜⬜⬜⬜⬜⬛⬛⬜⬛⬜⬜⬜
    ⬜⬜⬜⬜⬛⬜⬜⬜⬜⬜⬛⬜⬜⬛⬜⬜⬜⬜⬜⬛⬜⬜⬜
    ⬜⬜⬜⬜⬛⬜🟪🟪⬜⬜⬛⬛⬛⬛⬜⬜🟪🟪⬜⬛⬜⬜⬜
    ⬜⬜⬜⬜⬛⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬛⬜⬜⬜
    ⬜⬜⬜⬜⬜⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬜⬜⬜⬜

- [Back to top 🔼](#Project-Organizer)


## Support

    🐣 Twitter: https://twitter.com/itamaesanorg
    🌐 Homepage: https://itamaesan.org redirects to https://SushiJS.com

- [Back to top 🔼](#Project-Organizer)


## License

    ⚖️ MIT at: https://github.com/itamaesanorg/SushiJS/blob/main/LICENSE

- [Back to top 🔼](#Project-Organizer)


## We run on

    Vercel 🍣 Thanks Vercel if you read that!

- [Back to top 🔼](#Project-Organizer)


## Fix

    😍 Before dealing with the deploy please take while to read this for 100% optimization.
    [Here are posible steps before](https://github.com/itamaesanorg/edu)

- [Back to top 🔼](#Project-Organizer)



# Recovery

    🍣 SushiJS is a project that is being developed by the community, and it is open source, so you can contribute to the project, and help us to improve it, and make it better for everyone.
    Here down below you have a way to recover the project, and make it work again, if you have any problem with the project, or you want to contribute to the project, please contact us at: https://twitter.com/itamaesanorg

# Create T3 App Sushis App

This is an app bootstrapped according to the [init.tips](https://init.tips) stack, also known as the T3-Stack.

## Why are there `.js` files in here?

As per [T3-Axiom #3](https://github.com/t3-oss/create-t3-app/tree/next#3-typesafety-isnt-optional), we take typesafety as a first class citizen. Unfortunately, not all frameworks and plugins support TypeScript which means some of the configuration files have to be `.js` files.

We try to emphasize that these files are javascript for a reason, by explicitly declaring its type (`cjs` or `mjs`) depending on what's supported by the library it is used by. Also, all the `js` files in this project are still typechecked using a `@ts-check` comment at the top.

## What's next? How do I make an app with this?

We try to keep this project as simple as possible, so you can start with the most basic configuration and then move on to more advanced configuration.

If you are not familiar with the different technologies used in this project, please refer to the respective docs. If you still are in the wind, please join our [Discord](https://t3.gg/discord) and ask for help.

- [Next-Auth.js](https://next-auth.js.org)
- [Prisma](https://prisma.io)
- [TailwindCSS](https://tailwindcss.com)
- [tRPC](https://trpc.io) (using @next version? [see v10 docs here](https://alpha.trpc.io))

Also checkout these awesome tutorials on `create-t3-app`.

- [Build a Blog With the T3 Stack - tRPC, TypeScript, Next.js, Prisma & Zod](https://www.youtube.com/watch?v=syEWlxVFUrY)
- [Build a Live Chat Application with the T3 Stack - TypeScript, Tailwind, tRPC](https://www.youtube.com/watch?v=dXRRY37MPuk)
- [Build a full stack app with create-t3-app](https://www.nexxel.dev/blog/ct3a-guestbook)
- [A first look at create-t3-app](https://dev.to/ajcwebdev/a-first-look-at-create-t3-app-1i8f)

## How do I deploy this?

### Vercel

We recommend deploying to [Vercel](https://vercel.com/?utm_source=t3-oss&utm_campaign=oss). It makes it super easy to deploy NextJs apps.

- Push your code to a GitHub repository.
- Go to [Vercel](https://vercel.com/?utm_source=t3-oss&utm_campaign=oss) and sign up with GitHub.
- Create a Project and import the repository you pushed your code to.
- Add your environment variables.
- Click **Deploy**
- Now whenever you push a change to your repository, Vercel will automatically redeploy your website!

### Docker

You can also dockerize this stack and deploy a container.

Please note that Next.js requires a different process for buildtime (available in the frontend, prefixed by `NEXT_PUBLIC`) and runtime environment, server-side only, variables. In this demo we are using two variables, `NEXT_PUBLIC_FOO` and `BAR`. Pay attention to their positions in the `Dockerfile`, command-line arguments, and `docker-compose.yml`.

1. In your [next.config.mjs](./next.config.mjs), add the `standalone` output-option to your config:

   ```diff
     export default defineNextConfig({
       reactStrictMode: true,
       swcMinify: true,
   +   output: "standalone",
     });
   ```

2. Remove the `env`-import from [next.config.mjs](./next.config.mjs):

   ```diff
   - import { env } from "./src/env/server.mjs";
   ```

3. Create a `.dockerignore` file with the following contents:
   <details>
   <summary>.dockerignore</summary>

   ```
   .env
   Dockerfile
   .dockerignore
   node_modules
   npm-debug.log
   README.md
   .next
   .git
   ```

  </details>

4. Create a `Dockerfile` with the following contents:
   <details>
   <summary>Dockerfile</summary>

   ```Dockerfile
   ########################
   #         DEPS         #
   ########################

   # Install dependencies only when needed
   # TODO: re-evaluate if emulation is still necessary on arm64 after moving to node 18
   FROM --platform=linux/amd64 node:16-alpine AS deps
   # Check https://github.com/nodejs/docker-node/tree/b4117f9333da4138b03a546ec926ef50a31506c3#nodealpine to understand why libc6-compat might be needed.
   RUN apk add --no-cache libc6-compat
   WORKDIR /app

   # Install dependencies based on the preferred package manager
   COPY package.json yarn.lock* package-lock.json* pnpm-lock.yaml* ./
   RUN \
     if [ -f yarn.lock ]; then yarn --frozen-lockfile; \
     elif [ -f package-lock.json ]; then npm ci; \
     elif [ -f pnpm-lock.yaml ]; then yarn global add pnpm && pnpm i; \
     else echo "Lockfile not found." && exit 1; \
     fi

   ########################
   #        BUILDER       #
   ########################

   # Rebuild the source code only when needed
   # TODO: re-evaluate if emulation is still necessary on arm64 after moving to node 18
   FROM --platform=linux/amd64 node:16-alpine AS builder

   ARG NEXT_PUBLIC_FOO
   ARG BAR

   WORKDIR /app
   COPY --from=deps /app/node_modules ./node_modules
   COPY . .

   # Next.js collects completely anonymous telemetry data about general usage.
   # Learn more here: https://nextjs.org/telemetry
   # Uncomment the following line in case you want to disable telemetry during the build.
   # ENV NEXT_TELEMETRY_DISABLED 1

   RUN \
     if [ -f yarn.lock ]; then yarn build; \
     elif [ -f package-lock.json ]; then npm run build; \
     elif [ -f pnpm-lock.yaml ]; then yarn global add pnpm && pnpm run build; \
     else echo "Lockfile not found." && exit 1; \
     fi

   ########################
   #        RUNNER        #
   ########################

   # Production image, copy all the files and run next
   # TODO: re-evaluate if emulation is still necessary after moving to node 18
   FROM --platform=linux/amd64 node:16-alpine AS runner
   # WORKDIR /usr/app
   WORKDIR /app

   ENV NODE_ENV production
   # Uncomment the following line in case you want to disable telemetry during runtime.
   # ENV NEXT_TELEMETRY_DISABLED 1

   RUN addgroup --system --gid 1001 nodejs
   RUN adduser --system --uid 1001 nextjs

   COPY --from=builder /app/next.config.mjs ./
   COPY --from=builder /app/public ./public
   COPY --from=builder /app/package.json ./package.json

   # Automatically leverage output traces to reduce image size
   # https://nextjs.org/docs/advanced-features/output-file-tracing
   COPY --from=builder --chown=nextjs:nodejs /app/.next/standalone ./
   COPY --from=builder --chown=nextjs:nodejs /app/.next/static ./.next/static

   USER nextjs

   EXPOSE 3000

   ENV PORT 3000

   CMD ["node", "server.js"]
   ```

  </details>

5. To build and run this image locally, run:

   ```bash
   docker build -t ct3a -e NEXT_PUBLIC_FOO=foo .
   docker run -p 3000:3000 -e BAR="bar" ct3a
   ```

6. You can also use a PaaS such as [Railway's](https://railway.app) automated [Dockerfile deployments](https://docs.railway.app/deploy/dockerfiles) to deploy your app.

### docker-compose

You can also use docker-compose to build and run the container.

1. Follow steps 1-4 above

2. Create a `docker-compose.yml` file with the following:

   <details>
   <summary>docker-compose.yml</summary>

   ```yaml
   version: "3.7"
   services:
     app:
       platform: "linux/amd64"
       build:
         context: .
         dockerfile: Dockerfile
         args:
           NEXT_PUBLIC_FOO: "foo"
       working_dir: /app
       ports:
         - "3000:3000"
       image: t3-app
       environment:
         - BAR=bar
   ```

   </details>

3. Run this using `docker-compose up`.

## Useful resources

Here are some resources that we commonly refer to:

- [Protecting routes with Next-Auth.js](https://next-auth.js.org/configuration/nextjs#unstable_getserversession)
