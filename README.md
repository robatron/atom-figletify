# figletify

> [Atom](https://atom.io/) package to convert the selected text to ASCII art using [FIGlet](http://www.figlet.org/)

Select some text to convert something like this:

```
Hello World!
```

to something like this:

```
 _  _     _ _      __      __       _    _ _
| || |___| | |___  \ \    / /__ _ _| |__| | |
| __ / -_) | / _ \  \ \/\/ / _ \ '_| / _` |_|
|_||_\___|_|_\___/   \_/\_/\___/_| |_\__,_(_)
```

## Usage

To figletify text, select the text you wish to convert, and do **any** of the following:

- Press `ctrl-alt-f` **or**
- Select `Figletify: Convert` in the [command pallet](https://atom.io/docs/latest/getting-started-atom-basics#command-palette) **or**
- Select *Packages* -> *Figletify Selection* from the main menu **or**
- Right click on the selected text, and select *Figletify Selection* from the context menu

## Configuration

You can configure the FIGfont produced by editing the following configuration
entry in you Atom config file:

```
figletify:
  font: "Small"
```

To see a demo of available fonts, go here: http://patorjk.com/software/taag

## Credits

Based on the [Hacking Atom: Package: Modifying Text](https://atom.io/docs/v1.0.0/hacking-atom-package-modifying-text) tutorial.
