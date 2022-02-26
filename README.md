# lenovo-300e-2ndgen-chromeos

Fixes for issues I've encountered when running ChromeOS on 300e 2nd gen Windows edition.
I am using brunch but I guess the fixes would work with ChromeOS Flex.

## trigger-tabletmode

To detect when tablet mode is engaged and switch. Monitors /var/log/messages for the keycodes 0x63 and 0x62, there might be a better way to do it... but it works!! Add to /etc/init

## touchscreen-suspend-fix

Fix for touchscreen stopped working after resume. Add to /etc/init

## thinkpad-keyboard-layout

Fixes the slash / question mark key on Lenovo ABNT2 keyboards.
Add it as an extension then select the new keyboard layout on settings.
