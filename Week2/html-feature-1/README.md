# WebP

## LIVE



## What is WebP?

"WebP is a modern image format that provides superior lossless and lossy compression for images on the web. Using WebP, webmasters and web developers can create smaller, richer images that make the web faster.

WebP lossless images are 26% smaller in size compared to PNGs. WebP lossy images are 25-34% smaller than comparable JPEG images at equivalent SSIM quality index."

[A new image format for the Web](https://developers.google.com/speed/webp/)

## Fallback

### <picture>

"The HTML <picture> element is a container used to specify multiple <source> elements for a specific <img> contained in it. The browser will choose the most suitable source according to the current layout of the page (the constraints of the box the image will appear in) and the device it will be displayed on (e.g. a normal or hiDPI device.)"

[<picture>](https://developer.mozilla.org/nl/docs/Web/HTML/Element/picture)

### srcset

"A list of one or more strings separated by commas indicating a set of possible image sources for the user agent to use."

[srcset](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)

If everything fails, then the browser will look for the ancient and precious img tag and display the given picture.
