### HTML Chapter 5

`<figure>` contains images and their captions so they're both associated
`<figcaption>` adds a caption with the image

### HTML Chapter 11

Any HTML element can have a background color, even headers.
Opacity is a property that has a value between 0 and 1. 50% opacity is .5
Hue Saturation Lightness Alpha (transparency)
`{background-color: #C8C8C8;
background-color: hsla(0,100%,100%,0.5);
}`

### HTML Chapter 12
`font-family: Georgia, Times, serif:` means the font has to be installed on their computer. If the first choice isn't installed then it will go next on the list.
Setting a font size in pixels is the best way to ensure the type appears like you want it. 
The default size of text in a web browser is 16 pixels.
Ems allow you to change the size of the text relative to the size of the text in the parent element. 
Since the user can change their default font settings, ems and percentages will be based off that.
`@font-face` allows you to use a font even if it's not installed on the user's computer. You have to specify a path to the font.
`@font-face {
    font-family: 'ChunkFive regular';
    src: ulr('fonts/chunkfive.eot);}
    h1, h2 {
    font-family: ChunkFiveRegular, Georgia, serif;
    }`

Open Source Fonts
(www.google.com/webfonts) - but have to link your CSS file to their servers
(www.fontsquirrel.com)
(www.fontex.org)
(www.openfontlibrary.org)

Commercial Font Access
(www.typekit.com)
(www.kernest.com)
(www.fontspring.com)

Three pseudo classes allow you to change the elements when the user is interacting with them. :hover, :active, :focus


