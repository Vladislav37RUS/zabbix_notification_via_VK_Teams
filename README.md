# zabbix_notification_via_VK_Teams
Оповещение через VK Teams Для Zabbix 6.4.15

Данный скрипт позволяет делать оповещения на VK Teams<br>
Установка очень проста, переходите в ваш Zabbix > Оповещения > Способы оповещения > Создать способ оповещения<br>
СПОСОБ ОПОВЕЩЕНИЯ (Вкладка)<br>
Имя : VKTeams<br>
Тип : Webhook<br>
Параметры : <br>
  Subject  {ALERT.SUBJECT}<br>
  Message  {ALERT.MESSAGE}<br>
  To  {ALERT.SENDTO}<br>
  Token  ВАШ ТОКЕН БОТА<br>
Скрипт :  копируете сожержимое scripts данного проекта<br>
Время ожидания : 10s<br>
