# react-native-svg-icon-generator
A small python script that lets you easily generate react-native aware pngs in different resolutions of the form @2x, @3x and @4x using Inkscape

# installation (for Debian)
`sudo apt-get install inkscape`

# usage
`python getIcons.py path/to/the/svg/file.svg`

# output
```
.
|-- getIcons.py
\`-- path/to/the/svg/
    |-- file.svg
    |-- icons.png
    |-- icons@1,5x.png
    |-- icons@2x.png
    |-- icons@3x.png
    \`-- icons@4x.png
```
