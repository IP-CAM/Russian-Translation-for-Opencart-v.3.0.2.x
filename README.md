## Русский язык для OpenCart 3.0.2.0
`<OpenCart>` : <https://www.opencart.com/>

**Установка**

- Скопировать папки **Admin, Catalog, Install** в папку upload Вашего OpenCart.
> Если OpenCart был установлен ранее, папку Install можно не копировать.
- Перейти **System -> Localization -> Languages**. Нажать на кнопку *'Add New'*. Заполнить:
  * **Language Name:** Русский
  * **Code:** ru-ru
  * **Locale:** ru,ru_RU, ru_RU.UTF-8, ru-ru, ru_ru, russian
  * **Status:** Enabled
  * Нажать кнопку *'Save'*
- Перейти **System -> Settings -> Your Store -> Local**. Переключить **Language** и **Administration Language** на *Русский* и сохранить.
- Можно использовать oc3_order_status.sql для локализации статусов заказов.

