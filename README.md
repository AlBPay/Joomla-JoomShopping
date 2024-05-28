Данный модуль интеграции разработан для CMS Joomla и компонента JoomShopping. 
Перед установкой модуля у Вас должны быть установлены следующие версии CMS Joomla и компонента JoomShopping:
1) Joomla 2.5.x + JoomShopping 3.x.x
2) Joomla 3.x.x + JoomShopping 4.x.x


Перед установкой модуля оплаты необходимо зарегистрироваться на сайте Alliance bank (http://example.com , раздел "Подключиться").

#Установка
-------------
1. Зайдите в административную панель Вашего сайта (http://your.site/administator) .

2. Перейдите в меню "Компоненты" -> "JoomShopping" -> "Установка и обновление".

3. В разделе "Загрузить файл пакета" нажмите кнопку "Выберите файл", выберите архив с модулем оплаты Alliance bank (fondy_payment.zip) и нажмите кнопку "Загрузить".

4. Затем перейдите в меню "Компоненты" -> "JoomShopping" -> "Опции" -> "Способ оплаты", нажмите на "Alliance bank" и на открывшейся странице настроек модуля перейдите на вкладку "Конфигурация". В данной вкладке необходимо заполнить следующие поля:
	- "Merchant ID", "Секретный ключ"
	- "Статус заказа для успешных транзакций": рекомендуется установить статус "Paid" (заказ оплачен)
	- "Статус заказа для неуспешных транзакций": если при отказе покупателем от оплаты нужно отменять заказ, то выберите статус "Canceled"; если хотите дать возможность после отказа повторно переходить к оплате, выберите статус "Pending"
	
5. После ввода необходимых настроек модуля на вкладке "Конфигурация", перейдите на вкладку "Главный" и отметьте галочкой пункт меню "Публикация" для того, чтобы данный способ оплаты стал доступен для выбора при оформлении заказа.

6. Сохраните изменения, нажав на кнопку "Сохранить".

7. Enable no redirect mode: "Да" для выбора без перенаправления и "Нет" для выбора режима с перенаправлением на сайт оплаты.

------------
![Скриншот][1]
----

[1]: https://raw.githubusercontent.com/cloudipsp/joomshopping/master/jomjom.PNG