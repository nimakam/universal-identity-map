# Personas

## 👩 Connie - Consumer

![Connie the consumer][connie-consumer]

[connie-consumer]: personas/images/connie-consumer.png

Connie is the consumer end user, one of the main persons we all ultimately serve as Universal Identity ecosystem stakeholders. She is part of the early majority of technology adopters, but not part of the early adopter crypto or general tech communities. She is likely in the age range 20-40, likely with undergraduate education. She is comfortable using consumer technology such as a selection of the following: smart phone (iPhone or Android), the web (Chrome, Safari), search (Google), email (GMail, Outlook), social networking and messaging (Instagram, Facebook, Twitter, WhatsApp, Skype, iMessage, FaceTime), and other consumer services (AirBnB, Google Maps, Spotify, Uber, Amazon, Office). She has a non-technology day job, likely a family and kids, and little time to tinker with technology. She wants things to just work, the way her iPhone and apps just work for the most part.

### ✅ Truong & Troy - Consumer's trusted contacts

![Truong, Connie's trusted contact][truong-trusted-contact]![Troy, Connie's trusted contact][troy-trusted-contact]

[truong-trusted-contact]: personas/images/truong-trusted-contact@128h.png
[troy-trusted-contact]: personas/images/troy-trusted-contact@128h.png

Troy and Truong are Connie's more trusted contacts, ones that may be entrusted with guardianship responsibilities for the purpose of monitoring, approval, recovery and/or estate planning. For example Troy can be Connie's brother or father, a responsible family member she trusts more, and Truong could be Connie's romantic or life partner.

### 👋 Akon and Akira - Consumer's acquaintances

![Akon, Connie's acquaintance][akon-acquaintance] ![Akira, Connie's acquaintance][akira-acquaintance]

[akon-acquaintance]: personas/images/akon-acquaintance@128h.png
[akira-acquaintance]: personas/images/akira-acquaintance@128h.png

Akon and Akira are two of Connie's extended group of social acquaintances, with varying levels of closeness.

## 🧑‍💻 Devin - App developer

![Devin the app developer][devin-app-dev]

[devin-app-dev]: personas/images/devin-app-dev.png

Devin is the development-operations person working on UID-enabled consumer apps. She spends most of her day focusing on the aspects of their app services and infrastructure that are key to their app's main business. She needs to ensure that the app interfaces like their web portal and smart phone apps (iPhone and Android) just work for their customer Connie, who also happens to be our customer. When beginning to look at a new identity subsystem, she has limited time to dedicate to fully understanding, integrating and operating identity infrastructure for WhatsApp's services. However she does also demand a certain degree of control and customizability to their identity infrastructure, given Devin's full control over other parts of their service. As time passes, Devin will demand more and more from the identity subsystem, and may even demand to fork off the code, customize, maintain and operate it herself.

## 🧑‍💻 Divya - UID core developer

![Divya the core developer][divya-core-dev]

[divya-core-dev]: personas/images/divya-core-dev.png

Divya is a UID core platform, app or infrastructure development-operations person, which means she is a major stakeholder on the Universal Identity ecosystem. She spends most of her day focusing on the aspects of services and infrastructure that are key to UID's ecosystem operations. She needs to ensure that infrastructure pieces function and are easy to use for app developers such as Devin. She also needs to provide support to Devin and app developers in general, with any issues.

The following diagram demonstrates how the developer and consumer personas come together in building and using the ecosystem's assets.

![Developer scenarios][developer-scenarios]

[developer-scenarios]: scenarios/images/developer-scenarios.png

Divya can further focus on one or many of the following areas, depending on her company's focus:

1. **Identity operator service** - An identity operator service that provides a home for user's digital identity similar to how an email provider holding a user's emails.
2. **Identity app** - Is a dedicated identity management app that consumers use to perform basic tasks such as setting up, logging in and authorizations with their digital identities.
3. **App platform UID support** - Are libraries and tools provided to app developers by an app platform (such as Android, iOS, React, NodeJS, dotNET, etc) to support Universal Identity in their apps.

As a result there are 3 different sub-personas that we will focus on as described below:

### Identity operator service developer

**Divya IdOp** is the development-operations person focusing on building and managing an Identity Operator service.

### Identity app developer

**Divya IdApp** is the development-operations person focusing on building and managing a dedicated Identity Management App that the consumers such as Connie use directly.

### App platform UID developer

**Divya AppPlat** is the development-operations person focusing on providing libraries and tools to app developers such as Devin, in order to enable integrating Universal Identity into their apps based on Divya's App Platform offering.

## 🤓 Earl - Early adopter

![Earl the early adopter and technology enthusiast][earl-early-adopter]

[earl-early-adopter]: personas/images/earl-early-adopter.png

Earl is the tech enthusiast (technophile) and early adopter end user, one of the main persons we all ultimately serve as Universal Identity ecosystem stakeholders. His abilities and demands are a superset of Connie's (the consumer end user). He is an early adopter of crypto and/or other new technologies, as well as a member of tech communities. He is likely in the age range 15-40, with technical education and/or coding experience. He likely has a technology-related day job, and plenty of time to tinker with technology. He is comfortable using consumer technology but wants deeper involvement, he wants to understand how things work, and be able to customize the functions of his digital gadgets and apps.

### 🤓 Erica - Fellow early adopter

![Erica, fellow early adopter][erica-early-adopter]

[erica-early-adopter]: personas/images/erica-early-adopter@128h.png

## ⏹ Apps and services

In addition to persona's this document highlights typical and representative examples of apps and backing web services that each persona could interact with in some way.

Most importantly consumers will have to choose one or more identity operator web services to host their identity, and one primary identity app to interact with on their devices, especially for high security identity operations.

Additionally consumers will typically interact with a large number of vertical apps and businesses that will rely on the greater Universal Identity system comprising of connected, public and private identity subsystems.

### 🗝 Identity app & identity operator service

![Some identity app][some-identity-app]![Some identity app text][some-identity-app-text]

[some-identity-app]: personas/images/some-identity-app@128h.png
[some-identity-app-text]: personas/images/some-identity-app-text@128h.png

SomeIdentityApp is a identity operator service and a paired identity app that consumers interact with directly on their devices.

![Other identity app][other-identity-app]![Other identity app text][other-identity-app-text]

[other-identity-app]: personas/images/other-identity-app@64h.png
[other-identity-app-text]: personas/images/other-identity-app-text@64h.png

OtherIdentityApp is an alternative identity operator service and a paired identity app that consumers interact with directly on their devices. The alternative choice is provided to highlight the multi-tenant nature of identity operator services and the fact that almost all consumers will have their identity hosted by more than one operator service at any given time.

### 📲 Vertical app and service

![Some app][some-app]![Some app text][some-app-text]

[some-app]: personas/images/some-app@128h.png
[some-app-text]: personas/images/some-app-text@128h.png

SomeApp is a well known commercial web service and app that consumer interact with directly on their devices. It is representative of any vertical app in any given commercial vertical business area, such as direct retail, hospitality, technology applications, communications, etc.

![Some brand][some-brand]![Some brand text][some-brand-text]

[some-brand]: personas/images/some-brand@64h.png
[some-brand-text]: personas/images/some-brand-text@64h.png

SomeBrand is a public facing brand that consumer interact with directly. It is representative of any commercial vertical business, in an area such as retail, hospitality, technology, communications, energy, real estate etc. It is differentiate from SomeApp in that it does not necessarily offer a consumer app.

### 📇 Contacts app

![Some contacts app][some-contacts-app]![Some contacts app text][some-contacts-app-text]

[some-contacts-app]: personas/images/some-contacts-app@64h.png
[some-contacts-app-text]: personas/images/some-contacts-app-text@64h.png

SomeContactsApp is a well known contact management app that consumer interact with directly on their devices.
