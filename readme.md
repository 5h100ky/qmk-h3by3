# 5h100ky_h3by3
![426209262-d8a6fc79-fa1c-4b83-ad6a-d28cd0f54d95](https://github.com/user-attachments/assets/d51081e0-a6ea-441f-946c-b1a83b16766c)
![423172246-a7425337-f2b4-47ea-812e-445c9285351a](https://github.com/user-attachments/assets/43758523-bbff-4b82-8cb0-5872e95d7816)
![423172247-0897bf8c-f920-4b50-9a67-7ac5fa111cd2](https://github.com/user-attachments/assets/2c8ce682-8b24-4362-942c-a172b065926f)
![426209244-7741698c-cd29-4e5f-a11b-5e73266d05d9](https://github.com/user-attachments/assets/bfd52f80-8a14-499c-bbdf-b54df7e4057f)
<img width="1035" alt="2025-04-07 203955" src="https://github.com/user-attachments/assets/14c2c654-45c1-4cdc-83ed-c0bd5aaa9557" />


*A short description of the keyboard/project*

* Keyboard Maintainer: [5h100ky](https://github.com/5h100ky)
* Hardware Supported: handwired, RP2040
* Hardware Availability:
* 3D Case https://github.com/victorlucachi/void9

Make example for this keyboard (after setting up your build environment):

    make h3by3:vial

Flashing example for this keyboard:

    make h3by3:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
