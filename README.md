Модуль Oschadpay для ModX revo minishop2.
=====
-----

##### Инструкция по установке модуля оплаты Oschadpay

1. Скопируйте каталог assets и core в корень системы modx.

2. В админ.панели Modx зайдите: Приложения -> Minishop2 -> Настройки -> Способы оплаты -> Создать 

3. Заполните все поля, в поле Класс-обработчик указать oschadpay.

4. Открыть файл для редактирования core/components/minishop2/custom/payment/oschadpay.class.php

#### Заполнить поля:
```
MERCHANT_ID - можно узнать в личном кабинете Oschadpay
SECRET_KEY - можно узнать в личном кабинете Oschadpay
SUCCESS_URL - ссылка для перехода на страницу после успешного платежа
```