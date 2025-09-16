### About OG (Open Graph protocol)

The Open Graph protocol is a set of meta tags that can be added to a webpage's HTML to control how the page is represented when shared on social media platforms like Facebook, Twitter, LinkedIn, and others. By using Open Graph tags, website owners can specify the title, description, image, and other attributes that will be displayed in the preview snippet when the page is shared. This helps improve the appearance and engagement of shared content, making it more likely that users will click on the link. Open Graph tags are placed within the ```<head>``` section of an HTML document. 


- The first important OG property to include would be the title. 
Here is an example of setting the OG title for the freeCodeCamp homepage:

```<meta content="freeCodeCamp.org" property="og:title" />```
For the property attribute, you will need to specify that it is og:title. The content attribute is where you will write the title you want displayed for social media sites.

- The next important OG property would be the type.
Here is an example of using the OG type for the freeCodeCamp homepage:

```<meta property="og:type" content="website" />```
The type property is used to represent the type of content being shared on social media. Examples of this content include articles, websites, videos, or music.

- The third important OG property would be the image.
```<meta property="og:image" content="https://www.freecodecamp.org/news/content/images/2022/04/fcc-meta-image.png" />```

In this example, the open graph image is pointing to the freeCodeCamp logo. All of these images should be high quality with good dimensions and ratios. Most social media platforms will include criteria for image requirements to help you ensure that your content displays well on their site. For example, the developers.facebook.com documentation page states:

"use images that are at least 1200 by 630 pixels for the best display on high resolution devices. At the minimum, you should use images that are 600 by 315 pixels to display link page posts with larger images."

- The fourth important OG property would be the url.
 Here is an example of setting the OG url for the freeCodeCamp homepage:
 ```<meta property="og:url" content="https://www.freecodecamp.org" />```