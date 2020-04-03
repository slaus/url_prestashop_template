Глобальные переменные Smarty в шаблонах PrestaShop
============

Действующие переменные
-------

```bash
{$link} Класс ссылок Link
```
```bash
{$cart} Класс текущей корзины Cart
```
```bash
{$currency} Класс текущей валюты Сurrency
```
```bash
{$cookie} Класс Сookie
```
```bash
{$page_name} Имя страницы (соответствует названию скрипта, например index, product, best-sales, …)
```
```bash
{$base_dir} URL базовой директории магазина (http://myshop.x/)
```
```bash
{$base_dir_ssl} URL базовой директории c использованием SSL, если его использование включено, иначе то же, что и base_dir (https://myshop.x/)
```
```bash
{$content_dir} $protocol_content.Tools::getShopDomain().PS_BASE_URI
```
```bash
{$tpl_dir} Директория темы (/home/v/server/myshop.x/public_html/themes/prestashop/)
```
```bash
{$tpl_uri} URL темы (/themes/prestashop/) 
```
```bash
{$modules_dir} Директория модулей (/modules/) 
```
```bash
{$mail_dir} _MAIL_DIR_ 
```
```bash
{$lang_iso} ISO-код языка 
```
```bash
{$come_from} Строка запроса (http://myshop.x/product.php?id_product=1) 
```
```bash
{$cart_qties} Число товаров в корзине 
```
```bash
{$currencies} Массив доступных валют
```
```bash
{$languages} Массив доступных языков 
```
```bash
{$priceDisplay} Метод отображения цены (с налогом, без налога) 
```
(int)Configuration::get('PS_ATTRIBUTE_CATEGORY_DISPLAY') 
```bash
{$add_prod_display}
```
```bash
{$shop_name} Название магазина 
```
```bash
{$roundMode} Режим округления 
```
```bash
{$use_taxes} Используется ли налог (true/false) 
```
```bash
{$vat_management} (int)Configuration::get('VATNUMBER_MANAGEMENT') 
```
```bash
{$opc} (bool)Configuration::get('PS_ORDER_PROCESS_TYPE') 
```
```bash
{$PS_CATALOG_MODE} Режим каталога (не доступно оформление заказа) 
```
```bash
{$img_ps_dir} Директория картинок магазина (/img/) 
```
```bash
{$img_cat_dir} Директория картинок категорий магазина (/img/с/)
```
```bash
{$img_lang_dir} Директория картинок языков (/img/l/)
```
```bash
{$img_prod_dir} Директория картинок товаров (/img/p/)
```
```bash
{$img_manu_dir} Директория картинок производителей (/img/m/)
```
```bash
{$img_sup_dir} Директория картинок поставщиков (/img/su/)
```
```bash
{$img_ship_dir} Директория картинок способов доставки (/img/s/)
```
```bash
{$img_store_dir} Директория картинок магазинов (/img/st/)
```
```bash
{$img_col_dir} _THEME_COL_DIR_
```
```bash
{$img_dir} Директория картинок темы (http://myshop.x/themes/prestashop/img/)
```
```bash
{$css_dir} Директория стилей темы (http://myshop.x/themes/prestashop/css/)
```
```bash
{$js_dir} Директория скриптов темы (http://myshop.x/themes/prestashop/js/)
```
```bash
{$pic_dir} _THEME_PROD_PIC_DIR_
```
```bash
{$logged} Залогинен ли покупатель (можно заменить на {$cookie→isLogged()})
```
