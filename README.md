# ESP32 Security System - ENG 

This project is a security system for ESP32, allowing users to enter a PIN using a 4x4 membrane keypad. If the PIN is entered correctly, the system displays a message on the LCD screen, and in case of an incorrect PIN, it sends an email notification using MQTT.
- [Project Diagram](https://coggle.it/diagram/Zjx4aq4Gr7SFRWVx/t/chytr%C3%BD-z%C3%A1mek%F0%9F%A7%A0%F0%9F%94%92/20672b1634909aed497d98de96c98880f082fbf0277c11aa38c6f90ced6ce471): For a visual representation of the project architecture and components.

## Features

- Entering a four-digit PIN using a 4x4 membrane keypad
- Displaying the PIN on the LCD screen in the form of asterisks
- Verifying the PIN and displaying the corresponding output on the LCD screen
- Sending an email when an incorrect PIN is entered using MQTT

## Hardware

- ESP32
- IIC I2C LCD 1602 display, 16 x 2 LCD characters - Blue module
- 4x4 membrane keypad for single-board computers

## Software

- MQTT broker
- Gmail
- Arduino IDE

## Installation

1. Download this project from GitHub.
2. Open the project in Arduino IDE.
3. Set the correct information for Wi-Fi connection, MQTT broker, and email account in the code.
4. Upload the code to ESP32.
5. Connect the hardware according to the wiring diagram.

## Usage

1. Upon system startup, the LCD screen displays "Enter PIN: ----".
2. Enter the four-digit PIN using the membrane keypad.
3. If the PIN is entered correctly, "PIN code was entered correctly" is displayed on the LCD screen.
4. In case of an incorrect PIN, an error message is displayed on the LCD screen, and an email notification is sent using MQTT.

## MADE BY Roman GALERT & Roman PROKSCH
---

# ESP32 Security System - CZ

Tento projekt je zabezpečovací systém pro ESP32, který umožňuje uživatelům zadávat PIN pomocí 4x4 membránové klávesnice. Pokud je PIN zadán správně, systém zobrazí hlášku na LCD displeji a v případě chybného PINu odešle upozornění e-mailem pomocí MQTT.
- [Schéma projektu](https://coggle.it/diagram/Zjx4aq4Gr7SFRWVx/t/chytr%C3%BD-z%C3%A1mek%F0%9F%A7%A0%F0%9F%94%92/20672b1634909aed497d98de96c98880f082fbf0277c11aa38c6f90ced6ce471): Pro vizuální znázornění architektury a komponent projektu.
## Funkce

- Zadání čtyřmístného PINu pomocí 4x4 membránové klávesnice
- Zobrazení PINu na LCD displeji ve formě hvězdiček
- Ověření PINu a zobrazení odpovídajícího výstupu na LCD displeji
- Odeslání e-mailu při zadání nesprávného PINu pomocí MQTT

## Hardware

- ESP32
- IIC I2C displej LCD 1602, 16 x 2 LCD znaků - Modrý modul
- Membránová klávesnice 4x4 pro jednodeskové počítače

## Software

- MQTT broker
- Gmail
- Arduino IDE

## Instalace

1. Stáhněte tento projekt z GitHubu.
2. Otevřete projekt v Arduino IDE.
3. Nastavte správné údaje pro Wi-Fi připojení, MQTT broker a e-mailový účet v kódu.
4. Nahrajte kód na ESP32.
5. Připojte hardware podle schématu zapojení.

## Použití

1. Po spuštění systému se na LCD displeji zobrazí "Zadejte PIN: ----".
2. Zadejte čtyřmístný PIN pomocí membránové klávesnice.
3. Pokud je PIN zadán správně, na LCD displeji se zobrazí "PIN kód byl zadán správně".
4. V případě nesprávného PINu se zobrazí chybová zpráva na LCD displeji a odešle se e-mailové upozornění pomocí MQTT.

## VYTVOŘILI Roman GALERT a Roman PROKSCH

