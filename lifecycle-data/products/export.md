---
title: Eksport af data for livscyklus
description: Eksportere oplysninger om produktlivscyklus
ms.date: 08/21/2020
layout: ContentPage
ms.openlocfilehash: 56cab0b1a87b24a963dd5c252a0199dfabb08767
ms.sourcegitcommit: 37ac01a1d5492bb2bf54cbd018ea34074db8c998
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 09/01/2020
ms.locfileid: "940810"
---
# <a name="lifecycle-data-export"></a>Eksport af data for livscyklus

> [!IMPORTANT]
> Denne side er under udvikling.

## <a name="export-all-products"></a>Eksportér alle produkter
Eksportér livscyklus data for alle produkter ved at klikke herunder:

> [!div class="nextstepaction"]
> [Eksportér alle produkter](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export)

## <a name="export-products-by-family-and-group"></a>Eksportere produkter efter familie og gruppe
Vælg en familie og derefter en gruppe, der skal eksporteres. Bemærk: eksporten starter, når Gruppeværdien er markeret. 

> [!div class="op_multi_selector" title1="Pc'er" title2="Gruppe"]
> - [(.NET | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'.NET')
> - [(.NET | .NET)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'.NET'%20and%20parent/parent/name%20eq%20'.NET')
> - [(Azure | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure')
> - [(Azure | Pi](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'AI')
> - [(Azure | Azure](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Azure')
> - [(Azure | Databaser](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Databases')
> - [(Azure | Bort](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Other')
> - [(Dynamics | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics')
> - [(Dynamics | Webstedet](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics')
> - [(Dynamics | Dynamics 365)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20365')
> - [(Dynamics | Dynamics AX)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20AX')
> - [(Dynamics | Dynamics C5)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20C5')
> - [(Dynamics | Dynamics CRM)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20CRM')
> - [(Dynamics | Dynamics GP)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20GP')
> - [(Dynamics | Dynamics NAV)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20NAV')
> - [(Dynamics | Dynamics POS)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20POS')
> - [(Dynamics | Dynamics RMS)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20RMS')
> - [(Dynamics | Dynamics SL)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20SL')
> - [(Dynamics | Bort](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Other')
> - [(Udtryk | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Expression')
> - [(Udtryk | Udtryk](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Expression'%20and%20parent/parent/name%20eq%20'Expression')
> - [(Microsoft 365 | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365')
> - [(Microsoft 365 | Enterprise Mobility + sikkerhed)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365'%20and%20parent/parent/name%20eq%20'Enterprise%20Mobility%20%2B%20Security')
> - [(Microsoft 365 | Identitetsstyring)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365'%20and%20parent/parent/name%20eq%20'Identity%20Management')
> - [(Microsoft Connected Services Framework | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Connected%20Services%20Framework')
> - [(Microsoft Connected Services Framework | Framework til forbundne tjenester](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Connected%20Services%20Framework'%20and%20parent/parent/name%20eq%20'Connected%20Services%20Framework')
> - [(Microsoft Customer Care Framework | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Customer%20Care%20Framework')
> - [(Microsoft Customer Care Framework | Kundens pleje Framework)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Customer%20Care%20Framework'%20and%20parent/parent/name%20eq%20'Customer%20Care%20Framework')
> - [(Microsoft Edge | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Edge')
> - [(Microsoft Edge | Nyeste](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Edge'%20and%20parent/parent/name%20eq%20'Edge')
> - [(Microsoft Internet Explorer | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Internet%20Explorer')
> - [(Microsoft Internet Explorer | Internet Explorer)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Internet%20Explorer'%20and%20parent/parent/name%20eq%20'Internet%20Explorer')
> - [(Microsoft Office | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office')
> - [(Microsoft Office | Client](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Client')
> - [(Microsoft Office | Advarsel](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Security')
> - [(Microsoft Office | Replikaserveren](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Server')
> - [(Microsoft-servere | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers')
> - [(Microsoft-servere | BizTalk Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'BizTalk%20Server')
> - [(Microsoft-servere | Commerce Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Commerce%20Server')
> - [(Microsoft-servere | Indholds administrations server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Content%20Management%20Server')
> - [(Microsoft-servere | Host Integration Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Host%20Integration%20Server')
> - [(Microsoft-servere | Intelligent Application Gateway)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Intelligent%20Application%20Gateway')
> - [(Microsoft-servere | Advarsel](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Security')
> - [(Microsoft System Center | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20System%20Center')
> - [(Microsoft System Center | System Center)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20System%20Center'%20and%20parent/parent/name%20eq%20'System%20Center')
> - [(Silverlight | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Silverlight')
> - [(Silverlight | Silverlight](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Silverlight'%20and%20parent/parent/name%20eq%20'Silverlight')
> - [(SQL Server | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server')
> - [(SQL Server | Power BI)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server'%20and%20parent/parent/name%20eq%20'Power%20BI')
> - [(SQL Server | SQL Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server'%20and%20parent/parent/name%20eq%20'SQL%20Server')
> - [(Visual Studio | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Visual%20Studio')
> - [(Visual Studio | Visual Studio)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Visual%20Studio'%20and%20parent/parent/name%20eq%20'Visual%20Studio')
> - [(Windows | Alle](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows')
> - [(Windows | Client](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Client')
> - [(Windows | IOT](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'IoT')
> - [(Windows | MSN](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Mobile')
> - [(Windows | Advarsel](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Security')
> - [(Windows | Replikaserveren](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Server')

## <a name="export-products-by-end-of-support-date"></a>Eksportere produkter ved hjælp af dato for ophør
Vælg et år for at få vist produkter, når du når til sidst i support. Bemærk: eksporten begynder, når år-værdi er valgt.

> [!div class="op_single_selector"]
> - [2002](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2002))
> - [2003](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2003))
> - [2004](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2004))
> - [2005](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2005))
> - [2006](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2006))
> - [2007](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2007))
> - [2008](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2008))
> - [2009](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2009))
> - [2010](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2010))
> - [2011](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2011))
> - [2012](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2012))
> - [2013](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2013))
> - [2014](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2014))
> - [2015](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2015))
> - [2016](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2016))
> - [2017](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2017))
> - [2018](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2018))
> - [2019](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2019))
> - [2020](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2020))
> - [2021](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2021))
> - [2022](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2022))
> - [2023](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2023))
> - [2024](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2024))
> - [2025](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2025))
> - [2026](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2026))
> - [2027](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2027))
> - [2028](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2028))
> - [2029](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2029))
> - [2030](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2030))
