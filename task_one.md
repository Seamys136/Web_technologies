###Знакомство с веб-технологиями (семинары)

**Задача:** на основе сайта https://pet7.ru/
**1.** Определите, на каком протоколе работает сайт.
**2.** Проанализируйте структуру страницы сайта. Покажите в коде где хедер, футер и контент.
**3.** Внесите не менее 3 изменений на страницу с помощью инструмента разработчика и представьте скриншоты было/стало.
**4.** Создайте прототип низкой детализации.

**Пункт 1:**

Сайт https://pet7.ru/ работает на проколое **HTTPS**.
_**Как это можно увидеть?**_

Чтобы злоумышленники не перехватили конфиденциальную информацию, сайты используют протокол **HTTPS**, который шифрует данные.
Сайт, работающий на протоколе **HTTPS**, содержит сертификат **SSL**.

**SSL-сертификаты** сайтов требуются для обеспечения безопасности данных пользователей, подтверждения прав собственности на сайт, предотвращения создание поддельной версии сайта злоумышленниками и обеспечения доверия со стороны пользователей. 

Перейдя в инструменте разработчика (**Chrome DevTools**) на вкладку **Security**, можно увидеть такой сертификат, также увидеть и протокол:

![protocol.PNG](protocol.PNG)

Также информация о протоколе становится видна, если дважды кликнуть в строке браузера:

![protocol_1.PNG](protocol_1.PNG)

**Пункт 2:**

**Header:**
HTML-элемент **header** представляет собой вводный контент, обычно группу вводных или навигационных средств.
**Примечание:**
Содержит вложенный **nav**.
**Nav** - это семантический html5-элемент, который был введен, чтобы указать, что этот код является навигацией вашей страницы.

![header.PNG](header.PNG)

**Content:**

Основное содержимое старницы (до **footer**):
![content.PNG](content.PNG)

**Footer:**

**Footer, или подвал сайта (англ. footer)** — это раздел, который размещается внизу каждой страницы сайта. Обычно в нём можно найти ссылки на основные разделы, информацию о доставке, контакты компании, пользовательские соглашения, политику конфиденциальности, форму обратной связи, ссылки на соцсети и другое.
На данном сайте он тут:
![footer.PNG](footer.PNG)

**Пункт 3:**

Изменен цвет навигационной панели:
![background-color.PNG](background-color.PNG)

Удалены значки социальных сетей:
![delete.PNG](delete.PNG)

Изменена картинка в шапке сайта (получился заботливый **Google😺😍😜**):

![header-google.png](header-google.png)

Размножен  элемент:

![search.png](search.png) 

Изменен слоган:

![slogan.png](slogan.png) 

**Пункт 4:**
![prototype.PNG](prototype.PNG) 
