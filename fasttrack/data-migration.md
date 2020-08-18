---
title: Перенос данных
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса). Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас.
ms.openlocfilehash: fc7f07aea6104fdc6f06b3d624778919b351b34d
ms.sourcegitcommit: 81ad135578a329f8b0a3325c4e43bb8f90648597
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/17/2020
ms.locfileid: "46777092"
---
# <a name="data-migration"></a>Перенос данных

FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса).

Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас:

  - **Для клиентов Office 365 с 150-499 лицензиями**: FastTrack предоставляет только руководство по переносу данных; ответственность за выполнение переноса данных лежит на вас. Вам будет предоставлена документация, которая поможет спланировать и использовать бесплатные ресурсы для самостоятельного переноса данных.
  - **Для клиентов Office 365 с 500 и более лицензиями**: FastTrack предоставляет инструкции по руководство по переносу данных и службы переноса данных. Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и клиента Office 365, а также использовать наши службы переноса данных для переноса ваших данных. Создайте и запланируйте события переноса данных. Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.

> [!NOTE]
> Если вы приобрели или обновили коммерческий план до 9/1/2017, вам необходимо только 150 лицензий для получения доступа к службам переноса данных. В случае планов для образовательных учреждений право на получение доступа к службам переноса данных есть только у преподавателей и персонала с оплаченными лицензиями.

### <a name="considerations"></a>Рекомендации

  - Ваша исходная среда должна соответствовать определенным ожиданиям для переноса данных в Office 365. Дополнительные сведения об ожиданиях исходной среды для Exchange, SharePoint и OneDrive для бизнеса, см. в статье [Продукты и возможности](products-and-capabilities.md).
  - Для использования служб переноса данных необходимо получить соответствующий доступ и разрешения для вашей исходной среды и клиента Office 365.
  - Наши службы переноса данных не предназначены для работы с данными, попадающими под действие особых законодательных или нормативных актов. В процессе переноса данных их можно переносить, хранить и обрабатывать в любом месте, где расположены наши офисы (за исключением случаев, когда для вашего проекта миграции FastTrack предусмотрено иное).
  - Мы не можем гарантировать скорость перемещения почты и файлов.
  - Непредвиденные проблемы (например, нечитаемые или поврежденные элементы в исходной среде) могут помешать переносу некоторых элементов данных.
  - Внешние факторы, находящиеся вне нашего контроля, например, изменения в API сторонних разработчиков, могут привести к изменениям, задержкам или приостановке работы наших служб переноса данных.

### <a name="migration-service-availability"></a>Служба переноса данных доступна

  - **Для заказчиков — коммерческого сектора и государственных организаций Соединенного Королевства:** предоставляются услуги по переносу данных 24 часа в сутки семь (7) дней в неделю (24x7).
  - **Для заказчиков — государственных организаций и Министерства обороны США:** предоставляются услуги по переносу данных 24 часа в сутки пять (5) рабочих дней в неделю (24x5).

## <a name="migration-to-exchange-online"></a>Перенос данных в Exchange Online

После принятия вами решения об использовании FastTrack для переноса электронной почты в Exchange Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных. Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и Exchange Online, а также использовать наши службы переноса данных для переноса ваших почтовых ящиков. Создайте и запланируйте события переноса данных. Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии. После окончания переноса данных, вы можете ожидать переноса почты из запланированных и зарегистрированных исходных почтовых ящиков в вашей исходной среде в Exchange Online.

### <a name="considerations"></a>Рекомендации

  - До переноса данных необходимо выполнить подключения FastTrack для Exchange Online;
      - При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия. Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).
  - FastTrack может перенести только в активные почтовые ящики Office 365.
  - При миграции из локальной среды Exchange необходимо соответствовать определенным требованиям. Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).
  - Во всех исходных средах должны быть установлены последние пакет обновления (SP) и накопительный пакет обновления (CU) для соответствующих продуктов.
  - Списки рассылки (объекты *MailEnabledGroup*) и внешние контакты (объекты *MailEnabledContact*), которые находятся в локальном каталоге Active Directory, не переносятся при переносе данных почтовых ящиков. Однако вы можете синхронизировать их с помощью Azure Active Directory (Azure AD) Connect. 

## <a name="source-environments"></a>Исходные среды

Наша служба переноса данных переносит данные из следующих исходных сред:

  - Один или несколько лесов Active Directory с одной или несколькими организациями Exchange (каждая почтовая система Exchange должна быть Exchange 2010 или более поздней).
  - Одна почтовая среда с поддержкой IMAP.
  - Среда G Suite (только Gmail, Контакты и Календарь).

В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:

<table>
<thead>
<tr class="header">
<th><strong>Исходная среда</strong></th>
<th><strong>Тип миграции</strong></th>
<th><strong>Что переносится</strong></th>
<th><strong>Что не переносится</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong><br />
<br />
<strong>Примечание</strong>  Сведения о зависимостях для локального Exchange см. в статье  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Предварительные условия для гибридного развертывания</span></a>.</td>
<td>Миграция с гибридным развертыванием</td>
<td><ul>
<li>Сообщения электронной почты</li>
<li>Правила для почтового ящика</li>
<li>Делегаты</li>
<li>контакты для почтового ящика; </li>
<li> Календарь </li>
<li> Задачи </li>
<li> Сообщения электронной почты с управляемыми правами </li>
<li> Зашифрованные сообщения электронной почты </li>
<li> Подписи </li>
<li> Личный архив, перенесенный с почтовым ящиком пользователя </li>
<li> Элементы с возможностью восстановления </li>
</ul></td>
<td><ul>
<li> Общедоступные папки </li>
<li> Электронные письма, превышающие предельный размер сообщения. </li>
<li> Архив ведения журнала или сторонние решения для архивации </li>
<li> Заблокированные или неактивные пользователи </li>
<li> Архивные данные из PST-файлов </li>
<li> Поврежденные элементы </li>
<li> Неактивные почтовые ящики </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Среда G Suite (только Gmail, Контакты и Календарь)</strong><br />
<br />
<strong>Примечание:</strong> Ваша среда G Suite должна соответствовать предварительным условиям, описанные в разделе <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Выполнение переноса данных G Suite</a>.</td>
<td>Прямая или поэтапная миграция</td>
<td><ul>
<li> Сообщения электронной почты </li>
<li> Контакты почтового ящика (переносятся не более трех адресов электронной почты для каждого контакта) </li>
<li> Календарь </li>
<li> Метки </li>
</ul></td>
<td><ul>
<li> Правила </li>
<li> Делегаты </li>
<li> Подписи </li>
<li> Задачи </li>
<li> Письма и вложения, превышающие предельный размер </li>
<li> Заблокированные или неактивные пользователи </li>
<li> Архивные данные из PST-файлов или стороннего архива (например, Google Сейфа) </li>
<li> Сообщения с управляемыми правами или зашифрованные сообщения </li>
<li> Поврежденные элементы </li>
<li> Google Hangouts** </li>
<li> Группы Google </li>
<li> Почтовые ящики ресурса </li>
<li> Неактивные почтовые ящики </li>
<li> Параметры отпусков и параметры автоматических ответов </li>
<li> Общие календари, облачные вложения, ссылки Google Hangout и цвета событий </li>
</ul>
Сохраненные сообщения Hangout** переносятся. </td>
</tr>
<tr class="odd">
<td><strong>Источник IMAP4 (например, Domino, GroupWise или Zimbra)</strong></td>
<td>Миграция с помощью собственных средств IMAP4</td>
<td><li>Сообщения электронной почты </li></td>
<td><ul>
<li> Правила </li>
<li> Делегаты </li>
<li> Списки рассылки </li>
<li> Внешние контакты </li>
<li> Пользователи с включенной поддержкой почты. </li>
<li> Заблокированные или неактивные пользователи </li>
<li> Контакты почтового ящика </li>
<li> Календарь </li>
<li> Подписи </li>
<li> Задачи </li>
<li> Сообщения электронной почты, превышающие предельный размер </li>
<li> Архивные данные </li>
<li> Зашифрованная электронная почта </li>
<li> Поврежденные элементы </li>
<li> Неактивные почтовые ящики </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Обязанности специалистов FastTrack

Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции. Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).

Наши специалисты FastTrack выполняют также следующие действия, относящиеся к переносу данных в Exchange:

  -  Предоставляют руководство по включению сосуществования маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.

## <a name="your-responsibilities"></a>Ваши обязанности

Вы выполняете стандартные действия в ходе проекта миграции. Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).

Вы также выполняете следующие действия, относящиеся к переносу данных в Exchange:

  - Выполнить подключение FastTrack для Exchange Online. При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия. Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).
  -  Устанавливаете клиентское программное обеспечение необходимого уровня согласно рекомендациям для Office 365. Дополнительные сведения см. в разделе [Современное рабочее место](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).
  -  Соответствие определенным требованиям при миграции из локальной среды Exchange. Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).
  -  Убедитесь, что в каждой исходной среде используется последний пакет обновления (SP) и накопительный (RU) пакет обновления (CU), если это применимо.
  -  Настройте и подтвердите сосуществование маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.
  -  Убедитесь, что размер исходного почтового ящика не превышает квоту конечного почтового ящика. В зависимости от исходной платформы может потребоваться ограничить объем исходных данных 85 процентами квоты конечного почтового ящика.
  -  При необходимости перенесите данные клиента. Помимо прочего эти данные включают локальные адресные книги, данные в локальных PST-файлах, правила Outlook и локальные параметры Outlook.
  -  Помогите вашим конечным пользователям в устранении проблем, связанных с переносом данных клиента.

## <a name="migration-to-sharepoint-online"></a>Миграция в SharePoint Online

После принятия вами решения об использовании FastTrack для переноса ваших файлов в SharePoint Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных. Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и SharePoint Online, а также использовать наши службы переноса данных для переноса ваших файлов. Создайте и запланируйте события переноса данных. Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии. После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в SharePoint Online.

## <a name="considerations"></a>Рекомендации

  - На все миграции распространяются квоты SharePoint Online. Дополнительные сведения см. в разделе [<span class="underline">Программные ограничения и пороговые значения SharePoint Online и OneDrive для бизнеса</span>](https://go.microsoft.com/fwlink/?LinkId=698855).
  - Рекомендуем ограничить объем всех перенесенных данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.

## <a name="source-environment-details"></a>Сведения об исходной среде

Наши службы переноса данных переносят данные из следующих исходных сред:

  - Файловые ресурсы (общие каталоги SMB на устройствах, поддерживающих SMB 2.0 и более поздних версий).
  - Одна среда G Suite (только Google Диск).
  - Box (Starter, Business, Enterprise).
  - Dropbox для Teams (стандартная и расширенная).

В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:

<table>
<thead>
<tr class="header">
<th><strong>Исходная среда</strong></th>
<th><strong>Тип миграции</strong></th>
<th><strong>Что переносится</strong></th>
 <th><strong>Что не переносится</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></td>
<td>Одно- или многоэтапная миграция</td>
<td><ul>
<li> Документы </li>
<li> Структура файлов и папок </li>
<li> Разрешения на доступ к папкам и файлам на уровне пользователя* </li>
<li> Разрешения на доступ к папкам и файлам на уровне группы* </li>
<li> Файлы размером до 15 ГБ </li>
<li> Базовые метаданные документов и папок
<ul>
<li> Дата создания </li>
<li> Дата изменения </li>
<li> Автор </li>
<li> Автор последнего изменения </li>
</ul></li>
</ul>
* Требуется настроить синхронизацию службы каталогов. Переносятся только разрешения NTFS, доступные в проводнике Windows. Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся. Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</td>
<td><ul>
<li> Журнал владения и предыдущие версии </li>
<li> Преобразование внедренных URL-адресов в содержимом </li>
<li> Предыдущие версии </li>
<li> Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый") </li>
<li> Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе </li>
<li> Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки) </li>
<li> Конфигурация аудита NTFS </li>
<li> Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI). </li>
<li> Поврежденные и недоступные документы </li>
<li> Скрытые общие папки </li>
<li> Общий доступ (например, разрешения, предоставленные на уровне общей папки) </li>
<li> Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Одна среда G Suite (только Google Диск)</strong></td>
<td>Одно- или многоэтапная миграция</td>
<td><ul>
<li> "Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office), в том числе файлы, превышающие 10 МБ </li>
<li> Структура файлов и папок </li>
<li> Разрешения на доступ к папкам на уровне пользователя </li>
<li> Разрешения на доступ к папкам на уровне группы </li>
<li> Файлы размером до 15 ГБ </li>
<li> Базовые метаданные документов и папок
<ul>
<li> Дата создания </li>
<li> Дата изменения </li>
<li> Автор </li>
<li> Автор последнего изменения </li>
</ul></li>
<li> Общие диски (папки и файлы) </li>
<li> Общее содержимое, принадлежащее переносимой учетной записи Google Drive </li>
</ul></td>
<td><ul>
<li> Журнал владения, предыдущие версии и комментарии </li>
<li> Описания файлов и папок, цвета папок </li>
<li> Разрешения на доступ к файлам на уровне пользователя </li>
<li> Разрешения на доступ к файлам на уровне группы </li>
<li> Расширенные метаданные </li>
<li> Атрибуты блокировки файлов </li>
<li> Преобразование внедренных URL-адресов в содержимом </li>
<li> Элементы, перемещенные в корзину </li>
<li> Поврежденные и недоступные документы </li>
<li> Заблокированные или неактивные пользователи </li>
<li> Google Фото, Google Формы, Google Карты и другие связанные приложения   </li>
<li> Google Рисунки </li>
<li> Общее содержимое, не хранящееся на серверах организации </li>
<li> Содержимое, не принадлежащее переносимой учетной записи Google Drive </li>
<li> Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями. Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных). </li>
<li> Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску. Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных). </li>
<li> Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Одно- или многоэтапная миграция</td>
<td><ul>
<li> Документы </li>
<li> Структура файлов и папок </li>
<li> Разрешения на доступ к папкам на уровне пользователя </li>
<li> Разрешения на доступ к папкам на уровне группы </li>
<li> Файлы размером до 15 ГБ </li>
<li> Базовые метаданные документов и папок
<ul>
<li> Дата создания </li>
<li> Дата изменения </li>
<li> Автор </li>
<li> Автор последнего изменения </li>
</ul></li>
<li> Общее содержимое, принадлежащее переносимой учетной записи Box </li>
</ul></td>
<td><ul>
<li> Журнал владения, предыдущие версии и комментарии </li>
<li> Описания файлов и папок </li>
<li> Разрешения на доступ к файлам на уровне пользователя </li>
<li> Разрешения на доступ к файлам на уровне группы </li>
<li> Дополнительные метаданные и теги Box </li>
<li> Атрибуты блокировки файлов </li>
<li> Преобразование внедренных URL-адресов в содержимом </li>
<li> Элементы, перемещенные в корзину </li>
<li> Поврежденные и недоступные документы </li>
<li> Заблокированные или неактивные пользователи </li>
<li> Приложения Box, закладки, избранное и рабочие процессы </li>
<li> Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box </li>
<li> Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями. Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных). </li>
<li> Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox для Teams (стандартная и расширенная)</strong></td>
<td>Одно- или многоэтапная миграция</td>
<td><ul>
<li> Документы </li>
<li> Структура файлов и папок </li>
<li> Разрешения на доступ к папкам на уровне пользователя </li>
<li> Разрешения на доступ к папкам на уровне группы </li>
<li> Файлы размером до 15 ГБ </li>
<li> Базовые метаданные документов и папок
<ul>
<li> Дата создания </li>
<li> Дата изменения </li>
<li> Автор </li>
<li> Автор последнего изменения </li>
</ul></li>
<li> Папки и содержимое для совместной работы </li>
<li> Общее содержимое, принадлежащее переносимой учетной записи Dropbox </li>
</ul></td>
<td><ul>
<li> Журнал владения, предыдущие версии и комментарии </li>
<li> Описания файлов и папок </li>
<li> Разрешения на доступ к файлам на уровне пользователя </li>
<li> Разрешения на доступ к файлам на уровне группы </li>
<li> Расширенные метаданные </li>
<li> Атрибуты блокировки файлов </li>
<li> Преобразование внедренных URL-адресов в содержимом </li>
<li> Элементы, перемещенные в корзину </li>
<li> Поврежденные и недоступные документы </li>
<li> Несмонтированные папки Dropbox </li>
<li> Удаленные или отключенные пользователи </li>
<li> Документы, демонстрации и пробелы Dropbox </li>
<li> Приложения и Избранное Dropbox (закрепленные файлы и звезды) </li>
<li> Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox </li>
<li> Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями. Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных) </li>
<li> Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Обязанности специалистов FastTrack

Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции. Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)

## <a name="your-responsibilities"></a>Ваши обязанности

Вы выполняете стандартные действия в ходе проекта миграции. Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)

Вы также выполняете следующие действия, относящиеся к переносу данных в SharePoint Online:

  - Настройте все сайты группы SharePoint для событий миграции.

## <a name="migration-to-onedrive-for-business"></a>Миграция в OneDrive для бизнеса

После принятия вами решения об использовании FastTrack для переноса ваших файлов в OneDrive для бизнеса, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных. Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и OneDrive для бизнеса, а также использовать наши службы переноса данных для переноса ваших файлов. Создайте и запланируйте события переноса данных. Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии. После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в OneDrive для бизнеса.

## <a name="considerations"></a>Рекомендации

  - На все миграции распространяются квоты OneDrive для бизнеса. Дополнительные сведения см. в разделе [<span class="underline">Программные ограничения и пороговые значения SharePoint Online и OneDrive для бизнеса</span>](https://go.microsoft.com/fwlink/?LinkId=698855).
  - Рекомендуем ограничить объем всех перенесенных вами данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.
  - FastTrack переносится только на активные диски OneDrive для бизнеса.

## <a name="source-environment-details"></a>Сведения об исходной среде

Наши службы переноса данных переносят данные из следующих исходных сред:

  - Файловые ресурсы (общие папки SMB на устройствах, поддерживающих SMB 2.0 и более поздней версии).
  - Одна среда G Suite (только Google Drive).
  - Box (Starter, Business, Enterprise).
  - Dropbox для Teams (стандартная и расширенная).

В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:

<table>
<thead>
<tr class="header">
 <th><strong>Исходная среда</strong></th>
 <th><strong>Тип миграции</strong></th>
 <th><strong>Что переносится</strong></th>
 <th><strong>Что не переносится</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></td>
<td>Одно- или многоэтапная миграция</td>
<td><ul>
<li> Документы </li>
<li> Структура файлов и папок </li>
<li> Разрешения на доступ к папкам и файлам на уровне пользователя* </li>
<li> Разрешения на доступ к папкам и файлам на уровне группы* </li>
<li> Файлы размером до 15 ГБ </li>
<li> Базовые метаданные документов и папок
<ul>
<li> Дата создания </li>
<li> Дата изменения </li>
<li> Автор </li>
<li> Автор последнего изменения </li>
</ul></li>
</ul>
<br>
* Требуется настроить синхронизацию службы каталогов. Переносятся только разрешения NTFS, доступные в проводнике Windows. Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся. Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB. </td>
<td><ul>
<li> Журнал владения и предыдущие версии </li>
<li> Преобразование внедренных URL-адресов в содержимом </li>
<li> Предыдущие версии </li>
<li> Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый") </li>
<li> Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе </li>
<li> Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки) </li>
<li> Конфигурация аудита NTFS </li>
<li> Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI). </li>
<li> Поврежденные и недоступные документы </li>
<li> Скрытые общие папки </li>
<li> Общий доступ (например, разрешения, предоставленные на уровне общей папки) </li>
<li> Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Одна среда G Suite (только Google Диск)</strong></td>
<td>Одно- или многоэтапная миграция</td>
<td><ul>
<li> "Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office, в том числе файлы, превышающие 10 МБ) </li>
<li> Структура файлов и папок </li>
<li> Разрешения на доступ к папкам на уровне пользователя </li>
<li> Разрешения на доступ к папкам на уровне группы </li>
<li> Файлы размером до 15 ГБ </li>
<li> Базовые метаданные документов и папок
<ul>
<li> Дата создания </li>
<li> Дата изменения </li>
<li> Автор </li>
<li> Автор последнего изменения </li>
</ul></li>
<li> Общие диски (папки и файлы) </li>
<li> Общее содержимое, принадлежащее переносимой учетной записи Google Drive </li>
</ul></td>
<td><ul>
<li> Журнал владения, предыдущие версии и комментарии </li>
<li> Описания файлов и папок, цвета папок </li>
<li> Разрешения на доступ к файлам на уровне пользователя </li>
<li> Разрешения на доступ к файлам на уровне группы </li>
<li> Расширенные метаданные </li>
<li> Атрибуты блокировки файлов </li>
<li> Преобразование внедренных URL-адресов в содержимом </li>
<li> Элементы, перемещенные в корзину </li>
<li> Поврежденные и недоступные документы </li>
<li> Заблокированные или неактивные пользователи </li>
<li> Google Фото, Google Формы, Google Карты и другие связанные приложения   </li>
<li> Google Рисунки </li>
<li> Общее содержимое, не хранящееся на серверах организации </li>
<li> Содержимое, не принадлежащее переносимой учетной записи Google Drive </li>
<li> Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями. Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных). </li>
<li> Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску. Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных). </li>
<li> Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Одно- или многоэтапная миграция</td>
<td><ul>
<li> Документы </li>
<li> Структура файлов и папок </li>
<li> Разрешения на доступ к папкам на уровне пользователя </li>
<li> Разрешения на доступ к папкам на уровне группы </li>
<li> Файлы размером до 15 ГБ </li>
<li> Базовые метаданные документов и папок
<ul>
<li> Дата создания </li>
<li> Дата изменения </li>
<li> Автор </li>
<li> Автор последнего изменения </li>
</ul></li>
<li> Общее содержимое, принадлежащее переносимой учетной записи Box </li>
</ul></td>
<td><ul>
<li> Журнал владения, предыдущие версии и комментарии </li>
<li> Описания файлов и папок </li>
<li> Разрешения на доступ к файлам на уровне пользователя </li>
<li> Разрешения на доступ к файлам на уровне группы </li>
<li> Дополнительные метаданные и теги Box </li>
<li> Атрибуты блокировки файлов </li>
<li> Преобразование внедренных URL-адресов в содержимом </li>
<li> Элементы, перемещенные в корзину </li>
<li> Поврежденные и недоступные документы </li>
<li> Заблокированные или неактивные пользователи </li>
<li> Приложения Box, закладки, избранное и рабочие процессы </li>
<li> Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box </li>
<li> Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями. Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных). </li>
<li> Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox для Teams (стандартная и расширенная)</strong></td>
<td>Одно- или многоэтапная миграция</td>
<td><ul>
<li> Документы </li>
<li> Структура файлов и папок </li>
<li> Разрешения на доступ к папкам на уровне пользователя </li>
<li> Разрешения на доступ к папкам на уровне группы </li>
<li> Файлы размером до 15 ГБ </li>
<li> Базовые метаданные документов и папок
<ul>
<li> Дата создания </li>
<li> Дата изменения </li>
<li> Автор </li>
<li> Автор последнего изменения </li>
</ul></li>
<li> Папки и содержимое для совместной работы </li>
<li> Общее содержимое, принадлежащее переносимой учетной записи Dropbox </li>
</ul></td>
<td><ul>
<li> Журнал владения, предыдущие версии и комментарии </li>
<li> Описания файлов и папок </li>
<li> Разрешения на доступ к файлам на уровне пользователя </li>
<li> Разрешения на доступ к файлам на уровне группы </li>
<li> Расширенные метаданные </li>
<li> Атрибуты блокировки файлов </li>
<li> Преобразование внедренных URL-адресов в содержимом </li>
<li> Элементы, перемещенные в корзину </li>
<li> Поврежденные и недоступные документы </li>
<li> Несмонтированные папки Dropbox </li>
<li> Удаленные или отключенные пользователи </li>
<li> Документы, демонстрации и пробелы Dropbox </li>
<li> Приложения и Избранное Dropbox (закрепленные файлы и звезды) </li>
<li> Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox </li>
<li> Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями. Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных). </li>
<li> Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Обязанности специалистов FastTrack

Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции. Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).

## <a name="your-responsibilities"></a>Ваши обязанности

Вы выполняете стандартные действия в ходе проекта миграции. Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).

Вы также выполняете следующие действия, относящиеся к переносу данных в OneDrive для бизнеса:

  - Настройте все сайты OneDrive для бизнеса для событий миграции.