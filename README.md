# Tarifit layout

Tarifit layout US based keyboard. 

This layout is tested on Ubuntu 21.04 Desktop machine.


## Installation



1. Clone `TarifitLayout` repository

```bash
git clone https://github.com/Ilyahoo/TarifitLayout.git
cd TarifitLayout/
```

2. Copy the the `ma` file to `xkb/symbols` folder and `evdev.xml` to `xkb/rules` folder.

```bash
sudo cp ma /usr/share/X11/xkb/symbols/
sudo cp evdev.xml /usr/share/X11/xkb/rules/evdev.xml
```

3. Copy the keyboard inducator to ubuntu theme folder.

```bash
sudo cp light.svg /usr/share/icons/ubuntu-mono-light/status/22/indicator-keyboard-Rif.svg
sudo cp dark.svg /usr/share/icons/ubuntu-mono-dark/status/22/indicator-keyboard-Rif.svg
```

4. Reconfigure the xkb data to apply the new modifications.

```bash
sudo dpkg-reconfigure xkb-data
```
5. Now logout and when you log back in, go to `settings > Region and language` (or wherever your keyboard preference is) and in input sources click on `+` button and search for `Tarifit` or `rif`, and add it.

## License
    Copyright (C) 2021  Ilyahoo Proshel

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

**Ilyahoo Proshel** - *Initial work* - [iPshel](https://ipshel.com)
