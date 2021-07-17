# Отчёт о тестировании Credit Card Number Validator

## Проверяем функциональность валидации номера банковской карты

17.07.21 - 17.07.21  было проведено функциональное тестирование программы Credit Card Number Validator

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* https://github.com/tazhieva2222/dzjava/issues/1#issue-946570315 
* https://github.com/tazhieva2222/dzjava/issues/2#issue-946792185 
* https://github.com/tazhieva2222/dzjava/issues/3#issue-946801107

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
*  Баг репорт





В качестве тестовых данных использовались данные :
* 5351719427810741 OK, номер карты из кода предыдущего программиста
* 4485586986059156 OK, VISA из сайта freeformatter.com
* 5208977874045790 OK, MASTERCARD из сайта freeformatter.com
* 6011259143521017 OK, Discover из сайта freeformatter.com
* 3538473824800373 OK, JCB из сайта freeformatter.com
* 3531372322331735158 FALSE, JCB из сайта freeformatter.com
* 6396852466920546 OK, InstaPayment из сайта freeformatter.com
* 5893398371188092 OK, Maestro из сайта freeformatter.com
* 5415971383628369 OK, Diners Club - North America из сайта freeformatter.com
* 36615040997747 FALSE, Diners Club - International из сайта freeformatter.com
* 36189084720019 FALSE, Diners Club - International из сайта freeformatter.com
* 36329552820731 FALSE, Diners Club - International из сайта freeformatter.com
* 376145927271477 FALSE, American Express (AMEX) из сайта freeformatter.com
* 341711497505057 FALSE, American Express (AMEX) из сайта freeformatter.com
* 343249966622051 FALSE, American Express (AMEX) из сайта freeformatter.com


Тестирование производилось в следующем окружении:
* Устройство: Windows 10   x 64
* Версия Java  "11.0.11" 
* IntelliJ IDEA
