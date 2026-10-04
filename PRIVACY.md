# Политика конфиденциальности Globus Lite

_Действует с 4 октября 2026 года._ [English version below](#privacy-policy-globus-lite)

Globus Lite (`client.globus.digital.lite`) — VPN-клиент: он подключает
устройство к VPN-серверам из подписки, которую пользователь добавил сам.
У приложения нет своих серверов, аккаунтов, рекламы, аналитики и отчётов
о сбоях. Разработчик не получает от приложения никаких данных.

**Разработчик:** [укажите разработчика]  
**Связь по вопросам конфиденциальности:** [укажите e-mail], Telegram
[@vpnglobussupport](https://t.me/vpnglobussupport)

## Какие данные обрабатывает приложение

### Подписка и настройки

Ссылка на подписку, полученные из неё конфигурации серверов и настройки
приложения хранятся только на устройстве. Ссылка на подписку — в
зашифрованном хранилище Android.

### Запрос подписки

Чтобы получить и обновить список серверов, приложение обращается по ссылке
подписки к серверу её владельца (провайдера, которого выбрал пользователь) и
передаёт ему:

- идентификатор устройства (HWID) — `ANDROID_ID` Android, а если он
  недоступен, случайный идентификатор, созданный приложением;
- модель устройства, версию ОС, язык системы, версию приложения и
  User-Agent.

Провайдер использует эти данные, чтобы считать устройства в рамках своей
подписки (лимит устройств). Передачу HWID можно отключить: Настройки →
Подписка → «Отправлять HWID». Пользователь может задать свой User-Agent там
же. Что провайдер делает с этими данными, определяет его собственная
политика конфиденциальности. Разработчик Globus Lite их не получает.

### VPN-трафик

Пока VPN включён, трафик устройства идёт через сервер, выбранный
пользователем. Приложение не записывает, не хранит и никуда не отправляет
содержимое трафика и историю посещений. Решения о маршрутизации (через VPN
или напрямую) принимаются на устройстве. Шифрование до сервера определяется
протоколом сервера, который задаёт провайдер.

### Проверка задержки (пинг)

Чтобы показать задержку, приложение подключается к серверам из подписки и
открывает адрес проверки (по умолчанию `https://www.gstatic.com/generate_204`,
его можно сменить в настройках пинга). Никаких данных о пользователе при
этом не передаётся.

### Журнал

Журнал подключений по умолчанию выключен. Если пользователь его включил,
он хранится только на устройстве. Передать его кому-либо пользователь может
только сам, скопировав текст кнопкой «Скопировать».

### Камера и изображения

Камера используется только для сканирования QR-кода подписки и только с
разрешения пользователя. QR-код можно также выбрать из галереи через
системный выбор фото. Изображения обрабатываются на устройстве, не
сохраняются и никуда не отправляются.

### Список приложений

Для режима «приложения через VPN / мимо VPN» приложение показывает список
установленных приложений. Он используется только на устройстве и никуда не
передаётся.

### Уведомления

Уведомление показывает состояние VPN-подключения. Push-уведомлений и
сторонних служб уведомлений нет.

### Ссылки

Ссылки на поддержку (Telegram) и на страницу подписки открываются в других
приложениях только по нажатию пользователя.

## Кому передаются данные

Только провайдеру подписки, которого выбрал пользователь, и только то, что
описано в разделе «Запрос подписки». Данные не продаются, не используются
для рекламы и не передаются никому ещё.

## Безопасность

Данные хранятся на устройстве, ссылка на подписку — в зашифрованном
хранилище Android. Запросы к провайдеру идут по протоколу ссылки подписки
(HTTPS, если провайдер его использует).

## Хранение и удаление

Все данные хранятся только на устройстве, у разработчика их нет. Удалить их
можно, удалив подписку в приложении, очистив данные приложения или удалив
приложение. Данные, которые получил провайдер, удаляются по запросу к
провайдеру.

## Дети

Приложение не предназначено для детей младше 13 лет.

## Изменения

Изменения этой политики публикуются на этой странице с новой датой.

---

# Privacy Policy: Globus Lite

_Effective October 4, 2026._

Globus Lite (`client.globus.digital.lite`) is a VPN client: it connects the
device to VPN servers from a subscription the user adds themselves. The app
has no servers, accounts, ads, analytics or crash reporting of its own. The
developer receives no data from the app.

**Developer:** [developer name]  
**Privacy contact:** [e-mail], Telegram
[@vpnglobussupport](https://t.me/vpnglobussupport)

## Data the app handles

### Subscription and settings

The subscription link, the server configurations it provides and the app
settings are stored on the device only; the subscription link in Android's
encrypted storage.

### Subscription request

To get and update the server list, the app requests the subscription link
from its owner's server (the provider the user chose) and sends it:

- a device identifier (HWID): Android's `ANDROID_ID`, or a random identifier
  created by the app when it is unavailable;
- the device model, OS version, system language, app version and User-Agent.

The provider uses them to count the devices on its subscription (device
limit). Sending the HWID can be turned off: Settings → Subscription → "Send
HWID"; a custom User-Agent can be set there too. What the provider does with
this data is governed by the provider's own privacy policy. The developer of
Globus Lite does not receive it.

### VPN traffic

While the VPN is on, the device's traffic goes through the server the user
chose. The app does not record, store or send the contents of the traffic or
the browsing history. Routing decisions (through the VPN or direct) are made
on the device. Encryption to the server is set by the server's protocol,
chosen by the provider.

### Latency check (ping)

To show latency, the app connects to the subscription's servers and opens a
check address (`https://www.gstatic.com/generate_204` by default, changeable
in the ping settings). No user data is sent.

### Log

The connection log is off by default. When the user turns it on, it is kept
on the device only; only the user can pass it on, by copying it with the
Copy button.

### Camera and images

The camera is used only to scan a subscription QR code, with the user's
permission. A QR code can also be picked from the gallery through the system
photo picker. Images are processed on the device, never stored or sent.

### App list

For the "apps through / around the VPN" mode the app lists installed apps.
The list is used on the device only and never sent.

### Notifications

A notification shows the VPN connection state. There are no push
notifications or third-party notification services.

### Links

Support (Telegram) and subscription page links open in other apps only when
the user taps them.

## Who receives data

Only the subscription provider the user chose, and only what the
"Subscription request" section lists. Data is not sold, not used for
advertising and not shared with anyone else.

## Security

Data is stored on the device; the subscription link in Android's encrypted
storage. Requests to the provider use the subscription link's protocol
(HTTPS when the provider uses it).

## Retention and deletion

All data is kept on the device only; the developer holds none. It is deleted
by removing the subscription in the app, clearing the app's data or
uninstalling the app. Data the provider received is deleted on request to
the provider.

## Children

The app is not directed at children under 13.

## Changes

Changes to this policy are published on this page with a new date.
