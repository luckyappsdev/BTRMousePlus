# BTRMousePlus

**Battery indicator for Bluetooth mice and keyboards on Windows**
**Индикатор заряда Bluetooth-мышей и клавиатур для Windows**

## English

BTRMousePlus shows the connection state and battery level of your paired Bluetooth devices in the system tray and in a small window, and warns you with sounds when the battery runs low.

**Features**
- Tray icon and window: gray = paired but not active, green = active.
- Color by charge: 100–21 % green, 20–11 % yellow, 10–6 % red, 5–1 % blinking red.
- Sound signals when the device connects or disconnects and warnings at 10, 5 and 1 %.
- Sound volume: Off / Low / Medium / High (the choice is remembered). Sounds can be replaced with your own in the `Assets\Sounds` folder.
- New devices are picked up automatically; optional start with Windows.

**Requirements**
- 64-bit Windows 10 (version 2004 or newer) or Windows 11. Developed and tested on Windows 10 22H2.
- [.NET 10 Desktop Runtime (x64)](https://dotnet.microsoft.com/download/dotnet/10.0). If it is missing, the program offers a download link on start.

**Notes**
- The battery level is read through the standard Bluetooth Battery Service (BLE). Devices without it are shown without a percentage. Game controllers are not supported.
- Tested with the Yenkee YMS 2085BK mouse.
- The files are new: they do not yet have a paid digital signature or an established reputation, so Windows or antivirus software may react to them with a warning. We recommend checking the downloaded file before using it, by any available means and programs of your choice.

**Download:** see the [Releases](../../releases) page. Two options with the same program inside: an installer (`BTRMousePlus_Setup_1.0.exe`) and a portable ZIP archive (`BTRMousePlus_1.0.zip`). Checksums and VirusTotal reports are listed in the release description.

**Privacy policy:** https://luckyappsdev.github.io/privacy-btrmouseplus.html
**Terms of use:** https://luckyappsdev.github.io/license-btrmouseplus.html

**Third-party components:** NAudio (MIT), see `ThirdPartyNotices.txt` in the archive and installer.

Author: LuckyGreenhorn. The program is free for personal use. The source code is not published.

## Русский

BTRMousePlus показывает состояние подключения и уровень заряда сопряжённых Bluetooth-устройств в системном трее и в небольшом окне, а когда заряд заканчивается, предупреждает звуком.

**Возможности**
- Значок в трее и окно: серый — сопряжено, но не активно, зелёный — активно.
- Цвет по заряду: 100–21 % зелёный, 20–11 % жёлтый, 10–6 % красный, 5–1 % красный мигающий.
- Звуковые сигналы при подключении и отключении устройства и предупреждения на 10, 5 и 1 %.
- Громкость звука: выкл. / тихо / средне / громко (выбор запоминается). Звуки можно заменить своими в папке `Assets\Sounds`.
- Новые устройства подхватываются автоматически; запуск вместе с Windows по желанию.

**Требования**
- 64-разрядная Windows 10 (версия 2004 и новее) или Windows 11. Разработана и проверена на Windows 10 22H2.
- [.NET 10 Desktop Runtime (x64)](https://dotnet.microsoft.com/download/dotnet/10.0). Если его нет, при запуске программа предложит ссылку для скачивания.

**Примечания**
- Заряд читается через стандартную службу батареи Bluetooth (BLE). Устройства без неё показываются без процентов. Геймпады не поддерживаются.
- Проверена с мышью Yenkee YMS 2085BK.
- Файлы новые: у них пока нет платной цифровой подписи и накопленной репутации, поэтому Windows или антивирус могут отреагировать на них предупреждением. Рекомендуем перед использованием проверить скачанный файл любыми доступными способами и программами по вашему выбору.

**Скачать:** страница [Releases](../../releases). Два варианта с одной и той же программой внутри: установщик (`BTRMousePlus_Setup_1.0.exe`) и переносимый ZIP-архив (`BTRMousePlus_1.0.zip`). Контрольные суммы и отчёты VirusTotal указаны в описании релиза.

**Политика конфиденциальности:** https://luckyappsdev.github.io/privacy-btrmouseplus.html
**Условия использования:** https://luckyappsdev.github.io/license-btrmouseplus.html

**Сторонние компоненты:** NAudio (MIT), см. `ThirdPartyNotices.txt` в архиве и установщике.

Автор: LuckyGreenhorn. Программа бесплатна для личного использования. Исходный код не публикуется.
