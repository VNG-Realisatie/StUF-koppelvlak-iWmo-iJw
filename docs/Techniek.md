---
layout: page-with-side-nav
title: Techniek StUF-koppelvlak iWmo-iJw
---
# Techniek StUF-koppelvlak iWmo-iJw

Bij de uitvoering van de taken die gemeenten uit de WMO 2015 en Jeugdwet toebedeeld hebben gekregen wisselen gemeenten met een groot aantal ketenpartijen gestructureerde en ongestructureerde gegevens uit. Ten behoeve van deze gegevensuitwisselingen maken gemeenten gebruik van de diensten van het Gemeentelijk Gegevensknooppunt (GGk). Het GGk biedt portaal- en webservicediensten die door gemeenten gebruikt worden om de gegevensuitwisselingen ten aanzien van de verschillende gegevensstromen mee vorm te geven. Ketenpartijen die aangesloten zijn op het GGk zijn onder andere zorgaanbieders (via VECOZO), de RvIG, het CBS, het CIZ en de SVB. In de toekomst worden nog meer ketenpartijen, zoals het CAK, aangesloten.

De infrastructuur die de gemeenten verbind met ketenpartijen wordt de ISD-keten genoemd. Binnen de ISD-keten wordt een veelheid aan berichten en berichtformaten gebruikt. Om de diensten die door de ISD-keten worden geboden onafhankelijk te houden van de verschillende soorten en versies van berichten die via de ISD-keten gerouteerd worden is ervoor gekozen routeringsgegevens los te knippen van inhoudelijke berichten. Inhoudelijke berichten (de payload) worden ingepakt in een envelop: de StUF-GGk berichtenvelop. Alle berichten die door gemeenten aan de ISD-keten worden aangeboden, onafhankelijk of dit plaatsvindt via webservices of via portaaldiensten van het GGk, dienen ingepakt te zijn in een StUF-GGk berichtenvelop.