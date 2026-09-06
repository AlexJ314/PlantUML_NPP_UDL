# PlantUML_NPP_UDL
PlantUML UDL syntax highlighting for Notepad++

Inspired by https://github.com/brianmaher84/PlantUML_Notepad-_UDL

## Highlights
- Supports code folding
- Supports comment folding
- Builtin functions, keywords, commands, and the like all style
- Differentiation between classes that support nesting (`node`, `class`, `rectangle`) and those that do not (`destroy`, `actor`, `collections`)

## Default
1. Default
    - White (#CCCCCC) on black (#000000)

## Comments
1. Comments
    - Grey (#555555)
2. Line comments
    - Grey (#555555)

## Numbers
1. Numbers
    - Bright orange (#FF8040)

## Keywords
1. Nesting classes
    - Red (#CC2222)
2. Lines and arrows
    - Blue (#0080FF)
    - Arrows starting with `-0`, `-0)`, `.0`, and `.0)` all style a bit weirdly because they're recognized as `Number`
    - Arrows starting with `<<` style a bit weirdly because they're recognized as `Sterotype`
      - Don't use `Stereotype`? Get rid of the delimiter
      - Don't use `<<-` arrows? Don't worry about it
3. Pre-processor functions
    - Faded cyan (#0080CC)
4. Declaration symbols
    - Dark violet (#6C71C4)
    - Also styles the following word
5. Numbers
    - Bright orange (#FF8040)
    - This fixes numbers not styling correctly when including `0`
6. CSS style and builtin colors
    - Pale yellow (#CCCC80)
7. Instructions and settings
    - Dark cyan (#009999)
8. Non-nesting classes
    - Dark orange (#CC7000)

## Operators
1. Operators
    - Blue (#0080FF)

## Folders in code
1. Folder in code 1
    - Red (#CC0000)
2. Folder in code 2
    - Red (#CC0000)

## Folders in comment
1. Folder in comment
    - Grey (#555555)

## Delimiters
1. Mono space
    - Dark green (#007700)
    - Nests `Mono space`, `Quotes`, `Bold`, `Italics`, and `Underline` (`0b111101`)
2. Builtin functions
    - Cyan (#00CCCC)
    - Nests `Builtin functions`, `Quotes`, `Declaration symbols`, `Numbers` (the keywords), and `Numbers` (the real ones) (`0b100000000000110000000000110`)
3. Quotes
    - Bright green (#22CC22)
4. Bold
    - White (#CCCCCC)
    - Bolded
    - Nests `Mono space`, `Quotes`, `Bold`, `Italics`, `Underline` (`0b111101`)
5. Italics
    - White (#CCCCCC)
    - Italic
    - Nests `Mono space`, `Quotes`, `Bold`, `Italics`, `Underline` (`0b111101`)
6. Underline
    - White (#CCCCCC)
    - Underlined
    - Nests `Mono space`, `Quotes`, `Bold`, `Italics`, `Underline` (`0b111101`)
7. Stereotype
    - Yellow (#CCCC00)
8. Environment variables
    - Violet (#8080FF)
