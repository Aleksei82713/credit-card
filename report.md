# Отчёт о тестировании <Credit Card Number Validator>

13.08.2021 - 13.08.2021 было проведено функциональное тестирование валидаций банковских карт.

На тестирование затрачено: 1 час

## В результате тестирования выявлены следующие дефекты:

* [Ошибка при тестировании номеров банковских карт  Visa](https://github.com/Aleksei82713/credit-card/issues/1#issue-970948916)

* [Ошибка при тестировании номеров банковских карт Discover](https://github.com/Aleksei82713/credit-card/issues/2#issue-970949140)

* [Ошибка при тестировании номеров банковских карт JCB](https://github.com/Aleksei82713/credit-card/issues/3#issue-970949282)

* [Ошибка при тестировании банковских карт Diners Club - International](https://github.com/Aleksei82713/credit-card/issues/4#issue-970949386)
## В качестве тестовых данных использовались данные:
<https://www.freeformatter.com/credit-card-number-generator-validator.html>

* Visa:

4539896184532193 - OK

4485116637091364 - OK

4539515216422382039 - FAIL

* Discover:

6011128790556628 - OK

6011807956807012 - OK

6011299455801432987 - FAIL

* JCB:

3544263214273501 - OK

3529841328481836 - OK

3529845497711144883 - FAIL

* Visa Electron:

4844263183082680 - OK

4844304944588886 - OK

4917477705545584 - OK

* Diners Club - International:

36793371651876 - FAIL

36586213591759 - FAIL

36499229268497 - FAIL


## Тестирование производилось в следующем окружении:

* Windows 10, 64-разрядная операционная система, процессор x64

* openjdk version "11.0.11" 2021-04-20. OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9).OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)

* IntelliJ IDEA 2020.1
