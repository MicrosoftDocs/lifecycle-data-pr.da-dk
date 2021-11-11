---
title: Vejledning til eksport af livscyklusdata
description: Vejledning til eksport af oplysninger om produktlevetid
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: da-DK
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546765"
---
# <a name="lifecycle-data-export-guidance"></a>Vejledning til eksport af livscyklusdata
I dette dokument beskrives det, hvordan du bruger produkteksportfilen.

## <a name="query-information"></a>Forespørgselsoplysninger
I Excel-dokumentet er der felter, der kan hjælpe med at identificere de data, der er i produkttabellen.

### <a name="end-of-support"></a>Ophør af support
Ved slutningen af supportværdien filtreres produkter efter enten slutdatoen for produktets support eller slutdatoen for udgivelsen.

Mulige værdier: Alle (intet filter anvendt), År og Område.

### <a name="family"></a>Familie
Familieværdien filtrerer produkter efter det overordnede niveau i hierarkiet, som kaldes familien.

Mulige værdier: Alle (intet filter anvendt), Familienavn

### <a name="group"></a>Gruppe
Gruppeværdien filtrerer produkter inden for det overordnede niveau (familie) til en bestemt gruppe.

Mulige værdier: Alle (intet filter anvendt), Gruppenavn

## <a name="table-columns"></a>Tabelkolonner
Produkttabellen består af kolonner, der definerer produkter, udgaver, udgivelser og tilsvarende supportdatoer.

> [!NOTE]
> Der er en række for hvert produkt, hver udgave og hver udgivelseskombination.

### <a name="product"></a>Produkt
Produktnavnet.

### <a name="edition"></a>Edition.
Versionskolonnen udfyldes, når produktet indeholder udgaver. Når der ikke er nogen produktversion, er dette felt tomt.

### <a name="release"></a>Udgivelse
Kolonnen Udgivelse udfyldes, når produktet indeholder flere udgivelser.
Når produktet kun findes i én version, er dette felt tomt.

### <a name="support-policy"></a>Supportpolitik
Dette felt definerer, hvilken supportpolitik produktet følger.

Mulige værdier: [Faste](/lifecycle/policies/fixed), [Moderne](/lifecycle/policies/modern) og Komponent

### <a name="start-date"></a>Startdato
Dato for start af support for produktet.

### <a name="mainstream-date"></a>Generel dato
Når supportpolitikken er **fast** eller **komponent**, er dette produktets almindelige slutdato.
  
Når supportpolitik er **moderne**, er dette tomt.

### <a name="extended-end-date"></a>Slutdato for udvidet support
Når Supportpolitik er **Fast** eller **Komponent**, er dette den dato, hvor produktforlængelsen slutter.

Når supportpolitik er **moderne**, er dette tomt.

### <a name="retirement-date"></a>Dato for tilbagetrækning
Når Supportpolitik er **Fast** eller **Komponent,** er dette tomt.

Når supportpolitikken er **Moderne**, er dette produktets tilbagetrækningsdato.

### <a name="release-start-date"></a>Startdato for udgivelse
Dato for start af support til udgivelse. Når produktet kun findes i én version, er dette felt tomt.
 
### <a name="release-end-date"></a>Slutdato for udgivelse
Dato for ophør af understøttelse af udgivelsen.
Når produktet kun findes i én version, er dette felt tomt.

### <a name="docs-url"></a>Url-adresse til Docs
URL-adresse til udvidet dokumentation.
