🛠 К сожалению браузер не предоставляет никаких средств для нормальной стилизации элемента `<option>`, и это доставляет очень много головной боли фронтенд-разработчикам :( Стиль элементов `<option>` можно поменять, только если тегу [`<select>`](/html/select/) задан атрибут `multiple`. Тогда список целиком становится частью потока страницы, и мы имеем возможность применять стили к его элементам:

<iframe title="Стилизация option" src="../demos/option-styles/" height="200"></iframe>
