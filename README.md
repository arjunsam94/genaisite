# Creating a web page with GenAI

## Background
Used ChatGPT to generate HTML, CSS, and JavaScript code to test its limitations when it came to creating a web page with interactive elements. I also used DALL-E and Runway.ML to create images and video for the webpage.

## Implementation
* Implemented an image carousel which automatically changes every 3 seconds. The images were generated with DALL-E.
* Added the content to a container with border shadow and gradient colors to make it more aesthetic.
* Included a button that becomes darker when a cursor hovers over it. This button takes users to the next page.
* Generated a video with Runway.ML which plays automatically in the next page.

## Observations
* At first, ChatGPT split the code into separate HTML, CSS, JS files based on my requirement. However, this required my intervention since the style and functionality weren't being applied to the right elements with the generated code.
* The first iteration that ChatGPT gave me was quite plain with solid colors and without any container. I asked it to make the page more modern by adding gradient colors and content sections.
* Image carousel was challenging to implement since the first iteration didn’t apply styles and functionalities to the right elements in the page. Although I didn’t need to change the over JS and Style sheet code structure a lot, I still had to step in and manually ensure that the elements were in the right html blocks and the JS and style code was pointing to the right element in the right hierarchy. This shows that while ChatGPT can be great for getting a simple page up and running with good design, it might be easier and faster to tweak the code manually with more complex requirements.
* When generating images using ChatGPT, it got the overall idea of the prompt spot on. When it came to resizing the image, ChatGPT had some minor issues which it rectified with more specific prompts.
* Some versions of the video were too unrealistic to use. One version particularly had two suns setting over Mt.Rainier. Although there were some minor distortions, the video used on the site seemed better than other versions.
