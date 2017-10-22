# about.php
lesson1.1

<?php 

$firstname = 'Евгений';
$yearOfBirth = 1983;
$currentYear = 2017;
$age = $currentYear - $yearOfBirth;
$email = 'psyaries@yandex.ru';
$city = 'Vyshgorod';
$about = 'Менеджер по развитию проекта malevichpro.com';

echo 
'Страница пользователя ', ($firstname), PHP_EOL, PHP_EOL,
'Имя                         ', ($firstname), PHP_EOL, 
'Возраст                     ', ($age), PHP_EOL, 
'Адрес электронной почты     ', ($email), PHP_EOL, 
'Город                       ', ($city), PHP_EOL, 
'О себе                      ', ($about);

?>
