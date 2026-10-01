# OpenFIRE ESP32

[English](#english) · [Italiano](#italiano)

<a id="english"></a>

## English

OpenFIRE ESP32 **7.0.0** is the lightgun firmware and configuration ecosystem for supported ESP32-S3 boards. This repository hosts the [central hub](https://alessandro-satanassi.github.io/OpenFIRE-ESP32/?lang=en).

- [Web Flasher](https://alessandro-satanassi.github.io/OpenFIRE-ESP32-WebFlasher/?lang=en): install or update Lightgun, Dongle and Pedal firmware. Select the exact board and memory variant. One lightgun image supports DFRobot/Wii, PAJ7025R2 and PAJ7025R3; select the camera later in the App. A clean installation erases all settings and calibration.
- [Configuration WebApp](https://alessandro-satanassi.github.io/OpenFIRE-ESP32-WebApp/?lang=en): use Chrome or Edge on a computer and connect the lightgun's USB serial port or its paired dongle. The launcher opens the App corresponding to the installed firmware.
- [Tools and downloads](https://alessandro-satanassi.github.io/OpenFIRE-ESP32-Tools/?lang=en): utilities and downloads, including the compatible desktop App.
- [Firmware and user guides](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32#english-version) · [Wiki](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32/wiki/Home_EN) · [Getting Started](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32#getting-started) · [Common Problems](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32/blob/main/lightgun/src/README.md#common-problems)

For offline configuration, hold **B** at lightgun startup for about **2 seconds**. Join **OpenFIRE_Config**, accept using the network without Internet, then open **http://openfire.local/** or **http://192.168.4.1/** in your normal browser. With USB NCM on a supported computer, use **http://192.168.7.1/**. Save and restart normally afterwards.

Hold **Trigger + A** at startup for about **2 seconds** to prepare a gun already running 7.0.0 for firmware flashing through its own USB OTG port. For a blank board or recovery, use its physical BOOT/RESET procedure.

When upgrading from 6.2.1, a clean installation is recommended: note your settings first, then configure and calibrate again. Use the same release for gun, dongle and pedal. Older configuration Apps are not compatible with the new protocol.

---

<a id="italiano"></a>

## Italiano

OpenFIRE ESP32 **7.0.0** è l'ecosistema firmware e di configurazione per lightgun con schede ESP32-S3 supportate. Questo repository ospita l'[hub centrale](https://alessandro-satanassi.github.io/OpenFIRE-ESP32/?lang=it).

- [Web Flasher](https://alessandro-satanassi.github.io/OpenFIRE-ESP32-WebFlasher/?lang=it): installa o aggiorna il firmware di Lightgun, Dongle e Pedal. Seleziona la scheda e la variante di memoria esatte. Una sola immagine lightgun supporta DFRobot/Wii, PAJ7025R2 e PAJ7025R3; la telecamera si seleziona successivamente nell'App. L'installazione pulita elimina tutte le impostazioni e calibrazioni.
- [WebApp di configurazione](https://alessandro-satanassi.github.io/OpenFIRE-ESP32-WebApp/?lang=it): usa Chrome o Edge su computer e collega la seriale USB della lightgun o del suo dongle associato. Il launcher apre l'App corrispondente al firmware installato.
- [Tools e download](https://alessandro-satanassi.github.io/OpenFIRE-ESP32-Tools/?lang=it): utilità e download, tra cui l'App desktop compatibile.
- [Firmware e guide utente](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32#versione-italiana) · [Wiki](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32/wiki/Home_IT) · [Primi passi](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32#primi-passi) · [Problemi comuni](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32/blob/main/lightgun/src/README.md#problemi-comuni-italiano)

Per la configurazione offline tieni premuto **B** all'avvio della lightgun per circa **2 secondi**. Collegati a **OpenFIRE_Config**, accetta di usare la rete senza Internet, poi apri **http://openfire.local/** oppure **http://192.168.4.1/** nel browser normale. Con USB NCM su un computer supportato usa **http://192.168.7.1/**. Al termine salva e riavvia normalmente.

Tieni premuti **Grilletto + A** all'avvio per circa **2 secondi** per predisporre una pistola che esegue già la 7.0.0 al flashing tramite la propria porta USB OTG. Per una scheda vuota o il recupero usa la procedura BOOT/RESET fisica.

Passando dalla 6.2.1 è consigliata un'installazione pulita: annota prima le impostazioni, poi configura e calibra nuovamente. Usa la stessa release per pistola, dongle e pedale. Le vecchie App di configurazione non sono compatibili con il nuovo protocollo.
