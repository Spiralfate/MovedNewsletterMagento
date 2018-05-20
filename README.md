# MovedNewsletterMagento

Модуль для Magento 2, меняющий расположение блока подписки с "футера" на "хедер".



Установка:

1. Скопировать каталог Vendor в директорию <Директория Magento 2>/app/code/
2.1 Убедиться в правильности роутов, введя команду 

      php bin/magento module:status
      
   увидя среди модулей добавленный модуль Vendor_MovedNewsletter.
2.2 Затем, если модуль не числится среди подключенных, подключить его командой
   
      php bin/magento module:enable Vendor_MovedNewsletter
      
3. При необходимости, очистить кэш командой

      php bin/magento cache:clean
