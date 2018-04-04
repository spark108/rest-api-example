Пример REST приложения

### rest.local

![Example REST](https://github.com/vovancho/rest-api-example/blob/master/project/view.jpg)

### api.rest.local

Запрос | Параметры | Описание
--- | --- | ---
`GET http://api.rest.local/products` | | Вывести список продуктов
`POST http://api.rest.local/products` | `name` - Наименование продукта <BR> `price` - Стоимость продукта | Добавить новый продукт
`PUT http://api.rest.local/products/{productId}` | `productId` - ИД продукта <BR> `name` - Наименование продукта <BR> `price` - Стоимость продукта | Изменить запись продукта с ИД `productId`
`DELETE http://api.rest.local/products/{productId}` | `productId` - ИД продукта | Удалить запись продукта с ИД `productId`

### Документация API на [Swagger](https://swagger.io/)

`http://api.rest.local/docs/index.html`

![Example REST](https://github.com/vovancho/rest-api-example/blob/master/project/swagger.jpg)