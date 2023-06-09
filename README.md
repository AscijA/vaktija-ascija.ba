# vaktija-ext-ascija.ba  

This extension displays daily prayer times of European cities which are a part of Bosnian Islamic Community in the panel menu.

## License

This program is licensed under the GNU General Public License version 2.0. For more details, please see the [GNU General Public License](http://www.gnu.org/licenses/) page.

## Requirements

- GNOME Shell 42

## Optional
- [Poppins Font](https://fonts.google.com/specimen/Poppins)
- GNOME Shell Theme [Qogir-dark](https://www.gnome-look.org/p/1230631/)  

  
## Installation

1. Clone this repository or download the source code and extract the archive.
2. Run `./install.sh local-install`
3. Restart the GNOME Shell by pressing **Alt+F2** and entering `r` in the prompt, then press **Enter**.
4. Enable the extension using **GNOME Extensions** or by running `gnome-extensions enable vaktija@ascija.ba` in your terminal .

## Usage

After installing and enabling the extension, a new icon ![Vaktija icon](assets/vaktija-symbolic.png) will appear in the panel. Clicking on the icon will open a menu displaying the daily prayer times. Underneath is shown time before the next prayer and after the previous respectively. Current prayer/time is highlighted.  

![Vaktija Panel Menu](assets/widget.png)  
![My desktop example](assets/whole.png)
*Font used in the screenshots is Poppins, and is as such as default in the stylesheet. GNOME Shell theme used is Qogir-dark ([see Optional](#optional))*

## Further planned improvements

Following improvements and features are planned to be implamented in future:
- [ ] Preferences with following options:
  - [X] All cities provided by [Vaktija.eu](https://vaktija.eu/), ~~currently supports only Graz, Austria~~
  - [ ] Other cities in Europe
  - [ ] 12/24 time formats, currently only 24 hour format is supported 
  - [ ] Light Theme
  - [X] Add positioning for Background Widget
- [x] Highlight current prayer time and show remaining time until next Prayer
- [X] Add Desktop Background Widget
- [ ] Add Notifications X minutes before the prayer
- [x] Custom Translations via JSON file
- [x] Guide for Translation JSON file
- [x] Install script
- [x] Add Date and Islamic/Hijri Date and weekday, and clock
- [ ] Add significant events on current day as submenu

## Acknowledgements

This extension is inspired by [Vaktija.eu](https://vaktija.eu/) and [Vaktija.ba](https://vaktija.ba/).
Vectors and icons inpired by [SVGRepo](https://www.svgrepo.com/svg/48266/muslim-man-praying).


## Contact

For any questions, feedback, feature request or bugs please submit an issue.  

## Notice

This project is following the **Atwood's law** which states: 
> Any application that can be written in JavaScript, will eventually be written in JavaScript. :rofl: :rofl:
