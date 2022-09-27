# Class 13

## [Local Storage and How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)
## [“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)

1. Why would a developer use local storage for a web application?
- LocalStorage in JavaScript is a property that allows us to save data to be stored in the browser even a user refreshes or closes a page. The stored data in localStorage has no expiration time, it’s a little bit similar to the cookies. It is supported by all the major web browsers, we can access it from the browser developer tools. This means the data stored in the browser will persist even after the browser window is closed.

2. What information should not be stored in local storage?
- any sensitive information

3. Local storage can store what type of data? How would you convert it to that type before storing?
- "string only", no objects
- You can work around this by using the native `JSON.stringify()` and `JSON.parse()` methods:
