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
Класс текущей валюты Сurrency
```bash
{$currency}
```
Класс Сookie
```bash
{$cookie}
```
Имя страницы (соответствует названию скрипта, например index, product, best-sales, …)
```bash
{$page_name}
```
URL базовой директории магазина (http://myshop.x/)
```bash
{$base_dir}
```
URL базовой директории c использованием SSL, если его использование включено, иначе то же, что и base_dir (https://myshop.x/)
```bash
{$base_dir_ssl}
```
$protocol_content.Tools::getShopDomain().PS_BASE_URI 
```bash
{$content_dir}
```
Директория темы (/themes/prestashop/) 
```bash
{$tpl_dir}
```
URL темы (/themes/prestashop/) 
```bash
{$tpl_uri}
```
Директория модулей (/modules/) 
```bash
{$modules_dir}
```
_MAIL_DIR_ 
```bash
{$mail_dir}
```
ISO-код языка 
```bash
{$lang_iso}
```
Строка запроса (http://myshop.x/product.php?id_product=1) 
```bash
{$come_from}
```
Число товаров в корзине 
```bash
{$cart_qties}
```
Массив доступных валют 
```bash
{$currencies}
```
Массив доступных языков 
```bash
{$languages}
```
Метод отображения цены (с налогом, без налога) 
```bash
{$priceDisplay}
```
(int)Configuration::get('PS_ATTRIBUTE_CATEGORY_DISPLAY') 
```bash
{$add_prod_display}
```
Название магазина 
```bash
{$shop_name}
```
Режим округления 
```bash
{$roundMode}
```
Используется ли налог (true/false) 
```bash
{$use_taxes}
```
(int)Configuration::get('VATNUMBER_MANAGEMENT') 
```bash
{$vat_management}
```
(bool)Configuration::get('PS_ORDER_PROCESS_TYPE') 
```bash
{$opc}
```
Режим каталога (не доступно оформление заказа) 
```bash
{$PS_CATALOG_MODE}
```
Директория картинок магазина (/img/) 
```bash
{$img_ps_dir}
```
Директория картинок категорий магазина (/img/с/)
```bash
{$img_cat_dir}
```
Директория картинок языков (/img/l/)
```bash
{$img_lang_dir}
```
Директория картинок товаров (/img/p/)
```bash
{$img_prod_dir}
```
Директория картинок производителей (/img/m/)
```bash
{$img_manu_dir}
```
Директория картинок поставщиков (/img/su/)
```bash
{$img_sup_dir}
```
Директория картинок способов доставки (/img/s/)
```bash
{$img_ship_dir}
```
Директория картинок магазинов (/img/st/)
```bash
{$img_store_dir}
```
_THEME_COL_DIR_
```bash
{$img_col_dir}
```
Директория картинок темы (http://myshop.x/themes/prestashop/img/)
```bash
{$img_dir}
```
Директория стилей темы (http://myshop.x/themes/prestashop/css/)
```bash
{$css_dir}
```
Директория скриптов темы (http://myshop.x/themes/prestashop/js/)
```bash
{$js_dir}
```
_THEME_PROD_PIC_DIR_
```bash
{$pic_dir}
```
Залогинен ли покупатель (можно заменить на {$cookie→isLogged()})
```bash
{$logged}
```
