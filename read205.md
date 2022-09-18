# Class 05

## HTML Media

### [Using images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
[Common Image Flie Types](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)
[Choosing Imgae types](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format)

1. What is a real world use case for the 'alt' attribute being used in a website?
- Its value is supposed to be a textual description of the image, for use in situations where the image cannot be seen/displayed or takes a long time to render because of a slow internet connection.
- You may want to provide text for search engines to utilize; for example, search engines can match alt text with search queries.


2. How can you improve accessibility of images in an HTML document?
- From an accessibility viewpoint, captions and alt text have distinct roles. Captions benefit even people who can see the image, whereas alt text provides the same functionality as an absent image. Therefore, captions and alt text shouldn't just say the same thing, because they both appear when the image is gone. Try turning images off in your browser and see how it looks.

3. Provide an example of when the 'figure' element would be useful in an HTML document.
-  to provide a semantic container for figures, and to clearly link the figure to the caption. 
-  when you have multiple images and captions - this containerizes the images and caption together

4. Describe the difference between a 'gif' image and an 'svg' image, pretend you are explaining to an elder in your community.
- Graphics Interchange Format / good for small imgages or animations / supported by many browsers
- Scalable Vector Graphics / good for graphics and images that need to be scaled / will not distort with changes in size

5. What image type would you use to display a screenshot on your website and why?
- Unless you're willing to compromise on quality, you should use a lossless format for screenshots. This is particularly important if there's any text in your screenshot, as text easily becomes fuzzy and unclear under lossy compression.
- PNG is probably your best bet, but lossless WebP is arguably going to be better compressed.


## Learn CSS
### [Using Color in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)
### [Styling Text](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.
-  the color property defines the foreground color of an HTML element's content and the background-color property defines the element's background color.
-  background is behind the text/element. Foreground is the element

2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?
- maybe allow the user to select the background/font color. Maybe give an option of a light or dark theme. Create a margin, border, and padding with different colors to focus the reader into the content

3. What should you consider when choosing fonts for an HTML document?
- Serif vs sans // web safe fonts
- no cursive, unless absolutly neccesary
- text that looks good big and small
- font families
- limiting the number of fonts/styles used

4. What do font-size, font-weight, and font-style do to HTML text elements?
- Font size (set with the font-size property) can take values measured in most of these units (and others, such as percentages); however, the most common units you'll use to size text are: px / em / rem 
- font-weight: Sets how bold the text is. This has many values available in case you have many font variants available (such as -light, -normal, -bold, -extrabold, -black, etc.), but realistically you'll rarely use any of them except for normal and bold:
- font-style: Used to turn italic text on or off. Possible values are as follows (you'll rarely use this, unless you want to turn some italic styling off for some reason):

5. Describe two ways you could add spacing around the characters displayed in an h1 element.
- The letter-spacing and word-spacing properties allow you to set the spacing between letters and words in your text.
