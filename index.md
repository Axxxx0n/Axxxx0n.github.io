# Design to dev transition task list

## ASSETS
- all image/video/font assets are included in bundle and can be downloaded
- assets are free for commercial use
- fonts in bundle can be in .tiff, .otf, .woff or .woff2. In development all fonts are transformed to .woff
- icons are .svg, images without background are .png and the rest are .jpg. In development, assets can become .webp to optimise for web.
- preoptimise assets on https://kraken.io/web-interface. Choose LOSSLESS option.
- if there are multiple states for icons (dark mode, light-dark header etc.), multiple versions are included in bundle. Exeptions are .svg icons which can be transformed in communication with developers.

## PAGES
- there is 404
- check for font inconsistences
- all pages have resposive equivalent. Exeptions can be those who have trivial layout or are easily transferable to mobile experience
- have a general idea of hover effects, scroll effects and interaction animations
- linked pages in prototype are nice to have but only if it dosen't take a lot of time
- "made by ALT" with website link in footer

## ERRORS
- if it's neccessary, create global error interface when something goes wrong (ie. API calls)
- if it's possible for some part of UI to have validation errors, handle those accordingly (ie. input field validations)
- if buttons can be clicked or interacted with only if some dependency or action is satisfied, handle those accordingly (ie. with invisible/visible buttons, disabled/active buttons)

## LANGUAGES
- communicate ammount of locales/languages in web/app
- if some text in prototype isnt't final or close to final, it is better to put "lorem ipsum"
- define browser title and description for search engines

