---
title: Требования к исходной среде
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 10/01/2018
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 533063e2-2630-46f3-9a88-ad07bb7dac9a
description: Преимущество FastTrack Center включает руководство по настройке уровней интеграции с исходной средой (например, если в исходной среде уже есть службы, которые требуется переместить в Office 365).
ms.openlocfilehash: 6dfb952b85d26efcfee9b8dc5d6cd4c68a5fe0cd
ms.sourcegitcommit: a754d02f1dea1a2147f716a2cbebda7b68141777
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/01/2018
ms.locfileid: "25353636"
---
# <a name="source-environment-expectations"></a><span data-ttu-id="f4c95-103">Требования к исходной среде</span><span class="sxs-lookup"><span data-stu-id="f4c95-103">Source Environment Expectations</span></span>

<span data-ttu-id="f4c95-104">Преимущество FastTrack Center включает руководство по настройке уровней интеграции с исходной средой (например, если в исходной среде уже есть службы, которые требуется переместить в Office 365).</span><span class="sxs-lookup"><span data-stu-id="f4c95-104">The FastTrack Center Benefit provides guidance for you to set up levels of integration with your source environment (for example, if you already have services in your source environment that you want to move to Office 365).</span></span>
  
> [!NOTE]
> <span data-ttu-id="f4c95-105">Если требуется интеграция, исходная среда должна быть на минимальном уровне для этого приложения.</span><span class="sxs-lookup"><span data-stu-id="f4c95-105">If integration is required, your source environment must be at a minimum level for that application.</span></span> 
  
<span data-ttu-id="f4c95-106">В приведенной ниже таблице представлены требования к имеющейся исходной среде для входящей миграции.\*</span><span class="sxs-lookup"><span data-stu-id="f4c95-106">The following table shows expectations for your existing source environment for onboarding.\*</span></span>

|<span data-ttu-id="f4c95-107">**Действие**</span><span class="sxs-lookup"><span data-stu-id="f4c95-107">**Activity**</span></span>|<span data-ttu-id="f4c95-108">**Требование к исходной среде**</span><span class="sxs-lookup"><span data-stu-id="f4c95-108">**Source environment expectation**</span></span>|
|:-----|:-----|
|<span data-ttu-id="f4c95-109">**Базовое подключение**</span><span class="sxs-lookup"><span data-stu-id="f4c95-109">**Core onboarding**</span></span> | <span data-ttu-id="f4c95-110">Леса Active Directory с функциональным уровнем, соответствующим Windows Server 2003 или более поздней версии, и указанной ниже конфигурацией.</span><span class="sxs-lookup"><span data-stu-id="f4c95-110">Active Directory forests with the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>  <br/>      <span data-ttu-id="f4c95-111">Один лес Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f4c95-111">A single Active Directory forest.</span></span>  <br/>    <span data-ttu-id="f4c95-112">Топологии с одним лесом учетных записей Active Directory и лесом ресурсов (Exchange или Lync 2010, Lync 2013 или Skype для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="f4c95-112">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  <br/>  <span data-ttu-id="f4c95-113">Топологии с несколькими лесами учетных записей Active Directory и лесом ресурсов (Exchange или Lync 2010, Lync 2013 или Skype для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="f4c95-113">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  <br/>  <span data-ttu-id="f4c95-114">Несколько лесов учетных записей Active Directory, один из которых является централизованным лесом учетных записей Active Directory, включающим Exchange и/или Lync 2010, Lync 2013 или Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="f4c95-114">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  <br/>  <span data-ttu-id="f4c95-115">Несколько лесов учетных записей Active Directory, каждый из которых включает свою организацию Exchange.</span><span class="sxs-lookup"><span data-stu-id="f4c95-115">Multiple Active Directory account forests, each with its own Exchange organization.</span></span> <br/> <br/> <span data-ttu-id="f4c95-116">**Примечание**  *В сценариях с несколькими лесами Active Directory Lync 2010, Lync 2013 или Skype для бизнеса следует развертывать в том же лесу Active Directory, что и Exchange.*</span><span class="sxs-lookup"><span data-stu-id="f4c95-116">**Note**  *For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.*</span></span>   <br/>  <br/>      <span data-ttu-id="f4c95-117">**Примечание**  *При реализации нескольких лесов Active Directory с несколькими организациями Exchange в мультигибридной конфигурации Exchange общие пространства имен UPN между исходными лесами не поддерживаются. Основные пространства имен SMTP между организациями Exchange также должны быть отдельными. Дополнительные сведения см. в статье [Гибридные развертывания с несколькими лесами Active Directory](https://go.microsoft.com/fwlink/?linkid=845444).*</span><span class="sxs-lookup"><span data-stu-id="f4c95-117">**Note**  *When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported. Primary SMTP namespaces between Exchange organizations should also be separated. For more information, see [Hybrid deployments with multiple Active Directory forests](https://go.microsoft.com/fwlink/?linkid=845444).*</span></span>     <br/>   <br/>   <span data-ttu-id="f4c95-118">**Примечание**  *Преимущество FastTrack Center недоступно для развертывания AD FS с несколькими лесами.*</span><span class="sxs-lookup"><span data-stu-id="f4c95-118">**Note**  *For all multiple forests configurations, AD FS deployment is out of scope for the FastTrack Center Benefit.*</span></span>           |
|<span data-ttu-id="f4c95-119">**Подключение Exchange Online**</span><span class="sxs-lookup"><span data-stu-id="f4c95-119">**Exchange Online onboarding**</span></span> | <span data-ttu-id="f4c95-120">Среда должна включать один из указанных ниже минимальных уровней.</span><span class="sxs-lookup"><span data-stu-id="f4c95-120">Your environment must have one of the following minimum levels:</span></span>  <br/>  <span data-ttu-id="f4c95-121">Одна или несколько организаций Exchange с Exchange Server 2003 или более поздней версии.</span><span class="sxs-lookup"><span data-stu-id="f4c95-121">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  <br/>  <span data-ttu-id="f4c95-122">Одна среда IBM Domino 7.0.3 или более поздней версии ([Приложение А. Миграция с IBM Domino в Exchange Online](O365-from-ibm-domino-to-exchange-online.md)).</span><span class="sxs-lookup"><span data-stu-id="f4c95-122">A single IBM Domino 7.0.3 onward environment ([Appendix A - Migration from IBM Domino to Exchange Online](O365-from-ibm-domino-to-exchange-online.md)).</span></span>  <br/>  <span data-ttu-id="f4c95-123">Одна почтовая среда, поддерживающая протокол IMAP.</span><span class="sxs-lookup"><span data-stu-id="f4c95-123">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  <br/>  <span data-ttu-id="f4c95-124">Одна среда G Suite (только Gmail, Контакты и Календарь).</span><span class="sxs-lookup"><span data-stu-id="f4c95-124">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  <br/>  <span data-ttu-id="f4c95-125">Одна среда Novell GroupWise 7.0.4 или более поздней версии.</span><span class="sxs-lookup"><span data-stu-id="f4c95-125">A single Novell GroupWise 7.0.4 onward environment.</span></span>  <br/><br/> <span data-ttu-id="f4c95-126">**Примечание**  *Сведения о поддержке нескольких регионов см. в статье [Поддержка нескольких регионов в Exchange Online](https://go.microsoft.com/fwlink/?linkid=872776).*</span><span class="sxs-lookup"><span data-stu-id="f4c95-126">**Note**  *For information on Multi-Geo Capabilities, see [Multi-Geo Capabilities in Exchange Online](https://go.microsoft.com/fwlink/?linkid=872776).*</span></span>           |
|<span data-ttu-id="f4c95-127">**Подключение SharePoint Online и OneDrive для бизнеса**</span><span class="sxs-lookup"><span data-stu-id="f4c95-127">**SharePoint Online and OneDrive for Business onboarding**</span></span>  | <span data-ttu-id="f4c95-128">**Гибридная среда SharePoint**</span><span class="sxs-lookup"><span data-stu-id="f4c95-128">**SharePoint Hybrid**</span></span>  <br/>  <span data-ttu-id="f4c95-p101">Конфигурация гибридной среды SharePoint включает настройку гибридных сайтов, поиска, таксономии, типов контента, версии OneDrive для бизнеса, расширенного средства запуска приложений, сайтов экстрасети, а также функции самостоятельного создания сайтов с локальным подключением к одной целевой среде SharePoint Online. Чтобы включить гибридную среду SharePoint, вам потребуется одна из следующих локальных сред SharePoint Server:  </span><span class="sxs-lookup"><span data-stu-id="f4c95-p101">SharePoint Hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment. To enable SharePoint Hybrid, you must have one of the following on-premises SharePoint Server environments:  </span></span><br/> <br/> <span data-ttu-id="f4c95-131">***SharePoint Server 2013***</span><span class="sxs-lookup"><span data-stu-id="f4c95-131">***SharePoint Server 2013***</span></span>  <br/>  <span data-ttu-id="f4c95-p102">Общедоступное обновление за июнь 2017 г. для гибридных типов контента. Дополнительные сведения см. в статье [Настройка таксономии гибридного развертывания SharePoint и гибридных типов контента](https://go.microsoft.com/fwlink/?linkid=853547).  </span><span class="sxs-lookup"><span data-stu-id="f4c95-p102">June 2017 Public Update (PU) for hybrid content types. For more information, see [Configure hybrid SharePoint taxonomy and hybrid content types](https://go.microsoft.com/fwlink/?linkid=853547).  </span></span><br/>  <span data-ttu-id="f4c95-p103">Общедоступное обновление за март 2017 г. (PU) для настройки функции самостоятельного создания сайтов. Гибридная функция самостоятельного создания сайтов поддерживается только в SharePoint Server 2013. Дополнительные сведения см. в статье [Гибридные средства самостоятельного создания сайтов](https://go.microsoft.com/fwlink/?linkid=846015).  </span><span class="sxs-lookup"><span data-stu-id="f4c95-p103">March 2017 PU for self-service site creation configuration. Hybrid self-service site creation is only supported with SharePoint Server 2013. For more information, see [Hybrid self-service site creation](https://go.microsoft.com/fwlink/?linkid=846015).  </span></span><br/>  <span data-ttu-id="f4c95-p104">Общедоступное обновление за ноябрь 2016 г. и более позднее с гибридной таксономией. Дополнительные сведения см. в статье [Планирование таксономии гибридного развертывания SharePoint](https://go.microsoft.com/fwlink/?linkid=844867).  </span><span class="sxs-lookup"><span data-stu-id="f4c95-p104">November 2016 PU onward with hybrid taxonomy. For more information, see [Plan hybrid SharePoint taxonomy](https://go.microsoft.com/fwlink/?linkid=844867).  </span></span><br/>  <span data-ttu-id="f4c95-139">Общедоступное обновление за июль 2016 г. и более позднее для всех других сценариев гибридной конфигурации.</span><span class="sxs-lookup"><span data-stu-id="f4c95-139">July 2016 PU onward for all other hybrid configuration scenarios.</span></span>  <br/><br/> <span data-ttu-id="f4c95-140">**Примечание**  *Гибридные сценарии SharePoint Server 2013 поддерживаются только в SharePoint Server 2013. Эти сценарии не поддерживаются в SharePoint Foundation 2013.*</span><span class="sxs-lookup"><span data-stu-id="f4c95-140">**Note**  *SharePoint Server 2013 hybrid scenarios are only supported with SharePoint Server 2013. These scenarios aren't supported in SharePoint Foundation 2013.*</span></span>  <br/>   <br/>    <span data-ttu-id="f4c95-141">***SharePoint Server 2016***</span><span class="sxs-lookup"><span data-stu-id="f4c95-141">***SharePoint Server 2016***</span></span>  <br/>  <span data-ttu-id="f4c95-p105">Общедоступное обновление за июнь 2017 г. для гибридных типов контента. Дополнительные сведения см. в статье [Настройка таксономии гибридного развертывания SharePoint и гибридных типов контента](https://go.microsoft.com/fwlink/?linkid=853547).  </span><span class="sxs-lookup"><span data-stu-id="f4c95-p105">June 2017 PU for hybrid content types. For more information, see [Configure hybrid SharePoint taxonomy and hybrid content types](https://go.microsoft.com/fwlink/?linkid=853547).  </span></span><br/>  <span data-ttu-id="f4c95-p106">Общедоступное обновление за ноябрь 2016 г. (пакет дополнительных компонентов 1) с гибридной таксономией. Дополнительные сведения см. в статье [Планирование таксономии гибридной среды SharePoint](https://go.microsoft.com/fwlink/?linkid=844867).  </span><span class="sxs-lookup"><span data-stu-id="f4c95-p106">November 2016 PU (Feature Pack 1) with hybrid taxonomy. For more information, see [Plan hybrid SharePoint taxonomy](https://go.microsoft.com/fwlink/?linkid=844867).  </span></span><br/>  <span data-ttu-id="f4c95-146">Общедоступное обновление за июль 2016 г. и более позднее для всех других сценариев гибридной конфигурации.</span><span class="sxs-lookup"><span data-stu-id="f4c95-146">July 2016 PU onward for all other hybrid configuration scenarios.</span></span>  <br/><br/> <span data-ttu-id="f4c95-147">**Примечание**  *Обновление локальных сред SharePoint до SharePoint Server 2013 или SharePoint Server 2016 не входит в состав Преимущества FastTrack Center. Дополнительные сведения см. в статье [Минимальные уровни общедоступных обновлений для гибридных функций SharePoint](https://go.microsoft.com/fwlink/?linkid=853548).*</span><span class="sxs-lookup"><span data-stu-id="f4c95-147">**Note**  *Upgrade of on-premises SharePoint environments to SharePoint Server 2013 or SharePoint Server 2016 isn't provided by the FastTrack Center Benefit. For more information, see [Minimum public update levels for SharePoint hybrid features](https://go.microsoft.com/fwlink/?linkid=853548).*</span></span>   <br/><br/>        <span data-ttu-id="f4c95-148">**Примечание**  *Информацию о поддержке нескольких регионов см. в статье [Поддержка нескольких регионов в OneDrive и SharePoint Online в Office 365](https://go.microsoft.com/fwlink/?linkid=831056).*</span><span class="sxs-lookup"><span data-stu-id="f4c95-148">**Note**  *For information on Multi-Geo Capabilities, see [Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365](https://go.microsoft.com/fwlink/?linkid=831056).*</span></span>           |
|<span data-ttu-id="f4c95-149">**Подключение Skype для бизнеса Online**</span><span class="sxs-lookup"><span data-stu-id="f4c95-149">**Skype for Business Online onboarding**</span></span>  | <span data-ttu-id="f4c95-150">**Оценка сети**</span><span class="sxs-lookup"><span data-stu-id="f4c95-150">**Network assessment**</span></span>  <br/>  <span data-ttu-id="f4c95-151">Проверка портов и конечных точек.</span><span class="sxs-lookup"><span data-stu-id="f4c95-151">Port and endpoint checks.</span></span>  <br/>  <span data-ttu-id="f4c95-152">Проверка качества подключения.</span><span class="sxs-lookup"><span data-stu-id="f4c95-152">Connection quality checks.</span></span>  <br/>  <span data-ttu-id="f4c95-153">Оценка пропускной способности.</span><span class="sxs-lookup"><span data-stu-id="f4c95-153">Bandwidth estimates.</span></span>  <br/><br/>  <span data-ttu-id="f4c95-154">**Гибридная среда Lync**</span><span class="sxs-lookup"><span data-stu-id="f4c95-154">**Lync Hybrid**</span></span>  <br/>  <span data-ttu-id="f4c95-155">Один локальный лес Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f4c95-155">A single on-premises Active Directory forest.</span></span>  <br/>  <span data-ttu-id="f4c95-156">Среда Lync 2010 Server со средствами администрирования Lync 2013 или средствами администрирования Skype для бизнеса 2015 и ролью пограничного сервера Lync 2010.</span><span class="sxs-lookup"><span data-stu-id="f4c95-156">A Lync 2010 Server environment with Lync 2013 admin tools or Skype for Business 2015 admin tools and a Lync 2010 edge server role.</span></span>  <br/>  <span data-ttu-id="f4c95-157">Среда Lync 2013 Server и роль пограничного сервера Lync 2013.</span><span class="sxs-lookup"><span data-stu-id="f4c95-157">A Lync 2013 Server environment and a Lync 2013 edge server role.</span></span>  <br/><br/>  <span data-ttu-id="f4c95-158">**Гибридная среда Skype для бизнеса Online**</span><span class="sxs-lookup"><span data-stu-id="f4c95-158">**Skype for Business Online Hybrid**</span></span>  <br/>  <span data-ttu-id="f4c95-159">Один локальный лес Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f4c95-159">A single on-premises Active Directory forest.</span></span>  <br/>  <span data-ttu-id="f4c95-160">Один лес учетных записей Active Directory и топологии леса ресурсов (Exchange и/или Skype для бизнеса)</span><span class="sxs-lookup"><span data-stu-id="f4c95-160">A single Active Directory account forest onward and resource forest (Exchange and/or Skype for Business) topologies.</span></span>  <br/>  <span data-ttu-id="f4c95-161">Несколько лесов учетных записей Active Directory, один из которых является централизованным лесом учетных записей Active Directory с Exchange и/или Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="f4c95-161">Multiple Active Directory account forests, with one forest being a centralized Active Directory account forest with Exchange and/or Skype for Business in it.</span></span>  <br/>  <span data-ttu-id="f4c95-162">Среда Skype для бизнеса Server 2015, включающая роль пограничного сервера Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="f4c95-162">A Skype for Business Server 2015 environment including a Skype for Business edge server role.</span></span>  <br/><br/> <span data-ttu-id="f4c95-163">**Примечание**  *Эта дополнительная услуга предназначена для настройки и проверки задач разделенного домена (гибридного) и не включает установку локальных компонентов (например, средств администрирования Lync 2013, серверов Lync 2013/Skype для бизнеса Online или пограничных серверов Lync 2013, Lync 2010 или Skype для бизнеса).*</span><span class="sxs-lookup"><span data-stu-id="f4c95-163">**Note**  *This additional service is for configuring and validating of the split domain (hybrid) tasks and doesn't include introducing on-premises components (for example, Lync 2013 admin tools or Lync 2013/Skype for Business Online servers, or Lync 2010, Lync 2013, or Skype for Business edge servers).*</span></span>    <br/><br/>        <span data-ttu-id="f4c95-164">**Устройство для конференц-связи**</span><span class="sxs-lookup"><span data-stu-id="f4c95-164">**Conference room device**</span></span>  <br/>  <span data-ttu-id="f4c95-165">Создание учетных записей интернет-служб, необходимых для поддерживаемых устройств для конференц-связи. Устройства перечислены на вкладке "Системы комнаты собраний" в [каталоге решений для Skype для бизнеса](https://go.microsoft.com/fwlink/?LinkId=615775).  </span><span class="sxs-lookup"><span data-stu-id="f4c95-165">Creation of online accounts needed for supported conference room devices listed on the Meeting Room Systems tab in the [Skype for Business Solutions Catalog](https://go.microsoft.com/fwlink/?LinkId=615775).</span></span>  <br/><br/>  <span data-ttu-id="f4c95-166">**Включение Аудиоконференций**</span><span class="sxs-lookup"><span data-stu-id="f4c95-166">**Enabling Audio Conferencing**</span></span>  <br/>  <span data-ttu-id="f4c95-167">Настройка организации с использованием параметров моста конференции по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="f4c95-167">Organization setup for conference bridge default settings.</span></span>  <br/>  <span data-ttu-id="f4c95-168">Назначение моста конференции лицензированным пользователям.</span><span class="sxs-lookup"><span data-stu-id="f4c95-168">Assignment of conference bridge to licensed users.</span></span>  <br/><br/>  <span data-ttu-id="f4c95-169">**Руководство по включению Телефонной системы и Планов звонков (только для США)**</span><span class="sxs-lookup"><span data-stu-id="f4c95-169">**Enabling Phone System and Calling Plans guidance (US only)**</span></span>  <br/>  <span data-ttu-id="f4c95-170">Настройка облачных голосовых функций для организации.</span><span class="sxs-lookup"><span data-stu-id="f4c95-170">Organization setup for Cloud Voice default settings.</span></span>  <br/>  <span data-ttu-id="f4c95-171">Назначение номеров лицензированным пользователям.</span><span class="sxs-lookup"><span data-stu-id="f4c95-171">Assignment of numbers to licensed users.</span></span>  <br/>  <span data-ttu-id="f4c95-172">Рекомендации по портированию локальных номеров до 999 в пользовательском интерфейсе.</span><span class="sxs-lookup"><span data-stu-id="f4c95-172">Local number porting guidance through user interface (UI) up to 999.</span></span>  <br/>  <span data-ttu-id="f4c95-173">Поддержка запросов на обслуживание для портирования локальных номеров выше 999.</span><span class="sxs-lookup"><span data-stu-id="f4c95-173">Local number porting service request (SR) support over 999.</span></span>  <br/><br/>  <span data-ttu-id="f4c95-174">**Подключение руководства по включению трансляции собраний Skype для бизнеса**</span><span class="sxs-lookup"><span data-stu-id="f4c95-174">**Enabling Skype for Business Meeting Broadcast guidance onboarding**</span></span>  <br/>  <span data-ttu-id="f4c95-175">Настройка организации для федерации со службой трансляции собраний.</span><span class="sxs-lookup"><span data-stu-id="f4c95-175">Organization setup for federation with Meeting Broadcast service.</span></span>   |
|<span data-ttu-id="f4c95-176">**Подключение Microsoft Teams**</span><span class="sxs-lookup"><span data-stu-id="f4c95-176">**Microsoft Teams onboarding**</span></span>  | <span data-ttu-id="f4c95-177">Удостоверения включены в Azure Active Directory для Office 365.</span><span class="sxs-lookup"><span data-stu-id="f4c95-177">Identities enabled in Azure Active Directory for Office 365.</span></span>  <br/>  <span data-ttu-id="f4c95-178">Пользователи, для которых включен SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f4c95-178">Users enabled for SharePoint Online.</span></span>  <br/>  <span data-ttu-id="f4c95-179">Есть почтовые ящики Exchange (в сети и/или локально в гибридной конфигурации Exchange).</span><span class="sxs-lookup"><span data-stu-id="f4c95-179">Exchange mailboxes are present (online and/or on-premises in an Exchange hybrid configuration).</span></span>  <br/>  <span data-ttu-id="f4c95-180">Включено для групп Office 365.</span><span class="sxs-lookup"><span data-stu-id="f4c95-180">Enabled for Office 365 Groups.</span></span>  <br/><br/> <span data-ttu-id="f4c95-181">**Примечание**  *Если пользователям не назначены лицензии SharePoint Online, у них не будет хранилища OneDrive для бизнеса в Office 365. Без него можно обмениваться файлами в Каналах, но нельзя обмениваться файлами в чатах. Microsoft Teams не поддерживает локальную среду SharePoint.*</span><span class="sxs-lookup"><span data-stu-id="f4c95-181">**Note**  *If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365. File sharing will continue to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365. Microsoft Teams doesn't support SharePoint on-premises.*</span></span>   <br/> <br/>       <span data-ttu-id="f4c95-182">**Примечание**  *В идеале почтовые ящики всех пользователей должны храниться в Exchange Online. Удостоверения пользователей, чьи почтовые ящики хранятся локально, должны синхронизироваться с каталогом Office 365 через Azure Active Directory Connect. Пользователи, чьи почтовые ящики хранятся локально, не могут добавлять и настраивать соединители.*</span><span class="sxs-lookup"><span data-stu-id="f4c95-182">**Note**  *The ideal state is for all users to have their mailboxes homed on Exchange Online. Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 Directory through Azure Active Directory Connect. For these Exchange hybrid customers, if the user's mailbox is on-premises, the user can't add or configure Connectors.*</span></span>          |
|<span data-ttu-id="f4c95-183">**Подключение Microsoft StaffHub**</span><span class="sxs-lookup"><span data-stu-id="f4c95-183">**Microsoft StaffHub onboarding**</span></span>  | <span data-ttu-id="f4c95-184">Удостоверения включены в Azure Active Directory для Office 365.</span><span class="sxs-lookup"><span data-stu-id="f4c95-184">Identities enabled in Azure Active Directory for Office 365.</span></span>  <br/><br/> <span data-ttu-id="f4c95-185">**Примечание**  *Приложение Microsoft StaffHub включено по умолчанию.*</span><span class="sxs-lookup"><span data-stu-id="f4c95-185">**Note**  *Microsoft StaffHub is enabled by default.*</span></span>           |
| <span data-ttu-id="f4c95-186">**Подключение службы**, в том числе:</span><span class="sxs-lookup"><span data-stu-id="f4c95-186">**Service onboarding**, including:</span></span>  <br/>  <span data-ttu-id="f4c95-187">*Exchange Online  <br/>  SharePoint Online  <br/>  OneDrive для бизнеса  <br/>  Skype для бизнеса Online  <br/>  Microsoft Teams  <br/>  Power BI  <br/>  Project Online  <br/>  Yammer  <br/>  Office 365 профессиональный плюс  <br/>  Microsoft StaffHub*</span><span class="sxs-lookup"><span data-stu-id="f4c95-187">*Exchange Online  <br/>  SharePoint Online  <br/>  OneDrive for Business  <br/>  Skype for Business Online  <br/>  Microsoft Teams  <br/>  Power BI  <br/>  Project Online  <br/>  Yammer  <br/>  Office 365 ProPlus  <br/>  Microsoft StaffHub*</span></span>   |<span data-ttu-id="f4c95-188">Программное обеспечение сетевых клиентов, например Project для Office 365, клиента Outlook, клиента синхронизации OneDrive для бизнеса, Power BI Desktop и Skype для бизнеса должно соответствовать минимальным требованиям, указанным в статье [Требования к системе для Office](https://go.microsoft.com/fwlink/?LinkID=723597).</span><span class="sxs-lookup"><span data-stu-id="f4c95-188">Online client software like Project for Office 365, Outlook client, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in [System requirements for Office](https://go.microsoft.com/fwlink/?LinkID=723597).</span></span>  <br/> <span data-ttu-id="f4c95-189">Установщики клиентов Microsoft Teams для настольных компьютеров Windows и Mac можно скачать на странице [https://go.microsoft.com/fwlink/?linkid=839411](https://go.microsoft.com/fwlink/?linkid=839411).</span><span class="sxs-lookup"><span data-stu-id="f4c95-189">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from [https://go.microsoft.com/fwlink/?linkid=839411](https://go.microsoft.com/fwlink/?linkid=839411).</span></span>   |
   
<span data-ttu-id="f4c95-190">\*Сведения о требованиях к исходной среде для Office 365 для государственных организаций США см. в статье [Требования к исходной среде для Office 365 для государственных организаций США](US-Gov-appendix-source-environment-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="f4c95-190">\*For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](US-Gov-appendix-source-environment-expectations.md).</span></span>
  
