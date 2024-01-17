# Quarto-cert 

This is a quarto template for creating certificates.

## Installing


```bash
quarto use template produnis/quarto-cert
```

This will install the extension and create an example qmd file that you can use as a starting place for your certificates.

## Using

You just need to fill out the YAML header. Please note that the main text must not be longer than 3 lines!

## Format Options

You can alter text color and vertical spaces between text blocks

```
---
bordercolor: blue!30!black!60 # Color of the border
titlecolor: red!30!black!90   # Text color of title
textcolor: green!10!black!90  # Color of text
participantcolor: black       # Text color of paricipant name
vspacelogo: -8mm              # vertical space before logo
vspaceopening: 2mm            # vertical space before opening text
vspacename: 2mm               # vertical space before paricipant name
vspacetext: 1mm               # vertical space before main text
vspacesignature: -50mm        # vertical space before signature image
vspaceauthor: -7mm            # vertical space before author name
---
```

## Screenshot

![](https://i.imgur.com/JLM3g9a.jpeg)
