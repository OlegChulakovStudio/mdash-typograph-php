PHP версия Типографа Муравьева (с поддержкой PHP 7.2.0+)
===============

Данный репозиторий содержит PSR-4 совместимый пакет Composer, созданный на основе кода [Типографа Муравьева](http://mdash.ru/)

Evgeny Muravjev Typograph, http://mdash.ru Authors: Evgeny Muravjev & Alexander Drutsa

EMT - Evgeny Muravjev Typograph

### Использование

```php
$typograph = new \Emuravjev\Mdash\Typograph();
$typograph->set_text('Текст "к которому" применить - типограф.');

// типографируем
$result = $typograph->apply();

// выводим результат
echo $result;
```