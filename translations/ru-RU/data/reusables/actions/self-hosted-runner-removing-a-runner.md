---
ms.openlocfilehash: 0d73e17e61dc0848a42a18a7e1811b43e541b6a4
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/05/2022
ms.locfileid: "147061301"
---
1. В разделе "Средства выполнения" найдите нужное средство выполнения. Если ваше средство выполнения находится в группе, щелкните {% octicon "chevron-down" aria-label="The downwards chevron" %}, чтобы развернуть список.
1. Рядом со средством выполнения, которое вы хотите удалить, щелкните {% octicon "kebab-horizontal" aria-label="The horizontal kebab icon" %}, а затем **Удалить**.

    ![Параметр удаления локального средства выполнения](/assets/images/help/settings/actions-runner-remove.png)
1. Вы увидите инструкции по удалению локального средства выполнения. Выполните одно из следующих действий, чтобы удалить средство выполнения в зависимости от того, есть ли к нему доступ:

    * **Если у вас есть доступ к компьютеру средства выполнения:** следуйте инструкциям на экране для операционной системы этого компьютера, чтобы выполнить команду удаления. Инструкции включают необходимый URL-адрес и автоматически создаваемый маркер с ограниченным временем действия.

        Команда удаления выполняет следующие задачи:

        * Удаляет средство выполнения из {% data variables.product.product_name %}.
        * Удаляет все файлы конфигурации локального приложения средства выполнения на компьютере.
        * Удаляет все настроенные службы, если они не выполняются в интерактивном режиме.

    * **Если у вас нет доступа к компьютеру:** щелкните **Принудительно удалить это средство выполнения**, чтобы {% data variables.product.product_name %} принудительно удалил средство выполнения.