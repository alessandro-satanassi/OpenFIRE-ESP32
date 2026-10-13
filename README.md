# OpenFIRE ESP32

[English](#english) · [Italiano](#italiano)

<a id="english"></a>

## English

OpenFIRE ESP32 **7.0.0** is the lightgun firmware and configuration ecosystem for supported ESP32-S3 boards. This repository hosts the [central hub](https://alessandro-satanassi.github.io/OpenFIRE-ESP32/?lang=en).

- [Web Flasher](https://alessandro-satanassi.github.io/OpenFIRE-ESP32-WebFlasher/?lang=en): install or update Lightgun, Dongle and Pedal firmware. Select the exact board and memory variant. One lightgun image supports DFRobot/Wii, PAJ7025R2 and PAJ7025R3; select the camera afterwards in the WebApp. **Base Update** keeps your settings; **Clean Install** erases all settings and calibrations.
- [Configuration WebApp](https://alessandro-satanassi.github.io/OpenFIRE-ESP32-WebApp/?lang=en): use Chrome or Edge on a computer and connect the lightgun's USB serial port or its paired dongle. The page opens the WebApp made for the firmware installed in the gun.
- [Tools and downloads](https://alessandro-satanassi.github.io/OpenFIRE-ESP32-Tools/?lang=en): utilities and downloads, including the compatible desktop App.
- [Firmware and user guides](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32#english-version) · [Wiki](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32/wiki/Home_EN) · [Getting Started](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32#getting-started) · [Common Problems](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32/blob/main/lightgun/src/README.md#common-problems)

For offline configuration, hold **B** at lightgun startup for about **2 seconds**. Join **OpenFIRE_Config**, accept using the network without Internet, then open **http://openfire.local/** or **http://192.168.4.1/** in your normal browser. With USB NCM on a supported computer, use **http://192.168.7.1/**. Save and restart normally afterwards.

Hold **Trigger + A** at startup for about **2 seconds** to prepare a gun already running 7.0.0 for firmware flashing through its own USB OTG port. For a blank board or recovery, use its physical BOOT/RESET procedure.

When upgrading from 6.2.1, a clean installation is recommended: note your settings first, then configure and calibrate again. Use the same release for gun, dongle and pedal. Configuration Apps for earlier firmware do not work with the new protocol.

---

<a id="italiano"></a>

## Italiano

OpenFIRE ESP32 **7.0.0** è l'ecosistema firmware e di configurazione per lightgun con schede ESP32-S3 supportate. Questo repository ospita l'[hub centrale](https://alessandro-satanassi.github.io/OpenFIRE-ESP32/?lang=it).

- [Web Flasher](https://alessandro-satanassi.github.io/OpenFIRE-ESP32-WebFlasher/?lang=it): installa o aggiorna il firmware di Lightgun, Dongle e Pedal. Seleziona la scheda e la variante di memoria esatte. Una sola immagine lightgun supporta DFRobot/Wii, PAJ7025R2 e PAJ7025R3; la telecamera si sceglie poi nella WebApp. **Aggiornamento Base** conserva le impostazioni; **Installazione Pulita** elimina tutte le impostazioni e calibrazioni.
- [WebApp di configurazione](https://alessandro-satanassi.github.io/OpenFIRE-ESP32-WebApp/?lang=it): usa Chrome o Edge su computer e collega la seriale USB della lightgun o del suo dongle associato. La pagina apre la WebApp fatta per il firmware installato nella pistola.
- [Tools e download](https://alessandro-satanassi.github.io/OpenFIRE-ESP32-Tools/?lang=it): utilità e download, tra cui l'App desktop compatibile.
- [Firmware e guide utente](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32#versione-italiana) · [Wiki](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32/wiki/Home_IT) · [Primi passi](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32#primi-passi) · [Problemi comuni](https://github.com/alessandro-satanassi/OpenFIRE-Firmware-ESP32/blob/main/lightgun/src/README.md#problemi-comuni-italiano)

Per la configurazione offline tieni premuto **B** all'avvio della lightgun per circa **2 secondi**. Collegati a **OpenFIRE_Config**, accetta di usare la rete senza Internet, poi apri **http://openfire.local/** oppure **http://192.168.4.1/** nel browser normale. Con USB NCM su un computer supportato usa **http://192.168.7.1/**. Al termine salva e riavvia normalmente.

Tieni premuti **Grilletto + A** all'avvio per circa **2 secondi** per predisporre una pistola che esegue già la 7.0.0 al flashing tramite la propria porta USB OTG. Per una scheda vuota o il recupero usa la procedura BOOT/RESET fisica.

Passando dalla 6.2.1 è consigliata un'installazione pulita: annota prima le impostazioni, poi configura e calibra nuovamente. Usa la stessa release per pistola, dongle e pedale. Le App di configurazione dei firmware precedenti non funzionano con il nuovo protocollo.

## Shooting Gallery — web game / gioco web

### English

The home page includes an **OpenFIRE Shooting Gallery** panel that opens `./game/index.html` in the same tab. The game files live entirely in `game/`; updating them does not require editing the home page.

To publish a new game version, manually copy **all the contents** of `F:\OpenFIRE-ShootingGallery\release\web\` into this repository's `game/` directory, preserving filenames and any subdirectories. Keep `index.html` directly inside `game/` (not `game/web/`). Deploy the matching HTML, JavaScript, WASM, PCK and other exported files together. No automatic copying or updates are configured.

Test the game through a local HTTP server or the published HTTPS site; opening the exported HTML by double-clicking is not sufficient. The hub panel is translated into Italian and English; the game keeps its own language selection via **L**.

### Italiano

La home include il pannello **OpenFIRE Shooting Gallery**, che apre `./game/index.html` nella stessa scheda. Tutti i file del gioco risiedono in `game/`; aggiornarli non richiede modifiche alla home.

Per pubblicare una nuova versione del gioco, copia manualmente **tutto il contenuto** di `F:\OpenFIRE-ShootingGallery\release\web\` nella cartella `game/` di questo repository, mantenendo nomi e sottocartelle. Il file `index.html` deve trovarsi direttamente in `game/` (non in `game/web/`). Pubblica insieme HTML, JavaScript, WASM, PCK e gli altri file della stessa esportazione. Non sono configurati copie o aggiornamenti automatici.

Prova il gioco tramite un server HTTP locale oppure sul sito HTTPS pubblicato: il doppio clic sull'HTML esportato non è sufficiente. Il pannello dell'HUB è tradotto in italiano e inglese; il gioco mantiene la propria selezione della lingua con **L**.
