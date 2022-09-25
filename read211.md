# Read 211

## Audio, Video, Images

### [Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
-The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions `<video>` and `<audio>` elements and the availability of JavaScript APIs for controlling them. We'll not be looking at JavaScript here — just the basic foundations that can be achieved with HTML.

2. Describe the use of the `src` and `controls` attributes in the `<video>` element.
- `src` In the same way as for the `<img>` element, the `src` (source) attribute contains a path to the video you want to embed. It works in exactly the same way.
- `controls` You must either use the `controls` attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API. At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.
  
3. Why is it important to have fallback content inside the <video> element?
- The paragraph inside the <video> tags is called fallback content — this will be displayed if the browser accessing the page doesn't support the <video> element, allowing us to provide a fallback for older browsers. 
  
4. Write a very short story where `<audio>` and `<video>` are characters.
- an audio and video file walk into the bar, audio says, "i'll have two beers", the video just holds up two fingers. The baretnder asks, who said that, you dont't have any dimensional data and you're not on a poster

### [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
  
1. How does Grid layout differ from Flex?
- The basic difference between CSS Grid Layout and CSS Flexbox Layout is that flexbox was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time. 
  
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
- Grid container = The element on which display: grid is applied. It’s the direct parent of all the grid items. In this example container is the grid container.
- grid item = The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.
- grid line = The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. 

### [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

### [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
- Having responsive images is important because it helps us deliver optimal file size, the right image for the right screen size, improves user experience and improves loading time.
  
2. Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.
- `srcset` = defines the set of images we will allow the browser to choose between, and what size each image is. Each set of image information is separated from the previous one by a comma.  (elva-fairy-480w.jpg)
- `sizes` = defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true  ((max-width:600px))
  
3. How is `srcset` more helpful for responsive images than CSS or JavaScript?
- Using the srcset attribute has made responsive image sizing much simpler. It allows you to define a list of differently-sized versions of the same image, and provide information about the size of each one


