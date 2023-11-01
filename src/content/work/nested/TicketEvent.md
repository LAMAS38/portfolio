---
title: Ticket Event
publishDate: 2023-10-31 21:12:12
img: /assets/TicketEvent_ex_billet.png
img_alt: Aperçu du billet electronique
description: |
  J'ai develeppé une application de Génération de Billets Électroniques pour un Gala
tags:
  - Automatisation
  - Python
  - Application Desktop
---

## Contexte
Lors d'un événement gala organisé par la communauté des jeunes nigériens, j'ai pris l'initiative de créer une application pour faciliter le processus de distribution des billets. Le système permet de générer des billets électroniques et de les envoyer directement aux participants par e-mail. Cette solution numérique a contribué à optimiser l'organisation de l'événement et à offrir une expérience utilisateur améliorée.

## Fonctionnalités
- **Génération de billets électroniques:** Chaque billet est unique et contient un code QR généré aléatoirement, les informations du participant et les détails de l'événement.
- **Validation des données:** Avant la création du billet, l'application vérifie si tous les champs sont correctement remplis et si l'adresse e-mail est valide.
- **Envoi automatique par e-mail:** Les billets sont envoyés automatiquement aux participants via e-mail dès leur création.
- **Base de données des participants:** Les informations des participants sont stockées dans un fichier Excel, facilitant ainsi la gestion et le suivi.

## Technologies Utilisées
- **Python:** Langage de programmation principal.
- **Tkinter:** Pour la création de l'interface utilisateur graphique.
- **Openpyxl:** Pour la manipulation du fichier Excel contenant les données des participants.
- **QR Code:** Génération des codes QR pour les billets.
- **SMTP:** Pour l'envoi des e-mails.
- **Excel:** Pour la liste des participants.

## Comment ça marche
L'application offre une interface utilisateur simple et intuitive. L'utilisateur doit entrer le nom, le prénom et l'adresse e-mail du participant. Après validation des données, un billet électronique est généré et envoyé à l'adresse e-mail fournie. Les informations du participant sont également enregistrées dans un fichier Excel pour un suivi facile.

## Aperçu
<!-- ![Aperçu de l'interface](/assets/UI.png) ![Aperçu de la liste excel](/assets/excel.png)
![Aperçu du bullet](/assets/ex_billet.png) ![Aperçu de mail envoyer](/assets/mail.png) -->
<table>
  <tr>
    <td>
      <img src="/assets/TicketEvent_UI.png" alt="Aperçu de l'interface" width="100%"/>
    </td>
    <td>
      <img src="/assets/TicketEvent_ex_billet.png" alt="Aperçu du billet" width="100%"/>
    </td>
  </tr>
  <tr>
    <td>
      <img src="/assets/TicketEvent_excel.png" alt="Aperçu de la liste Excel" width="200%"/>
    </td>
    <td>
      <img src="/assets/TicketEvent_mail.png" alt="Aperçu du mail envoyé" width="200%"/>
    </td>
  </tr>
</table>

## Conclusion
Cette application a non seulement simplifié le processus de distribution des billets mais a également offert une solution éco-responsable en éliminant le besoin de billets physiques. L'automatisation de la vérification des données et de l'envoi des e-mails a permis de gagner du temps et d'assurer une expérience fluide tant pour les organisateurs que pour les participants.

## Remerciements
Je tiens à remercier l'équipe d'organisation du Gala des Jeunes Nigériens pour m'avoir donné l'opportunité de contribuer à cet événement mémorable et d'appliquer mes compétences en développement logiciel pour faciliter l'organisation de l'événement.
