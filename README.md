# PINN_display_patch_GPI_CASE_2W

A quick edit of `config.txt` and `Microsoft_X-Box_360_pad_8A_11B.json` in order to boot PINN on the Raspberry Pi Zero 2W with the Retroflag GPI CASE 2W. This setup includes support for Wi-Fi and gamepad controls.

![GPI Case 2W](gpicase2w.jpg)

## Instructions

1. **Flash PINN on your microSD card** using the [Raspberry Pi Imager](https://www.raspberrypi.org/software/).
2. **Unmount and reinsert the card** into your computer (or just remount it).
3. **Go to the boot partition** (the one containing `config.txt`).
4. Copy over the following files to the root of your microSD card's boot partition:
   - `config.txt`
   - `Microsoft_X-Box_360_pad_8A_11B.json`
5. **Edit `wpa_supplicant.conf`** to add your Wi-Fi settings and copy it to the root of the boot partition as well.

## Controls (Microsoft_X-Box_360_pad_8A_11B.json)

- **Select**: On the keyboard, hold the `Shift` key (to access the PINN manager page).
- **D-Pad**: Mouse movement.
- **A**: Left click.
- **B**: Right click.
- **Start**: Enter.
- **X**: Escape (to choose which OS to boot).

For more information or custom controls, simply read and/or edit the `Microsoft_X-Box_360_pad_8A_11B.json` file.

## Help Needed

For now, I have been unable to boot a proper Linux desktop environment on the Raspberry Pi Zero 2W with the GPI CASE 2W. I would like to be able to navigate Raspbian with a virtual keyboard using only the GPI CASE 2W buttons.

If you know how to boot a proper Linux desktop environment or have suggestions, please contact me.

## Proof

Here is a [video demonstration](https://youtube.com/shorts/IJWCeiYET-E).

## Additional Thoughts

- The `Microsoft_X-Box_360_pad_8A_11B.json` config file could likely be improved.
- More ideas to come... stay tuned!
