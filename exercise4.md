# Чек-лист

## Тест-кейс №1 — Прохождения авторизации.
standard_user 
** `Результат: пройден.`

locked_out_user 
** `Результат: провален. Неожиданное поведение приложения: Пользователь неможет авторизоваться, его логин заблокирован. Дальнейшее тестирование этого пользователя невозможно.`

problem_user 
** `Результат: пройден. Неожиданное поведение приложения: Каталог товаров отображается не корректно.`

performance_glitch_user
** `Результат: пройден. Неожиданное поведение приложения: Есть задержка открытия страниц на сайте у этого логина. `
___
## Тест-кейс №2. Добавление товара в корзину на странице ___Products___.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: пройден. Неожиданное поведение приложения: добавляет не все товары в корзину. Не у всех товаров кнопка "Add to cart" меняется на "Remove" `

performance_glitch_user
** `Результат: пройден.`
___

## Тест-кейс №3 — Удаление товара из корзины на странице ___Products___.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: провален. Неожиданное поведение приложения: товар не удален из корзины, у рисунка корзины, в правом верхнем углу, не исчезает число, и не уменьшается количество. Кнопка "Remove" не меняется на "Add to cart."`

performance_glitch_user
** `Результат: пройден.`
___

## Тест-кейс №4 — Переход в корзину.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: пройден. Неожиданное поведение приложения: когда рядом со значком корзины есть цифра 1 или больше одного, а на странице каталога кнопок "Remove" меньше, чем число указанное возле значка корзина, после нажатия на значек корзина сайт "падает", экран становится белым.`

performance_glitch_user
** `Результат: пройден.`
___

## Тест-кейс №5 — Оформление заказа.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: провален. Неожиданное поведение приложения: на странице ___Checkout: Your Information___ поле ввода Last Name не дает ввести данные. Нажать на кнопку "Continue" не возможно.высвечивается ошибка "Error: Last Name is required". Дальнейшие шаги оформления заказа не возможны.`

performance_glitch_user
** `Результат: пройден.`
___

## Тест-кейс №6 — Сортировка товара в алфавитном порядке.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: провален. Неожиданное поведение приложения: сортировка товаров на странице не в алфавитном порядке не возможна. Кнопки Name (Z to A), Price (low to high), Price (high to low) не возможно активировать.`

performance_glitch_user
** `Результат: пройден. Неожиданное поведение приложения: после нажатия кнопки Name (Z to A), Price (low to high), Price (high to low) идет задержка обновления.`
___

## Тест-кейс 7 — Сортировка товара в обратном алфавитном порядке.
standard_user
** `Результат: пройден.`

problem_user 
** `Результат: провален. Неожиданное поведение приложения: сортировка товаров на странице в алфавитном порядке не возможна. Кнопка Name (Z to A) не возможно активировать.`

performance_glitch_user
** `Результат: пройден. Неожиданное поведение приложения: после нажатия кнопку Name (Z to A) идет задержка обновления.`

___

## Тест-кейс №8 — Сортировка товара от наименьшей стоимости к наибольшей.
standard_user
** `Результат: пройден.`

problem_user 
** `Результат: провален. Неожиданное поведение приложения: сортировка товаров на странице от наименьшей стоимости к наибольшей не возможна. Кнопка Price (low to high) не возможно активировать.`

performance_glitch_user
** `Результат: пройден. Неожиданное поведение приложения: после нажатия кнопку Price (low to high) идет задержка обновления.`
___

## Тест-кейс №9 — Сортировка товара от наибольшей цены к наименьшей.
standard_user
** `Результат: пройден.`

problem_user 
** `Результат: провален. Неожиданное поведение приложения: сортировка товаров на странице наибольшей цены к наименьшей не возможна. Кнопка Price (high to low) не возможно активировать.`

performance_glitch_user
** `Результат: пройден. Неожиданное поведение приложения: после нажатия кнопку Price (high to low) идет задержка обновления.`
___

## Тест-кейс №10 — Удаление товара из корзины на странице ___Your Cart___.
standard_user 
** `Результат: пройден. `

problem_user 
** `Результат: пройден.`

performance_glitch_user
** `Результат: пройден.`
___

## Тест-кейс №11 — Открытие карточки товара через изображение на странице ___Products___ .
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: провален. Неожиданное поведение приложения: не все карточки товаров открываются корректно. Карточка с товаром "Sauce Labs Fleece Jacket" выдает ошибку "ITEM NOT FOUND". При открытии карточки "Sauce Labs Backpack" открывается карточка "Sauce Labs Fleece Jacket". При открытии карточки "Sauce Labs Bike Light" открывается карточка с товаром "Sauce Labs Bolt T-Shirt". при открытии карточки "Sauce Labs Bolt T-Shirt" открывается "Sauce Labs Onesie". При открытии карточки "Sauce Labs Onesie" открывается карточка "Test.allTheThings() T-Shirt (Red)". При открытии карточки "Test.allTheThings() T-Shirt (Red)" открывается "Sauce Labs Backpack". При открытии карточек изменяется фото товара отличное от фото в каталоге.`

performance_glitch_user
** `Результат: пройден.`
___
## Тест-кейс №12 — Закрытие карточки товара.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: пройден.`

performance_glitch_user
** `Результат: пройден. Неожиданное поведение приложения: после нажатия кнопки "Back to products" идет задержка закрытия страницы.`
___

## Тест-кейс №13 — Открытие карточки товара по гипертексту на странице ___Products___.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: провален. Неожиданное поведение приложения: не все карточки товаров открываются корректно. Карточка с товаром "Sauce Labs Fleece Jacket" выдает ошибку "ITEM NOT FOUND". При открытии карточки "Sauce Labs Backpack" открывается карточка "Sauce Labs Fleece Jacket". При открытии карточки "Sauce Labs Bike Light" открывается карточка с товаром "Sauce Labs Bolt T-Shirt". при открытии карточки "Sauce Labs Bolt T-Shirt" открывается "Sauce Labs Onesie". При открытии карточки "Sauce Labs Onesie" открывается карточка "Test.allTheThings() T-Shirt (Red)". При открытии карточки "Test.allTheThings() T-Shirt (Red)" открывается "Sauce Labs Backpack". При открытии карточек изменяется фото товара отличное от фото в каталоге.`

performance_glitch_user
** `Результат: пройден.`
___

## Тест-кейс №14 — Добавление товара в корзину в карточке товара.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: провален. Неожиданное поведение приложения: в карточке "Sauce Labs Fleece Jacket" кнопка "Add to cart" после нажатия, не добавялет товар в корзину. У значка корзины не появилось число 1 и не увеличилось число на 1. Кнопка "Add to cart" не изменилась на "Remove". В карточке "Sauce Labs Bolt T-Shirt" кнопка "Add to cart" после нажатия, не добавялет товар в корзину. У значка корзины не появилось число 1 и не увеличилось число на 1. Кнопка "Add to cart" не изменилась на "Remove". в карточке "Test.allTheThings() T-Shirt (Red)" кнопка "Add to cart" после нажатия, не добавялет товар в корзину. У значка корзины не появилось число 1 и не увеличилось число на 1. Кнопка "Add to cart" не изменилась на "Remove".`

performance_glitch_user
** `Результат: пройден.`
___

## Тест-кейс №15 — Удаление товара из корзины в карточке товара.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: провален. В карточке "Sauce Labs Fleece Jacket" предусловие не выполнено, товар не в корзине. У значка корзины не уменьшилось число на 1 и не удалилось. Кнопка "Remove" отсутствует. В карточке "Sauce Labs Bolt T-Shirt" предусловие не выполнено, товар не в корзине. У значка корзины не уменьшилось число на 1 и не удалилось. Кнопка "Remove" отсутствует. В карточке "Sauce Labs Onesie" после нажатия на кнопку "Remove" товар из корзины не удалился. У значка корзины не уменьшилось число на 1 и не удалилось. Кнопка "Remove" не изменилась на кнопку "Add to cart". В карточке "Test.allTheThings() T-Shirt (Red)" предусловие не выполнено, товар не в корзине. У значка корзины не уменьшилось число на 1 и не удалилось. Кнопка "Remove" отсутствует. В карточке "Sauce Labs Backpack" после нажатия на кнопку "Remove" товар из корзины не удалился. У значка корзины не уменьшилось число на 1 и не удалилось. Кнопка "Remove" не изменилась на кнопку "Add to cart".`

performance_glitch_user
** `Результат: пройден. `

___

## Тест-кейс №16 — Отмена заказа на странице ___Your Cart___.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: пройден.`

performance_glitch_user
** `Результат: пройден. Неожиданное поведение приложения: после нажатия кнопки "Continue Shopping" идет задержка открытия страницы ___Products___.`
___

## Тест-кейс №17 — Отмена заказа на странице ___Checkout: Your Information___.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: пройден.`

performance_glitch_user
** `Результат: пройден.`
___

## Тест-кейс №18 — Отмена заказа на странице ___Checkout: Overview___.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: провален. Не выполнено предусловие: "пользователь на странице ___Checkout: Overview___", т.к. на этапе ввода данных ячейка "Last Name" не активна.   `

performance_glitch_user
** `Результат: пройден. Неожиданное поведение приложения: после нажатия кнопки "Continue Shopping" идет задержка открытия страницы ___Products___.`

___

## Тест-кейс №19 — Открытие карточки товара по гипертексту на странице ___Your Cart___.

standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: пройден. `

performance_glitch_user
** `Результат: пройден.`
___

## Тест-кейс №20 — Открытие бокового меню окна.

standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: пройден. `

performance_glitch_user
** `Результат: пройден.`
___

## Тест-кейс №21 — Открытие каталога товаров через боковое меню окна.

standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: пройден. `

performance_glitch_user
** `Результат: пройден. Неожиданное поведение приложения: после нажатия кнопки "All Items" идет задержка открытия страницы ___Products___. `
___

## Тест-кейс №22 — Открытие сайта разработчика через боковое меню окна.

standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: провален. Неожиданное поведение приложения: после нажатия ссылки "About" страница переходит на сайт https://saucelabs.com/error/404 и вывовид ошибку 404.`

performance_glitch_user
** `Результат: пройден. `
___

## Тест-кейс №23 — Выход из профиля через боковое меню окна.

standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: пройден. `

performance_glitch_user
** `Результат: пройден.`
___

## Тест-кейс №24 — Сброс состояния приложения
standard_user 
** `Результат: пройден. Неожиданное поведение приложения: кнопки у товаров остаются с названием "Remove". Если пользователь находится на старнце ___Your Cart___, товар остается в списке. Если пользователь находится на странице ___Checkout: Overview___ товар остается в списке. `

problem_user 
** `Результат: пройден. Неожиданное поведение приложения: кнопки у товаров остаются с названием "Remove". Если пользователь находится на старнце ___Your Cart___, товар остается в списке. Если пользователь находится на странице ___Checkout: Overview___ товар остается в списке.`

performance_glitch_user
** `Результат: пройден.  Неожиданное поведение приложения: кнопки у товаров остаются с названием "Remove". Если пользователь находится на старнце ___Your Cart___, товар остается в списке. Если пользователь находится на странице ___Checkout: Overview___ товар остается в списке.`
___

## Тест-кейс №25 — Закрытие бокового меню окна.
standard_user 
** `Результат: пройден. `

problem_user 
** `Результат: пройден. `

performance_glitch_user
** `Результат: пройден.`
___

## Тест-кейс №26 — Открытие ссылки "Twitter" из подвала сайта.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: пройден. `

performance_glitch_user
** `Результат: пройден. `
___

## Тест-кейс №27 — Открытие ссылки "Facebook" из подвала сайта.
standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: пройден. `

performance_glitch_user
** `Результат: пройден. `
___

## Тест-кейс №28 — Открытие ссылки "Linkedin" из подвала сайта.

standard_user 
** `Результат: пройден.`

problem_user 
** `Результат: пройден. `

performance_glitch_user
** `Результат: пройден. `
___