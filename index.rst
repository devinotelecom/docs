Документация по API
===================

В данном разделе представлена документация по различными протоколам для взаимодействия с платформой Devino Telecom.
Документация содержит описание API cервисов для отправки и приема SMS-сообщений, отправки Email и выполнения запросов IMSI
Каждое руководство включает в себя описание схемы работы с API, краткий обзор всех параметров, а также подробные описания по каждому из параметров, снабженные реальными примерами. 

Документация предназначена для разработчиков, которые хотят добавить возможность взаимодействия с сервисом отправки SMS и Email сообщений на страницы своих сайтов или в свои приложения.

Для начала использования API: 

1. Зарегистрируйтесь в Личном кабинете; 
2. Заключите договор; 
3. Ознакомьтесь с интересующей документацией. 


.. _sms-docs::

.. toctree::
   :maxdepth: 2
   :caption: SMS Рассылки

   httpapi
   httpapiv2
   smpp
   smtp
   modyl1c
   xml
   soap
   soapv2
   ftps
   1cbitrix
   
.. _incoming-docs:

.. toctree::
   :maxdepth: 2
   :caption: Входящие сообщения
   
   httppriem
   
   
.. _viber-docs:
.. toctree::
   :maxdepth: 2
   :caption: Viber
   
   viber-resender


.. _email-docs:   
.. toctree::
   :maxdepth: 2
   :caption: E-Mail Рассылки
   
   emailsmtp
   emailhttp

.. _vk-docs:
.. toctree::
   :maxdepth: 2
   :caption: VK API

   VKAPI

.. _hlr-docs:

.. toctree::
   :maxdepth: 2
   :caption: HLR HTTP API
   
   httpapihlr   

.. _addressbookapi-docs:
.. toctree::
   :maxdepth: 2
   :caption: Адресная книга
   
   addressbookapi
   

.. _phoneverification-docs:
.. toctree::
   :maxdepth: 2
   :caption: Сервис двухфакторной аутентификации
   
   phoneverification

  
.. _imsi-docs:

.. toctree::
   :maxdepth: 2
   :caption: IMSI
   
   imsi
   
   
Документация по DEVINO Online 
=============================

Документация содержит описание API cервисов для отправки SMS-сообщений, отправки Email и HLR.
Каждое руководство включает в себя описание схемы работы с API, краткий обзор всех параметров, а также подробные описания по каждому из параметров. 

Документация предназначена для разработчиков, которые хотят добавить возможность взаимодействия с сервисом отправки SMS и Email сообщений на страницы своих сайтов или в свои приложения.

Для начала использования API: 

1. Зарегистрируйтесь в Личном кабинете https://devino.online; 
2. Заключите договор; 
3. Ознакомьтесь с интересующей документацией. 

При работе с API в заголовках необходимо передавать параметры Content-Type : application/x-www-form-urlencoded. 
Для авторизации используется ApiKey полученный в личном кабинете для соответствующей компании. 
Пример заголовка:

.. code-block:: json

   Authorization : Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJjYW1wYWlnbiI6eyJpZCI6MzI3LCJ0eXBlIjoiQXBpQ2FtcGFpZ2
   
Формат запроса к API:
   
.. code-block:: json

   https://devino.online/api/v1/



.. _hlronline-docs:

.. toctree::
   :maxdepth: 2
   :caption: DEVINO Online
   
   HLROnline
   
.. _emailonline-docs:
.. toctree::
   :maxdepth: 2
   
   EmailOnline
