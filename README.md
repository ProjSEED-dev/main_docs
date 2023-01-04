# Intro

This repo contains docs of ProjSEED, including structure of project, api description, and so on.

About this repo:

* structure_info_images: Images about project structure.



# About ProjSEED

ProjSEED is an open-source ACGMN (Anime+Comic+Game+Music+Novel) CMS (Content Manager System) project, with content fetching support.

Subproject description:

* Prometheus: Framework of a tool to steal resources like anime, comic, music and so on from websites. Put simply, web crawler framework for ProjSEED.

* Evergarden: Main part of CMS. It manages database and resources on disk,  supports api for frontend.

  Resources got by Prometheus will be transferred to Evergarden, where they are managed.

* Vladilena: Admin frontend for Prometheus and Evergarden.

* ProjectorS: It consists of lots of frontend project of CMS, like web page and android app.

> Prometheus is known as theft of fire. [Evergarden](https://en.wikipedia.org/wiki/Violet_Evergarden) and [Vladilena](https://86-eighty-six.fandom.com/wiki/Vladilena_Miliz%C3%A9) are the name of anime characters.
