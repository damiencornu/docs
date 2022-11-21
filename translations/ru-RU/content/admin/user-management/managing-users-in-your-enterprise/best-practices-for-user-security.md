---
title: Рекомендации по безопасности пользователей
intro: '{% ifversion ghes %}Помимо мер безопасности на уровне экземпляра (SSL, изоляция поддомена, настройка брандмауэра), которые может реализовать администратор сайта, имеются {% else %}Имеются {% endif %} действия, которые пользователи могут сами предпринять для защиты вашего предприятия.'
redirect_from:
  - /enterprise/admin/user-management/best-practices-for-user-security
  - /admin/user-management/best-practices-for-user-security
versions:
  ghes: '*'
  ghae: '*'
type: reference
topics:
  - Enterprise
  - Security
  - User account
shortTitle: User security best practices
ms.openlocfilehash: 57d19d97a8944ac20d6b90794bcf0cda63fc5bd0
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/05/2022
ms.locfileid: '146331659'
---
{% ifversion ghes %}
## Включение двухфакторной проверки подлинности

Двухфакторная проверка подлинности (2FA) — это способ входа на веб-сайты и в службы, для проверки подлинности которым помимо пароля требуется второй фактор. В случае {% data variables.product.prodname_ghe_server %} второй фактор является одноразовым кодом проверки подлинности, созданным приложением на смартфоне пользователя. Настоятельно рекомендуем пользователям в учетных записях включить двухфакторную проверку подлинности. Чтобы получить несанкционированный доступ к учетной записи, при двухфакторной проверке подлинности необходимо скомпрометировать пароль пользователя и его смартфон.

Дополнительные сведения о настройке двухфакторной проверки подлинности см. в разделе "[О двухфакторной проверке подлинности](/enterprise/user/articles/about-two-factor-authentication)".
{% endif %}

## Требование диспетчера паролей

Настоятельно рекомендуем пользователям устанавливать и использовать диспетчер паролей, например [LastPass](https://lastpass.com/) или [1Password](https://1password.com/), на любом компьютере, который используется для подключения к вашей организации. Это улучшает защиту паролей, что затрудняет их подбор или кражу.

## Ограничение доступа к командам и репозиториям

Чтобы ограничить потенциальную поверхность атаки в случае нарушения безопасности, настоятельно рекомендуется предоставлять пользователям доступ только к командам и необходимым для работы репозиториям. Так как участники с ролью владельца могут получить в организации доступ ко всем командам и репозиториям, настоятельно рекомендуется как можно реже использовать эту команду.

Дополнительные сведения о настройке команд и разрешений команды см. в разделе "[Роли в организации](/organizations/managing-peoples-access-to-your-organization-with-roles/roles-in-an-organization)".