# GLIF Base CSS styles

This provides a single CSS file to be used for the base styling of GLIF apps.

It includes:

- normalize.css
- fonts definitions (RT-Alias-Medium and RT-Alias-Grotesk, light, regular and bold)
- root font size and general font behaviour

The fonts are base64 encoded into the CSS file, so loading this file will also enable the fonts.

The root font size is set on the `html` element and the default behaviour for any other element is to have a `font-size` of `1rem`.

## Publishing module

Go to the actions page on GitHub, and select the "publish" workflow.

On the dropdown menu, select the version you'd like to increment:
X.Y.Z-J
`major` (X)<br />
`minor`(Y)<br />
`patch`(Z)<br />
`prerelease`(J)<br />
