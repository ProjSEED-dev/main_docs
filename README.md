# Intro

This repo contains docs of ProjSEED, including structure of project, api description, and so on.

About this repo:

* struct_img: Images about project structure.



# Little words about ProjSEED

ProjSEED is a open-source project for ACGMN (Anime+Comic+Game+Music+Novel) CMS (Content Manager System), with content fetching support.

Subproject description:

* Prometheus: Framework of a tool to steal resources like anime, comic, music and so on from website. Put simply, web crawler framework for ProjSEED.

* Evergarden: Main part of CMS. It manages database and resources on disk,  supports api for frontend.

  Resources got by Prometheus will be transferred to Evergarden, where they are managed.

* Lena: Admin frontend for Prometheus and Evergarden.

* ProjectorS: It consists of lots of frontend of CMS, like web page and android app.

> Prometheus is known as theft of fire. Evergarden and Lena is the name of an anime character.
