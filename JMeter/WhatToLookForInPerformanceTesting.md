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


