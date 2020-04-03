Глобальные переменные Smarty в шаблонах PrestaShop
============

Действующие переменные
-------

**{$link}** Класс ссылок Link  
**{$cart}** Класс текущей корзины Cart  
**{$currency}** Класс текущей валюты Сurrency  
**{$cookie}** Класс Сookie  
**{$page_name}** Имя страницы (соответствует названию скрипта, например index, product, best-sales, …)  
**{$base_dir}** URL базовой директории магазина (http://myshop.x/)  
**{$base_dir_ssl}** URL базовой директории c использованием SSL, если его использование включено, иначе то же, что и base_dir (https://myshop.x/)  
**{$content_dir}** $protocol_content.Tools::getShopDomain().PS_BASE_URI  
**{$tpl_dir}** Директория темы (/home/v/server/myshop.x/public_html/themes/prestashop/)  
**{$tpl_uri}** URL темы (/themes/prestashop/)  
**{$link->getCMSLink(id)}** ЧПУ ссылка на cms-страницу с номером id  
**{$modules_dir}** Директория модулей (/modules/)  
**{$mail_dir}** _MAIL_DIR_  
**{$lang_iso}** ISO-код языка  
**{$come_from}** Строка запроса (http://myshop.x/product.php?id_product=1)  
**{$cart_qties}** Число товаров в корзине  
**{$currencies}** Массив доступных валют  
**{$languages}** Массив доступных языков  
**{$priceDisplay}** Метод отображения цены (с налогом, без налога)  
**{$add_prod_display}** (int)Configuration::get('PS_ATTRIBUTE_CATEGORY_DISPLAY')  
**{$shop_name}** Название магазина  
**{$roundMode}** Режим округления  
**{$use_taxes}** Используется ли налог (true/false)  
**{$vat_management}** (int)Configuration::get('VATNUMBER_MANAGEMENT')  
**{$opc}** (bool)Configuration::get('PS_ORDER_PROCESS_TYPE')  
**{$PS_CATALOG_MODE}** Режим каталога (не доступно оформление заказа)  
**{$img_ps_dir}** Директория картинок магазина (/img/)  
**{$img_cat_dir}** Директория картинок категорий магазина (/img/с/)  
**{$img_lang_dir}** Директория картинок языков (/img/l/)  
**{$img_prod_dir}** Директория картинок товаров (/img/p/)  
**{$img_manu_dir}** Директория картинок производителей (/img/m/)  
**{$img_sup_dir}** Директория картинок поставщиков (/img/su/)  
**{$img_ship_dir}** Директория картинок способов доставки (/img/s/)  
**{$img_store_dir}** Директория картинок магазинов (/img/st/)  
**{$img_col_dir}** _THEME_COL_DIR_  
**{$img_dir}** Директория картинок темы (http://myshop.x/themes/prestashop/img/)  
**{$css_dir}** Директория стилей темы (http://myshop.x/themes/prestashop/css/)  
**{$js_dir}** Директория скриптов темы (http://myshop.x/themes/prestashop/js/)  
**{$pic_dir}** _THEME_PROD_PIC_DIR_  
**{$logged}** Залогинен ли покупатель (можно заменить на {$cookie→isLogged()})  

