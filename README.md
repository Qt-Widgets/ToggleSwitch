# ToggleSwitch

> Toggle switch widget extension for the Qt library

## Usage

It is possible to use this custom widget lika any other standart Qt widget. Just link the library to your project
and include the header file ```toggleswitch.hpp```.

```cpp
#include <QApplication>
#include <QMainWindow>
#include <toggleswitch.hpp>

int main(int argc, char **argv)
{
    QApplication application(argc, argv);
    QMainWindow mainWindow;
    
    ToggleSwitch *toggleSwitch = new ToggleSwitch(&mainWindow);
    toggleSwitch->setStatus(false);
    
    mainWindow.show();
    return application.exec();
}
```

## License

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.
 * 
This program is distributed in the hope that it will be useful,
but **WITHOUT ANY WARRANTY**; without even the implied warranty of
**MERCHANTABILITY** or **FITNESS FOR A PARTICULAR PURPOSE**.  See the
GNU General Public License for more details.
 
You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston,
MA 02110-1301, USA.

[GNU General Public License](http://www.gnu.org/licenses/gpl.html) or [LICENSE](LICENSE) for
more details.

### Forbidden

**Hold Liable**: Software is provided without warranty and the software
author/license owner cannot be held liable for damages.
