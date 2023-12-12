# What is an SVG ?


[SVG (Scalable Vector Graphics)](https://en.wikipedia.org/wiki/SVG) is an XML-based vector image format for defining two-dimensional graphics, having support for interactivity and animation. The SVG specification is an open standard developed by the World Wide Web Consortium since 1999.

SVG images are defined in a vector graphics format and stored in XML text files. SVG images can thus be scaled in size without loss of quality, and SVG files can be searched, indexed, scripted, and compressed. The XML text files can be created and edited with text editors or vector graphics editors, and are rendered by the most-used web browsers.

## How to Create an SVG
Before you continue, you should have some basic understanding of the following:

HTML
Basic XML

- An SVG image begins with an <svg> element
- The width and height attributes of the <svg> element define the width and height of the SVG image
- The <circle> element is used to draw a circle
- The cx and cy attributes define the x and y coordinates of the center of the circle. If cx and cy are not set, the circle's center is set to (0, 0)
- The r attribute defines the radius of the circle
- The stroke and stroke-width attributes control how the outline of a shape appears. We set the outline of the circle to a 4px green "border"
- The fill attribute refers to the color inside the circle. We set the fill color to yellow
- The closing </svg> tag closes the SVG image

SVG's allow you to be creative. From a house to your name you are able to make endless vector images.




# Example

[W3school](https://www.w3schools.com/graphics/svg_intro.asp)




<html>
<body>

<h1>My first SVG</h1>

<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
</svg>

</body>
</html>

'''

[return to home page](README.md)
