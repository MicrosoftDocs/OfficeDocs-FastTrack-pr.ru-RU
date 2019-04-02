---
title: Процесс FastTrack
description: Обзор процесса входящей миграции FastTrack Center
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 04/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a2d3f601c1395b908d2ad8fd7a6a0dde38502784
ms.sourcegitcommit: 8d1fbbfc6b05522ea1259149349548f072fefcac
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/01/2019
ms.locfileid: "31016783"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Процесс реализации преимущества FastTrack Center для Enterprise Mobility + Security (EMS)
Если ваша организация соответствует преимуществам FastTrack Center для EMS, вы можете работать удаленно с FastTrack, чтобы получить Microsoft Azure Active Directory Premium и Microsoft Intune готов к использованию. Вы также можете запросить помощь через [сайт FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) для Azure Information Protection, Microsoft Cloud App Security и Microsoft Advanced Threat Analytics. Чтобы узнать, соответствует ли ваша организация требованиям, ознакомьтесь со статьями [Доступные службы и планы](M365-eligible-services-and-plans.md).


Мы рассмотрим процесс входящей миграции:

-   [Общие сведения о процессе входящей миграции](EMS-fasttrack-benefit-overview.md)

-   [Ожидания для исходной среды](EMS-source-environment-expectations.md)

-   [Этапы процесса входящей миграции](EMS-onboarding-phases.md)

-   [Обязанности FastTrack](EMS-fasttrack-responsibilities.md) для каждого этапа

-   [Обязанности клиента](EMS-your-responsibilities.md) для каждого этапа

При завершении входящей миграции вы можете ожидать:

-   Будут созданы клиенты EMS для выбранных служб.

-   Лицензированные пользователи могут получить доступ к службам EMS с помощью одного из следующих параметров удостоверения.

    -   Облачные удостоверения (уникальные учетные записи EMS).

    -   Синхронизированные удостоверения: учетные записи EMS, синхронизированные из локальной службы Active Directory, с помощью средства Azure Active Directory Connect (синхронизация хэша паролей или сквозная проверка поДлинности). Этот параметр предназначен для клиентов с одним лесом или несколькими лесами Active Directory.

    -   Федеративные удостоверения (с учетными записями Майкрософт EMS):

        -   Синхронизируется из Active Directory с помощью средства Azure AD Connect. Этот параметр предназначен для пользователей с одной конфигурацией леса Active Directory.

        -   Федеративные службы федерации Active Directory (AD FS) с Windows Server 2012 R2 (AD FS) 2,0 или более поздней версии из локальной службы Active Directory.