# drupal-custom-tokens

Deze module voegt custom tokens toe.
* Een url encoded pad van de pagina (onder current page tokens te vinden)
* Een url encoded titel van de pagina (onder current page tokens te vinden)
* Een token met aantal webformulier inzendingen (onder custom tokens te vinden)
* Een token met aantal contacten in civicrm groep (onder custom tokens te vinden)

Het token voor het weergeven van aantal contacten in een CiviCRM groep vergt een drupal variabele met daarin de id's van de groepen die geteld moeten worden.

In local.settings.php

```
$conf = array(
  'custom_tokens_civi_groups' => array(
    2658,
    10077,
  ),
);
```
