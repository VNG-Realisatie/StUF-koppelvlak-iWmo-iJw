---
layout: page-with-side-nav
title: StUF-koppelvlak iWmo-iJw
---
# StUF-koppelvlak iWmo-iJw

**Actuele versie:** 2.1
**Beheerder:**  VNG Realisatie
**Afkorting:**  StUF-GGK

Bij de uitvoering van de taken die voortvloeien uit de Wmo 2015 en de Jeugdwet zijn een groot aantal keten- en netwerkpartijen betrokken. Het netwerk van deze partijen wordt de ISD-Keten genoemd. Binnen deze ISD-Keten worden tussen de verschillende partijen op diverse momenten binnen de uitvoering van de processen gegevens uitgewisseld. Het gaat hierbij bijvoorbeeld om het toewijzen van ondersteuning aan een zorgaanbieder, het declareren of factureren van geleverde ondersteuning en het aanleveren van gegevens aan het CAK ten behoeve van de vaststelling van de hoogte van de eigen bijdrage. Deze gegevensuitwisselingen vinden plaats via gestructureerde berichten (iWmo en iJw berichten), maar ook via ongestructureerde uitwisselingen met ketenpartners. Om binnen de SD-Keten op een eenduidige manier berichten tussen partijen te kunnen routeren is er voor gekozen om het transport van berichten te scheiden van de inhoud van berichten. De wijze waarop dit tot stand is gebracht is via het inpakken van berichten in een envelop. De envelop bevat enerzijds gegevens ten behoeve van de routering van berichten van afzender naar ontvanger en anderzijds bevat de envelop de inhoudelijke gegevens die uitgewisseld worden (de payload). Deze systematiek is vergelijkbaar met het verzenden van een brief. Ook een brief wordt verzonden in een envelop. Een postbezorger kan de brief bezorgen bij de ontvanger aan de hand van het adres op de envelop, en kan de brief aan de hand van het retouradres retour zenden naar de verzender indien de brief niet bezorgd kan worden. De postbezorger heeft heeft geen kennis van de inhoud van de brief.

De standaard die gekozen is voor de enveloppering binnen de ISD-keten is gebaseerd op de gemeentelijke StUF-standaard. Bij de routering op basis van deze StUF-envelop wordt gebruik gemaakt van de StUF vrije berichten ggk0310-Di01 als initieel bericht, en ggk0310-Du01 als bijbehorende retourbericht. In de StUF-standaard zijn afspraken gemaakt over de manier waarop bij vrije berichten omgegaan dient te worden met bevestigings- en foutberichten.

In het tabblad 'Documentatie' kunt u de specificatie voor de StUF-envelop ten behoeve van het uitwisselen van berichten binnen de ISD-Keten vinden.