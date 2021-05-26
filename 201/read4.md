# HTML Images; CSS Color & Text

# Images :

There are several things to consider when selecting and preparing **images** for your site, but taking time to get them right will make it look more attractive and professional.A picture can say a thousand words, and great **images** help make the difference between anaverage-looking site and a really engaging one.**Images** can be used to set the tone for a site in less time than it takes to read a description. If you do not have photographs to use on your website, there are companies who sell stock **images**; these are **images** you pay to use . If you are building a site from scratch, it is good practice to create a folder for all of the **images** the site uses .



 ## To add an **image** into the page you need to use an (img)element. 
 **This is an empty element (which means there is no closing tag). It must carry the following two attributes:**
- src
This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your
own site. (Here you can see that the images are in a child folder called images.
- alt
This provides a text description of the image which describes the image if you cannot see it. title
You can also use the title attribute with the (img) element to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image.


**You will also often see an (img) element use two other attributesthat specify its size:**
- **height** This specifies the height of the image in pixels.
- **width** This specifies the width of the image in pixels.


# Colors :
Every color on a computer screen is created by mixing amounts of red,green, and blue. To find the color you want, you can use a color picker.
## The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
- **rgb values** These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90).

- **hex codes** These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash (#) sign. For example: #ee3e80.

- **color names** There are 147 predefined color names that are recognizedby browsers. For example: DarkCyan.

## background-color : 
You can specify your choice of **background color** in the samethree ways you can specify foreground colors: RGB values,
hex codes, and color names (covered on the next page). If you do not specify a **background color**, then the
background is transparent. By default, most browser windows have a white background, but browser users can set a **background color** fortheir windows, so if you want to be sure that the background is white you can use the
**background-color** property on the (body) element.

## types of colors :
- **RGB Values** Values for red, green, and blueare expressed as numbersbetween 0 and 255. 
- **Hex Codes** Hex values represent values for red, green, and blue in hexadecimal code.
- **Color Names** Colors are represented by pre defined names. However,they are very limited in number.
- **Hue** Hue is near to the colloquial idea of color. Technically speaking however, a color can also have saturation    and brightness as well as hue.
- **Saturation** Saturation refers to the amount of gray in a color. At maximum saturation, there would be no gray in the color. At minimum saturation, the color would be mostly gray.
- **Brightness** Brightness (or "value") refers to how much black is in a color. At maximum brightness, there would be no black in the color. At minimum brightness, the color would be very dark.


# Text :
The properties that allow you to control the appearance of text can be split into two groups:
- Those that directly affect the font and its appearance(including the typeface, whether it is regular, bold or italic and the size of the text).
- Those that would have the same effect on text no matter what font you were using (including the color of text and the spacing between words and letters).

## There are several ways to use fonts:
**type faces are subject to copyright, so the techniques you can choose from are limited by their respective licenses.**
- Font-family : The user's computer needs the typeface installed. CSS is used to specify the typeface.
- Font-face : CSS specifies where a font can be downloaded from if it is not installed on the computer.
- Service-based Font-Face : Commercial services give users access to a wider range of fonts using @font-face.


# JPEG vs PNG :
## JPEG :
 is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any perceivable difference in quality. Beyond this, the compression artefacts become more prominent. JPEG images are best suited for photographs and paintings of natural scenes where the variations in colour and intensity are smooth.

## PNG :
 is a lossless image format using DEFLATE compression. No data is lost during compression and no compression artefacts are introduced in the image. For this reason, a PNG image would retain higher quality than an image than JPEG and would look a lot sharper, it would also occupy more space on the disk. This makes it unsuitable for storing or transferring high-resolution digital photographs but a great choice for images with text, logos and shapes with sharp edges.