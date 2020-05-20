# UXer Toolbox
This is the GitHub repo for my website "UXer Toolbox". This website is created because I wanted to have a place where I can conveniently access the tools that I frequently use while doing my UX design work.
## Website URL
You can access the website via: [https://troyanovsky.github.io/UXerToolbox/](https://troyanovsky.github.io/UXerToolbox/)
## Built with

 - [Bulma](https://bulma.io/): CSS framework
 - [Buefy](https://buefy.org/): UI components for Vue.js based on Bulma
 - [Vue.js](https://vuejs.org/): JavaScript framework
 - [Webfont Loader](https://github.com/typekit/webfontloader): JavaScript library to load Google Fonts
 - [Color Thief](https://lokeshdhakar.com/projects/color-thief/): JavaScript library to extract color palette from images
 Other API's used are in the detailed tool descriptions.

## Current Tools
Currently, there are four tools that I've created: Color Converter, Color Mixer (Gradient), Color Scheme Generator, and Font Comparer.

**Color Converter**

 - Supports conversion across RGB, Hex, HSL, HWB, and CMYK. 
 - The background of this section will change dynamically according to the color input. 
 - User input is saved locally using localStorage.

**Color Mixer (Gradient)**

 - Takes two Hex colors and generates colors between the two (using RGB scheme). 
 - The number of colors is based on the slider input. 
 - The background of this section will be a linear gradient of the two color inputs.
 - User can copy a color by clicking on the tags generated.
 - User input is saved locally using localStorage.

**Color Scheme Generator**

 - Takes one Hex color input and generates the following color schemes: 
	 - complementary
	 - monochromatic
	 - split-complementary
	 - 30° analogous
	 - triadic
	 - tetradic
	 - square.
 - User can copy a color by clicking on the tags generated.
 - User input is saved locally using localStorage.

**Font Comparer**

 - Allows users to choose two fonts available from [Google Fonts](https://fonts.google.com/) and display some user-inputted characters side-by-side.
 - Uses webfont loader to dynamically load chosen fonts from Google Fonts.

**Palette Extractor**

 - Allows users to upload an image and extract a color palette with 10 colors from it.
 - The image is not saved anywhere.
 
 **Lorem Ipsum Generator**

 - Allows users to generate lorem ipsum dummy texts.
 - Has 5 different generators, including:
 	- Lorem Ipsum: The classic lorem ipsum generator, using [loripsum.net](https://loripsum.net/)
	- Literature Ipsum: Random text from The Adventures of Sherlock Holmes, Dr Jekyll and Mr Hyde, Dracula, Evelina, The Life of Samuel Johnson, The Picture of Dorian Gray, and Pride and Prejudice; uses [litipsum](https://litipsum.com/)
	- Bacon Ipsum: Random meaty words; uses [bacon ipsum](https://baconipsum.com/)
	- Dino Ipsum: Random dinosaur names; uses [dino ipsum](http://dinoipsum.herokuapp.com/)
	- Metaphor Ipsum: A wise– if perhaps slightly pedantic– generator of metaphor; uses [metaphorpsum](http://metaphorpsum.com/)

**Fake Profile Generator**

 - Allows users to generate a fake profile with a picture and personal info.
 - For profile picture, there are 8 choices: [adorable](http://avatars.adorable.io/), [pixel male, pixel female, robot, avataaars, jdenticon, identicon](https://avatars.dicebear.com/), and [life-like](https://thispersondoesnotexist.com/). 
