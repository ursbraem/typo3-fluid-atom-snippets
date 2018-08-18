# TYPO3 Fluid Atom Snippets

This is a collection of common TYPO3 fluid viewhelpers snippets for [Atom](https://atom.io/ "Atom").

The viewhelpers documentation can be found at the [TYPO3 wiki](http://wiki.typo3.org/Fluid "TYPO3 wiki")

## Maintenance

🚧🚧🚧 I've also switched to vscode & this isn't maintained anymore... 🚧🚧🚧

## Usage

You can use these snippets in all `.html` files. Just type the name of the viewhelper e.g. `image` and use atoms autocomplete

Result: `<f:image src="$1" />` where your cursor will be placed at `$1`

Blocks: e.g. `switch`

```
<f:switch expression="$1">
  <f:case value="$2">$3</f:case>
  <f:case value="$4">$5</f:case>
</f:switch>

```

There you can use tabs to cycle through the cursor positions

## Install
Go to Atom > Preferences... then search for fluid typo3 in Packages tab.

## Credits
Original author: https://github.com/pille72
