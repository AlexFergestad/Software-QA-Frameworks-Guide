# What to look for in Performance Testing

## When the page is visible
When will the user know that something is actually happening on the web page?

## When is the page itself usable?
When can somebody start entering things into a form? Things like that.

## How are resources being handled?
Is there a large quantity of images? Or, are there very large images, or scripts that need to be downloaded?

## How much scripting is there?
Are there a lot of different scripts going on? Are they blocking the main thread, so that the page is not usable while the scripts are running? Are there bugs in the scripts that are perhaps making them slower than they should be? These are all things to look at.

## Is the network usage being optimized?
Is the site using a content delivery network so that the images are being sourced from a location that's closest to the client? And, if resources aren't immediately available, is the webpage able to handle that situation? Or, is it blocked? Another aspect of network usage is how many background requests are being made. This can include getting resources, API requests, any of that sort of thing.

## Things to remember:

What does "First Contentful Paint" mean?
- It means the first time a new page is visible to the user.

What is one way a CDN (Content Delivery Network) can help with performance?
- By hosting content in various locations to better serve people in different places.

Which performance property can you profile with Chrome Developer Tools?
- Frames per second, request response time, and time spent running scripts.

How can scripts affect the performance of a web page?
- By blocking further content loading and making additional network requests.

Tests on WebPageTest can be run on...
- Real devices in various locations.