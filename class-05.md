# HTML

### IMAGES
* Images should be:
  1. Be relevant. 
  2. Convey information
  3. Convey the right mood
  4. Be instantly recognisable
  5. Fit the color palette

* If you are building a site from scratch, it is good
  practice to create a folder for all of the images
  the site uses.

* To add an image into the page you need to use an <img>
  element. This is an empty element (which means there is
  no closing tag). 

* You must always specify a src attribute to indicate the
  source of an image and an alt attribute to describe the
  content of an image.

* Photographs are best saved as JPEGs; illustrations or
  logos that use flat colors are better saved as GIFs.


* Height & Width of Images:
   * height: This specifies the height of the
     image in pixels.
   * width :This specifies the width of the
     image in pixels.

* If the <img> is followed by a **block level** element       (such as a paragraph) then the block level element will     sit on a new line after the images.

* If the <img> element is inside a block level element, any   text or other inline elements will flow around the image.

* Three Rules for Creating Images:
    * Save images in the right format: Websites mainly use images in jpeg, gif, or png format.
    * Save images at the right size.
    * Use the correct resolution.

### Color
* The color property allows you to specify the color of       text inside an element. You can specify any
  color in CSS in one of three ways:
    1. **rgb values** These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)

    2. **hex codes** These are six-digit codes that represent the amount of red, green and blue in a color,preceded by a pound or hash # sign. For example: #ee3e80

    3. **color names** There are 147 predefined color names that are recognized by browsers. For example: DarkCyan

* It is important to ensure that there is enough contrast
  between any text and the background color (otherwise
  people will not be able to read your content).

* CSS3 has introduced an extra value for RGB colors to
  indicate opacity. It is known as RGBA.

* CSS3 also allows you to specify colors as HSL values,
  with an optional opacity value. It is known as HSLA.


### Text 
* When choosing a typeface, it is important to understand     that a browser will usually only display it if it's         installed on that user's computer.

* The **font-family** property allows you to specify the
  typeface that should be used for any text inside the elements to which a CSS rule applies.

* The **font-size** property enables you to specify a size    for the font.

* Units of font Size:
  1. Pixels
  2. Percentages
  3. Ems

* @font-face allows you to use a font, even if it is not      installed on the computer of the person browsing, by        allowing you to specify a path to a copy of the font,       which will be downloaded if it is not on the user's         machine.

* The font-weight property allows you to create bold text.
There are two values that this property commonly takes:
   * normal            
   * bold

* If you want to create italic text, you can use the          font-style property. There are three values this property   can take:
   * normal
   * italic
   * oblique

* The text-transform property is used to change the case of
text giving it one of the following values:
   * uppercase
   * lowercase
   * capitalize
* The text-decoration property allows you to specify the
  following values:
   * none
   * underline
   * overline
   * line-through
   * blink

* The text-align property allows you to control the            alignment of text. The property can take one of four        values:
  * left
  * right
  * center
  * justify

## JPEG vs PNG vs GIF — which image format to use and when?

* **JPEG** images are best suited for photographs and         paintings of natural scenes where the variations in         colour and intensity are smooth
* **PNG** PNG image would retain higher quality than an image than JPEG and would look a lot sharper, it would also occupy more space on the disk. This makes it unsuitable for storing or transferring high-resolution digital photographs but a great choice for images with text, logos and shapes with sharp edges.

* **GIF** mainly used only if the image contains animations.