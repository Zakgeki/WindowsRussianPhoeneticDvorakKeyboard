# WindowsRussianPhoeneticDvorakKeyboard
A windows phoenetic Russian keyboard, but it's setup like the Russian keyboard found in GNOME.

![Keyboard Layout](https://raw.githubusercontent.com/Zakgeki/WindowsRussianPhoeneticDvorakKeyboard/main/layout.png)


## Installation

- Download the [`endv-ru.zip`](https://github.com/Zakgeki/WindowsRussianPhoeneticDvorakKeyboard/releases/) from the latest release.
- Run `setup.exe`and restart your PC.

## Modificaton/Creating an installer

- Download and install [`MSKLC`](https://www.microsoft.com/en-us/download/details.aspx?id=102134)
- Open the `*.mskl` in `MSKLC`
- Modify and test the layout (optional)
- go to `Project > Build DLL and Setup Package` 

Note: You can ignore all the warnings about the layout table not being the default system code page. Additionally, a setup package will not be created if the keyboard description already exists on your machine.
