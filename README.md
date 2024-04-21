# BB9900 wireless Keyboard: zmk-config
## Keymap

### Default Layer

| Shoulder Key1 |    |    |    |    |    |    |    |    | Shoulder Key2 |
|---------------|----|----|----|----|----|----|----|----|---------------|
|   Tab      || Command || Trackpad || Escape || Caps Lock |
| Q | W | E | R | T | Y | U | I | O | P |
| A | S | D | F | G | H | J | K | L | ← |
| alt | Z | X | C | V | B | N | M | $ | Enter |
| aA | 0 | SPACE | SYM | aA |

### Symbol Layer

| Up |    |    |    |    |    |    |    |    | Down |
|----|----|----|----|----|----|----|----|----|------|
| Tilde Key || Search || Left Click || Refresh Key/F5 || F12 Key |
| # | 1 | 2 | 3 | [( | )] | _ | - | + | @ |
| * | 4 | 5 | 6 | / | : | ; | ' | " | ← |
| \| | 7 | 8 | 9 | ? | ! | , | . | & | Enter |
| Ctrl | 0 | SPACE | SYM | UPPER |

### Upper Layer

| Scroll Up |    |    |    |    |    |    |    |    | Scroll Down |
|-----------|----|----|----|----|----|----|----|----|-------------|
| BT Slot 0 || BT Slot 1 || Toggle Trackpad || BT Slot 2 || BT Slot 3 |
| None | Up | None | Reset | EP Toggle | None | < | > | \| | = |
| Left | Down | Right | None | \\ | & | [ | ] | ^ | Del |
| Shift | None | None | None | BL Decrease | BL Toggle | BL Increase | None | Bootloader | Enter |
| Ctrl | Alt | Space/Toggle | SYM | UPPER |


  
[Keycode that you can use in ZMK firmware](https://zmk.dev/docs/codes)  
[Different behaviors that you can use in ZMK firmware](https://zmk.dev/docs/behaviors)  
## Customizing (instrux from [ZitaoTech](https://github.com/ZitaoTech)):
0. Register a github account if you don't have one.
1. Fork this repo.![fork](https://github.com/ZitaoTech/zmk-config_9900/assets/145678024/4ffc71b9-0ed3-4ae9-ace7-99078dd1d9bc)  
2. Open up `config/bb9900.keymap` and edit the keymap to your liking.![image](https://github.com/ZitaoTech/zmk-config_9900/assets/145678024/a0900a5c-6650-4794-9d11-a17c380a973d)  
3. After editing the keymap, choose commit changes![image](https://github.com/ZitaoTech/zmk-config_9900/assets/145678024/c708dbd0-6c90-49da-aeda-053668ae43c8)
 and then check the Github Actions section.![image](https://github.com/ZitaoTech/zmk-config_9900/assets/145678024/fb534054-add6-4517-8643-8270cbf6d8c7)
 Your new firmware file should be available for download.![image](https://github.com/ZitaoTech/zmk-config_9900/assets/145678024/ae6a1646-c8ab-4966-b969-12e68ecaa0ab)
![image](https://github.com/ZitaoTech/zmk-config_9900/assets/145678024/a6140108-9e27-4d51-aa42-ba12233b8738)
5. Unzip the firmware.zip file. You should see one files: `bb9900-zmk.uf2`.  
6. Flash the keyboard with your new firmware.[How to flash the firmware](https://github.com/ZitaoTech/BB9900-USB_BLE_Keyboard?tab=readme-ov-file#-how-to-update-the-firmware---) 
