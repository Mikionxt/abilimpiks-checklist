# Чек-лист Абилимпикс

Пошаговая инструкция по подготовке рабочего места: настройка VPN и установка драйверов для подключения платы.

## Последовательность

1. **Установите VPN.** Скачайте установщик по ссылке и запустите его от имени администратора:
   [Happ для Windows](https://backups.tgvpnbot.com/kamil/Official-Files/media/branch/main/Happ_windows.exe)

2. **Добавьте ключ в VPN.** Откройте приложение и вставьте ключ доступа:
   [Ключ VPN](https://a.my-keyboards.shop/cart/0XW9xawx_FmeAcL4)

3. **Скачайте библиотеку `EEPROM.h`** с GitHub:
   [PaulStoffregen/EEPROM](https://github.com/PaulStoffregen/EEPROM)

4. **Установите расширение PlatformIO в VS Code.** Откройте VS Code, перейдите в раздел расширений (`Ctrl+Shift+X`) и установите расширение:
   [PlatformIO IDE](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide)

5. **Скачайте драйвер USB-UART (CP210x)** для подключения платы по проводу:
   [USB to UART Bridge VCP Drivers](https://www.silabs.com/software-and-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads)

## Примечания

- Установку VPN выполняйте с правами администратора.
- После установки драйвера плата определится как COM-порт в «Диспетчере устройств».
