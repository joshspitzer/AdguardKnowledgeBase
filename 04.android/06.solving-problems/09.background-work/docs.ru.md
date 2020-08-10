---
title: 'Как настроить фоновую работу AdGuard'
published: true
taxonomy:
    category:
        - docs
---

Приложения на устройствах не всегда продолжают работать и оставаться в фоновом режиме по нескольким причинам, чаще всего это происходит из-за встроенной функции оптимизации операционной системы (ОС) Android или же из-за включения режима энергосбережения. Поэтому система закрывает приложения для того, чтобы снизить нагрузку и освободить оперативную память. Чтобы избежать этого, вам необходимо выполнить следующие шаги, указанные в инструкции (отдельно для каждого производителя/версии ОС Android). Обратите внимание, что эта инструкция может быть применима практически для любой версии Android OS.

**Список устройств и производителей/версий OS Android:**

* [Asus](#Asus)

* [Xiaomi](#Xiaomi)

* [Samsung](#Samsung)

* [Huawei](#Huawei)

* [Meizu](#Meizu)

* [Nokia](#Nokia)

* [Oppo](#Oppo)

* [Oneplus](#Oneplus)

* [Sony](#Sony)

* [Wiko](#Wiko)

* [Стоковые устройства Pixel/Nexus/Essential на базе Android](#Google)

<a id="Asus"></a>

## Asus

Информация о проблемах на устройствах Asus ещё далеко не исчерпывающая, поэтому в перспективе их может быть куда больше, чем указано здесь. Мы будем дополнять статью по мере поступления информации.

Зайдите в «Настройки» - «Power Manager» - «Mobile Manager» - «Настройки» - «Параметры экономии заряда батареи» - «Автозапуск Nanager» - «AdGuard» - снимите флажок.

<a id="Xiaomi"></a>

## Xiaomi

#### MIUI 10-11


Чтобы приложение успешно работало в фоновом режиме, настройте следующие параметры:

<img src="https://cdn.adguard.com/public/Adguard/screenshots/android/xiaomi1ru.png" width="300">

- *Настройки* > *Батарея и производительность* > отключите режим *«Экономия энергии»*

<img src="https://cdn.adguard.com/public/Adguard/screenshots/android/xiaomi2ru.png" width="300">

- Затем откройте настройки *Контроль фоновой активности* > *AdGuard* > *Нет ограничений*

<img src="https://cdn.adguard.com/public/Adguard/screenshots/android/xiaomi3ru.png" width="300">


#### Управление питанием


Пожалуйста, включите:

- *Настройки > Расширенные настройки > Battery manager > установите *План электропитания* на *Производительность*

- *Настройки устройства* > Расширенные настройки > Battery Manager > Защищённые приложения* – ваше устройство должно быть в списке 


- *Настройки устройства > Приложения > ваше приложение > Батарея > *Энергосберегающая подсказка* и *Продолжить работу после выключения экрана*

- *Настройки > Дополнительные настройки > Батарея и производительность > Управлять использованием батареи приложениями*. И здесь:

1. Отключите режимы энергосбережения

2. Выберите следующие параметры: *Энергосбережение в фоновом режиме > Выбрать приложение > выберите своё приложение > Фоновые настройки > Нет ограничений*


#### Режим Энергосбережения
*Безопасность > Батарея > Режим Энергосбережения > AdGuard > Нет ограничений*


#### Закрепление приложения
Чтобы настроить фоновую работу AdGuard для устройств Xiaomi, обратите внимание на Батарею и права дос.

- Нажмите на кнопку *«Недавние задачи»* проведите вниз, AdGuard, чтобы сделать опции *видимыми* (как показано на скриншоте):

<img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/xiaomirecent.png" width="300">

- Нажмите на иконку *замка*. Это не даст Xiaomi автоматически закрывать AdGuard. Должно выглядеть так:

<img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/xiaomilocked.png" width="300">

- Перейдите в раздел *Батарея*
- Выберите *Battery saver»* 
- Найдите и выберите AdGuard
- Настройте следующие *Фоновые параметры*:

<img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/xiaomirest.png" width="300">

- Перейдите в *Разрешения*
- Выберите *Автозапуск*
- Убедитесь, что эта функция включена для AdGuard:

<img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/xiaomiautostart.png" width="300">

<a id="Samsung"></a>

## Samsung

#### Galaxy S9 / S10

 Оптимизация батареи **включена по умолчанию**. В какие-то неясные моменты (возможно, при обновлении приложения или ПО?) настройки также возвращаются к значениям по умолчанию, заставляя вас выключать их снова и снова.
 
#### Режим сна

 Меню «спящих» приложений — это снайперское гнездо для политики Samsung, убивающей приложения. Точно следуйте инструкциям, чтобы предотвратить закрытие приложений.
 Чеклист:

 - Отключите **«Перевод в режим сна»**
 - Отключите **«Автоотключение приложений»**
 - Удалите своё приложение из списка приложений в спящем режиме
 - Отключите фоновые ограничения для вашего приложения

 1. Начните **Device care** с настроек телефона

<img src="https://cdn.adguard.com/public/Adguard/screenshots/android/samsung1ru.png" width="300">

 2. Нажмите на кнопку **Батарея**

 <img src="https://cdn.adguard.com/public/Adguard/screenshots/android/samsung2ru.png" width="300">

 3. Нажмите на иконку меню в виде **трёх точек** > **Настройки**

<img src="https://cdn.adguard.com/public/Adguard/screenshots/android/samsung3ru.png" width="300">

 4. Отключить все переключатели (кроме Уведомлений)
 
 5. Нажмите на **Приложения в спящем режиме**

 <img src="https://cdn.adguard.com/public/Adguard/screenshots/android/samsung45ru.png" width="300">
 
 6. «Разбудите» все приложения с помощью значка мусорной корзины

<img src="https://cdn.adguard.com/public/Adguard/screenshots/android/samsung6ru.png" width="300">

 > **Важно**: Убедитесь, что функции «Перевод в режим сна» и «Автоотключение приложений» отключены. В противном случае Samsung вернёт ваши приложения в спящий режим через несколько дней (по умолчанию через три), даже если вы разбудили их вручную!
 
#### Ранние устройства Samsung

Для ранних устройств Samsung нет особой необходимости в настройке фоновой работы, но если вы столкнулись с тем, что приложение закрывается или исчезает из меню недавних задач через некоторое время, сделайте следующее:

- Нажмите кнопку вызова фоновых приложений, коснитесь значка дополнительных настроек. Он должен выглядеть так:

 <img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/samsungoptions.png" width="300">

 - Нажмите на "Закрепить приложения":

  <img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/samsunglockapps.png" width="300">

  - Нажмите на значок "замочка"

   <img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/samsunglock.png" width="300">

<a id="Huawei"></a>

 ## Huawei
 


#### Запуск приложения на устройствах с EMUI 8, 9 и 10 (Huawei P20, Huawei P20 Lite, Huawei Mate 10…)

- *Настройки телефона* > *Батарея* > *Запуск приложений*. Активируйте у нужного приложения «Управление вручную» и убедитесь, что все тумблеры включены.
 
<img src="https://cdn.adguard.com/public/Adguard/screenshots/android/huawei1ru.png" width="300">

1. *Настройки телефона* > *Батарея* > *Запуск приложений*. На некоторых устройствах эта функция может быть недоступна или названа по-другому.

<img src="https://cdn.adguard.com/public/Adguard/screenshots/android/huawei2ru.png" width="300">

2. Выключите «Управлять всем автоматически»

<img src="https://cdn.adguard.com/public/Adguard/screenshots/android/huawei3ru.png" width="300">

3. Убедитесь, что вы **включили** все тумблеры.

Также для надёжных фоновых процессов вы можете удалить Power Genie, как описано ниже.

#### Устройства EMUI 9 и более поздними версиями

> Важно: На некоторых телефонах с EMUI 9 и позже (Android P+) Huawei представили новый менеджер процессов (task killer), названный PowerGenie. Это приложение закрывает все приложения, не находящиеся в белом списке Huawei, и не предоставляет пользователям никакие параметры конфигурации. Ниже описано, как его удалить.

Huawei чрезвычайно изобретательны в оптимизации ресурсов, используемых сторонники приложениями на своих устроствах. В дополнение ко всем нестандартным мерам управления питанием, описанным ниже, они представили новое приложение-менеджер процессов, встроенное прямо в EMUI 9 на Android Pie.

Оно называется **PowerGenie** и «убивает» все приложения не из его белого списка. Вы не можете добавлять собственные приложения в предопределённый белый список. Это означает, что удаление Power Genie – единственный способ исправить правильную функциональность приложения на Huawei.

К сожалению, это системное приложение, которое можно удалить только полностью, используя ADB (Android Debug Bridge) Источник: [XDA](https://forum.xda-developers.com/mate-20-pro/themes/remove-powergenie-to-allow-background-t3890409).

**Вам нужно**:

1) [Установить ADB](https://www.xda-developers.com/install-adb-windows-macos-linux/) на ваш компьютер;
2) Подключить телефон с помощью кабеля передачи данных (дата-кабеля);
3) Включить на телефоне *Параметры разработчика*;
4) Включить отладку через USB в *Параметрах разработчика*;
5) Выполните следующие команды на компьютере:
   
`adb shell pm uninstall —user 0 com.huawei.powergenie`

Мы ещё не подтвердили это, но вполне возможно, что вы можете просто отключить Power Genie через *Настройки телефона* > *Приложения*. Этот параметр необходимо будет повторно применять каждый раз при перезагрузке устройства.

> Пожалуйста, следуйте шагам ниже - у телефонов Huawei обычно много механизмов энергосбережения.

И ещё, у вас может не быть PowerGenie на телефоне, но ваши приложения всё ещё будут закрываться с помощью другого механизма.

#### Устройства с EMUI 6 и позже (и некоторые устройства с EMUI 5):

- *Настройки устройства* > *Расширенные настройки* > *Диспетчер батареи* > *План 
электропитания* установлен на *Производительность*;
- *Настройки устройства* > *Расширенные настройки* > *Battery Manager* > *Защищённые приложения* – добавьте ваше приложение;
- *Настройки устройства* > *Приложения* > *Ваше приложение* > *Батарея* > *Энергосберегающая подсказка* `[убрать галочку]` и *Продолжить работу после выключения экрана* `[поставить галочку]`;
- *Настройки устройства* > *Приложения* > *Расширенные (внизу)* > *Игнорировать оптимизацию батареи* > Нажмите «Разрешено» > *Все приложения* > Найдите своё приложение в списке и выберите *«Разрешить»*.



#### Huawei P9 Plus:

- Откройте настройки устройства > *"Приложения"* > *"Настройки"* > *"Специальный доступ"* > выберите *"Игнорировать оптимизацию батареи"* > нажмите *"Разрешить"* для выбранного приложения.

#### Huawei P20, Huawei Honor 9 Lite и Huawei Mate 9 Pro:

- Откройте настройки устройства > *"Батарея"* > *"Запуск приложений"* > выберите *"Управление вручную"* для вашего приложения.

#### Ранние устройства Huawei

 Устройства Huawei наиболее легки в настройке, достаточно выполнить два шага для того, что бы закрепить приложение в фоновом режиме.
 
- Нажмите на кнопку вызова фоновых приложений:
  
  <img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/huaweirecentapps.jpg" width="300">
  
- Нажмите на значок *"замочка"*:
  
   <img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/huaweilock.jpg" width="300">
   
 Для более эффективной настройки фоновой работы приложения необходимо открыть настройки устройства и выполнить следующие действия: 
   
- Откройте *"Расширенные настройки"* > затем *"Менеджер батареи"* > установите схему *"Управление питанием"* на "Производительность";
- Выберите *"Защищенные приложения"* в разделе *"Менеджер батареи"* и проверьте, защищено ли ваше приложение;
- Отправляйтесь в *"Приложения"* в основных настройках и выберите AdGuard > затем *"Батарея"* > активируйте опции *"Сообщать об энергоемкости"* и *"Работа при выключенном экране"*;
- Затем в разделе *"Приложения"* откройте *"Настройки"* (внизу экрана) > *"Специальный доступ"* > выберите *"Игнорировать оптимизацию батареи"* > нажмите *"Разрешено"* > *"Все приложения"* > найдите AdGuard в списке и выберите *"Запретить"*.

Ниже вы найдете другие способы настройки фоновой работы приложений для определенных моделей Huawei. 
  
  
<a id="Meizu"></a> 
   
 ## Meizu
 
Подход к ограничениям фонового процесса у Meizu практически такой же, как и у двух предыдущих устройств — Huawei и Xiaomi. Чтобы избежать отключения фоновой работы AdGuard и любого другого приложения, настройте следующие параметры:

- Отправляйтесь в *"Расширенные настройки"* > затем откройте *"Менеджер батареи"* > установите схему *"Управление питанием"* на "Производительность";
- Выберите *"Защищенные приложения"* в разделе *"Менеджер батареи"* и проверьте, защищено ли ваше приложение;
- Откройте раздел *"Приложения"* и выберите AdGuard > затем *"Батарея"* > активируйте опции *"Сообщать об энергоемкости"* и *"Работа при выключенном экране"*.
 
<a id="Nokia"></a> 
   
 ## Nokia
 
Nokia на Android *O* и *P* отключает все фоновые процессы приложений через 20 минут после выключения экрана.
 
Вот что необходимо сделать для предотвращения остановки фоновой работы приложений: 

- Отправляйтесь в настройки устройства > откройте *"Приложения"* > выберите *"Все приложения"*;
- Затем зайдите в правое верхнее меню > выберите *"Показать системные"*;
- Найдите приложение *Power saver* в списке приложений, выберите его и нажмите *"Остановить"*. Приложение будет остановлено до следующего перезапуска системы.

Теперь фоновые приложения должны работать без перебоев, используя стандартную оптимизацию батареи в системе Android.

**Существует альтернативный метод оптимизации фоновой работы приложения, однако он подходит, прежде всего, продвинутым пользователям. Вы найдете инструкции ниже.**

#### Nokia 1 (Android Go) 

- Удалите файл `com.evenwell.emm` с помощью следующей команды *"adb"*:

`adb shell`
`pm uninstall -- user 0 com.evenwell.emm`

#### Другие модели Nokia

- Удалите файл `com.evenwell.powersaving.g3` с помощью следующей команды *"adb"*:

`adb shell`
`pm uninstall -- user 0 com.evenwell.powersaving.g3`

<a id="Oppo"></a>

## Oppo

Фоновые службы и приложения иногда отключатюся (включая службы специальных возможностей, которые затем необходимо включать вручную) после того, как вы выключаете экран. Чтобы избежать этого, необходимо выполнить следующие шаги:

Перейдите в "Центр безопасности" - нажмите "Разрешения на конфиденциальность" - "Менеджер запуска" и дайте приложению AdGuard разрешение работать в фоновом режиме.

Другие решения:

* Закрепите приложение в меню последних действий
* Добавьте приложение в список приложений в "менеджере запуска" и "плавающем списке приложений" приложения безопасности (com.coloros.safecenter / com.coloros.safecenter.permission.Permission)
* Отключите оптимизацию батареи
   
<a id="Oneplus"></a> 
   
 ## Oneplus
 
В OxygenOS встроен внутренний функционал для очистки кэша и оперативной памяти для экономии заряда. Кроме того, OxygenOS может закрыть приложение, если вы его не используете некоторое время. Чтобы исправить это, выполните следующие действия:
 
- Перейдите в настройки
 
- Батарея - Оптимизация батареи
 
- Найдите приложение AdGuard
 
- Нажмите на него и выберите опцию *«Не оптимизировать»*
 
- Нажмите «Готово», чтобы сохранить изменения
 
- Нажмите на кнопку вызова фоновых приложений, затем зафиксируйте приложение AdGuard нажав на значок *"замочка"* (как показано на скриншоте):

<img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/onepluslock.png" width="300">

- Нажмите на значок замочка:

<img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/oneplusdots.png" width="300">

> На некоторых устройствах OnePlus есть функции под названием *"Автозапуск"* и *"Глубокая Оптимизация"*. Использование этих функций не позволяет приложениям нормально работать в фоновом режиме.

А вот еще один способ активации фоновой работы приложения:

- Откройте настройки устройства > *"Батарея"* > *"Оптимизация батареи"* > откройте список *"Все приложения"* (верхнее меню) >  AdGuard > активируйте функцию *"Не оптимизировать"*.

- Откройте настройки устройства > *"Батарея"* > *"Оптимизация батареи"* > три точки (справа вверху) *"Дополнительная оптимизация*" > Отключите глубокую оптимизацию.

<a id="Sony"></a>

## Sony

Sony были первым разработчиком мобильных OS, который внедрил нестандартную оптимизацию фонового процесса и тем самым открыл ящик Пандоры. Этот механизм оптимизации называется Stamina (режим оптимизации батареи) и он мгновенно прерывает все фоновые процессы при включении.

**Решение:**

Перейдите в Настройки - Батарея - Три точки справа вверху - Оптимизация батареи - Приложения - **AdGuard** - отключите оптимизацию батареи.

<a id="Wiko"></a>

## Wiko

У устройств Wiko могут возникать проблемы с точки зрения нестандартной оптимизации фоновых процессов, которые необходимо настроить, чтобы приложения работали должным образом.

**Решение:**

- Перейдите в Ассистент - Аккумулятор - Выключить *Режим энергосбережения*
- Вернитесь в предыдущее меню и перейдите в *Ручной режим*
- Нажмите на значок шестеренки в правом верхнем углу - Белый список фоновых приложений - Выберите *AdGuard*

<a id="Google"></a>

## Стоковые устройства Pixel/Nexus/Essential на базе Android

Android на заводской прошивке как правило не конфликтует с фоновыми процессами, но если вы все же столкнулись с проблемой фоновой работы, то необходимо включить режим «Всегда в VPN».

 - Перейдите в раздел Настройки - Сеть и Интернет
 
 <img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/stocknetwork.png" width="300">

 - Откройте режим VPN и выберите AdGuard
 
 <img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/stockvpn.png" width="300">
 
 - Выберите пункт "Постоянная VPN" 
 
 <img src="https://cdn.adguard.com/public/Adguard/kb/PicturesEN/android/stockadguard.png" width="300">

