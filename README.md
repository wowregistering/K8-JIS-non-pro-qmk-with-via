# K8-JIS-non-pro-qmk-with-via
K8 JIS(non-pro) firmware and vial files, not standard layout, F24 wrap on shifted layer.

Layout is NOT standard JIS, IME specific keys replaced with FKEYS for program compatibility.

半角 / 全角 / 漢字 -> F13  Above TAB

英数(Capslock on K8) -> F14 Capslock

無変換(英数 on K8) -> F15 Left of Space

変換 - NA, change keybinds in VIAL if you need it.

カタカナ / ひらがな ->F16 Right of Space




# MouseKeys

FN+Arrow keys -> Mouse Movement

FN+Space -> Left Click

FN+カタ -> Mouse Wheel Up

FN+Ralt -> Mouse Wheel Down

FN+無変換(英数 on K8) -> Right Click

FN+Lalt -> Mouse 3

FN+LWin -> Mouse 4

FN+Lctrl -> Mouse 5

# Lighting

FN+Microphone -> RGB Toggle

FN+Lightbulb -> RGB Mode

FN+Ins -> Hue+

FN+Home -> Sat+

FN+Page Up -> Effect+

FN+Del -> Hue-

FN+End -> Sat-

FN+Page Down -> Effect-

# FN/F24
The function key uses a custom key code (0x5da5 in vial) to hold down F24 and also shift to Mod Layer 1

Most keys on Mod Layer 1 are pass throughs to Layer 0.

Pressing FN+1 will send F24+1, this works the same way for all passed through keys.

Use this F24 wrapped layer with the AHK script to use for binding AHK macros to the Mod1/FN1 layer.

# Steps to use:

1. Flash Firmware keychron_k8_rgb_jis_jis-win_mouse_vial_F24WRAP.bin

2. Download Vial and load k8_via_jis.json
![image](https://user-images.githubusercontent.com/32309624/231613412-451aff87-4087-4332-8d5f-a68b24d2c3c3.png)

3. load Vial layout k8 jis F24_Wrap vial.vil
![image](https://user-images.githubusercontent.com/32309624/231613506-888cd426-3444-4180-8780-46d279f8d13a.png)

If you want to rebind the JIS IME keys back to the standard JIS layout just use the ISO/JIS tab in Vial
![image](https://user-images.githubusercontent.com/32309624/231613888-2dfe432e-ffa7-464d-bba8-7d3895bdd819.png)
