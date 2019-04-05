# TechnoTimer homework
Домашнее задание для лекции по взаимодействию с операционной системой в технополисе

От вас требуется написать простейшее приложение-таймер.

Поддерживаемые функции:
* запустить таймер
* поставить таймер на паузу
* сбросить таймер

Требования:
* если таймер запущен и приложение свернуто, показывать оповещение о том, что таймер продолжает работать.
* оповещение должно поддерживать следующие опции:
  * кнопку паузы/продолжения таймера
  * кнопку сброса таймера
  * по клику на оповещение пользователь должен возвращаться в приложение
* таймер должен продолжать работать пока пользователь явно не завершит его(сброс таймера)
* если таймер не был сброшен, после перезапуска телефона приложение должно продолжить свою работу
* приложение должно корректно работать на всех версиях OS Android. (Особенно на Android O и выше)

Хинт:
* https://developer.android.com/guide/topics/ui/notifiers/notifications
* https://developer.android.com/guide/components/services
* https://developer.android.com/guide/components/broadcasts
* https://developer.android.com/reference/android/app/PendingIntent
* https://developer.android.com/guide/components/intents-filters
