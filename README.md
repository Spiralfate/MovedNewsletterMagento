# MovedNewsletterMagento

Модуль для Magento 2, меняющий расположение блока подписки с "футера" на "хедер".



Установка вручную без композера:

1. Скопировать каталог Vendor в директорию 

      <Директория Magento 2>/app/code/Vendor/MovedNewsletter   

2.1 Проверить правильность роутов и регистрации модуля, введя команду 

      php bin/magento module:status
      
   убедиться, что среди модулей есть добавленный модуль Vendor_MovedNewsletter.
   
2.2 Затем, если модуль не числится среди подключенных, подключить его командой
   
      php bin/magento module:enable Vendor_MovedNewsletter
      
3. Обновить конфигурацию командой
      
      php bin/magento setup:upgrade
      
4. При необходимости, очистить кэш командой      

      php bin/magento cache:clean
