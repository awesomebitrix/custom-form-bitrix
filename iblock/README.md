# Форма для битрикс, работающая через инфоблокиблоки

```php
$APPLICATION->IncludeComponent(
	"custom:form.faq",
	"",
	array(
		"AJAX_MODE" => "Y",
		"AJAX_OPTION_JUMP" => "N",
		"AJAX_OPTION_HISTORY" => "N",
		"AJAX_OPTION_STYLE" => "N",
		"AJAX_OPTION_SHADOW" => "N",
		"IBLOCK_ID" => ID инфоблока,
		"FORM_TITLE" => "Заголовок для формы",
		"SITE_ID" => SITE_ID
	)
);
```
