# Based on victorsavu3's Keychron Q1 keymap (ISO)

Very similar to the default layout. Enables reactive and framebuffer RGB, but disables most effects enabled by keychron.
Uses Caps Lock as a leader key for emojis and to enable a random mouse wiggler to prevent the system from going to sleep.

Updates from victorsavu3: 
 - Removed unicode.
 - Changed keymaps variable back to `via` keymap, but with Fn moved and KC_LEAD added.
 - Added email and username output.


# Instructions.

 - In WSL, navigate to `~/dev/qmk_firmware`.
 - Run `util/docker_build.sh keychron/q1/rev_0102:jamesthurley`
 - Copy `keychron_q1_rev_0102_jamesthurley.hex` from `\\wsl.localhost\Ubuntu-20.04\home\james\dev\qmk_firmware` to `Dropbox\Dev\configs`
 - Run QMK Toolbox
 - Select hex file.
 - Unplug keyboard, remove spacebar, hold down reset button and plug back in.
 - QMK will say "device connected".
 - Flash.
 - Done.