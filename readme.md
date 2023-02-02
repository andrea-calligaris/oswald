# Oswald - Static HTML minimalist site builder

Fork of [_sw_](https://github.com/jroimartin/sw) with ordered menus and sub-menus.

## Features

- The shell script is POSIX and portable, and the commands and options used are fully **compatible with [_sbase_](https://core.suckless.org/sbase/).**
- Ordered menus and submenus with tree structure.
- Accessibility features, and it looks good on _Lynx_.
- Minimal responsive design.
- Program options, including a debug option.

<p align="center">
  <img alt="preview" src="https://andreacalligaris.netsons.org/media/dev/oswald_preview.jpg">
</p>

To convert from markdown, by default it uses [_smu_](https://github.com/karlb/smu/). This can be changed in the file [site.conf](site.conf).

## Troubleshooting

If you get errors, it's because you're not using _sbase_. Either compile and install it (keep in mind that it's not necessary to replace your default system binaries) or manually change the responsible commands in the script (there should be very few occurrences).

